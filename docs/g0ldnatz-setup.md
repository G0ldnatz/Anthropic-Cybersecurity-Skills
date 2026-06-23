# G0ldnatz — Skills Setup

Personal cloud copy of the Anthropic Cybersecurity Skills library.

**Repository:** https://github.com/G0ldnatz/Anthropic-Cybersecurity-Skills

## Auf neuem Rechner installieren

```bash
# Skills global installieren
npx skills add G0ldnatz/Anthropic-Cybersecurity-Skills -y -g

# Hackermode-Trigger kopieren
git clone https://github.com/G0ldnatz/Anthropic-Cybersecurity-Skills.git /tmp/cs-skills
cp -r /tmp/cs-skills/.grok/skills/hackermode ~/.grok/skills/
```

## Hackermode nutzen

```
hackermode: analysiere diesen pcap auf C2 beaconing
```

## Sync mit Upstream

```bash
git remote add upstream https://github.com/mukul975/Anthropic-Cybersecurity-Skills.git
git fetch upstream
git merge upstream/main
```
