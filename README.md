## AI & Agent Tooling

### How I work

[shepherd](https://github.com/rohaquinlop/shepherd) drives each change from an issue to a merge-ready PR. One agent writes the code. A separate read-only agent, with no chat history, reviews it before every push.

study → brief → implement → review (max 3) → push → CI → triage comments → merge-ready

When the cause of a bug is unknown, `/shepherd:diagnose` finds and proves it first. A fresh session then fixes it.

### Claude Code

Plugins and tools for [Claude Code](https://claude.com/product/claude-code).

- [shepherd](https://github.com/rohaquinlop/shepherd): issue → merge-ready PR loop with a fresh read-only reviewer; stops only for decisions that need you
- [crit](https://github.com/rohaquinlop/crit): design work with an independent critique; Figma, HTML prototypes, images, and copy
- [be-terse](https://github.com/rohaquinlop/be-terse): keeps responses terse (Simplified Technical English / caveman modes); modified fork
- [claude-config](https://github.com/rohaquinlop/claude-config): my sanitized Claude Code setup: global instructions, skills, agents, hooks, status line
- [claude-multi-session-handler](https://github.com/rohaquinlop/claude-multi-session-handler): switch between multiple Claude accounts instantly, no re-login; Rust CLI

### Agent infrastructure

Standalone tooling around AI coding agents.

- [michin](https://github.com/rohaquinlop/michin): extensible terminal coding agent harness written in Rust
- [gh-inline-review-comments](https://github.com/rohaquinlop/gh-inline-review-comments): gh CLI extension that posts inline PR review comments; built for AI agents and scripts
- [led-notify](https://github.com/rohaquinlop/led-notify): ThinkPad mic-mute LED as agent status indicator, driven by Claude Code hooks
- [omarchy-agent-collectors](https://github.com/rohaquinlop/omarchy-agent-collectors): Omarchy shell plugin feeding the `omarchy.agents` panel with usage from Pi, OpenCode, and more

---

## Open Source Contributions

- [rust-lang/rust](https://github.com/rust-lang/rust)
  - [PR #109418](https://github.com/rust-lang/rust/pull/109418)
  - [PR #157594](https://github.com/rust-lang/rust/pull/157594)
- [terraform-aws-gitlab-runner](https://github.com/cattle-ops/terraform-aws-gitlab-runner)
  - [PR #962](https://github.com/cattle-ops/terraform-aws-gitlab-runner/pull/962)
- [fluidattacks/makes](https://github.com/fluidattacks/makes)
  - Former maintainer
