# Single PR Announcement Example

Title: 🔧 Webpack 5→6
Subtitle: Build Toolchain Upgrade — April Release Target

The Core team has upgraded Webpack from version 5 to 6 across the Frontend module. The changes have been merged today, **Mar 15th**. Product teams are requested to conduct standard verification procedures. The migration is scheduled to be incorporated into the **April release**.

You can refer to the pull request for more information regarding the upgrade: https://github.com/acme/frontend-core/pull/1842

**Notable Changes**

Among the notable changes are the following:

- webpack 5.94.0 -> 6.2.0. [Changelog](https://github.com/webpack/webpack/releases/tag/v6.0.0)
- webpack-cli 5.1.4 -> 6.0.1
- css-loader 6.11.0 -> 7.1.2
- Dropped support for Node.js 16 in build pipeline
- Native CSS modules support enabled by default

**Impact**

Build times are expected to improve by approximately 20%. No changes to application behavior. Should you have any concerns, please contact the Core team.
