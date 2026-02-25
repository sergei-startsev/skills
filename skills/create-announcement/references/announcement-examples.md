# Announcement Examples

## Framework Upgrade

```markdown
Title: ⚛️ React 18→19
Subtitle: React has been upgraded from v18.3.12 to v19.1.0

The Core team is pleased to announce that React has been upgraded across all products in the Frontend module today. The migration is scheduled to be incorporated into the **July release**.

You can refer to the pull request for more information regarding the upgrade: https://github.com/acme/frontend-core/pull/1175

It took several months and the efforts of the entire Core team to prepare the module for the React 19 migration (React 19 was [officially released in Dec 2024](https://react.dev/blog/2024/12/05/react-19#react-19-is-now-stable)). This is a significant milestone in the module development history.

**What should I know about React 19**

Check out [React v19](https://react.dev/blog/2024/12/05/react-19) and [React 19 Upgrade Guide](https://react.dev/blog/2024/04/25/react-19-upgrade-guide) to learn more about notable changes including new features, improvements, and breaking changes.

**Impact**

The Core team has worked to make the upgrade as smooth as possible, and we do not expect the changes to impact products. Should you have any concerns or issues related to React 19, please contact the Core team.
```

## Security Patch

```markdown
Title: 🅰️ Angular 18→19
Subtitle: Critical Security Patch — February Release Target

The Core team has upgraded Angular from version 18 to 19 to address **urgent security vulnerabilities** (see [CVE-2025-XXXXX](https://www.cve.org/) and [CVE-2025-YYYYY](https://www.cve.org/) for details). The changes have been merged today, **Jan 2nd**. Product teams are requested to conduct standard verification procedures. The migration is scheduled to be incorporated into the **February release**.

You can refer to the pull request for more information regarding the upgrade: https://github.com/acme/frontend-core/pull/2938

**Notable Changes**

Among the notable changes are the following:

- Components are explicitly marked as non-standalone `standalone: false`
- @angular/\* ^18 -> ^19. [Changelog](https://github.com/angular/angular/blob/main/CHANGELOG.md)
- TypeScript 5.5.4 -> 5.8.3. [Changelog](https://devblogs.microsoft.com/typescript/announcing-typescript-5-8/)
- ngrx 18.2.21 -> 19.2.1. [Changelog](https://github.com/ngrx/platform/blob/main/CHANGELOG.md)
- zone.js 0.14.10 -> 0.15.1
```

## New Language Features

```markdown
Title: 🚀 Welcome ECMAScript 2025
Subtitle: ES2025 is Here — New Language Features Now Available

**What**

On June 25, 2025, the Ecma General Assembly approved ECMAScript 2025 features. These features are now standardized and fully supported in our module!

**What's new in ES2025**

- [RegExp.escape()](https://github.com/tc39/proposal-regex-escaping)
- [Promise.try](https://github.com/tc39/proposal-promise-try)
- [Sync Iterator helpers](https://github.com/tc39/proposal-iterator-helpers)
- [JSON Modules](https://github.com/tc39/proposal-json-modules)
- [Import Attributes](https://github.com/tc39/proposal-import-attributes)
- [New Set methods](https://github.com/tc39/proposal-set-methods)

**🔗 Check out the GitHub discussion post for more details on these features!**

[🚀 ECMAScript 2025 Features Now Supported! · Discussion #338](https://github.com/acme/frontend-core/discussions/338)
```

## Runtime Deprecation Notice

```markdown
Title: ⚠️ Drop Node.js 18 Support

The Core team has discontinued support for Node.js 18 in the Frontend module effective today, **Nov 19, 2025**. If you're currently using Node.js 18 on your local workstation, please upgrade it to version 22.

You can verify your current Node.js version by running: `node --version`

Should you have any questions, please contact the Core team.
```

## New Tooling Announcement

```markdown
Title: 🤖 AI Assistant First-Class Support
Subtitle: AI-Powered Development in the Frontend Module

We're excited to announce that our AI coding assistant now has first-class support in the Frontend repository. This means you can start using the tool right out of the box with minimal setup.

**Comprehensive Documentation**
  - Step-by-step setup guide at https://docs.acme.com/development/ai-assistant
  - Instructions for configuring authentication
  - Tips for local and global settings configuration

**Pre-configured Project Instructions & Settings**
  - Project instructions with codebase conventions and rules
  - Project-scoped settings with security guardrails already in place
  - GitHub integration enabled for seamless workflows

**What is coming**
  - Repo-specific commands (e.g. testing, accessibility, code review)
  - More integrations

We encourage everyone to give it a try! Give it a spin and share your experience with the team.

Questions? Drop them below!
```

## New Skill/Feature Announcement

```markdown
Title: 📄 New Skill: localize
Subtitle: Standardizing i18n across the Frontend Module

We've introduced a new skill to help with internationalization (i18n) and localization (l10n) across the Frontend module.

**What is it?**

The localize skill teaches your AI assistant how to properly internationalize user-facing strings, numbers, and dates using our Localizer API and .properties files. It works in two modes:

- Active mode — Point it at a file or folder and it will scan for hard-coded strings, generate property keys, update .properties files, and replace strings with Localizer calls.
- Passive mode — Automatically kicks in during regular development. When building new features or refactoring code that touches user-facing text, the assistant will ensure proper localization practices are followed.

Give it a try next time you're working on a feature with user-facing labels!
```

## Documentation Release

```markdown
Title: 📚 New Tech Doc: AI Coding Best Practices

A new guide is now available for the community covering [best practices working with AI coding agents](https://docs.acme.com/development/ai-best-practices). The guide is based on extensive hands-on experience from the Core team and applies broadly across different AI coding tools.

**What's covered**:
  - Selecting the right problems for AI assistance
  - Context management (hint: less is more)
  - Effective prompting and iteration (practical advice)
  - Environment setup recommendations
  - Quick checklist before starting with AI tools

**Read it here**: [https://docs.acme.com/development/ai-best-practices](https://docs.acme.com/development/ai-best-practices)

Feedback and contributions welcome! 🤝
```

## Runtime Support Announcement

```markdown
Title: 🟢 Node.js 22 LTS Support
Subtitle: Node v22 is supported for local development and CI runners

[Node.js 22.x was transitioned into Long Term Support (LTS)](https://nodejs.org/en/blog/release/v22.11.0) yesterday and the Core team is excited to announce that Node.js v22 support has been enabled in our module today: https://github.com/acme/frontend-core/pull/3530

**⚠️ IMPORTANT ⚠️**

As part of this update, **we discontinue support of Node.js 18, effective November 19, 2025**. Please upgrade Node.js to version 22 or 20 on your local workstations to ensure ongoing compatibility and support.

You can check your current Node.js version running the following command: `node --version`

Should you have any questions, please contact the Core team.
```
