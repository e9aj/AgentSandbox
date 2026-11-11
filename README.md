# AgentSandbox

**Give your agents room to work. Not room to wreck things.**

AgentSandbox is an early-stage, open-source, Windows-first desktop application intended to run AI agents in isolated environments with monitoring and permission controls.

> **Security notice:** This repository currently contains a UI foundation only. It does **not** sandbox agents, enforce permissions, or protect your machine. Do not use it to run untrusted code.

## Getting started (development)

Prerequisites: Node.js 22+, Rust stable, Microsoft C++ Build Tools, and WebView2 (see Tauri Windows prerequisites).

```powershell
npm install
npm run tauri -- dev
```

## Roadmap

- [x] Tauri + React Windows desktop foundation
- [ ] Threat model and security architecture
- [ ] VM-backed isolation backend
- [ ] Agent adapters (Hermes first)
- [ ] Policy enforcement and approval gates
- [ ] Auditable logs and change review
- [ ] Security verification and Windows installers

## Compatibility

Windows 11 is the primary target; Windows 10 22H2 is a compatibility target, subject to backend requirements. Windows 10's standard support has ended, so it is not recommended for security-sensitive deployments without appropriate extended security updates.

## Links

- Creator: https://e9aj.pages.dev/
- Repository: https://github.com/e9aj/AgentSandbox

## Licence

Apache-2.0 planned; add the full licence file before publishing or accepting contributions.
