# Multi-PR Release Announcement Example

Title: 🚀 Q2 Developer Experience Improvements
Subtitle: Tooling, Testing & Performance — June Release

The Core team is happy to share the Q2 developer experience improvements that have been merged over the past two weeks. These changes are scheduled for the **June release**.

**Testing Infrastructure**
  - Jest 29 -> 30 with native ESM support. [Changelog](https://jestjs.io/blog/2025/01/01/jest-30)
  - New shared test utilities package reducing boilerplate by ~40%
  - PR: https://github.com/acme/frontend-core/pull/2101

**Build Performance**
  - Incremental builds now 3x faster through improved caching strategy
  - Parallel compilation enabled for multi-package workspaces
  - PR: https://github.com/acme/frontend-core/pull/2115

**Developer Tooling**
  - Added pre-commit hook for auto-formatting with Prettier 4
  - New `dev:debug` script with source map support for all packages
  - PR: https://github.com/acme/frontend-core/pull/2123

**⚠️ IMPORTANT ⚠️**

Teams using custom Jest configurations should verify compatibility with Jest 30. See the migration guide in PR #2101 for details.

Questions? Reach out to the Core team!
