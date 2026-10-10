# Genesis GitBook + Netlify Template

Template for new repositories to ensure seamless GitBook Site Git Sync and agentic Netlify compatibility.

## Usage

1. Create a new repository from this template (Use this template button).
2. Replace `{{PROJECT_TITLE}}` in `gitbook-docs.yaml` with the project name.
3. Add content directories matching the `content.directory` paths (or adjust the YAML to match actual structure).
4. For GitBook: Connect the repo via Git Sync in the GitBook UI (GitHub → GitBook). The `gitbook-docs.yaml` drives the site structure.
5. For Netlify: Link the repo for continuous deployment. Compatible with Agent Runners and Netlify MCP.

## Presets Included

- `gitbook-docs.yaml`: Schema-compliant site structure mapping.
- `netlify.toml`: Basic build/redirect config for agentic workflows.
- Directory placeholders under `docs/` and `skills/`.

All previous repositories can be updated by copying these files and adjusting directories to existing content (never invent directories).
