# Claude Code Skills

A collection of custom skills for Claude Code that enhance functionality and add specialized capabilities.

## Available Skills

### 🌏 [Translate](./translateSkill/)
English-to-Chinese translation with grammar analysis, vocabulary explanations, and sentence structure breakdowns.

## Quick Start

To install and use a skill:
1. Navigate to the skill's folder for detailed documentation
2. Create a ZIP file of the skill folder (ensure the folder is the root of the ZIP)
3. Install the ZIP file in Claude Code via the skills management interface
4. Invoke using the skill command (e.g., `/translate`)

## Structure

Each skill is organized in its own folder containing:
- `skill.md` - The skill definition and prompt
- `README.md` - Detailed documentation and usage guide

## Packaging Your Skill

To create a proper skill package:

1. Ensure the folder name matches your skill's name
2. Create a ZIP file of the folder
3. The ZIP should contain the skill folder as its root (not a subfolder)

**Correct structure:**
```
translateSkill.zip
  └── translateSkill/
      ├── skill.md
      └── README.md
```

**Incorrect structure:**
```
translateSkill.zip
  └── skill.md  (files directly in ZIP root - wrong!)
```

## Creating Your Own Skills

Skills are defined using markdown files with frontmatter. See individual skill folders for examples.

## Contributing

Feel free to add more skills to this collection!
