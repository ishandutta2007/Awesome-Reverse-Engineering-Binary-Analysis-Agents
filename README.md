# Awesome-Reverse-Engineering-Binary-Analysis-Agents
# Awesome-Reverse-Engineering-Binary-Analysis-Agents

# Top Reverse Engineering & Binary Analysis Agents Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on AI-Driven Reverse Engineering, Autonomous Binary Analysis, Decompilers, MCP Servers & Malware Sandboxes*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Reverse Engineering & Binary Analysis Agents**. These tools combine disassemblers, decompilers, dynamic instrumentation, and Model Context Protocol (MCP) servers with autonomous AI agents to inspect native binaries, firmware, Electron/JS apps, and malware without source code.

**Examples** include Binary Ninja Cloud, IDA Pro Cloud, Ghidra Server, Cutter Cloud, JEB Decompiler, RevEng.AI, Binarly, VMRay Analyzer, Intezer Analyze, ReversingLabs, and `morluto/rea` (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for AI reverse-engineering agents, MCP decompiler bridges, headless binary analysis frameworks, and self-hosted malware sandboxes — ideal for security researchers, vulnerability analysts, CTF players, and malware reverse engineers.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Binary Ninja Cloud](https://binary.ninja)**  
  Browser-based collaborative reverse engineering platform powered by Vector 35's Intermediate Languages (LLIL/MLIL/HLIL) and decompiler.

- **[IDA Pro & Hex-Rays Cloud](https://hex-rays.com)**  
  Industry-standard commercial disassembler, decompiler, and cloud team collaboration suite for multi-architecture binary analysis.

- **[JEB Decompiler](https://pnfsoftware.com)**  
  Commercial multi-architecture decompiler and reverse engineering suite specializing in Android Dalvik/APK, WebAssembly, and native binaries.

- **[RevEng.AI](https://reveng.ai)**  
  AI-powered binary analysis platform using foundation models for binary code similarity, function recovery, and automated vulnerability discovery.

- **[Binarly](https://binarly.io)**  
  AI-driven firmware and software supply chain security platform detecting hidden vulnerabilities, implants, and cryptographic weaknesses in compiled binaries.

- **[VMRay Analyzer](https://vmray.com)**  
  Agentless hypervisor-based malware analysis and dynamic threat intelligence sandbox designed to evade anti-VM detection.

- **[Intezer Analyze](https://intezer.com)**  
  Automated malware triage and genetic code reuse platform mapping binary code fragments to known threat actors and legitimate software.

- **[ReversingLabs (Spectra Analyze)](https://reversinglabs.com)**  
  High-speed static binary decomposition and software supply chain threat intelligence platform inspecting complex archives and executables.


## Open-Source GitHub Projects

- **[morluto/rea (Reverse Engineer Anything)](https://github.com/morluto/rea)**  
  Open-source MCP server and CLI toolkit connecting AI coding agents (Claude Code, Codex, Cursor, Gemini CLI) to Ghidra, Hopper, IDA, and runtime inspectors to reverse engineer native binaries, Electron apps, and websites with verifiable evidence.

- **[Ghidra & Ghidra Server](https://github.com)**  
  Foundational open-source software reverse engineering (SRE) suite and multi-user collaboration server developed by the NSA.

- **[Rizin & Cutter](https://github.com)**  
  Free, open-source reverse engineering framework and Qt-based GUI powered by Rizin, featuring Ghidra decompiler integration and collaborative workflows.

- **[Radare2](https://github.com)**  
  Portable, scriptable open-source UNIX-like reverse engineering framework, disassembler, debugger, and binary patching toolkit.

- **[GhidraMCP](https://github.com)**  
  Open-source Model Context Protocol (MCP) server allowing LLM agents to autonomously decompile functions, rename symbols, and inspect cross-references in Ghidra.

- **[open-reverselab](https://github.com/LING71671/open-reverselab)**  
  Open-source AI reverse-engineering workspace featuring a desktop app, parallel agent goals, a security knowledge base, and MCP tools for Ghidra, Frida, x64dbg, and Rizin.

- **[Rev·Deck (AI-Assisted Reverse Engineering)](https://github.com/biniamf/ai-reverse-engineering)**  
  Local, evidence-first open-source static analysis workstation pairing a web UI and LLM copilot with a headless Ghidra service.

- **[angr](https://github.com)**  
  Open-source Python binary analysis platform combining static and dynamic symbolic ("concolic") execution for automated vulnerability discovery and exploit generation.

- **[Frida](https://github.com)**  
  Dynamic instrumentation toolkit for developers, reverse-engineers, and security researchers to inject JavaScript and Python hooks into running native processes.

- **[frida-mobile-mcp](https://github.com)**  
  Open-source Mobile Frida MCP server enabling AI agents to perform runtime exploration, hooking, and dynamic analysis on iOS and Android apps.

- **[dnSpy.MCP](https://github.com)**  
  Open-source MCP server for dnSpyEx enabling AI-assisted .NET assembly decompilation, IL inspection, and automated code analysis.

- **[windbg-mcp](https://github.com)**  
  Open-source MCP server exposing WinDbg/DbgEng (user-mode, kernel debugging, crash dumps, and Time Travel Debugging) to AI agents.

- **[CAPA (Mandiant)](https://github.com)**  
  Open-source tool that automatically identifies capabilities in executable files (PE, ELF, .NET, shellcode) using community-curated rules.

- **[CAPEv2](https://github.com)**  
  Open-source automated malware analysis and configuration extraction sandbox serving as a self-hosted alternative to VMRay and Joe Sandbox.

- **[Qu1cksc0pe](https://github.com)**  
  All-in-one open-source static malware and binary analysis framework supporting Windows, Linux, macOS, Android APKs, and document payloads.

- **[Detect It Easy (DIE)](https://github.com)**  
  Open-source programmatic file type, packer, compiler, and protector identification engine for rapid binary triage.

- **[JADX](https://github.com)**  
  Popular open-source Dex-to-Java decompiler with CLI and GUI interfaces for reverse engineering Android APKs and DEX bytecode.

- **[ILSpy](https://github.com)**  
  Open-source .NET assembly browser and decompiler supporting C# reconstruction, BAML decompilation, and ReadyToRun binaries.

### Additional Strong Open-Source Options

- **[x64dbg](https://github.com)** for open-source x64/x32 dynamic debugging on Windows with extensive plugin and scripting support.
- **[Binwalk](https://github.com)** for open-source firmware extraction, entropy analysis, and embedded file system carving.
- **[ImHex](https://github.com)** for open-source hex editing, custom binary pattern language parsing, and data visualization.
- **[Speakeasy](https://github.com)** and **[Unicorn Engine](https://github.com)** for CPU emulation and safe shellcode/malware execution without full OS overhead.
- Many community **IDA MCP bridges**, **Binary Ninja AI plugins**, and **Decompiler-as-a-Service Docker images** for agentic reverse engineering pipelines.

**Frameworks for building custom systems**: Combine **morluto/rea**, **Ghidra / GhidraMCP**, **Frida**, and **angr** with **CAPEv2** and **CAPA** for autonomous, evidence-backed static and dynamic binary analysis agents.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Always analyze untrusted binaries and malware samples inside isolated, air-gapped virtual machines or sandboxes (e.g., CAPEv2) to prevent host compromise.
- Only reverse engineer software, firmware, and binaries that you own, have explicit authorization to audit, or are permitted to study under applicable interoperability and security research laws.

---

**Made for reverse engineers, malware analysts, vulnerability researchers, and AI security agent builders.**  
Let's make binary analysis and reverse engineering faster, reproducible, and open.
