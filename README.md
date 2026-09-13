# Academic Humanizer — OpenAI/Codex GitHub Marketplace wrapper

This repository packages the MIT-licensed
[AIScientists-Dev/academic-humanizer](https://github.com/AIScientists-Dev/academic-humanizer)
as a skill-only OpenAI/Codex plugin.

## Layout

```text
.agents/plugins/marketplace.json
plugins/academic-humanizer/
  .codex-plugin/plugin.json
  NOTICE.md
  skills/academic-humanizer/
    SKILL.md
    LICENSE.txt
    examples/before-after.md
```

## Import into a ChatGPT workspace

Workspace admins can import the repository as a plugin marketplace:

1. Open Workspace settings > Plugins.
2. Choose Add > Import marketplace.
3. Enter this repository URL.
4. Leave Path blank because `.agents/plugins/marketplace.json` is at the repository root.
5. Select Import marketplace.
6. Review the imported plugin and choose the workspace installation policy.

Private GitHub repositories are supported when the importing workspace can authorize GitHub access.

## Codex

The same marketplace layout can be used by Codex. The plugin is skill-only and has no MCP server or external account dependency.

## Upstream and license

Upstream project: https://github.com/AIScientists-Dev/academic-humanizer

The upstream project is MIT licensed. See the included license and NOTICE.

## Public Plugins Directory

Hosting this repository on GitHub makes it importable as a GitHub marketplace. It does not automatically publish the plugin into OpenAI's public Plugins Directory. Public-directory availability is a separate OpenAI distribution/review path.
