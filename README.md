# Awesome AI Reverse Engineering [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI/LLM and MCP tools for reverse engineering: MCP servers for disassemblers and debuggers, agent toolkits, models, benchmarks and guides.

Only use these tools on software you own or are authorized to analyze.

## Contents

- [Agent Toolkits](#agent-toolkits)
- [MCP Servers](#mcp-servers)
  - [IDA Pro](#ida-pro)
  - [Ghidra](#ghidra)
  - [Binary Ninja](#binary-ninja)
  - [radare2](#radare2)
  - [x64dbg](#x64dbg)
  - [Android](#android)
- [Decompiler AI Plugins](#decompiler-ai-plugins)
- [Models, Datasets and Benchmarks](#models-datasets-and-benchmarks)
- [Guides](#guides)

## Agent Toolkits

- [REA](https://github.com/morluto/rea) - MCP server and CLI that lets coding agents reverse engineer native binaries, JS/Electron apps, .NET and websites.

## MCP Servers

### IDA Pro

- [ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) - Bridges IDA Pro with language models through MCP.
- [Hex-Rays IDA MCP](https://github.com/HexRaysSA/ida-mcp) - Official Hex-Rays MCP server for IDA 9.4+.
- [ida-free-mcp](https://github.com/0xshlomil/ida-free-mcp) - Native C++ IDA plugin that runs an MCP HTTP server inside IDA's process.

### Ghidra

- [GhidraMCP](https://github.com/LaurieWired/GhidraMCP) - Ghidra extension plus Python MCP bridge, with a headless mode.
- [ghidra-mcp](https://github.com/bethington/ghidra-mcp) - 200+ MCP tools, GUI plugin and headless server.
- [pyghidra-mcp](https://github.com/clearbluejar/pyghidra-mcp) - Python, headless-first Ghidra MCP server.
- [GhidrAssistMCP](https://github.com/symgraph/GhidrAssistMCP) - Native MCP server extension for Ghidra.
- [GhydraMCP](https://github.com/starsong-consulting/GhydraMCP) - Ghidra plugin with a HATEOAS REST API, MCP bridge and CLI.
- [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP) - Socket-based MCP server for Ghidra.

### Binary Ninja

- [binary_ninja_mcp](https://github.com/fosdickio/binary_ninja_mcp) - Binary Ninja plugin that runs an MCP server for LLM clients.

### radare2

- [radare2-mcp](https://github.com/radareorg/radare2-mcp) - MCP stdio server for radare2.

### x64dbg

- [x64dbgMCP](https://github.com/Wasdubya/x64dbgMCP) - MCP server for x64dbg and x32dbg.
- [x64DbgMCPServer](https://github.com/AgentSmithers/x64DbgMCPServer) - C# MCP server for x64dbg (no license specified).

### Android

- [jadx-ai-mcp](https://github.com/zinja-coder/jadx-ai-mcp) - JADX plugin that exposes an MCP server.
- [apktool-mcp-server](https://github.com/zinja-coder/apktool-mcp-server) - MCP server for Apktool.

## Decompiler AI Plugins

- [DAILA](https://github.com/mahaloz/DAILA) - Decompiler-agnostic plugin for using LLMs inside your decompiler.
- [r2ai](https://github.com/radareorg/r2ai) - LLM-based reversing for radare2.
- [reverser_ai](https://github.com/mrphrazer/reverser_ai) - Binary Ninja plugin that suggests function names from decompiler output using offline local LLMs.

## Models, Datasets and Benchmarks

- [LLM4Decompile](https://github.com/albertan017/LLM4Decompile) - Open-source LLMs that decompile Linux x86_64 binaries into C; includes the HumanEval-Decompile benchmark.
- [Decompile-Bench](https://huggingface.co/collections/LLM4Binary/decompile-bench) - Two million binary-source function pairs for training and 70K for evaluation.
- [decompile-ghidra-100k](https://huggingface.co/datasets/LLM4Binary/decompile-ghidra-100k) - 100K-sample training subset (25K per optimization level) released by the LLM4Decompile team.

## Guides

- [REA documentation](https://rea.tools/guides/) - Official worked guides for agent-driven reverse engineering.
- [AI reverse engineering tools compared](https://reaguide.com/ai-reverse-engineering-tools/) - Community comparison of IDA, Ghidra and agent MCP setups.
- [IDA MCP vs IDA Pro MCP](https://reaguide.com/ida-mcp-vs-ida-pro-mcp/) - How the official and community IDA MCP servers differ.

## Contributing

Contributions are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
