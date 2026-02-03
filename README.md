# l3-openclaw-contrib

OpenClaw contributions: skills, tools, and documentation.

## About

This repository contains skills and tools developed for use with [OpenClaw](https://github.com/openclaw/openclaw), an AI assistant framework. These contributions are shared publicly for the benefit of the OpenClaw community.

## Skills

### Guardian Angel v2.0

A moral evaluation system using a System-1/System-2 trigger architecture. A lightweight filter runs on all actions, escalating to deliberate analysis only when specific patterns indicate moral risk. Grounded in Thomistic principles.

**Features:**
- Layered gate architecture (fast pattern matching → full analysis only when needed)
- Intrinsic evil detection with immediate stop
- "Ostensibly good" learned whitelist for consistently safe actions
- Comprehensive affected-parties analysis based on *ordo caritatis*
- Reversibility × Commitment matrix for quick risk assessment

📁 [skills/guardian-angel/](skills/guardian-angel/)

## Installation

To use a skill from this repo, copy its folder into your OpenClaw skills directory or reference it via ClawHub.

## License

MIT License — see [LICENSE](LICENSE)

## Author

Leo Linbeck III ([@leo3linbeck](https://github.com/leo3linbeck))

With assistance from Reginald Jeeves 🧐
