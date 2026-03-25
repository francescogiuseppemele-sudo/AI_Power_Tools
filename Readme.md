# AI Power Tools (APT) 🚀

AI Power Tools is a browser extension for ChatGPT, Claude, and Gemini, built to improve recap workflows, context management, prompt reuse, exports, and power-user productivity.

It adds a practical workflow layer on top of modern AI chat platforms, helping users handle long conversations, preserve project continuity, organize instructions, and reduce repetitive work.

---

## Supported Platforms

AI Power Tools is designed to work on:

- ChatGPT
- Claude
- Gemini

---

## Installation

### Firefox
Install the extension from Firefox Add-ons:

**[Install on Firefox]([https://addons.mozilla.org/en-US/developers/addons](https://addons.mozilla.org/it/firefox/addon/ai-power-tools/))**

### Chrome
Chrome Web Store release: **Coming Soon**

---

## What AI Power Tools Does

AI Power Tools is designed for users who work seriously inside AI chats and need more than a simple prompt box.

It helps with:

- transferring large project context into a fresh conversation
- reducing token waste
- reusing prompts and workflow instructions
- monitoring conversation size and context pressure
- exporting useful content
- improving structured work inside long technical chats

---

# Main Features

## 1) Smart Recap

Smart Recap generates a structured handoff of the current chat so you can continue the same project in a new conversation without losing the important context.

### What it does
It analyzes the current conversation and compresses the key working state into a reusable transfer block.

Typical elements include:
- project objective
- current state
- tech stack
- important files
- recent conversation context
- current direction of work

### How to use it
1. Open a long conversation in ChatGPT, Claude, or Gemini.
2. Open AI Power Tools.
3. Click **Smart Recap**.
4. Wait for the extension to generate the recap block.
5. Copy the generated output.
6. Start a new chat.
7. Paste the recap block at the top of the new conversation.

### Best use case
Use Smart Recap when:
- the chat is getting too long
- the model is starting to forget details
- you want a cleaner new session
- you want to continue a project without manually rewriting the whole context

---

## 2) Session Resume

Session Resume creates a denser and more compact transfer block than Smart Recap, optimized for lower token usage.

### What it does
It produces a more compressed version of the current project/session state while keeping the essential information.

### How to use it
1. Open the current AI conversation.
2. Open AI Power Tools.
3. Click **Session Resume**.
4. Copy the generated compact output.
5. Paste it into a new chat when you want a lighter handoff.

### Best use case
Use Session Resume when:
- you want to save tokens
- you already know the project and only need the essentials
- you want a smaller context transfer than a full recap

---

## 3) Context / Token Awareness

AI Power Tools helps you understand when a conversation is getting too large or risky to continue.

### What it does
It provides a visual context awareness indicator so you can judge whether the session is still healthy or whether it is time to move to a fresh chat.

Typical status logic:
- **Green**: healthy conversation size
- **Yellow**: large conversation, increasing context pressure
- **Red**: conversation may be too large or unstable, recap recommended

### How to use it
1. Work normally inside the chat.
2. Keep an eye on the context/token indicator.
3. When the indicator becomes large-risk or unstable, use **Smart Recap** or **Session Resume**.

### Best use case
Use it to avoid:
- hidden context degradation
- model confusion
- forgetting earlier instructions
- messy late-session behavior

---

## 4) Prompt Library

Prompt Library lets you save prompts you use often and reuse them quickly.

### What it does
It stores useful prompts so you do not need to rewrite them every time.

Examples:
- coding prompts
- review prompts
- debugging prompts
- summarization prompts
- writing prompts
- workflow prompts

### How to use it
1. Open AI Power Tools.
2. Go to **Prompt Library**.
3. Save a prompt you want to reuse.
4. Give it a clear name.
5. When needed later, reopen the library.
6. Select the saved prompt and reuse or copy it.

### Best use case
Use it when:
- you repeat the same prompt patterns often
- you want consistency across sessions
- you want faster workflow execution

---

## 5) Pinned Instructions

Pinned Instructions allow you to keep persistent workflow rules ready for reuse.

### What it does
It stores stable instructions you want to repeatedly apply across recaps, prompts, or working sessions.

Examples:
- output formatting rules
- coding style rules
- language preferences
- project-specific behavioral instructions
- workflow constraints

### How to use it
1. Open AI Power Tools.
2. Go to **Pinned Instructions**.
3. Add your recurring instruction blocks.
4. Save them.
5. Reuse them when generating recaps or when preparing a new session.

### Best use case
Use it when you always want the AI to follow certain rules without rewriting them manually.

---

## 6) Export Tools

Export Tools help you extract useful content from a conversation for storage, documentation, or reuse.

### What it does
It lets you preserve important material generated during a session.

Possible examples include:
- recap exports
- reusable text blocks
- project handoffs
- saved outputs for documentation
- structured working notes

### How to use it
1. Open the conversation you want to preserve.
2. Open AI Power Tools.
3. Use the relevant export option.
4. Save or copy the output for later use.

### Best use case
Use export tools when:
- you want to archive useful work
- you want to document project progress
- you want reusable material outside the chat

---

## 7) Multi-Chat Merge (PRO)

Multi-Chat Merge helps combine selected content from multiple conversations into one reusable context block.

### What it does
It allows advanced users to assemble context from more than one chat and build a cleaner master handoff.

### How to use it
1. Open the extension.
2. Select the merge workflow.
3. Choose the relevant messages or chat segments you want to combine.
4. Generate the merged output.
5. Copy the resulting block into a new master session.

### Best use case
Use it when:
- project information is spread across multiple chats
- you want to consolidate fragmented work
- you want a single clean session from scattered conversations

---

## 8) Code Minimap / Code Navigation (PRO)

Code Minimap helps technical users navigate code-heavy conversations more efficiently.

### What it does
It identifies code areas or code-related structure in the conversation and helps you access them faster.

### How to use it
1. Open a code-heavy conversation.
2. Open AI Power Tools.
3. Open the code navigation or minimap tool.
4. Jump through the available code sections more quickly.

### Best use case
Use it when:
- the conversation contains a lot of code
- you need faster navigation
- you are reviewing long technical sessions

---

## 9) Diff Tracker (PRO)

Diff Tracker is designed to help users understand what changed between code versions.

### What it does
It helps highlight or organize code changes more clearly, reducing guesswork during iterative AI-assisted coding.

### How to use it
1. Generate or review code changes in the chat.
2. Open **Diff Tracker**.
3. Compare the relevant changes.
4. Use the result to update your local files more safely.

### Best use case
Use it when:
- you are applying AI-generated code patches
- you want clearer visibility into modifications
- you want less confusion during repeated edits

---

## 10) Dependency Hunter

Dependency Hunter helps identify libraries, packages, or install requirements mentioned in the conversation.

### What it does
It extracts likely dependencies and helps you turn them into usable install actions more quickly.

### How to use it
1. Open a conversation containing setup or code instructions.
2. Open **Dependency Hunter**.
3. Review the detected dependencies.
4. Use the generated install suggestions in your terminal or project setup.

### Best use case
Use it when:
- the AI mentions several packages
- you want faster setup
- you do not want to manually scan the whole chat for dependencies

---

## 11) Right-Side Toolbar Layout

AI Power Tools uses a sidebar-oriented layout designed to stay accessible without covering the AI input area.

### What it does
It keeps the extension tools available while reducing interference with the chat UI.

### Why it matters
This is especially useful on modern AI websites where bottom overlays can block the input box or reduce usable space.

---

## 12) Compact UI

Compact UI mode makes the extension less invasive and more space-efficient.

### What it does
It reduces visual footprint while keeping the main workflow tools accessible.

### Best use case
Use it if you want:
- less screen occupation
- a cleaner look
- a more minimal working environment

---

## 13) Freemium Model

AI Power Tools includes both free functionality and PRO-only functionality.

### What it means
Some tools are available to all users, while advanced workflow modules are reserved for PRO access.

### Typical structure
**Free**
- core workflow utilities
- base recap/productivity features

**PRO**
- advanced workflow tools
- enhanced productivity modules
- selected power-user features

---

# How to Use AI Power Tools in a Real Workflow

A common workflow looks like this:

## Workflow Example: Continuing a Large Project
1. Work normally in ChatGPT, Claude, or Gemini.
2. Watch the context/token awareness indicator.
3. When the conversation becomes too large, open AI Power Tools.
4. Generate a **Smart Recap** or **Session Resume**.
5. Copy the generated handoff.
6. Start a fresh conversation.
7. Paste the handoff at the top.
8. Continue the project with a cleaner context window.

## Workflow Example: Reusing Instructions
1. Save important recurring instructions in **Pinned Instructions**.
2. Save repeated prompt templates in **Prompt Library**.
3. Reuse both when starting new chats or recap sessions.

## Workflow Example: Technical / Coding Sessions
1. Use recap tools to keep project continuity.
2. Use code navigation/minimap for large code discussions.
3. Use diff tracking to understand what changed.
4. Use dependency tools to speed up project setup.

---

# Who It Is For

AI Power Tools is built for:

- developers
- engineers
- technical users
- researchers
- prompt-heavy users
- people running long project conversations
- anyone who needs more structure than the default AI chat interface provides

---

# Why Use It

Modern AI chats are powerful, but long sessions become messy fast.

AI Power Tools helps solve common problems such as:
- losing context
- wasting tokens
- repeating the same prompts
- forgetting project rules
- struggling to continue large sessions cleanly
- managing code-heavy conversations inefficiently

---

# Notes

- AI Power Tools is designed to enhance workflow, not replace the underlying AI platform.
- Feature availability may vary depending on platform, browser, and plan.
- PRO features require an active PRO entitlement where applicable.

---

# Roadmap

Planned or ongoing directions may include:
- Chrome Web Store release
- continued UI refinement
- additional workflow modules
- stronger cross-platform consistency
- further improvements for technical users

---

# Developer / Project Links

- Firefox Add-ons: [Install on Firefox]([YOUR_FIREFOX_ADDON_URL](https://addons.mozilla.org/it/firefox/addon/ai-power-tools/))
- Official site: [Add your site URL here]
- Chrome Web Store: Coming Soon

---

# License

Choose the license you want to apply to this repository.
If you do not want reuse by others yet, leave the repository without an open-source license for now.
