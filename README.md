# Gemini CLI Skills Collection

A curated collection of [Agent Skills](https://geminicli.com/docs/cli/skills/) designed for the *Gemini CLI*.

This repository serves as a toolbox of specialized workflows and expert personas that you can "install" into your Gemini environment.

## 📂 Repository Structure

This repository follows the **Agent Skills Open Standard**. Each folder represents a self-contained skill that can be installed independently.

```
gemini-cli-skills
├── LICENSE
├── README.md
├── skill-name-A/           # Name of the skill
│   ├── SKILL.md            # REQUIRED: Metadata and Instructions
│   ├── scripts/            # OPTIONAL: Executable scripts (bash, python, etc.)
│   └── assets/             # OPTIONAL: Templates, documents, or static files
└── skill-name-B/
    └── SKILL.md
```

## 🚀 How to Install

You can install these skills directly from your terminal using the Gemini CLI.

### Install the Python Modern Skill
To install all available skills:

```bash
gemini skills install https://github.com/acariman/gemini-cli-skills.git
```

To install specifically one of them, such as the Python developer skill:

```bash
gemini skills install https://github.com/acariman/gemini-cli-skills.git --path code-python
```
