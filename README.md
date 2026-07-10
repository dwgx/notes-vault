# Notes Vault

> A personal plain-Markdown vault of programming notes, snippets, and quick references.
>
> 个人纯 Markdown 编程笔记库，代码片段和速查手册。

## Overview / 概述

Notes Vault is a lightweight personal collection of technical notes kept as plain Markdown files. One file per topic, all under a single `notes/` directory. No application to build, no framework to install — the value is the notes themselves, browsable on GitHub or in any editor.

这是一个轻量的个人技术笔记合集，一个话题一个 Markdown 文件，全部放在 `notes/` 目录下。不需要构建，不需要安装任何东西——笔记本身就是全部价值，GitHub 上直接看或者拉到本地随便用什么工具翻都行。

The repo is public and MIT-licensed. Browse freely, take what you need.

仓库公开，MIT 协议。随便看，随便拿。

## Contents / 内容

Notes are grouped by topic, one Markdown file each:

每个话题一个文件，当前覆盖的方向：

- **Languages / 语言特性**: Rust ownership, Go concurrency, Java streams, Kotlin DSL, TypeScript generics, JavaScript async, C++ templates, Python (type hints, dataclasses, decorators, generators, iterators, comprehensions, context managers, lambdas)
- **Functional patterns / 函数式**: closures, map/filter, reduce/fold, partial application
- **Shell & CLI / 命令行**: awk, sed, grep, find, curl, jq, zsh aliases, tmux, ssh tunneling, Linux commands, bash tricks
- **Web & frontend / 前端**: React hooks, CSS flexbox, semantic HTML
- **Tooling & infra / 工具链**: Docker, nginx, CMake, Make, gdb, Git workflow, Vim cheatsheet, VS Code shortcuts
- **Data & misc / 数据和杂项**: SQL snippets, regex patterns, memory-leak notes, performance tuning

<!-- TODO: confirm — as of reading, the note files contain placeholder stubs rather than fully written content. -->

## Project Structure / 项目结构

```
notes-vault/
├── notes/            # One Markdown file per topic
├── README.md
├── LICENSE           # MIT
├── SECURITY.md
└── .gitignore
```

## Usage / 使用方法

Nothing to install or build. Clone and read:

不需要安装，不需要构建。克隆下来直接看：

```sh
git clone https://github.com/dwgx/notes-vault.git
cd notes-vault

# List topics / 列出所有话题
ls notes/

# Read a note / 读一篇笔记
cat notes/vim-cheatsheet.md

# Search across all notes / 全文搜索
grep -ri "rust" notes/
```

Or just browse `notes/` on GitHub directly.

或者直接在 GitHub 上翻 `notes/` 目录。

## Status / 状态

Personal scratchpad, actively used. Content grows and changes without notice.

个人草稿本，持续使用中。内容随时增减，不另行通知。

## License / 许可证

MIT License. Copyright (c) 2026 dwgx. See [LICENSE](LICENSE).

MIT 协议。详见 [LICENSE](LICENSE)。
