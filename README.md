# [ESLint Config MAF](https://git.io/eslint-config-maf "ESLint Config MAF")
Configuration files for ESLint

[![NSP Status](https://nodesecurity.io/orgs/metrological/projects/5ac986fa-4f12-4e56-bda6-ed142e8c230c/badge)](https://nodesecurity.io/orgs/metrological/projects/5ac986fa-4f12-4e56-bda6-ed142e8c230c)
[![Code Climate](https://codeclimate.com/github/Metrological/eslint-config-maf/badges/gpa.svg)](https://codeclimate.com/github/Metrological/eslint-config-maf)
[![Issue Count](https://codeclimate.com/github/Metrological/eslint-config-maf/badges/issue_count.svg)](https://codeclimate.com/github/Metrological/eslint-config-maf)
[![dependencies Status](https://david-dm.org/metrological/eslint-config-maf/status.svg?style=flat-square)](https://david-dm.org/metrological/eslint-config-maf)
[![dependencies Status](https://david-dm.org/metrological/eslint-config-maf/peer-status.svg?style=flat-square)](https://david-dm.org/metrological/eslint-config-maf)
[![dependencies Status](https://david-dm.org/metrological/eslint-config-maf/optional-status.svg?style=flat-square)](https://david-dm.org/metrological/eslint-config-maf)

To use this from your IDE, use any of the following plugins:
- [Sublime Text](https://packagecontrol.io/packages/ESLint "Sublime Text")
- [WebStorm](https://www.jetbrains.com/help/webstorm/2016.2/eslint.html "WebStorm")
- [VS Code](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint "VS Code")
- [TextMate](https://github.com/natesilva/javascript-eslint.tmbundle "TextMate")

Before SDK release:
- run image optimizer on these apps
- check alle met timeout op API of correct ingevuld
- also check listener removal in all apps again
  ButtonsTemplate
  EmptyTemplate
  ExtendTemplate
  KeyboardTemplate
  GridTemplate
  RSSTemplate
  TabsTemplate
  ViewHandlingTemplate
  VideoTemplate - test on STB specifically!!!
  VideoTransportTemplate - test on STB specifically!!!
  YoutubeTemplate - remove key!!! + test on STB specifically!!!
  Rooms - Needs fixing!
  VideoTemplate2 - remove from SDK
  RunnerHTML - remove from SDK
  Ufo - remove from SDK

  ui.AutoStart - remove from SDK
  com.metrological.ui.Horizon
- remove maf logs, remove nl.nl strings errors
- release to public maf-sdk, combined with servicemail!!! - come up with persistent solution for this.

SDK after initial release:
- [ ] update shortlinks, make it load dynamically and in-memory cache or load from external github config file???
- [ ] add service mail via webhook to github/dashboard for public sdk
- [ ] use semantic versioning and commitizen friendly or use zeit/release?
- [ ] discuss auto-fix enable on SDK?
- [ ] use workers! https://github.com/Metrological/maf-release/blob/master/server.js
- [ ] performance optimization via async handlers for everything - all modules as well
- [ ] code voor sdk server opnieuw schrijven met modules (die herbruikbaar zijn voor release server) en volgens release server process
- [ ] nagaan of stripcomments niet eslint comments verwijderd
- [ ] nagaan hoe om te gaan in het dashboard met eslint comments. En/of dat dit via code-review moet blijken.
- [ ] make console logger maf into plugin formatter for eslint
- [ ] make formatting of console output better
- [ ] error grouping by type/rule?
- [ ] make console output linkable via chrome dev tools workspaces - fix console mapping in maf?
- [ ] try to avoid stack output of error... only (anonymous) @VM???
- [ ] do including/bundling of file in eslint processor plugin - pre/post process - via maf module
- [ ] add dependency indicators: david-dm, etc... for public sdk + config; https://greenkeeper.io/ https://npm-stat.com/ charts.html?package=eslint-find-rules&from=2015-08-01 https://nodei.co/npm/semantic-release/ (image) packagequality.com https://www.sourceclear.com/
- [ ] add badges; https://shields.io/; https://github.com/sarbbottam/eslint-find-rules -> functional + images
- [ ] incorporate in dashboard/release server
