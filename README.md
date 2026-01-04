# Claude Code Skills

A collection of custom skills for [Claude Code](https://claude.ai/code).

## Available Skills

| Skill | Description |
|-------|-------------|
| [pinme](./pinme) | Deploy static websites to IPFS using PinMe CLI |

## Installation

Clone the repository and copy skills to your Claude Code skills directory:

```bash
git clone https://github.com/glitternetwork/skills.git
cp -r skills/* ~/.claude/skills/
```

Or copy individual skills:

```bash
cp -r skills/pinme ~/.claude/skills/
```

## Usage

After installation, skills are automatically available in Claude Code. Simply describe what you want to do:

- "Deploy this website" - triggers the pinme skill
- "Upload to IPFS" - triggers the pinme skill

## Creating New Skills

Each skill should have:

- `SKILL.md` - Skill definition with metadata and instructions
- `README.md` - Documentation for users

See existing skills for examples.

## License

MIT
