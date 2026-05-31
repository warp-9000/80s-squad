---
'@bradygaster/squad-cli': minor
'@bradygaster/squad-sdk': minor
---

Add Yoda as Squad's third built-in agent — a Responsible AI (RAI) reviewer

- Yoda is always on the roster (like Miyagi and McClane), exempt from casting
- Traffic light verdict model: 🟢 Green (proceed), 🟡 Yellow (advisory), 🔴 Red (blocking)
- Background mode by default — only blocks on critical RAI violations
- Phase 1 high-signal checks: credentials, injection, harmful content, bias, PII
- New templates: rai-charter.md, rai-policy.md
- New `.squad/rai/` directory with policy.md and audit-trail.md
- Tiered opt-out model (cannot disable critical checks)
