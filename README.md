# skill-improver

"Runs an autonomous review-and-fix improvement loop over a Claude Code skill until a review comes back clean, with a cross-round findings ledger, escalation when fixes stop converging, and a mechanical scope guard. Reviews are performed by the plugin-dev skill-reviewer agent. Use to fix skill quality issues, iteratively refine a skill, or resume a loop after an escalation ('fix my skill', 'improve this skill until it passes review', 'skill improvement loop'). NOT for a one-time review — use the plugin-dev skill-reviewer agent directly."

## Overview

This directory contains the operational guidance for the `skill-improver` skill. Start with [SKILL.md](SKILL.md), which defines when to use it and the workflow it provides.

## Usage

Install or reference this directory through your agent's skill-discovery mechanism, then invoke `skill-improver` when the task matches the description above. Review linked resources in `SKILL.md` only when that workflow calls for them.
