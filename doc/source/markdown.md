# Markdown Works Too

Markdown syntax is supported through the [recommonmark](http://recommonmark.readthedocs.io/en/latest/index.html) library.

PlantUML syntax is however not directly supported, so it's necessary to use something like the plantuml service to render diagrams. For example:

```uml
@startuml
Alice -> Joe: Authentication Request
Joe --> Alice: Authentication Response

Alice -> Bob: Another authentication Request
Alice <-- Bob: another authentication Response
@enduml
```
Equates to the URL: `http://www.plantuml.com/plantuml/uml/TSx12O0m38NXUwV80bb0HAf7ZsvGQy229chJ_GqgUD7p-_XvFciujAoBQvSK2R21NgY2jkXCh2a6JS8mq5uegxCDqCo5FrJUX3EvDzR9Q8p5t07XEthZ6l7MuKy_SKyysU4J`

![](http://www.plantuml.com/plantuml/svg/TSx12O0m38NXUwV80bb0HAf7ZsvGQy229chJ_GqgUD7p-_XvFciujAoBQvSK2R21NgY2jkXCh2a6JS8mq5uegxCDqCo5FrJUX3EvDzR9Q8p5t07XEthZ6l7MuKy_SKyysU4J)

The encoding of the UML text to a URL path element is interesting. An example
of an encoder in python: [plantuml.py](https://github.com/dougn/python-plantuml/blob/master/plantuml.py)

