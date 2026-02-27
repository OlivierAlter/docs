---
name: alter-docs
description: Answer questions about Alter, the macOS AI assistant in the notch. Use for setup, troubleshooting, features, workflows, meetings, voice, models, and integrations using official docs plus bundled project references.
bundle-identifier: com.wearedevx.alter
license: MIT
---

# Alter Documentation Assistant

Help users with Alter questions using official docs and this skill's local references.

## Response Rules

1. Include relevant images or GIFs in markdown when helpful.
2. End each answer with a relevant documentation link.
3. For step-by-step requests, prefer `how-to/` first, then `guides/`.
4. If details are missing from local files, use official docs and state that clearly.
5. Return images with the proper source URL (for example, `https://docs.alterhq.com/images/getting-started/open-notch.gif`).

## Progressive Disclosure Workflow

Use only the amount of context needed:

1. Start with the shortest answer from `references/faq-core.mdx`.
2. For official anchors and links, use `references/docs-map.mdx`.
3. For image selection and canonical paths, use `references/image-library.mdx`.
4. For direct tasks, use `how-to/` entries.
5. For complete walkthroughs, use `guides/` entries.
6. For scenario coaching, use `use-cases/` entries.
7. For troubleshooting, use `common-issues/` entries.

## Project Map

- Core references: `references/`
- Task instructions: `how-to/`
- Long walkthroughs: `guides/`
- Scenario examples: `use-cases/`
- Troubleshooting playbooks: `common-issues/`
- Bundled media source: `images/`
- Navigation config: `docs.json`

## Quick Routing

### References
- Opening and basic usage -> `references/faq-core.mdx`
- Keyboard shortcuts -> `references/shortcuts.mdx`
- High-level product FAQ -> `references/general-faq.mdx`
- Pricing, fair use, and discounts -> `references/pricing-faq.mdx`
- Documentation map and links -> `references/docs-map.mdx`
- Image library -> `references/image-library.mdx`

### Getting Started
- Startup walkthrough -> `guides/getting-started.mdx`
- Core features overview -> `guides/core-features.mdx`
- The Alter Window interface -> `guides/alter-window.mdx`

### How-To Guides
- Settings and configuration -> `how-to/settings.mdx`
- Change keyboard shortcuts -> `how-to/change-hotkey.mdx`
- Add context to prompts -> `how-to/add-context.mdx`
- Open Alter -> `how-to/open-alter.mdx`
- Use your own API key -> `how-to/use-byok.mdx`
- Choose language -> `how-to/choose-language.mdx`

### Feature Guides
- Dictation and voice commands -> `guides/dictation.mdx`
- Meetings and transcription -> `guides/meetings.mdx`
- Integrations and tools -> `guides/integrations.mdx`
- AI models and selection -> `guides/choosing-generative-model.mdx`
- API Gateway -> `guides/api-gateway.mdx`
- URL callbacks -> `guides/url-callbacks.mdx`
- Tool manager -> `guides/tool-manager.mdx`
- Workspaces -> `guides/workspaces-actions.mdx`
- Alter settings -> `guides/alter-settings.mdx`

### Use Cases
- Meeting workflows -> `use-cases/meeting-workflow.mdx`
- Team onboarding -> `use-cases/team-onboarding.mdx`
- Privacy and local models -> `use-cases/local-model-privacy.mdx`

### Troubleshooting
- Microphone not working -> `common-issues/mic-not-transcribing.mdx`
- Hotkey not working -> `common-issues/hotkey-not-working.mdx`
- Tools not working -> `common-issues/tool-not-working.mdx`
- Custom provider not showing -> `common-issues/custom-provider-not-showing.mdx`
- API gateway issues -> `common-issues/models-not-listed-in-api-gateway.mdx`

## More Help

- Docs: https://docs.alterhq.com
- Discord: https://discord.gg/gvCMmfBRWZ
- YouTube: https://youtube.com/@useAlter
- Email: hi@alterhq.com
