# Vault CMS Presets

This repository contains preconfigured templates for [Vault CMS](https://github.com/davidvkimball/vault-cms) tailored for specific [Astro](https://astro.build) themes and projects.

## How to use

These presets are designed to be installed using the [Vault CMS CLI](https://github.com/davidvkimball/vault-cms#installation-guide). 

Run the following command in your Astro project root and follow the prompts:

```bash
# Using pnpm
pnpm create vault-cms --template template-name

# Using npm
npm create vault-cms --template template-name

# Using yarn
yarn create vault-cms --template template-name
```

*Note: Replace `template-name` with `starlight`, `slate`, or `chiri`.*

### Available Presets

| Preset | Target Theme |
| :--- | :--- |
| **starlight** | [Starlight](https://starlight.astro.build/) |
| **slate** | [Slate](https://github.com/SlateDesign/slate-blog) |
| **chiri** | [Chiri](https://github.com/the3ash/astro-chiri) |

## About Vault CMS

Vault CMS allows you to use [Obsidian](https://obsidian.md) as a powerful, local-first content management system for your Astro website. It features auto-detection of content types, frontmatter analysis, and a preconfigured workspace optimized for Astro workflows.

For more information, visit the [main Vault CMS repository](https://github.com/davidvkimball/vault-cms).
