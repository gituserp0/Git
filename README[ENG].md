# Repository Guide (English)

This repository organizes schoolwork and hands-on learning in IT, cloud infrastructure, automation, and AI.

## Structure

- `Skola/` contains school materials and uses Swedish folder and file names.
- `Networking/`, `Cybersecurity/`, `Cloud/`, and other topic folders contain personal labs and notes.
- `Automation/` groups scripts by language, workflow tooling, configuration management, and infrastructure as code.
- `AI-and-LLM/Agent-Development/` is for agent projects, integrations, and workflows.

## Safe usage

Never commit passwords, API keys, access tokens, private keys, cloud credentials, or sensitive configuration. Use local environment files that are ignored by Git and provide sanitized example files when needed.

Large virtual-machine disks, generated files, caches, and Terraform state are excluded by the root `.gitignore`.
