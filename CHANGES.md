# Changes
Recently completed and planned work is tracked here.

## [0.0.0](.) to [0.1.11](.)
- Created early versions

## [0.1.12](.) to [0.1.17](.)
- Added `profile` param for `s3d-assume-role` script
- Added `s3d-unset-aws-vars`
- Added local branch management for `s3d-git-push-main`
- Changed `s3d-assume-role` to set duration for `43200`
- Cleaned up `s3d-flow-json` script
- Skip in `s3d-tf-lock` if `main.tf` does not exist

## [0.1.18](.)
- Added `tflint` to `s3d-test`
- Changed `s3d-tf-lock` to include darwin and windows


## [0.1.19](.) to [0.1.20](.)
- Added `s3d-submodule-main-delta`

## [0.1.21](.)
- Improved management of `--duration-seconds ` in `s3d-assume-role`
- Improved parsing of commit block in `s3d-flow-commit`

## [0.1.22](.)
- Removed `npm` scripting from `s3d-init`

## [0.1.23-1000](.)
- Changed `s3d-test` so it now checks sort order
