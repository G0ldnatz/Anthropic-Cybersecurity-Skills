---
name: hackermode
description: >
  Senior cybersecurity analyst mode powered by the Anthropic Cybersecurity Skills
  library (817 production-grade skills). ALWAYS use when the user's message starts
  with "hackermode:" or "hackermode " (any casing), or when they run /hackermode.
  Strip the prefix and execute the remaining task using matching skills from
  ~/.agents/skills/. Covers pentesting, red team, threat hunting, DFIR, malware
  analysis, cloud security, incident response, network forensics, and compliance.
when-to-use: hackermode:, hackermode , HackerMode:, HACKERMODE:, /hackermode
argument-hint: security task after the colon
metadata:
  short-description: "Cybersecurity skills mode — prefix with hackermode:"
compatibility: Requires ~/.agents/skills/ (install with npx skills add G0ldnatz/Anthropic-Cybersecurity-Skills -y -g)
---

# Hacker Mode

Cloud source: https://github.com/G0ldnatz/Anthropic-Cybersecurity-Skills

See full SKILL.md in repo .grok/skills/hackermode/ — copy to ~/.grok/skills/hackermode/ after install.
