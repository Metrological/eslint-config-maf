[![dependencies Status](https://david-dm.org/metrological/eslint-config-maf/status.svg?style=flat-square)](https://david-dm.org/metrological/eslint-config-maf)
[![dependencies Status](https://david-dm.org/metrological/eslint-config-maf/peer-status.svg?style=flat-square)](https://david-dm.org/metrological/eslint-config-maf)
[![dependencies Status](https://david-dm.org/metrological/eslint-config-maf/optional-status.svg?style=flat-square)](https://david-dm.org/metrological/eslint-config-maf)

# [ESLint Config MAF](https://git.io/eslint-config-maf "ESLint Config MAF")
Configuration files for ESLint

To use this from your IDE, use any of the following plugins:
- [Sublime Text](https://packagecontrol.io/packages/ESLint "Sublime Text")
- [WebStorm](https://www.jetbrains.com/help/webstorm/2016.2/eslint.html "WebStorm")
- [VS Code](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint "VS Code")
- [TextMate](https://github.com/natesilva/javascript-eslint.tmbundle "TextMate")

## TODO:
### To make it work at all;
- maf changes in eslint branch importeren ivm versie in package.json
- nagaan of stripcomments niet eslint comments verwijderd
- before merge update maf documentation - readme
- sdk server opschonen en dubbele file check er uit halen
- nagaan hoe om te gaan in het dashboard met eslint comments. En/of dat dit via code-review moet blijken.
- [ ] release to public maf-sdk
Hi, paul was voor TC met Googlemaps bezig en we zien dat de linter het niet doet bij die app ;-)
catcher.js:197 GET http://localhost:8080/lint/com.metrological.app.GoogleMaps 500 (Internal Server Error)

### Also needs to be done, but later;
- [ ] publish as npm modules
- [ ] discuss auto-fix enable on SDK?
- [ ] use workers! https://github.com/Metrological/maf-release/blob/master/server.js
- [ ] performance optimization via async handlers for everything - all modules as well
- [ ] code voor sdk server opnieuw schrijven met modules (die herbruikbaar zijn voor release server) en volgens release server process
- [ ] make console logger maf into plugin formatter for eslint
- [ ] make formatting of console output better
- [ ] error grouping by type/rule?
- [ ] add packages to yarn as well
- [ ] make console output linkable via chrome dev tools workspaces - fix console mapping in maf?
- [ ] do including/bundling of file in eslint processor plugin - pre/post process - via maf module
- [ ] publish this and other config to NPM and update other repos
- [ ] add dependency indicators: david-dm, etc... for public sdk + config; https://greenkeeper.io/ https://npm-stat.com/ charts.html?package=eslint-find-rules&from=2015-08-01 https://nodei.co/npm/semantic-release/ (image) packagequality.com https://www.sourceclear.com/
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
  - offer conveniant way to set personal preferences stricter

### Separate project(s);
- [ ] own rules;
  - provide shortcut urls to MAF docs for rule explainations
  - in separate repo so maf extends two others
  - typeOf
  - what css properties are and aren't supported
  - don't extend/overwrite/append to MAF namespace/components
  - (un)subscribe - but only in maf repo -> so that extends this default config
  - check for unnesecary adding of components to view.elements or view.controls
  - geen maf scope functies in function die in global scope is gedefineerd, e.g. zonder var/ als statement
