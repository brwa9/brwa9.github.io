# brwa9.github.io

## Why Are Claude Sonnet and Other Premium Models Missing in VS Code?

If you don't see **Claude Sonnet** or other premium models in the GitHub Copilot Chat model picker inside VS Code, here's why and how to fix it.

### I Have the GitHub Student Developer Pack

The **GitHub Student Developer Pack** grants you free access to **GitHub Copilot Student**, which includes:

- ✅ Unlimited completions
- ✅ Access to **premium models** in Copilot Chat (including **Claude Sonnet**)
- ✅ Access to the Copilot coding agent
- ✅ A monthly allowance of premium requests

> **Claude Sonnet is included with your Student plan.** You do NOT need to upgrade to see it.

If you have the Student Pack but don't see Claude Sonnet, follow the troubleshooting steps below.

### Model Availability by Plan

| Model | Free | Student / Pro¹ | Pro+ | Business / Enterprise |
|-------|------|----------------|------|-----------------------|
| GPT-4o | ✅ | ✅ | ✅ | ✅ |
| Claude Sonnet | ❌ | ✅ | ✅ | ✅ |
| Gemini models | ❌ | ✅ | ✅ | ✅ |
| Claude Opus & all advanced models | ❌ | ❌ | ✅ | ✅ |

> ¹ **Student** (free via GitHub Student Developer Pack) and **Pro** ($10/month) have equivalent model access.

> **Note:** If you are looking for Claude Opus (sometimes referred to as the "Plus" model), that requires **Copilot Pro+** ($39/month). Claude Sonnet, however, is available on the Student plan.

### Steps to Fix Missing Models (Student Pack)

#### Step 1 — Verify your Student Pack is active and linked to Copilot

1. Go to [github.com/settings/copilot](https://github.com/settings/copilot)
2. Make sure your plan shows **GitHub Copilot Student** (not Free)
3. If it shows "Free", you need to activate your Student Pack benefit:
   - Visit [education.github.com/students](https://education.github.com/students)
   - Click **Get student benefits** and verify your student status
   - Once approved, return to [github.com/settings/copilot](https://github.com/settings/copilot) to activate Copilot Student

#### Step 2 — Update VS Code and extensions

1. Update **VS Code** to the latest version from [code.visualstudio.com](https://code.visualstudio.com/)
2. Open the Extensions panel (`Ctrl+Shift+X` / `Cmd+Shift+X`)
3. Search for **"GitHub Copilot"** — update both the **GitHub Copilot** and **GitHub Copilot Chat** extensions if an update is available

#### Step 3 — Select Claude Sonnet in VS Code

1. Open GitHub Copilot Chat (`Ctrl+Alt+I` / `Cmd+Option+I`)
2. At the bottom of the chat input box, click the current model name (e.g., "GPT-4o" or "Auto")
3. Select **Claude Sonnet** from the dropdown list

#### Step 4 — Sign out and back in (if models still don't appear)

1. Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
2. Run `GitHub Copilot: Sign Out`
3. Run `GitHub Copilot: Sign In` and sign in with the GitHub account that has the Student Pack

### VS Code Workspace Settings

This repository includes a `.vscode/settings.json` file with recommended GitHub Copilot settings. These settings ensure Copilot is enabled across all file types in this workspace.

### References

- [GitHub Copilot plans and pricing](https://github.com/features/copilot)
- [GitHub Copilot Student plan](https://docs.github.com/en/copilot/about-github-copilot/plans-for-github-copilot#github-copilot-student)
- [How to get free access as a student](https://docs.github.com/en/copilot/how-tos/manage-your-account/free-access-with-copilot-student)
- [Changing the AI model for Copilot Chat](https://docs.github.com/en/copilot/using-github-copilot/ai-models/changing-the-ai-model-for-copilot-chat)
- [Supported AI models in GitHub Copilot](https://docs.github.com/en/copilot/using-github-copilot/ai-models/supported-ai-models-in-copilot)