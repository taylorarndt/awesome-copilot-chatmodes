# 🧠 Awesome Copilot Chat Modes

[![Follow Doug Finke on LinkedIn](https://img.shields.io/badge/Follow-Doug%20Finke%20on%20LinkedIn-blue?logo=linkedin&style=flat-square)](https://www.linkedin.com/in/douglasfinke) [![Follow Doug Finke on X](https://img.shields.io/badge/Follow-Doug%20Finke%20on%20X-black?logo=x&style=flat-square)](https://x.com/dfinke)

[![Subscribe on YouTube](https://img.shields.io/badge/Subscribe-YouTube-red?logo=youtube&style=for-the-badge)](https://www.youtube.com/dougfinke/videos)


A curated collection of custom `chatMode.md` files for VS Code — supercharge your workflows with specialized AI personas.

Works with Copilot Chat in VS Code (Insiders).

## Why Awesome Copilot Chat Modes?

Copilot Chat Modes are a powerful way to customize the behavior of Copilot Chat in VS Code. By creating a `chatMode.md` file, you can define a specific persona or role for Copilot Chat to adopt, tailoring the AI’s responses and capabilities to your needs.

- Discover easy, ready-to-use chat modes that enhance your coding experience, improve productivity, and help you tackle specific tasks more effectively.
- Learn how to create your own custom chat modes to suit your unique workflows and preferences.
- Contribute to the community by sharing your own chat modes and benefiting from the collective knowledge of other prompt engineers.

## Official Documentation

- [Chat mode file example](https://code.visualstudio.com/docs/copilot/chat/chat-modes#_chat-mode-file-example)

## Getting Started


To use any of these custom chat modes:

1. Copy the desired `.chatmode.md` file from the `/chatmodes` directory in this repository to your workspace's `.github/chatmodes` directory (create it if it doesn't exist).
2. Restart VS Code to load the new chat mode.
3. Open the Copilot Chat panel in VS Code.
4. Click the dropdown menu at the bottom of the chat panel and select your custom chat mode from the list.

<img src="assets/vscode-custom-mode-selection.png" width=150>

The chat mode will now be active, and Copilot Chat will respond according to the persona and instructions defined in the chosen `.chatmode.md` file.

## 🧩 Custom Chat Modes

Custom chat modes define specific behaviors and tools for GitHub Copilot Chat, enabling enhanced context-aware assistance for particular tasks or workflows.
> 💡 **Usage**: Create new chat modes using the command `Chat: Configure Chat Modes...`, then switch your chat mode in the Chat input from _Agent_ or _Ask_ to your own mode.

| Title | Description |Stable|Insiders|
| ----- | ----------- |----- |------- |
|[Bullet Points](chatmodes/bullet-points.chatmode.md) | Outputs responses as clear, concise bullet points |[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/bullet-points.chatmode.md) | [![Install in VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-Install-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/bullet-points.chatmode.md) |
|[Claude Code System](chatmodes/claude-code-system.chatmode.md) | Claude-inspired code assistant persona |[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/claude-code-system.chatmode.md) | [![Install in VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-Install-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/claude-code-system.chatmode.md) |
|[Clean Code](chatmodes/clean-code.chatmode.md) | Chat mode for writing and maintaining clean, efficient code |[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/clean-code.chatmode.md) | [![Install in VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-Install-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/clean-code.chatmode.md) |
|[Dashboard Raw Data](chatmodes/dashboard-raw-data.chatmode.md) | Specialized chat mode for dashboard creation and analysis |[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/dashboard-raw-data.chatmode.md) | [![Install in VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-Install-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/dashboard-raw-data.chatmode.md) |
|[Explainer](chatmodes/explainer.chatmode.md) | Chat mode focused on explaining complex concepts and code |[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/explainer.chatmode.md) | [![Install in VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-Install-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/explainer.chatmode.md) |
|[GenUI](chatmodes/genui.chatmode.md) | Generates UI-focused code and explanations |[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/genui.chatmode.md) | [![Install in VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-Install-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/genui.chatmode.md) |
|[GitHub Spark System](chatmodes/github-spark-system.chatmode.md) | GitHub Spark system persona |[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/github-spark-system.chatmode.md) | [![Install in VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-Install-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/github-spark-system.chatmode.md) |
|[GPT-5 System](chatmodes/gpt5-system.chatmode.md) | GPT-5 system persona |[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/gpt5-system.chatmode.md) | [![Install in VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-Install-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/gpt5-system.chatmode.md) |[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/gpt5-system.chatmode.md) |
|[HTML Structured](chatmodes/html-structured.chatmode.md) | Produces HTML-structured output for web contexts |[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/html-structured.chatmode.md) | [![Install in VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-Install-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/html-structured.chatmode.md) |
|[Markdown Focused](chatmodes/markdown-focused.chatmode.md) | Optimized for markdown-formatted answers |[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/markdown-focused.chatmode.md) | [![Install in VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-Install-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/markdown-focused.chatmode.md) |
|[Table Based](chatmodes/table-based.chatmode.md) | Presents information in table format |[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/table-based.chatmode.md) | [![Install in VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-Install-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/table-based.chatmode.md) |
|[Test Writer](chatmodes/test-writer.chatmode.md) | Assistant for writing and maintaining tests |[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/test-writer.chatmode.md) | [![Install in VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-Install-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/test-writer.chatmode.md) |
|[Ultra Concise](chatmodes/ultra-concise.chatmode.md) | Extremely brief, to-the-point responses |[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/ultra-concise.chatmode.md) | [![Install in VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-Install-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/ultra-concise.chatmode.md) |
|[YAML Structured](chatmodes/yaml-structured.chatmode.md) | Outputs responses in YAML structure |[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect?url=vscode%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/yaml-structured.chatmode.md) | [![Install in VS Code Insiders](https://img.shields.io/badge/VS_Code_Insiders-Install-24bfa5?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect?url=vscode-insiders%3Achat-mode%2Finstall%3Furl%3Dhttps://raw.githubusercontent.com/dfinke/awesome-copilot-chatmodes/main/chatmodes/yaml-structured.chatmode.md) |

These chatmodes are from [Claude Code Hooks Mastery](https://github.com/disler/claude-code-hooks-mastery/tree/main/.claude/output-styles): 
Bullet Points, GenUI, HTML Structured, Markdown Focused, Table Based, Ultra Concise, YAML Structured

## 🤖 Agents Extended

**Agents Extended** is an advanced workflow system that leverages GitHub Copilot's custom agent capabilities to create sophisticated multi-agent workflows with automatic handoffs between specialized personas.

Unlike simple chat modes that modify response formatting, Agents Extended creates a complete software engineering team inside VS Code. Each agent is a specialized expert with distinct responsibilities, tools, and the ability to automatically hand off work to other agents when their part is complete.

### How It Works

The Agents Extended system uses:
- **Specialized Agents**: Each agent has a specific role (implementation, review, testing, etc.)
- **Automatic Handoffs**: Agents can trigger handoffs to other agents with structured context
- **Tool Access**: Agents have access to VS Code tools (search, edit, run tests, etc.)
- **Structured Communication**: Agents exchange information using predefined templates to ensure nothing is lost in transition

### Available Agents

| Agent | Role | Handoffs To |
| ----- | ---- | ----------- |
|[Developer Agent](developer.agent.md) | Professional engineering assistant that provides full reasoning, planning, and verification for implementation tasks. Shows complete thought process from understanding through execution. | Reviewer Agent (automatic after implementation) |
|[Reviewer Agent](reviewer.agent.md) | Senior software engineer performing thorough code reviews. Evaluates correctness, maintainability, security, and adherence to standards. Provides structured, actionable feedback. | Developer Agent (when changes needed) |

### Usage Example

1. Start with the Developer Agent for implementation work
2. Developer Agent completes the task and automatically hands off to Reviewer Agent with a structured review request
3. Reviewer Agent performs code review and either approves or hands back to Developer with specific feedback
4. Developer Agent implements feedback and the cycle continues until approval

This creates a real engineering workflow with checks and balances, ensuring higher quality outputs than single-agent approaches.

## Contributing to Open Source

Contributions are welcome! If you have a custom chat mode you'd like to share, please submit a pull request.

----
🌟 Don’t miss out on future updates! Star the repo now and be the first to know about new and exciting chatmodes for VS Code.
