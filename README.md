# brwa9.github.io

## Why Are Claude Sonnet and Claude Plus/Opus Models Missing in VS Code?

If you don't see **Claude Sonnet** or **Claude Opus (Plus)** models in the GitHub Copilot Chat model picker inside VS Code, here's why and how to fix it.

### Requirements

| Model | Required Plan |
|-------|--------------|
| GPT-4o | Copilot Free, Pro, Pro+, Business, Enterprise |
| Claude Sonnet | Copilot Pro+, Business, or Enterprise |
| Claude Opus (Plus) | Copilot Pro+, Business, or Enterprise |
| Gemini models | Copilot Pro+, Business, or Enterprise |

### Steps to Enable These Models

1. **Upgrade your GitHub Copilot plan** to **Pro+**, **Business**, or **Enterprise**:
   - Go to [github.com/settings/copilot](https://github.com/settings/copilot)
   - Choose a plan that includes premium models

2. **Update VS Code** to the latest version (1.96 or newer recommended)

3. **Update the GitHub Copilot and GitHub Copilot Chat extensions** in VS Code:
   - Open the Extensions panel (`Ctrl+Shift+X` / `Cmd+Shift+X`)
   - Search for "GitHub Copilot" and click **Update** if available

4. **Select the model in VS Code**:
   - Open GitHub Copilot Chat (`Ctrl+Alt+I` / `Cmd+Option+I`)
   - Click the model name at the bottom of the chat input box
   - Select **Claude Sonnet** or **Claude Opus** from the list

5. **Sign out and back in** if the models still don't appear after upgrading:
   - Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
   - Run `GitHub Copilot: Sign Out`, then `GitHub Copilot: Sign In`

### VS Code Workspace Settings

This repository includes a `.vscode/settings.json` file with recommended GitHub Copilot settings. These settings ensure Copilot is enabled across all file types in this workspace.

### References

- [GitHub Copilot plans and pricing](https://github.com/features/copilot)
- [Changing the AI model for Copilot Chat](https://docs.github.com/en/copilot/using-github-copilot/asking-github-copilot-questions-in-your-ide#changing-the-ai-model-for-copilot-chat)