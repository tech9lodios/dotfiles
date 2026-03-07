# dotfiles

My personal dotfiles and configurations

## Usage

```bash
chmod +x install.sh
./install.sh
```

## GitHub Copilot Agent

This repository includes a custom GitHub Copilot coding agent defined in
[`.github/agents/my-agent.agent.md`](.github/agents/my-agent.agent.md).

### How to use the agent

1. **Open an issue** in this repository describing the task or change you want.
2. **Assign the agent** by assigning `Copilot` as the assignee in the issue sidebar (or alternatively, mention `@github-copilot` in the issue body — either method alone is sufficient).
3. The agent will read the instructions in `.github/agents/my-agent.agent.md` and automatically work on your request inside a pull request.

Example issue body:

```
@github-copilot Please add my Zsh configuration files and update the install script.
```

> **Note:** You need GitHub Copilot access (individual or organization plan) and the repository must be hosted on GitHub for the agent to work.

## License

MIT
