---
"@bradygaster/squad-cli": patch
"@bradygaster/squad-sdk": patch
---

Rename built-in agent identities: Scribe → Miyagi (memory & decisions) and Ralph → McClane (work-queue monitor).

This updates all user- and agent-visible surfaces — generated agent folders, charters, `squad.agent.md`, roster/routing, cast summary, coordinator prompt, scaffolded skill docs, and runtime `watch` output — while preserving internal subsystem plumbing (role ids, the `ralph` SDK module, `RalphMonitor`, state files, and internal template filenames).
