# PlantUML

https://plantuml.com/fr/

## Online editor

http://www.plantuml.com/plantuml/uml/

## Desktop editor

Edit diagram with [vscode](https://code.visualstudio.com/) : https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml

## How to include into Markdown file

https://gist.github.com/noamtamim/f11982b28602bd7e604c233fbe9d910f

### Example (Dynamic)

The image is created directly form the source code of the diagram.

> The git branch has to be defined into the link and is not dynamic

```plantuml
@startuml diagram
actor client
node app
database db

db -> app
app -> client
@enduml
```

![diagram](http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/Capgemini-Architects/diagrams-examples/master/plantuml/diagram.plantuml)

### Example (Static)

![diagram png](http://www.plantuml.com/plantuml/png/SoWkIImgAStDKKZ9J4mlIipbIamkoIzIICx9JCqhuShBJqbLI2meu4f9B4bCIYnELKX9uk9AILBGjGCB0p6G2LFja9gN0ZGA0000)

![diagram svg](http://www.plantuml.com/plantuml/svg/SoWkIImgAStDKKZ9J4mlIipbIamkoIzIICx9JCqhuShBJqbLI2meu4f9B4bCIYnELKX9uk9AILBGjGCB0p6G2LFja9gN0ZGA0000)
