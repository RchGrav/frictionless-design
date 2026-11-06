**Frictionless Design**

`frictionless-design` is a portable design philosophy and AI agent skill for building tools that feel well-considered because their parts agree. Distilled from production systems tooling, it helps engineers and coding agents design, implement, and review interfaces, configuration state, build pipelines, and artifact workflows without introducing bookkeeping debt.

**Core Sensibilities**

* **Defaults are home:** Resetting returns users to a stocked, working workbench—never an empty void of nulls.

* **One tool, multiple views:** Interactive (TUI/GUI) and scripted (CLI/API) interfaces manipulate the exact same underlying state.

* **Switches match the activity:** Actions do work once; switches enable visible modes for a workflow; reset cleanly restores baseline state.

* **Curiosity in quarantine:** Staging areas let users experiment freely, with safeguards proportional to the target and explicit promotion to durable artifacts.

* **Self-describing artifacts:** Filenames communicate high-level precedence and conflict outcomes, while lightweight local manifests preserve provenance across renames.

* **Nonblocking honesty:** Unavailable optional integrations never halt the core workflow and never fake a full pass—they state what was skipped and keep moving.

* **Clarity without chores:** Every convenience must pay its own upkeep. Information stays accurate as a natural consequence of normal operation.

**Usage** Drop `SKILL.md` into your agent's skill directory or reference it during architectural reviews, CLI design, and workflow refactoring. The principles operate as guides rather than guards: apply them where they remove user friction, and leave working subsystems alone.
