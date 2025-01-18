# CHANGELOG

<!-- version list -->

## v1.1.5

- Replaced poetry with uv package manager

- Added setuptools as build backend

## v1.1.4

- Added a demo project by Jenny Xu

- Updated dependencies

## v1.1.3

- Migrated from Sphinx to Quarto documentation

## v1.1.2

- Updated dependencies

- Required Python 3.10 and pandas 2.2 to prevent numpy binary incompatibility error

- Repaired broken tests badge in README.ipynb

## v1.1.1

- Updated dependencies

- Removed deprecated pkg_resources import

- Fixed a problem with pyproject.toml that was breaking CI/CD

- Implemented automated PyPi deployment with GitHub Actions

## v1.1.0

- Implemented response mocking during unit tests

- Removed between-calls wait time during unit tests

- Changed wait time variable from a global variable to an environment variable

- Introduced new `set_imf_wait_time` function

## v1.0.8

- Handled a case where, apparently, certain databases have required request parameters

- Added a couple experimental scripts for users who want to download whole databases; use at your own risk (of being blocked by the API)!

## v1.0.7

- Added error handling for the case where the user-specified parameter codes are valid, but the years are outside the dataset's range

- Adjusted the regular expression used in passing through error messages from the API endpoint

## v1.0.6

- Corrected bug in URL handling when user omits one or more parameters

- Improved error handling to prevent confusing JSON decode errors from being passed to user

- Implemented formatting with `black` library


## v1.0.5

- Minor adjustments to project docs

- Linted unit tests

## v1.0.4

- Added `_imf_wait_time` variable for enhanced rate limit support

## v1.0.3

- Addressed bandwidth limit

## v1.0.2

- Fixed Python 3.11 async-related incompatibility problem

## v1.0.1

- README update

## v1.0.0

- Initial release of the first complete Python library for comprehensive access to the IMF API