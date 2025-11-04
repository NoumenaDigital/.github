# Noumena Digital

Hey there! 👋 This is where we keep all our NPL (NOUMENA Protocol Language) tools and examples. If you're looking to build with NPL, you're in the right place.

## Starter Projects & Examples

Need to get up and running quickly? We've got you covered with repos ranging from dead simple to production-ready.

### [**npl-init**](https://github.com/orgs/NoumenaDigital/npl-init)
The bare-bones starter template that powers `npl init`. Nothing fancy, just what you need to start building.

### [**npl-demo**](https://github.com/orgs/NoumenaDigital/npl-demo)
Want to see what NPL can actually do? This repo has a working backend + frontend that shows off the core concepts. Great for understanding how all the pieces fit together.

### [**npl-integrations**](https://github.com/orgs/NoumenaDigital/npl-integrations)
This is where things get interesting. A full-featured starter with:
- React frontend (because, obviously)
- Python Streamlit frontend (same features, different stack - pick your poison)
- Python services that listen and react to NPL events
- Bash integration tests (yes, actual tests!)

### [**npl-ai-starter**](https://github.com/orgs/NoumenaDigital/npl-ai-starter)
Our AI integration playground. We built this around an insurance claims automation use case that shows:
- How to hook up an LLM without letting it go rogue
- Teams & Slack integrations that actually work
- Real guardrails on AI decision-making (because nobody wants a runaway AI approving million-dollar claims)

## Developer Tools

The stuff that makes your life easier.

### CLI & Package Management
- [**npl-cli**](https://github.com/orgs/NoumenaDigital/npl-cli) - The NPL command line tool source
- [**homebrew-tools**](https://github.com/orgs/NoumenaDigital/homebrew-tools) - Brew tap so you can `brew install` like a civilized person

### Editor Support
- [**npl-vscode-extension**](https://github.com/orgs/NoumenaDigital/npl-vscode-extension) - VS Code/Cursor extension with syntax highlighting and all the good stuff
- [**npl-language-server**](https://github.com/orgs/NoumenaDigital/npl-language-server) - The LSP that powers the extension

## Runtime Packages

The images repo has Docker containers for the NPL Runtime. Here's what's under the hood:

### **Engine**
The workhorse that:
- Runs your NPL code
- Talks to the database
- Exposes the NPL API

### **Read Model**
Your data access layer with a GraphQL API. Query your NPL state without breaking a sweat.

## Quick Start

```bash
# Get the CLI
brew install NoumenaDigital/tools/npl

# Create a project
npl init --project-dir my-project

# Install the VS Code or IntelliJ extension and start coding
```

Then dig into the demo and example repos to see what's possible.

## Need Help?

Hit us up through the [NOUMENA Community](https://community.noumenadigital.com/) or GitHub issues on the relevant repo. We actually read them.
