# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.1.0-alpha - unreleased

This is an alpha version! The changes listed here are not final.

### Added
- Added skeleton PHP file to prevent errors upon composer install
- Added Social card to My Jetpack.
- E2E tests: added custom error messages to the expect functions
- Initial Commit.
- Search: After plugin activation, automatically redirect to the Search dashboard while enabling the search module and instant search if eligible
- Search: bootstrap the plugin
- Search plugin: show submenu when co-existing with Jetpack and site connected
- Updated lock file
- Use publicize composer config package

### Changed
- Allow Node ^14.17.6 to be used in this project. This shouldn't change the behavior of the code itself.
- E2E tests - bumped dependencies versions
- E2E tests: moved Search tests into search plugin folder
- General: update required node version to v16.13.2
- Janitorial: require a more recent version of WordPress now that WP 6.0 is coming out.
- Remove use of `pnpx` in preparation for pnpm 7.0.
- Set `convertDeprecationsToExceptions` true in PHPUnit config.
- Switch to pcov for code coverage.
- Tests: update PHPUnit polyfills dependency (yoast/phpunit-polyfills).
- Updated composer.lock
- Updated name to automattic/jetpack-search-plugin
- Updated package dependencies
- Updated package dependencies.
- Updated search package lockfile
- Update package.json metadata.
- Update package dependencies
- Update PHPUnit configs to include just what needs coverage rather than include everything then try to exclude stuff that doesn't.
- Use Node 16.7.0 in tooling. This shouldn't change the behavior of the code itself.

### Deprecated
- Moved the options class into Connection.

### Fixed
- Search: address feeback for #23477
- Search: move Jetpack plugin compatibility to the package
