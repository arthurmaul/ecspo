# ECSPO

NOTE: This was a learning project to help me understand ecs and development in python. It is not intended for serious use

## An ecs implementation for game development in python
- implementation focusing on basic data structures and functions
- intuitive api with minimal boilerplate and fast startup
- easy to understand src code, with a focus on simplicity and readability
- built as a simple implementation of ecs
- generic api, allowing use in game dev, app dev, or other applications

---

## Installation
the easiest way to get up and running is to start you vm of choice and then to use pip
  
```zsh
pip install ecspo
```

it can then be imported using the library name under whatever alias you want

```py
import ecspo as engine
```

## Documentation
For documentation, read the [manual](docs/manual.md)

## Features
- [x] Entities
- [x] Components
- [x] Tags
- [x] Prototypes
- [x] single component queries
- [x] multi component queries

## Credits
Heavily inspired by tinyecs, found [here](https://github.com/dickerdackel/tinyecs)
Massive thanks to [Matiiss](https://github.com/Matiiss) for doing code review, this project would be a mess without it!
