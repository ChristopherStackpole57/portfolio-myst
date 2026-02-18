# Core Projects
-----
## VRENDER Rendering Engine
**A modern Vulkan rendering engine emphasizing modularity and configurability.**

```{image} ./images/HERO_VRENDER.png
:alt: Miscellaneous Rendered Shapes
:width: 500px
:align: left
```

:::{figure} ./videos/DEMO_VRENDER.mp4
A Spinning Triangle Demo powered by VRENDER's dynamic mesh system.
:::

**Overview**
VRENDER is a real-time Vulkan rendering engine. This project emphasizes
control and configurability.

**Technical Overview**
- Driven my modern Vulkan techinques, such as: Dynamic Rendering, Local
Read, Bindless Descriptors, Sychronization2, and VMA
- Custom geometry allocation and suballocation system for static and
dynamic mesh streaming
- Cross-Platform and Cross-Vendor window abstraction supporting GLFW,
SDL, SFML, and Win32
- Custom CMake build system

**Technologies**
C++20, Vulkan, VMA, GLFW, SDL, SFML, Win32

**Links**
[GitHub](https://github.com/ChristopherStackpole57/vrender) |
[LinkedIn DevLog](https://www.linkedin.com/in/christopher-stackpole-ab234a304/recent-activity/all/)

-----
## Acrhimedes Math Engine
**A math engine utilizing generic typing and enforcing correctness.**

```{image} images/HERO_AME.png
:alt: Archimedes Math Engine Logo
:width: 500px
:align: left
```

**Overview**
Archimedes is a custom math engine built to support rendering and physics
engines. The library emphasizes performance, clarity, and deterministic
behavior.

**Technical Highlights**
- Template driven engine types, such as: vectors, matrices, and quaternions
- Header only implementation, massively simplifying engine integration
- Conformance test suite enforcing correctness

**Technologies**
C++11, DocTest

**Links**
[GitHub](https://github.com/ChristopherStackpole57/Archimedes-Math-Engine)

-----
## Asteroid Defense -- C++ Game Engine
**A Planet-Defense style game built on a custom, service driven C++ game engine.**

```{image} images/HERO_AsteroidsDefense.png
:alt: Asteroid Defense in play
:width: 500px
:align: left
```

**Overview**
Asteroid Defense is a real-time C++ game built on a custom engine. The project
explores service driven architecture, call order clarity, and entity systems.

**Technical Overview**
- Service driven architecture with dual engine and game layers, clearly
separating engine and game concerns
- Priority based call order control, allowing concise, configurable system
execution order
- Entity management system that safely pools objects for efficient game
execution
- Lightweight entity overlap detection designed for scenes with hundreds of
moving entities

**Technologies**
C++17, SFML

**Links**
[GitHub](https://github.com/ChristopherStackpole57/Asteroid-Defence)

-----
## Timeless Game Engine
**A lightweight 2D game engine written in Python**

```{image} ./HERO_Timeless2D
:alt: GoblinHops, a game built in Timeless2D in play
:width: 500px
:align: left
```

**Overview**
Timeless 2D is a lightweight game engine written in Python and PyGame.
Timeless2D explores various aspects of real-time game engines, such as
rendering, physics, collision, and input.

-----
## Fluid Dynamics LOD -- Research Project
**Level-of-Detail Oriented Overview of Methods for Fluid Simulation**

**Overview**
An undergraduate research project exploring performance and fidelity
oriented LOD strategies for real-time fluid simulation.

This project is still a WIP, but will be presented at the Purdue Spring 2026
Undergraduate Research Conference