# Claude Skills Collection

Curated collection of Claude Code skills, organized by category.

## Structure

```
skills/
├── development/      # Coding, testing, debugging
├── devops/          # CI/CD, deployment, infrastructure
├── productivity/    # Workflows, automation, organization
├── security/        # Security audits, hardening
├── documentation/   # Docs generation, templates
├── creative/        # Design, art, music
└── utilities/       # General purpose tools
```

## Adding a Skill

When sharing a repository, AIfred will:
1. Analyze if it contains a valid skill (SKILL.md file)
2. Determine the appropriate category
3. Add it to the collection with proper attribution

## Categories

| Category | Description |
|----------|-------------|
| `development` | Code generation, refactoring, testing, debugging |
| `devops` | CI/CD pipelines, deployment, infrastructure as code |
| `productivity` | Workflow automation, task management |
| `security` | Security audits, vulnerability scanning, hardening |
| `documentation` | README generation, API docs, guides |
| `creative` | UI/UX, design systems, art, music |
| `utilities` | General tools, file management, data processing |

## Format

Each skill is stored as:
```
skills/<category>/<skill-name>/
├── SKILL.md          # Main skill definition
├── README.md         # Description and usage (optional)
└── src/              # Supporting files (optional)
```

## Sources

Skills are collected from various sources:
- [anthropics/skills](https://github.com/anthropics/skills) - Official Anthropic skills
- [awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills) - Community collection
- [skillsmp.com](https://skillsmp.com) - Skills marketplace

---

Maintained by [Patrick Cohen](https://github.com/patrickcohen) with help from AIfred 🦞
