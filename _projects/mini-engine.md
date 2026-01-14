---
title: "MiniEngine - Custom C++ Engine (WIP)"
---

**High-performance, lightweight 3D engine built with modern C++**

- Ongoing personal project focused on building a performant, low-level C++ game engine using modern architecture and tooling

- Actively developed and refactored on a regular basis with emphasis on maintainability and performance

### Features
- Custom ECS (Entity–Component–System) framework enabling efficient entity management and data-oriented design
- 3D transform system with editor gizmos for scene manipulation and world construction
- Lightweight engine architecture designed to run on low-spec hardware as a less resource-intensive alternative to Unreal Engine
- Hardware-aware memory benchmarking, selecting optimal allocation strategies per machine on initial launch ( can also be re-benchmarked ) 
- Modular, extensible codebase designed for iterative development and future engine subsystems

### Latest Updates
- Integrating Lua as an in-engine scripting language, allowing users to code within the engine ( also added a link to Lua Documentation )
- Refreshed the UI a little, fully embraced the dockspace design
- Implemented basic gravity and started implementing physics system
- Further optimised processes, curent runtime full allocation of memory is around 120MB


 ### Roadmap
 - Provide templates for Lua scripts, and ability to create custom templates
 - The ability to convert projects into executable games
 - Basic Lighting systems
 - Level Systems ( currently one project can only technically be a scene ) 
  
### Technical Focus
- Low-level, performance-oriented C++ with careful memory management and minimal overhead
- Data-oriented ECS design prioritising cache efficiency, scalability, and ease of use
- Engine architecture & tooling — clean separation of systems, editor/runtime boundaries, and maintainable code structure

**Source code:**
[Github Repository](https://github.com/LewisW99/MiniEngine/)
  
