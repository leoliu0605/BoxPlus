# Box+

> [!WARNING]
> 本專案主要用於學習 Rust 跨平台實作以及面向個人用途！

使用 `Rust` 打造一款 cross-platform 的 command line tool，靈感來自於 `BusyBox`。

為自己打造設計一款隨開即用，帶著走的萬能工具箱。

## Installation

```bash
# Windows
winget install --id=astral-boxplus -e
```

```bash
# macOS
brew install boxplus
```

```bash
# Linux
wget -qO- https://raw.githubusercontent.com/leoliu0605/BoxPlus/main/install.sh | sh
```

## Key Feature

安裝後，使用 `bp <tool> <option> ...` 來使用此工具。

## TODO

- [ ] pdf
  - [ ] encrypt / decrypt
  - [ ] merge / split
- [ ] bin <-> hex
- [ ] hex <-> dfu
- [ ] bin <-> dfu

## Tech Reference

- [uv](https://github.com/astral-sh/uv)
