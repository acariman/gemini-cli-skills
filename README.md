# Gemini CLI Skills Collection

A curated collection of [Agent Skills](https://geminicli.com/docs/cli/skills/) designed for the *Gemini CLI*.

This repository serves as a toolbox of specialized workflows and expert personas that you can "install" into your Gemini environment.

## ⚠️ Prerequisites

**Important:** These skills require **Gemini CLI version 0.26.0 or higher**.

The Agent Skills standard and the directory structure used in this repository rely on features introduced in v0.26. Please ensure your CLI is up to date before installing.

```bash
# Check your current version
gemini --version
```

## 🚀 How to Install

You can install these skills directly from your terminal using the Gemini CLI.

To install all available skills:

```bash
gemini skills install https://github.com/acariman/gemini-cli-skills.git
```

To install specifically one of them, such as the Python developer skill, in a particular scope:

```bash
gemini skills install https://github.com/acariman/gemini-cli-skills.git --path code-python --scope workspace
```

### Other useful commands

```bash
gemini skills list  # list all available
```


## 📂 Repository Structure

This repository follows the **Agent Skills Open Standard**. Each folder represents a self-contained skill that can be installed independently.

```
gemini-cli-skills
├── LICENSE
├── README.md
├── skill-a/           # Name of the skill
│   ├── SKILL.md            # REQUIRED: Metadata and Instructions
│   ├── scripts/            # OPTIONAL: Executable scripts (bash, python, etc.)
│   └── assets/             # OPTIONAL: Templates, documents, or static files
└── skill-b/
    └── SKILL.md
```
