# jlindley-marketplace

A Claude Code plugin marketplace containing custom Agent Skills for spike-driven development, requirements facilitation, and game debugging.

## Skills Included

**Collaboration:**
- `defining-spikes` - Create structured spike definitions for parallel exploration
- `executing-spikes` - Execute one spike approach autonomously
- `prd-facilitator` - Transform ideas into requirements documentation

**Debugging:**
- `visual-bug-diagnosis` - Debug visual/spatial bugs in Godot games

## Installation

```bash
cd ~/Code
git clone git@github.com:jlindley/jlindley-marketplace.git
/plugin marketplace add ~/Code/jlindley-marketplace
/plugin install jlindley-skills@jlindley-marketplace
# Restart Claude Code
```

## Updating

```bash
cd ~/Code/jlindley-marketplace
git pull
/plugin uninstall jlindley-skills
/plugin install jlindley-skills@jlindley-marketplace
# Restart Claude Code
```

## Documentation

- [Claude Code Plugins](https://docs.claude.com/en/docs/claude-code/plugins)
- [Agent Skills Guide](https://docs.claude.com/en/docs/claude-code/skills)
