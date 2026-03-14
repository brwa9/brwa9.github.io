# brwa9.github.io

## Using Claude Sonnet & Claude Opus (Plus) Models in VS Code

This repository is configured to use **Claude 3.5 Sonnet** as the default GitHub Copilot model in VS Code.

### Why can't I see Sonnet or Opus/Plus models in VS Code?

If these models are not appearing in your VS Code GitHub Copilot Chat, here are the steps to enable them:

#### 1. Prerequisites
- Install the latest version of the **GitHub Copilot** and **GitHub Copilot Chat** extensions in VS Code.
- Ensure you have an active **GitHub Copilot Individual, Business, or Enterprise** subscription.

#### 2. Select a Model in Copilot Chat
1. Open **GitHub Copilot Chat** in VS Code (click the chat icon in the sidebar).
2. Click on the **model picker** dropdown at the top of the chat panel (it shows the current model name, e.g., "GPT-4o").
3. Select **Claude 3.5 Sonnet** or **Claude 3 Opus** from the list.

> **Note:** If the model picker is not visible, make sure you are on VS Code version **1.90 or later** and have the latest Copilot Chat extension installed.

#### 3. Set the Default Model via Settings
The `.vscode/settings.json` in this repository sets `claude-3.5-sonnet` as the default model. This ensures Copilot Chat uses Sonnet automatically when you open this project.

#### 4. Enable Model Access (Enterprise/Business)
If you are on a **GitHub Copilot Business or Enterprise** plan and still cannot see these models:
- Ask your **organization admin** to enable Claude models under **Organization Settings → Copilot → Policies → Claude models**.

#### Available Models
| Model | ID | Notes |
|---|---|---|
| Claude 3.5 Sonnet | `claude-3.5-sonnet` | Fast, highly capable (recommended) |
| Claude 3 Opus | `claude-3-opus` | Most powerful Claude model |
| GPT-4o | `gpt-4o` | OpenAI flagship model |
| o1 | `o1` | OpenAI reasoning model |