# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 1.1.0 - 2019-10-06

### Fixed

- Fix bug about can not detect changes from actual service configuration

## 1.0.0 - 2019-10-01

### Changed

- Introduce go.mod to manage go modules
- Upgrade terraform SDK to 0.12 for terraform upgrade
- Add and changelog and version number to provider
- Update `make install` to install to the terraform plugins folder directly
- Add `make dev-install` to test your local build
- Add `make release` command and release directory
