# Diagrams in mkdocs

mkdocs comes with a lot of plugins, some of them are really essential when creating technical documentation, such as UML diagrams.

## Plantuml

[mkdocs plantuml](https://github.com/MikhailKravets/mkdocs_puml)

Syntax;

```
    \`\`\`puml
    @startuml
    Bob -> Alice : hello
    @enduml
```

```puml
@startuml
Bob -> Alice : hello
@enduml
```

<br>

```puml
@startgantt
[Prototype design] requires 15 days
[Test prototype] requires 10 days
-- All example --
[Task 1 (1 day)] requires 1 day
[T2 (5 days)] requires 5 days
[T3 (1 week)] requires 1 week
[T4 (1 week and 4 days)] requires 1 week and 4 days
[T5 (2 weeks)] requires 2 weeks
@endgantt

```