# 🍄 About
Mycel Project aims to make continuous, curiosity-driven, long-term learning accessible to everyone, whether used as a standalone application or integrated into existing tools.
***
**[Mycel](https://github.com/mycel-project/mycel/tree/master)** is the name of the open-source backend integrating all tools related to learning, scheduling, data collection, and data processing.

**[Mycelium](https://github.com/mycel-project/mycelium)** is the official frontend, designed to integrate Mycel’s features in the most seamless way possible, with extensible support.

## Mission & Direction
The mission of this project is to address a key gap in modern learning tools: while access to information is abundant, long-term learning remains poorly supported.

- Read-it-later apps (such as Omnivore or Wallabag) are great for collecting information.
- Flashcard applications (such as Anki) are great for memorization.
- PKM tools like Obsidian or Logseq are great for storing knowledge and reflection.

However, when it comes to transforming information and curiosity into structured, long-term understanding and learning, existing solutions are either limited, fragmented, or closed.

**Mycel Project aims to fill this gap by creating a missing system for continuous learning, both as a fully open-source, optimized standalone application, and as a backend designed to integrate with existing tools such as PKM systems, when supported through APIs.**

## Current Status

Mycel Project is currently in a very early prototype stage, with many core features not yet implemented. It is open-source to encourage experimentation and the exchange of ideas. 

**Please be aware that this is an experimental state: data may be unstable, and loss or unexpected behavior can occur. Major and breaking changes may also be introduced at any time. For now, this project should be seen more as an experimental playground for testing and improvement than as a stable, production-ready solution.**

## Sustainable Model

In the interest of transparency, it is important to clarify that the project may include an **optional** paid service model. This model is **not based on exclusive features**, but rather on providing convenience and infrastructure services around the core open-source system.

**No functionality is locked behind a paywall, and no core capabilities of the application or backend depend on proprietary components. The system remains fully usable through self-hosting at all times. There is no intention to control or restrict access to user data, and data ownership is fully respected.**

The paid offering is intended purely as a facilitation layer, for users who prefer a managed, ready-to-use experience, while also helping support the long-term development and maintenance of the project.

The underlying infrastructure for these hosted services may remain proprietary, but it does not restrict access to, or usage of, the open-source components of Mycel.

## Roadmap

The current high-level roadmap of Mycel is structured around progressive stabilization and migration of the system.

- [ ] Release an early MVP of the Mycel backend in Python, available as a self-hosted option or experimental managed service, alongside an open-source basic Mycelium client for Windows, Linux, and Android
- [ ] Iterate based on feedback and stabilize core learning workflows and overall system design
- [ ] Gradually reimplement the backend in Rust for long-term architecture 
- [ ] Transition toward an official Mycelium release with a bundled Rust backend (Windows, macOS, Linux, Android, iOS), while preserving support for both self-hosted and managed sync services (v1.0)
- [ ] Evolve the ecosystem to support fully integrated in-app sync through the bundled backend
- [ ] ...

## Acknowledgements
This project is heavily inspired by [SuperMemo](https://www.super-memory.com/), a software developed by Piotr Wozniak and a pioneering application in the field of computer-assisted learning and spaced repetition, still actively maintained today. It implements the fundamental philosophy of Mycel, such as incremental learning and spaced repetition.

The spaced repetition system incorporates [FSRS](https://github.com/open-spaced-repetition), an open-source project focused on spaced repetition algorithms.
