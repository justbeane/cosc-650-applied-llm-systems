# CLAUDE.md

## Project

This is the course repository for **COSC 650: Applied LLM Systems** at Maryville University.

COSC 650 is an 8-week graduate course focused on applied large language model systems. The course covers tokenization, transformer architecture, inference, prompting, function calling, retrieval-augmented generation, fine-tuning, evaluation, and responsible use of LLM tools.

This repository will be used for weekly assignments, Google Colab notebooks, experiments, notes, and the final project.

## Repository Structure

Root structure:

- README.md
- CLAUDE.md
- week-01/
- week-02/
- week-03/
- week-04/
- week-05/
- week-06/
- week-07/
- week-08/
- notes/
- project/

## Directory Purposes

- `week-01/` through `week-08/`: Weekly assignments, notebooks, experiments, and reflections.
- `notes/`: Reading notes, research notes, terminology, and useful references.
- `project/`: Final project code, documentation, experiments, and supporting materials.
- `README.md`: Human-facing overview of the repository.
- `CLAUDE.md`: Project context and instructions for AI coding assistants.

## Course Workflow

- Notebooks are created or edited in Google Colab.
- Notebooks should be saved to GitHub using **File > Save a copy in GitHub**.
- Weekly work should be placed in the matching `week-XX/` directory.
- Notes that apply across multiple weeks should go in `notes/`.
- Final project materials should go in `project/`.

## Conventions

- Use **Python 3.11+** for code unless an assignment requires something else.
- Use clear, descriptive filenames.
- Use Markdown for notes and written explanations.
- Use Jupyter notebooks for interactive experiments and Colab-based work.
- Keep assignment files organized by week.
- Include short explanations with code when the purpose is not obvious.
- Prefer readable, educational code over overly compact code.
- Commit messages should describe the actual change, not just say `update` or `fix`.

## Suggested File Naming

Use names that make the topic and week clear.

Examples:

- `week-01/tokenization-notes.md`
- `week-01/bpe-experiment.ipynb`
- `week-02/inference-trace.md`
- `week-03/prompt-engineering-lab.ipynb`
- `notes/llm-terminology.md`
- `project/project-plan.md`

## Python Guidelines

- Use small, readable functions when code becomes repetitive.
- Add comments for non-obvious logic.
- Avoid unnecessary dependencies.
- If a notebook uses a package that is not part of the standard library, include the install command near the top.
- Do not assume API keys are available unless they are loaded from environment variables or explicitly provided in the runtime.

## API Key and Security Rules

- Never commit API keys, tokens, passwords, or secrets.
- Never place API keys directly in notebooks, scripts, Markdown files, or commit history.
- Use environment variables or Colab secrets for API credentials.
- Do not commit `.env` files.
- If a file appears to contain a secret, stop and warn the user before staging, committing, or pushing.

## Git Rules

- Check what is staged before committing.
- Use descriptive commit messages.
- Do not force push unless explicitly instructed.
- Do not delete files or directories without confirmation.
- Do not rewrite commit history unless explicitly instructed.
- Before pushing to `main`, summarize what changed.

## AI Assistant Instructions

When helping with this repository:

- Explain changes clearly and briefly.
- Preserve the existing directory structure unless asked to revise it.
- Ask before deleting or renaming files.
- Keep coursework language clear, direct, and student-facing.
- Do not overcomplicate assignments unless the prompt requires it.
- When writing explanations, prioritize conceptual clarity over excessive technical depth.
- When writing code, favor simple examples that demonstrate the course concept.
- When creating notebooks, include Markdown cells that explain what each section demonstrates.
- When reviewing work, identify both correctness issues and clarity issues.

## Do Not

- Do not delete files or folders without confirmation.
- Do not commit secrets, API keys, `.env` files, or credentials.
- Do not use vague commit messages such as `update`, `stuff`, or `fix`.
- Do not move weekly work outside the matching `week-XX/` folder unless asked.
- Do not add large datasets or generated files unless they are required for an assignment.
- Do not assume the final project topic until it is documented in `project/`.
