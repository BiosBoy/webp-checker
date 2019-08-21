# CORE - Torn


## 5.3.0
 * Created public folder for static file holding.

## 5.2.1
 * Fixed webpack.config.js fetch polyfill import.
 * Improved storybook running scripts.

## 5.2.0
 * Added fetch polyfill for IE11 support.

## 5.1.1
 * Fixed eslint prevProps & prevState missing.
 * Added new link - money recharging in docs.

## 5.1.0
 * Fixed eslint ts tslint rules.

## 5.0.1
 * Bump up React & React-Dom versions.

## 5.0.0
 * MAJOR V.5.0.0 UPDATE! All files linebreak rule were set to LF (Unix style).

## 4.5.0
 * Added missing ts types in typings.d.ts

## 4.4.1
 * Improved Stylelint settings to become more valuable, because we're only support latest browser.

## 4.3.1
 * Updated apps packages.json scripts runners due to core scripts migration inside bin dir.

## 4.3.0
 * Improved core post-css configuration.

## 4.2.5
 * server, compiler, uploader scripts were moved to the bin dir for more clearly look.

## 4.2.4
 * Fixed webpack env mode for test running (second time).

## 4.2.3
 * Fixed webpack env mode for test running.

## 4.2.2
 * Minor webpack & processor configs improvements.

## 4.2.1
 * Fixed webpack file serving while live developing is running.
 * Fixed cssmodules name collision after its bump up.

## 4.2.0
 * Improved debug info in all of the /config scripts.

## 4.1.0
 * Added brodserlist config into the root.
 * Added few important loaders inside the root package.json.
 * Improved main postcss.config.js in favor of its new required fashion way of configuration.

## 4.0.0
 * Major a whole react-apps update v.4.0.0!
 * Cut and move all of the copypast apps packages to the global root package.json.

## 3.1.2
  * Added remoteStaticPath .env variables for the all apps due to legacy neming collision.
  * Updated processor.js correspondetly.

## 3.0.1
  * Added webpack fix for christmastown building errors (cycle dependency)

## 3.0.0
 * Major core react-apps update v.3.0.0!
 * Fully rewritten server & webpack core arhitecture in favore of better speed, security and modern fashion .

## 2.1.1
 * Added nice debug messages to the /config scripts.

## 2.1.0
 * Upgraded webpack.config.js configuration.
 * Created .npmrc file confog.

## 2.0.3
 * Added JSDoc data for /config/* scripts.

## 2.0.2
 * Reverted .eslintrc line-break rule.

## 2.0.1
 * Up core version in changelog and lerna configs.
 * Fixed postcss module config.

## 2.0.0
 * Added several env variables to the eslintconfig.
 * Created first stabel brand new react-apps server configuration.
## 1.24.3
 * Added missing links in react-apps_links

## 1.24.2
 * Fixed story book svg_defs node position (moved from the end to start inside it).
 * Fixed type error for linearGradient and feDropShadow in React SVG lib.

## 1.24.1
 * MInor icons improvement in upload.js.

## 1.24.0
 * Improved upload script, responceble for the files upload on the server.
 * Updated few packages.

## 1.23.1
 * Fixed tests types in tsconfig.json.

## 1.23.0
 * Improved tsconfig.json.

## 1.22.0
 * Updated lerna config up to v^3.

## 1.21.3
 * Fixed Jest test running with ts/tsx files.

## 1.21.2
 * Fixed lerna config.

## 1.21.1
 * Fixed eslint modules import issue.
 * Fixed Jest async testing environment.

## 1.21.0
 * Added new eslint rules due to react hooks update.

## 1.20.0
 * Upgraded a lot of package.json core scripts due to React v.16.8 upgrade.

## 1.19.0
 * Upgraded webpackConfigFactory due to the core packages update.

## 1.18.0
 * Upgraded storybook configs due to react v.16.8.6 Upgrade and core updates as well.
 * Upgraded storybook storyes due to storybook update itself.

## 1.17.2
 * Fixed global multy-apps collision with lerna and jest.

## 1.17.1
 * Fixed eslint allowAfterThis rule unusefuless by cut it.
 * .babelrc rewritten by babel.config.js for more flexibility.
 * Cuted unuseful postfics on the end of the awesome-typescript-loader loader in webpack config.
 * babel.config.js plugins and presets were updated due to babel upgades and react migration (v.16.6.8).

## 1.16.0
 * Refactored global scss imports.
 * Addded progressive-images-set scss function for varios pixel-sizes images processing.

## 1.15.2
 * Fixed issue with SVG Shadow type checking incompatibility.

# 1.15.3
 * Updated airbnb-eslint-config in yarn.lock.

# 1.15.2
 * Revert fixed typings for SVG props in TS.

# 1.15.1
 * Fixed typings for SVG props in TS.

# 1.15.0
 * Updated storybook imports.
 * Added custom Torn's addons for better testing.

# 1.14.4
 * Added links dropdown in AppHeader.

# 1.14.3
 * Move storybook environment variable from scripts to .env file.

# 1.14.2
 * Fixed title padding in mobile layout.

# 1.14.1
 * Minor icons namespaces fix.

# 1.14.0
 * Added global LAYOUT mediaQueries variables.

# 1.14.0
 * Added global SCSS mediaQueries variables.
 * Updated Global Webpack Config.
 * Minor StoryBook impprovements.

# 1.13.0
 * Added support for SVG shadows in React

# 1.12.1
 * Fixed tslint on pre-commit hook.

# 1.12.0
 * Fixed prettier on pre-commit hook.
 * Fixed eslint on pre-commit hook.

# 1.12.0
 * Updated ESLint from 5.4.0 to 5.8.0

# 1.11.1
 * Added types for webpack, webpack-hot, webpack-dev, webpack-env pacakges.
 * Updated TypeScript to 3.1.1 version.
 * Updated tsconfig.json to support newest JS features.
 * Updated jest.config.json to support TypeScript tests with common imports.
 * Improved global types for TypeScript, now it support common imports and global usage of Redux-dev-tools.
 * Fixed WebpackConfigFactory for normal support of main.js nor main.tsx entry point.

# 1.10.1
 * Fixed TSLint rule for 'export const...'.
 * Make separate load for .scss and .cssmodule.scss syntaxes in webpackConf.

# 1.9.0
 * Updates TSLint rules, create name-convenieses for all projects.
 * Fixed Jest config to make in comportable with .ts|.tsx tests.

## 1.8.1
 * Added TSLint naming-convention.
 * Fixed broken TSLint rule in package.json.

## 1.7.1
 * Added TS types for redux, enzyme, react, jest and other dev packages.
 * Added global types for better handling css|scss|cssmodule|json files in aw-loader compiling.
 * Updated tsconfig.json, added roots for types.
 * Fixed tslint command about incorrect config file matching in package.json.

## 1.6.6
 * Updated tests doc file.
 * Fix for test:dev command.

## 1.6.5
 * Minor fix for eslint nas stylelint rules.
 * Minor fix for useful_links doc.

## 1.6.4
 * Added jest-cli for better testing.

## 1.5.4
 * Fixed ESlint TSlint and STYLElinst rules.

## 1.5.3
 * Minor fixes in TS and JS lint files. Removed standart-eslint-plugins

## 1.5.3
 * Minor fix in TS and JS lint files.

## 1.5.2
 * Fixed max-len in TS and JS lint files.

## 1.5.1
 * Improved styling rules for TS and JS files by new configs for tslint and eslint.
 * Fixed lint-staged for better lints work.
 * Updated webpack vesion to 4.16.5.

## 1.4.0
 * Added support for Jest with TS|TSX file testing. Added tests.md doc file (need more improvenments). Updated docs links in README.md file.

## 1.3.1
 * Fixed tsconfig.json file. Added aw-loader support for accepting the global config file in root dir, instead of parse tsconfig of each app.

## 1.3.0
 // TODO: in future we needs to add 'commitizer npm package' to make our commits more clearly for understanding and more controled from remote source (after on GitHub migration).
 * Added CHANGELOG.md file in the root Torn folder.

## 1.2.2
 * Fixed stylelint rules for better css linting.

## 1.2.1
 * Fixed pre-hook lint-staged modules from uncontrolled file checking.

## 1.2.0
 * Added stylelint linting file based on popular stylint community variants.

## 1.1.0
 * Added styleLint, tslint, jsonlint and pre-hook updates for all crimes.

## 1.0.0
 * Migrate Torn react-apps from JS to TS workflow.
