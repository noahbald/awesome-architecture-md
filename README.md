# Awesome ARCHITECTURE.md
> A list of awesome ARCHITECTURE.md files

A good ARCHITECTURE.md file helps developers understand how and where to make changes, whether they are new to a project or not.

Diagrams, source code maps, and discussing invariants and design decisions is essential.

This can also be a dedicated section of your README.md files.
## Contents
- [Examples](#examples)
- [Resources](#resources)

## Examples
- [Linux cryptography](https://github.com/torvalds/linux/blob/master/Documentation/crypto/architecture.rst) - Calls out different types of components, provides searchable areas, calls out invariants of different components, and describes structure with diagrams
- [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh/wiki/Design) - Describes the initialization process, calls out environment requirements
- [Flutter engine](https://github.com/flutter/flutter/blob/master/docs/about/The-Engine-architecture.md) - Good use of high level diagrams to show the stack and it's parts. Describes the main processes. Describes platform invariants.
- [VSCode](https://github.com/microsoft/vscode/wiki/Source-Code-Organization) - Good use of high-level diagrams. Describes source organisation.
- [NextJS](https://github.com/vercel/next.js/blob/canary/docs/03-architecture/index.mdx) - Breaks architecture into separate files, calls out important dependencies.
- [rust-analyser](https://github.com/rust-lang/rust/blob/main/src/tools/rust-analyzer/docs/book/src/contributing/architecture.md) - Good diagrams, describes entry points and source organisation, discusses architecture considerations.
- [Tauri](https://github.com/tauri-apps/tauri/blob/dev/ARCHITECTURE.md) - Well made source code map, discusses architecture considerations, calls out important dependencies.
- [NeoVim](https://github.com/neovim/neovim/blob/master/runtime/doc/dev_arch.txt) - Describes the main processes/lifecycle
- [GitLab](https://gitlab.com/gitlab-org/charts/gitlab/-/tree/master/doc/architecture) - Calls out design decisions
- [ESBuild](https://github.com/evanw/esbuild/blob/main/docs/architecture.md) - Great use of graphics for visualisations and project structure. Includes a list of important principles for the project.
- [Redis](https://github.com/redis/redis/blob/unstable/README.md) - Good source code map. Overviews of key files. Good use of documentation comments in-code rather than inline comments. 
- [OXVG](https://github.com/noahbald/oxvg/wiki/Architecture) - Use of GitHub markdown and mermaid diagrams. Points out locations of key features.

## Resources
- [Matklad's take](https://matklad.github.io/2021/02/06/ARCHITECTURE.md.html) - ARCHITECTURE.md files are useful for >10k line project. They should be start with a bird's eye view, provide a high-level code map, and show high-level relationships. Call out searchable starting points, such as a project's entry point.
- [John Jago's discussion](https://johnjago.com/great-docs/) - Explores esbuild & Redis' documentation. Users and contributors alike benefit from separating Architecture from a README. Using design principles, graphics, key files, and changelogs are important parts of good documentation.
