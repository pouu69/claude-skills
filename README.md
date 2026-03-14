# claude-skills

Claude Code custom skills collection.

## Available Skills

| Skill | Description | Source |
|-------|-------------|--------|
| `/plan-ceo-review` | CEO/founder-mode plan review. Three modes: SCOPE EXPANSION, HOLD SCOPE, SCOPE REDUCTION. 10-section deep review with error mapping, security, observability, and deployment analysis. | [gstack](https://github.com/garrytan/gstack) |
| `/plan-eng-review` | Engineering manager-mode plan review. Interactive 4-section review (Architecture, Code Quality, Tests, Performance) with opinionated recommendations. | [gstack](https://github.com/garrytan/gstack) |
| `/retro` | Weekly engineering retrospective. Analyzes commit history, work patterns, code quality metrics with persistent history and trend tracking. Team-aware. | [gstack](https://github.com/garrytan/gstack) |

## Setup

Copy skills to your Claude Code skills directory:

```bash
git clone git@github.com:pouu69/claude-skills.git ~/.claude/skills/claude-skills
```

Or symlink individual skills:

```bash
git clone git@github.com:pouu69/claude-skills.git /tmp/claude-skills
ln -s /tmp/claude-skills/plan-ceo-review ~/.claude/skills/plan-ceo-review
ln -s /tmp/claude-skills/plan-eng-review ~/.claude/skills/plan-eng-review
ln -s /tmp/claude-skills/retro ~/.claude/skills/retro
```

