# [Catppuccin (Macchiato)](https://catppuccin.com/) [PlantUML](https://plantuml.com) theme

Based on the [Catppuccin (Macchiato)](https://github.com/catppuccin/catppuccin) palette and the [Dracula PlantUML 
theme](https://github.com/guipatriota/dracula-plantuml-theme).

## Screenshots

JetBrains:

![Screenshot of WebStorm with PlantUML diagram code in left pane and diagram preview with Dracula PlantUML theme in right pane](docs/ide-screenshots/jetbrains.png)

<!-- Visual Studio Code:

![Screenshot of Visual Studio Code with PlantUML diagram code in left pane and diagram preview with Dracula PlantUML 
theme in right pane](docs/ide-screenshots/vs-code.png)-->

## Usage

[`!include`](https://plantuml.com/preprocessing#393335a6fd28a804) the theme file:

```puml
@startuml

!include https://raw.githubusercontent.com/ncosta-ic/catppuccin-macchiato-plantuml-theme/main/theme.puml

Bob->Alice : hello

@enduml
```

## Examples

Sequence diagram:

![PlantUML sequence diagram with Dracula theme](examples/sequence.svg)

Use case diagram:

![PlantUML use case diagram with Dracula theme](examples/use-case.svg)

Class diagram:

![PlantUML class diagram with Dracula Theme](examples/class.svg)

Activity diagram:

![PlantUML activity diagram with Dracula theme](examples/activity.svg)

Component diagram:

![PlantUML component diagram with Dracula theme](examples/component.svg)

State diagram:

![PlantUML state diagram with Dracula theme](examples/state.svg)
