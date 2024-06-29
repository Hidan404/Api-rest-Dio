# Api-rest-Dio
API reste em java desafo dio

## Diagrama de Classes

``` mermaid

classDiagram
    class User {
        +String name
        +Account account
        +Feature[] features
        +Card card
        +News[] news
    }

    class Account {
        +String number
        +String agencia
        +double balance
        +double limit
    }

    class Feature {
        +String icon
        +String description
    }

    class Card {
        +String cardNumber
        +double cardLimit
    }

    class News {
        +String newsIcon
        +String newsDescription
    }

    User --> Account
    User --> Feature
    User --> Card
    User --> News

´´´
