=======
# CHANGELOG

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

----

## 3.0.0

### Added

* Adds `json` output strategy
* Adds `addStrategy()` for multiple strategy support

### Changed

* Can configure strategy with "alias" name, like `strategy="HTML"`.

### Removed

* Removed HTML as the default strategy. You will need to explicitly pass this to the constructor or to `docbox.addStrategy( "HTML", props )` to set your desired output format.

### Fixed

* Fixed failing XMI strategy

## 2.2.1
* Bug on DocBox tracing errors, left over a couple of `()`

## 2.2.0
* Better output of trace commands for CLI integration
* Added `@throws` annotation to function definitions
* Added `@deprecated` annotation to function definitions
## 2.1.0
* Varscoping issue to help with COMMANDBOX-399
* BUGFIX: Missing pound sign in ExpandPath(), added better wording for custom strategy path
* Fix cleanPath without a leading slash with regex updates

## 2.0.7
* Build process messed up folder structure. Basically 2.0.6 was unusable

## 2.0.6
* DOCBOX-1 - Extra slash breaks some links on S3-hosted docs
* Updated build process
* Travis integration

## 2.0.5
* Moved CommandBox command to its own repo

## 2.0.4
* Update package directory and location for CommandBox command

## 2.0.3
* FireFox location bug

## 2.0.2
* Fixes on conversion to script
* Updates on box.json for standalone installations

## 2.0.1 
* Fixes for ACF

## 2.0.0
* Updated to DocBox styles