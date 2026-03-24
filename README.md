# quarkus-skills
Agent skills for developing and maintaining Quarkus applications

## Installation

### Using npx skills add

Install all skills from this repository:

```bash
npx skills add quarkusio/quarkus-skills
```

List available skills:

```bash
npx skills add quarkusio/quarkus-skills --list
```

Install specific skills only:

```bash
npx skills add quarkusio/quarkus-skills --skill quarkus-update
```

Install for specific agents:

```bash
npx skills add quarkusio/quarkus-skills -a claude-code
```

### Using Claude Code Plugin System

Within Claude Code, you can also install via the plugin marketplace:

```
/plugin marketplace add quarkusio/quarkus-skills
/plugin install quarkus-development@quarkus-skills
```

## Available Skills

### quarkus-update

Check if a Quarkus project's build files are up-to-date by comparing against reference generated projects. Use this skill when you want to:

- Check if your Quarkus project is up-to-date
- Compare your build configuration against the latest Quarkus version
- Upgrade your Quarkus version with guidance on what changes to make

**Usage:** Ask Claude Code: "Check if my Quarkus project is up to date" or "Update my Quarkus project"

## Learn More

- [npx skills documentation](https://github.com/vercel-labs/skills)
- [Claude Code skills documentation](https://code.claude.com/docs/en/plugin-marketplaces)
