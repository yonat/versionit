# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)

and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [1.3.4] - 2022-07-17

### Fixed
- handle any main branch name.

## [1.3.3] - 2022-05-25

### Changed
- when only changing build number (using `versionit 0`) tag with `<version>#<build>`.

### Fixed
- only push most recent tag, not all tags.

## [1.3.2] - 2022-03-25

### Fixed
- fix comparison to last version.

## [1.3.1] - 2022-03-10

### Fixed
- continue execution after user approves changes.

## [1.3.0] - 2022-02-24

### Added
- silent mode with `-f` argument.

### Fixed
- correctly match digits in previous version tag.
- allow missing Settings.bundle.

## [1.2.4] - 2021-03-24

### Fixed
- allow missing CHANGELOG.md.

## [1.2.3] - 2020-12-17

### Fixed
- allow warnings when pushing pod to trunk.

## [1.2.2] - 2020-06-01

### Fixed
- correctly extract latest version when there are several targets.

## [1.2.0] - 2019-07-19

### Added
- update Settings.bundle.
- optional target argument.
- only change version for specified target (default is same as proj name).
- only change build number if version is 0.
- automatically increment last version number if no version (or '-') is specified.

### Changed
- don't wait before showing changed files.

### Fixed
- commit changed proj file.

## [1.1.1] - 2019-03-09

### Fixed
- don't compare current version to tags that are not numeric.

## [1.1.0] - 2018-12-17

### Added
- cherrypick changes to commit.

## [1.0.4] - 2018-09-05

### Fixed
- don't add untracked Info.plist files to git (eg in Pods).

## [1.0.3] - 2018-08-18

### Fixed
- change version only in the main project, not in Pods project.

## [1.0.2] - 2018-07-10

### Fixed
- don't push private pods to trunk

## [1.0.1] - 2018-07-08

### Fixed
- allow misspellings in [Unreleased]
