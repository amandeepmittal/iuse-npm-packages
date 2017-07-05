# iUse-npm-packages
> is a curated list of npm packages that I am currently using or have used in a specific project.

![](http://i.imgur.com/ODTRiZE.png)

## Global
* [@angular]()
* [angular-cli-ghpages]() - Wrapper around gh-pages, made for angular-cli users
* [bower]() - front end package manager for MEAN Stack (v1) apps
* [codestats-cli]() - A command utility for Code::Stats
* [commitizen]() - use git cz instead of git commit when committing
* [cz-conventional-changelog-emoji]() - used with commitizen
* [cordova]() - essential for hybrid mobile app framework, ionic
* [express-generator]() - to scaffold a running Expressjs application, avoids boilerplate of basic Nodejs server app using Express as framework
* [grunt-cli]() - task runner
* [gulp]() - task runner
* [hexo-cli]() - CLI utility to generate and publish posts when using Hexo as static site generator
* [ionic]() - create hybrid mobile apps using Angular and TypeScript
* [npm]() - JS Package manager
* [npm-name-cli](https://github.com/sindresorhus/npm-name-cli) - Check whether a package name is available on npm
* [ts-node]() - TypeScript execution environment and REPL for node
* [tsun]() - REPL for TypeScript Upgraded Node
* [typescript]() - TypeScript is a language for application scale JavaScript development
* [yo]() - CLI tool for running Yeoman generators
* [yosay]() - Tell Yeoman what to say

## Local
* [nodemon]() - continuous run a  Nodejs server during development

## Web
* [NodeICO](https://nodei.co/) - npm package badges
* [snyk](https://snyk.io/) - fix and monitor known vulnerabilities in npm dependencies
* [npm-stat](https://npm-stat.com/) - statistics for any npm package
* [npm addict](https://npmaddict.com/) - daily updates new/most used npm packages
* [npm discover](http://www.npmdiscover.com/) - discover which npm packages are used together

## Browser extensions

* [Octo-Linker](https://chrome.google.com/webstore/detail/octo-linker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome extension to navigate across npm packages on GitHub with ease.
* [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - Chrome extension to explore npm dependencies on GitHub repos.

---

# Tips

* Update to the latest npm version:

```shell
$ npm install -g npm
```

* find the version of a specific package

```shell
# for local packages
$ npm list

# Or
$ npm list <package-name>

# Or
$ npm list --depth=0

# For global packages
$ npm list -g
```

* [Fixing npm permissions](https://docs.npmjs.com/getting-started/fixing-npm-permissions)

* [How to use npm as build tool by Keith Cirkel](https://www.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/)

* [Semver a primer](https://nodesource.com/blog/semver-a-primer/)

---
> Always remember, Write programs that do one thing and do it well. (Unix Philosophy)