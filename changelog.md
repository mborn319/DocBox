# CHANGELOG

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

----

## 3.0.0

### Added

* New `json` output strategy for machine-readable documentation
* New `addStrategy()` method for multiple strategy support

### Changed

* Can configure strategy with "alias" name, like `strategy="HTML"`.

### Removed

* Removed HTML as the default strategy. You will need to explicitly pass this to the constructor or to `docbox.addStrategy( "HTML", props )` to set your desired output format.

### Fixed

* Fixed failing XMI strategy
<<<<<<< HEAD
=======

----
>>>>>>> b5e7cd4e0c1eaf1375acbfd8360eb2cfa73e6d4a

## 2.2.1

### Fixed

* Bug on DocBox tracing errors, left over a couple of `()`

----

## 2.2.0

### Added

* Better output of trace commands for CLI integration
* Added `@throws` annotation to function definitions
* Added `@deprecated` annotation to function definitions

----
## 2.1.0

### Fixed

* Varscoping issue to help with COMMANDBOX-399
* BUGFIX: Missing pound sign in ExpandPath(), added better wording for custom strategy path
* Fix cleanPath without a leading slash with regex updates

----

## 2.0.7

### Fixed

* Build process messed up folder structure. Basically 2.0.6 was unusable

----

## 2.0.6

### Fixed

* DOCBOX-1 - Extra slash breaks some links on S3-hosted docs

### Improved

* Updated build process

### Added

* Travis integration

----

## 2.0.5

### Improved

* Moved CommandBox command to its own repo

----

## 2.0.4

### Improved

* Update package directory and location for CommandBox command

----

## 2.0.3

### Fixed

* FireFox location bug

----

## 2.0.2

### Fixed

* Fixes on conversion to script

### Improved

* Updates on box.json for standalone installations

<<<<<<< HEAD
## 2.0.1

## Fixed
=======
----

## 2.0.1

### Fixed
>>>>>>> b5e7cd4e0c1eaf1375acbfd8360eb2cfa73e6d4a

* Fixes for ACF

----

## 2.0.0

### Improved

* Updated to DocBox styles