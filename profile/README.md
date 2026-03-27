# Noumena Digital

This is where we keep all our NPL (NOUMENA Protocol Language) tools and examples. If you're looking to build with NPL, you're in the right place.

## Starter Projects & Examples

Need to get up and running quickly? We've got you covered with repos ranging from dead simple to production-ready.

### [**npl-init**](https://github.com/NoumenaDigital/npl-init)
The bare-bones starter template that powers the `npl init` and `npl init --bare` CLI command.

### [**npl-demo**](https://github.com/NoumenaDigital/npl-demo)
This repo is a good starting point to see what NPL can actually do. The repo has a working backend + frontend that shows off the core concepts. Great for understanding how all the pieces fit together.


### [**npl-replit-starter**](https://github.com/NoumenaDigital/npl-replit-starter)
Simple full-stack application configured to be built with Replit, allowing you to experiment with NPL applications directly in your browser and with Replit Agent development support. Involves backend deployment to NOUMENA Cloud.

https://github.com/NoumenaDigital/noumena-ai-starter
### [**npl-ai-starter**]([https://github.com/NoumenaDigital/npl-replit-starter](https://github.com/NoumenaDigital/noumena-ai-starter))
Starter repository that allows you to build full stack applications using your favorite AI leveraging our battle proven technology stack
* React / Typescript
* NPL backend
* Keycloak for authentication
* docker for the infra provisioning


## Developer Tools

A set of tools to develop and manage NPL application

### CLI & Package Management
- [**npl-cli**](https://github.com/NoumenaDigital/npl-cli) - The NPL command line tool source
- [**homebrew-tools**](https://github.com/NoumenaDigital/homebrew-tools) - Brew tap so you can `brew install NoumenaDigital/tools/npl`

### Editor Support
- [**npl-vscode-extension**](https://github.com/NoumenaDigital/npl-vscode-extension) - VS Code/Cursor extension
- [**npl-language-server**](https://github.com/NoumenaDigital/npl-language-server) - The language server that powers the extension

## Runtime Images

The images repo has Docker containers for the [NPL Runtime](https://documentation.noumenadigital.com/runtime/).

### **Engine**
The workhorse that:
- Runs your NPL code
- Talks to the database
- Exposes the NPL API

### **Read Model**
A data access layer with a GraphQL API.

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

Hit us up through the [NOUMENA Community](https://community.noumenadigital.com/) or GitHub issues on the relevant repo.
