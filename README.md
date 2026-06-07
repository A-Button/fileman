# fileman

A Python based powerful TUI file manager

# TODO List

## 1. Core / Backend

> Goal: Implement a UI-agnostic file system abstraction and operation layer. All
> code must be independent of any TUI library.

- [x] 1.1 **Project Scaffolding**
- [ ] 1.2 **File System Abstraction Layer**
- [ ] 1.3 **Metadata & Information Retrieval**
- [ ] 1.4 **File Operation Commands**
- [ ] 1.5 **Batch Operations & Conflict Handling**
- [ ] 1.6 **Unit Tests**

---

## 2. Terminal User Interface (TUI)

> Goal: Build the terminal interaction layer. Use a mock file tree for all data
> at this stage, focusing purely on rendering and keyboard interaction.

- [ ] 2.1 **TUI Application Initialization**
- [ ] 2.2 **Core Component Layout**
- [ ] 2.3 **File List Rendering**
- [ ] 2.4 **Keyboard Interaction Logic (with Mock Data)**
- [ ] 2.5 **Responsiveness & Performance**

---

## 3. Decoupling & Packaging

> Goal: Clean up code dependencies, and support distribution as a standalone
> binary or via package managers.

- [ ] 3.1 **Code Decoupling & Interface Abstraction**
- [ ] 3.2 **Project Structure Refinement**
- [ ] 3.3 **Build & Release**
- [ ] 3.4 **Package Manager Support**
- [ ] 3.5 **Documentation**

# Contributing

This project uses `ruff` as code formatter and linter, `ty` as a LSP, `prettier`
as a Markdown file formatter, `uv` to manage dependencies.

## Install tools

1. Clone this repo:

```bash
git clone https://github.com/PILIHU2022/fileman.git
```

2. Install `uv` and `ty`:

```bash
# Arch Linux
sudo pacman -S uv ty
```

3. Install dependencies:

```bash
uv sync
```

All done!

> > [!NOTE] Please keep `pyproject.toml` is in dir to keep the code style is the
> > same.
