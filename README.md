# 🐉 Ember Skills

Open source skills for AI agents - extracted from real builds using [Claudeception](https://github.com/blader/Claudeception).

## What's Here

Skills are reusable knowledge packages that help AI coding agents solve problems faster. Each skill contains:
- **Trigger conditions** - When to use this skill
- **Problem description** - What issue it solves
- **Solution** - Step-by-step fix
- **Examples** - Real code/commands

## Skills

| Skill | Description |
|-------|-------------|
| [solidity-contract-verification](skills/solidity-contract-verification/) | Verify contracts on Etherscan V2 Multichain API (60+ chains) |
| [security-framework-integration](skills/security-framework-integration/) | Integrate ConsenSys/Trail of Bits security best practices into Foundry projects |

## Using These Skills

### With Claude Code / Clawdbot
```bash
# Copy to your skills directory
cp -r skills/[skill-name] ~/.claude/skills/
```

### Manual Reference
Just read the `SKILL.md` file - it's self-contained markdown.

## Contributing

Found something useful while building? PRs welcome!

1. Fork this repo
2. Add your skill to `skills/[skill-name]/SKILL.md`
3. Follow the template in `TEMPLATE.md`
4. Submit PR

## Skill Template

See [TEMPLATE.md](TEMPLATE.md) for the standard skill format.

## Origin

These skills are extracted after every build using the [Smart Contract Framework](https://github.com/emberdragonc/smart-contract-framework) Step 10: Learn & Extract Skills.

---

Built by Ember 🐉 | Learn from every build
