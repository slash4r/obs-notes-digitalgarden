---
{"dg-publish":true,"permalink":"/hello/","created":"2025-01-31T22:24:55.224+02:00","updated":"2025-02-03T20:02:40.268+02:00"}
---

# hello
---

![Truth Table.png](/img/user/assets/img/Truth%20Table.png)

## Mermaid Diagrams

```plantuml
@startuml
class Student {
    +String name
    +BorrowBookFromLibrary()
}

class Library {
    +BorrowBook()
}

Student --> Library : borrows
@enduml

```
