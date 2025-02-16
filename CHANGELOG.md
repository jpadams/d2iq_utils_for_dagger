# Changelog

<!-- Release notes generated using configuration in .github/release.yaml at main -->

## What's Changed
### Exciting New Features 🎉
* feat: Include pre-commit configuraiton into a container by @mikolajb in https://github.com/mesosphere/daggers/pull/90
* feat: Add gotest target to mage catalog by @mikolajb in https://github.com/mesosphere/daggers/pull/91
### Other Changes
* build(deps): Bump dagger.io/dagger from 0.5.0 to 0.5.1 by @dependabot in https://github.com/mesosphere/daggers/pull/87
* build(deps): Bump dagger.io/dagger from 0.5.1 to 0.5.2 by @dependabot in https://github.com/mesosphere/daggers/pull/89


**Full Changelog**: https://github.com/mesosphere/daggers/compare/v0.5.6...v0.6.0

## Changelog

<!-- Release notes generated using configuration in .github/release.yaml at main -->

## What's Changed
### Other Changes
* build: bump dagger v0.4.5 by @aweris in https://github.com/mesosphere/daggers/pull/82
* build(deps): bump github.com/stretchr/testify from 1.8.1 to 1.8.2 by @dependabot in https://github.com/mesosphere/daggers/pull/84
* build(deps): bump dagger.io/dagger from 0.4.5 to 0.4.6 by @dependabot in https://github.com/mesosphere/daggers/pull/85
* build(deps): bump dagger.io/dagger from 0.4.6 to 0.5.0 by @dependabot in https://github.com/mesosphere/daggers/pull/86

## New Contributors
* @dependabot made their first contribution in https://github.com/mesosphere/daggers/pull/84

**Full Changelog**: https://github.com/mesosphere/daggers/compare/v0.5.5...v0.5.6

## Changelog

<!-- Release notes generated using configuration in .github/release.yaml at main -->

## What's Changed
### Other Changes
* build: bump dagger to v0.4.4 by @aweris in https://github.com/mesosphere/daggers/pull/80


**Full Changelog**: https://github.com/mesosphere/daggers/compare/v0.5.4...v0.5.5

## Changelog

<!-- Release notes generated using configuration in .github/release.yaml at main -->

## What's Changed
### Fixes 🔧
* fix: configure ssh socket and github token as well by @aweris in https://github.com/mesosphere/daggers/pull/74


**Full Changelog**: https://github.com/mesosphere/daggers/compare/v0.5.3...v0.5.4

## Changelog

<!-- Release notes generated using configuration in .github/release.yaml at main -->

## What's Changed
### Fixes 🔧
* fix: use fn to configure to avoid chicken egg dependency by @aweris in https://github.com/mesosphere/daggers/pull/72


**Full Changelog**: https://github.com/mesosphere/daggers/compare/v0.5.2...v0.5.3

## Changelog

<!-- Release notes generated using configuration in .github/release.yaml at main -->

## What's Changed
### Fixes 🔧
* fix: reverse condition for github auth config by @aweris in https://github.com/mesosphere/daggers/pull/69
### Other Changes
* refactor: except external directories as workdir as well by @aweris in https://github.com/mesosphere/daggers/pull/71


**Full Changelog**: https://github.com/mesosphere/daggers/compare/v0.5.1...v0.5.2

## Changelog

<!-- Release notes generated using configuration in .github/release.yaml at main -->

## What's Changed
### Exciting New Features 🎉
* feat: add default version option to asdf plugin versions by @aweris in https://github.com/mesosphere/daggers/pull/65
* feat: add ssh and docker socket support by @aweris in https://github.com/mesosphere/daggers/pull/67
* feat: add Github auth helpers by @aweris in https://github.com/mesosphere/daggers/pull/68
### Fixes 🔧
* fix: do not add empty args to container by @aweris in https://github.com/mesosphere/daggers/pull/66
### Other Changes
* build(deps): bump dagger version by @aweris in https://github.com/mesosphere/daggers/pull/63


**Full Changelog**: https://github.com/mesosphere/daggers/compare/v0.5.0...v0.5.1

## Changelog

<!-- Release notes generated using configuration in .github/release.yaml at main -->

## What's Changed
### Breaking Changes 🛠
* refactor!: restructure container operations by @aweris in https://github.com/mesosphere/daggers/pull/49
* refactor!: remove help package by @aweris in https://github.com/mesosphere/daggers/pull/51
* refactor!: merge mage and dagger directories as catalog by @aweris in https://github.com/mesosphere/daggers/pull/52
* refactor!: simplify goreleaser by @aweris in https://github.com/mesosphere/daggers/pull/53
### Exciting New Features 🎉
* feat: Introduce go tests by @mikolajb in https://github.com/mesosphere/daggers/pull/40
* feat: Add coveralls reporting by @mikolajb in https://github.com/mesosphere/daggers/pull/41
* feat: Add github-cli dagger package by @aweris in https://github.com/mesosphere/daggers/pull/38
* feat: introduce dagger/golang by @aweris in https://github.com/mesosphere/daggers/pull/43
* feat: add new config options to golang by @aweris in https://github.com/mesosphere/daggers/pull/56
* feat: add new config options to  github-cli by @aweris in https://github.com/mesosphere/daggers/pull/57
* feat: introduce customizers for configuring host env variables by @aweris in https://github.com/mesosphere/daggers/pull/60
* feat: load Github env vars in CustomizedContainerFromImage if CI is true by @aweris in https://github.com/mesosphere/daggers/pull/61
### Fixes 🔧
* fix: remove unnecessary error check by @aweris in https://github.com/mesosphere/daggers/pull/35
* fix: correct spelling in typo by @aweris in https://github.com/mesosphere/daggers/pull/36
* fix: list all plugin versions not just installed ones by @aweris in https://github.com/mesosphere/daggers/pull/58
### Other Changes
* refactor: use caarlos0/env lib to read env configuration by @aweris in https://github.com/mesosphere/daggers/pull/37
* build(deps): bump dagger version to 0.4.1 by @aweris in https://github.com/mesosphere/daggers/pull/42
* refactor: make GetContainer public for githubcli by @aweris in https://github.com/mesosphere/daggers/pull/44
* refactor: extract Option type to daggers package by @aweris in https://github.com/mesosphere/daggers/pull/47
* refactor: extract dagger.Connect to daggers.Runtime by @aweris in https://github.com/mesosphere/daggers/pull/48
* ci: add PR size label workflow by @aweris in https://github.com/mesosphere/daggers/pull/62
* refactor: clean-up svu by @aweris in https://github.com/mesosphere/daggers/pull/54
* refactor: move PrecommitWithOptions to mage.go again by @aweris in https://github.com/mesosphere/daggers/pull/55
* refactor: extract env map setting to container customizer by @aweris in https://github.com/mesosphere/daggers/pull/59

## New Contributors
* @mikolajb made their first contribution in https://github.com/mesosphere/daggers/pull/40

**Full Changelog**: https://github.com/mesosphere/daggers/compare/v0.4.0...v0.5.0

## Changelog

<!-- Release notes generated using configuration in .github/release.yaml at main -->

## What's Changed
### Exciting New Features 🎉
* feat: Add asdf mage targets by @aweris in https://github.com/mesosphere/daggers/pull/32
* feat: Add goreleaser mage package by @aweris in https://github.com/mesosphere/daggers/pull/33


**Full Changelog**: https://github.com/mesosphere/daggers/compare/v0.3.1...v0.4.0

## Changelog

<!-- Release notes generated using configuration in .github/release.yaml at main -->

## What's Changed
### Fixes 🔧
* fix: Use verbose logging always to see precommit output. by @aweris in https://github.com/mesosphere/daggers/pull/30


**Full Changelog**: https://github.com/mesosphere/daggers/compare/v0.3.0...v0.3.1

## Changelog

<!-- Release notes generated using configuration in .github/release.yaml at main -->

## What's Changed
### Exciting New Features 🎉
* feat: add WithMountedGoCache dagger option by @aweris in https://github.com/mesosphere/daggers/pull/28
### Other Changes
* build: Bump dagger to version 0.4.0 by @aweris in https://github.com/mesosphere/daggers/pull/25
* ci: Add dependabot config to repository by @aweris in https://github.com/mesosphere/daggers/pull/26


**Full Changelog**: https://github.com/mesosphere/daggers/compare/v0.2.2...v0.3.0

## Changelog

<!-- Release notes generated using configuration in .github/release.yaml at main -->

## What's Changed
### Fixes 🔧
* fix: Print command output if mage is not running in verbose mode by @aweris in https://github.com/mesosphere/daggers/pull/23


**Full Changelog**: https://github.com/mesosphere/daggers/compare/v0.2.1...v0.2.2

## Changelog

<!-- Release notes generated using configuration in .github/release.yaml at main -->

## What's Changed
### Fixes 🔧
* fix: Use correct package name for mage/svu by @aweris in https://github.com/mesosphere/daggers/pull/21


**Full Changelog**: https://github.com/mesosphere/daggers/compare/v0.2.0...v0.2.1

## Changelog

<!-- Release notes generated using configuration in .github/release.yaml at main -->

## What's Changed
### Exciting New Features 🎉
* feat: Add configuration options to svu via env by @aweris in https://github.com/mesosphere/daggers/pull/18
* feat: Add help targets for mage by @aweris in https://github.com/mesosphere/daggers/pull/19


**Full Changelog**: https://github.com/mesosphere/daggers/compare/v0.1.0...v0.2.0

## Changelog

<!-- Release notes generated using configuration in .github/release.yaml at main -->

## What's Changed
### Exciting New Features 🎉
* feat: Add go build and mod cache by @jimmidyson in https://github.com/mesosphere/daggers/pull/9
* feat: add dagger svu by @aweris in https://github.com/mesosphere/daggers/pull/10
* feat: Add mage targets for svu by @jimmidyson in https://github.com/mesosphere/daggers/pull/14
* feat: Add logger support by @aweris in https://github.com/mesosphere/daggers/pull/17
### Fixes 🔧
* fix: Remove redundant dagger client creation by @jimmidyson in https://github.com/mesosphere/daggers/pull/15
### Other Changes
* feat: Use pre-commit zipapp by @jimmidyson in https://github.com/mesosphere/daggers/pull/1
* feat: Cache pre-commit specified hooks by @jimmidyson in https://github.com/mesosphere/daggers/pull/2
* fix: Cache install hooks in earlier layer by @jimmidyson in https://github.com/mesosphere/daggers/pull/4
* chore: Lint repo by @aweris in https://github.com/mesosphere/daggers/pull/3
* ci: Add default workflows, including release-please by @jimmidyson in https://github.com/mesosphere/daggers/pull/6
* ci: Add release notes config by @jimmidyson in https://github.com/mesosphere/daggers/pull/8
* feat: Enable further configuration options by @jimmidyson in https://github.com/mesosphere/daggers/pull/5
* refactor: Rename module to github.com/mesosphere/daggers by @jimmidyson in https://github.com/mesosphere/daggers/pull/13
* ci: Add golangci-lint workflow by @jimmidyson in https://github.com/mesosphere/daggers/pull/16

## New Contributors
* @aweris made their first contribution in https://github.com/mesosphere/daggers/pull/3

**Full Changelog**: https://github.com/mesosphere/daggers/compare/v0.0.1...v0.1.0
