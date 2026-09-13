# Academic Humanizer — OpenAI/Codex GitHub Marketplace wrapper

This repository packages the MIT-licensed [AIScientists-Dev/academic-humanizer](https://github.com/AIScientists-Dev/academic-humanizer) as a skill-only OpenAI/Codex plugin.

## Current layout

```text
.agents/plugins/marketplace.json
plugins/academic-humanizer/
  .codex-plugin/plugin.json
  NOTICE.md
  skills/academic-humanizer/
    SKILL.md
VALIDATION.json
```

## Import into a ChatGPT workspace

Workspace admins can import the repository as a plugin marketplace:

1. Open Workspace settings > Plugins.
2. Choose Add > Import marketplace.
3. Enter this repository URL.
4. Leave Path blank because `.agents/plugins/marketplace.json` is at the repository root.
5. Select Import marketplace.
6. Review the imported plugin and choose the workspace installation policy.

Private GitHub repositories can be used when the importing workspace can authorize access to that repository. For public distribution, change the repository visibility to Public first.

## Codex

The same marketplace layout can be used by Codex. The plugin is skill-only and has no MCP server or external-account dependency.

## Upstream and license

Upstream project: https://github.com/AIScientists-Dev/academic-humanizer

Upstream license: MIT. The upstream copyright and license remain with AIScientists-Dev. See the upstream LICENSE and this repository's `NOTICE.md` for attribution.

## Public Plugins Directory

Hosting this repository on GitHub makes it usable as a GitHub marketplace source. It does not automatically publish the plugin into OpenAI's public Plugins Directory. Public-directory availability is a separate OpenAI distribution/review path.
