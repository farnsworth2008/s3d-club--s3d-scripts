# Changelog All notable changes to this project will be documented in this
file.

The format is based on [Keep a
Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [7.0.0-1] - 2022-09-15
### Changed
- Removed `v` prefix on tags **breaking**
- Major script updates related to tags

## [6.0.0] - 2022-09-15
### Changed
- Now using `0.0.0-0.0.0` format for pre-release tagging **breaking**

## [5.0.0] - 2022-09-15
### Fixed
- Now using `v` as a tag prefix **breaking**
- Added missing `README.md`

### Added
- `s3d-tf-lock-update`
- `s3d-git-fork`

## [4.0.0] - 2022-09-15
### Changed
- Filter pre-release tags
- Automaically Push current branch when pushing a release
- Added script to remove pre-release tags
- `USE...` error for git-setup script

## [3.0.0] - 2022-09-11
### Added
- Script for Git Pull/Push
- Scripts for listing EC2 running instances
- Scripts for working with Git Tags
- Scripts for listing EC2 running instances
- Created a script to configure the git user
- Fixed bug for when we aready had a ssh remote
- Fixed error that would occur if branch was already named `main`
- Script for adding a ssh remote
- Script for adding just a release commit without tag and push
- Script for re-establishing main branch with delete and re-create
- Fixed bug with `s3d-git-add-and-commit`

## [2.0.0] - 2022-09-10
### Changed
- Rename to `s3d-git-...`

### Added
- New script for add and commit

-## [1.0.0] - 2022-09-10
### Added
- Initial structure is in place

## [0.0.0] - 2022-09-10
### Added
- The scripts project

This will be where we maintain Bash scripts.
