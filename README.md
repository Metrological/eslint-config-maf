# [ESLint Config MAF](https://git.io/eslint-config-maf "ESLint Config MAF")
Configuration files for ESLint

To use this from your IDE:
- Sublime Text: https://packagecontrol.io/packages/ESLint
- WebStorm: https://www.jetbrains.com/help/webstorm/2016.2/eslint.html
- VS Code: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
- TextMate: https://github.com/natesilva/javascript-eslint.tmbundle

## TODO:
- [x] test maf.js with linter as well, before release to internal
- [x] run script on apps dir to test output
- [/] ignore maf + ui's + sdk, etc... for now, but discuss with Albert how to handle
- [x] run lint only on complete app file, to prevent undefined errors? requires source mapping!
- [x] run script to determine most made errors
- [x] release to internal teams via flowdock (& mail???) met mooi verhaaltje
- [ ] fix TODO's in SDK code
- [x] add Animator and Browser globals
- [x] ignore iframe apps
- [ ] fix stripcomments to not remove eslint comments...
- [ ] use workers! https://github.com/Metrological/maf-release/blob/master/server.js
- [x] provide shortcut urls to all rule definitions for ESLint - only for internal?
- [ ] make console logger maf into plugin formatter for eslint
- [ ] make formatting of console output better
- [ ] error grouping by type/rule?
- [ ] add packages to yarn as well
- [x] add bin file/link for easy starting sdk
- [ ] make console output linkable via chrome dev tools workspaces - fix console mapping in maf?
- [ ] update to latest node version 6.9.1
- [ ] do including/bundling of file in eslint processor plugin - pre/post process
- [ ] release to public maf-sdk
- [ ] publish this and other config to NPM and update other repos
- [ ] add dependency indicators: david-dm, etc... for public sdk + config; https://greenkeeper.io/ https://npm-stat.com/ charts.html?package=eslint-find-rules&from=2015-08-01 https://nodei.co/npm/semantic-release/ (image) https://www.sourceclear.com/
- [ ] add badges; https://shields.io/; https://github.com/sarbbottam/eslint-find-rules
- [ ] verify if we can implement https://github.com/semantic-release/semantic-release
- [ ] publish all possible to NPM
- [ ] incorporate in dashboard/release server
- [ ] more rules/plugins;
  - azeemba/eslint-plugin-json
  - sindresorhus/eslint-plugin-unicorn
  - Trott/eslint-plugin-new-with-error
  - johnstonbl01/eslint-no-inferred-method-name
  - buildo/eslint-plugin-no-loops
  - dustinspecker/eslint-plugin-no-use-extend-native
  - selaux/eslint-plugin-filenames
  - alex-shnayder/eslint-plugin-no-empty-blocks
  - sarbbottam/eslint-find-rules
- [ ] own rules;
  - provide shortcut urls to MAF docs for rule explainations
  - in separate repo so maf extends two others
  - typeOf
  - don't extend/overwrite/append to MAF namespace/components
  - (un)subscribe - but only in maf repo -> so that extends this default config
  - check for unnesecary adding of components to view.elements or view.controls
  - geen maf scope functies in function die in global scope is gedefineerd, e.g. zonder var/ als statement
