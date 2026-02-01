# Contributing to Awesome Claude Skills

Thank you for your interest in contributing! This document provides guidelines for contributing to this skills collection.

## How to Contribute

### Reporting Issues

- Use the GitHub issue tracker to report bugs or suggest features
- Clearly describe the issue including steps to reproduce (for bugs)
- Include relevant details like skill name, Claude Code version, and OS

### Submitting Changes

1. **Fork the repository**
2. **Create a new branch** for your changes
   ```bash
   git checkout -b feature/new-skill-name
   ```
3. **Make your changes** following the guidelines below
4. **Test your skill** thoroughly with Claude Code
5. **Commit your changes** with clear, descriptive commit messages
   ```bash
   git commit -m "Add new skill: financial-modeling"
   ```
6. **Push to your fork**
   ```bash
   git push origin feature/new-skill-name
   ```
7. **Submit a Pull Request** to the main repository

## Adding a New Skill

### Skill Structure

Each skill should follow this directory structure:

```
.github/skills/
└── your-skill-name/
    ├── SKILL.md           # Main skill definition
    ├── README.md          # User-facing documentation
    └── references/        # Optional: supporting materials
        ├── FRAMEWORK.md
        ├── EXAMPLES.md
        └── ...
```

### SKILL.md Format

The main skill file should include frontmatter and comprehensive instructions:

```markdown
---
name: skill-name
description: Brief description of what this skill does and when to use it
license: MIT
metadata:
  author: Your Name
  version: "1.0.0"
  last_updated: "YYYY-MM-DD"
  design_philosophy: "Core principles of this skill"
---

# Skill Name

## Overview
[Detailed description of the skill]

## When to Use This Skill
[Clear triggers and use cases]

## Methodology
[Step-by-step approach]

## Frameworks and Tools
[Any frameworks, templates, or tools used]

## Examples
[Usage examples]
```

### README.md Format

The skill README should be user-friendly:

```markdown
# Skill Name

[Brief overview]

## Overview
[What this skill does]

## Use Cases
- Use case 1
- Use case 2
- Use case 3

## Features
- Feature 1
- Feature 2

## Usage
[How to use the skill with examples]

## Requirements
[Any prerequisites or dependencies]

## Examples
[Real-world examples]
```

### Skill Guidelines

1. **Clear Scope**: Define exactly when the skill should activate
2. **Comprehensive Instructions**: Provide detailed methodology and frameworks
3. **Examples**: Include concrete examples of usage
4. **Best Practices**: Incorporate industry-standard practices
5. **Metadata**: Include author, version, and license information
6. **Testing**: Test thoroughly with Claude Code before submitting

### Skill Quality Standards

- **Actionable**: Skills should provide clear, step-by-step guidance
- **Professional**: Follow industry best practices and standards
- **Well-documented**: Include comprehensive documentation
- **Modular**: Keep skills focused on specific tasks
- **Tested**: Verify the skill works as expected with Claude Code

## Improving Existing Skills

When improving an existing skill:

1. **Maintain backwards compatibility** when possible
2. **Update the version number** in metadata
3. **Update the last_updated date**
4. **Document changes** in your PR description
5. **Test thoroughly** to ensure no regressions

## Documentation Guidelines

### Writing Style

- Use clear, concise language
- Write in English (unless skill is language-specific)
- Use active voice
- Provide concrete examples
- Use proper markdown formatting

### Code Examples

- Include syntax highlighting
- Provide complete, runnable examples when possible
- Add comments to explain complex parts
- Follow language-specific style guides

### Markdown Standards

- Use proper heading hierarchy (H1 → H2 → H3)
- Use code blocks with language specification
- Use tables for structured data
- Use bullet points and numbered lists appropriately
- Include links where relevant

## Updating the Main README

When adding a new skill, update the main README.md:

1. Add your skill to the Available Skills table
2. Add to the appropriate category section
3. Keep descriptions concise (one line)
4. Maintain alphabetical order within categories

Example entry:
```markdown
| [skill-name](.github/skills/skill-name/) | Brief description of what this skill does and key features... |
```

## Code of Conduct

### Our Standards

- **Be respectful** of differing viewpoints and experiences
- **Accept constructive criticism** gracefully
- **Focus on what is best** for the community
- **Show empathy** towards other community members

### Unacceptable Behavior

- Harassment, trolling, or discriminatory language
- Personal attacks or insults
- Spam or excessive self-promotion
- Publishing others' private information without permission

## Questions?

If you have questions about contributing:

1. Check existing issues and documentation
2. Open a new issue with your question
3. Tag it appropriately (e.g., "question", "help wanted")

## License

By contributing to this project, you agree that your contributions will be licensed under the MIT License.

## Recognition

Contributors will be recognized in:
- Git commit history
- Release notes (for significant contributions)
- GitHub contributors list

Thank you for contributing to Awesome Claude Skills! 🎉
