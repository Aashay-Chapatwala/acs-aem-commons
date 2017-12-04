# Change Log

All notable changes to this project will be documented in this file. This format was adapated
after the 2.12.0 release. All changes up until the 2.12.0 release can be found in https://github.com/Adobe-Consulting-Services/acs-aem-commons/releases.

The format is based on [Keep a Changelog](http://keepachangelog.com/)

## [Unreleased]

[Unreleased]: https://github.com/Adobe-Consulting-Services/acs-aem-commons/compare/acs-aem-commons-2.14.0...HEAD

### Changed

- #1192 - Ensure that HttpCache works with response objects when `getOutputStream()` throws `IllegalStateException`

## [2.14.0] - 2017-10-26

### Added

- #1139: Add support in StaticReferenceRewriterTransformerFactory for complex values, e.g. `img:srcset`

## [2.13.0] - 2017-08-20

### Added

- #958: Named Image Transform Servlet Sharpen transform 
- #1039: Health Check Status E-mailer (with minor feature removals)
- #1067: Vanity Path Web server re-writer mapping 

### Changed

- #1033: Allow Resource Resolver Map Factory's re-write attributes to be passed in as an array

### Fixed

- #1008: Email subject mangled for non-latin chars
- #1044: JCR Package Replication fixes a resource leak where the JCR Packages were not closed after being opened 

<!---
 
### Deprecated
### Removed
### Security 

---->