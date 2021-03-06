# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

# TODO
- Features
    * add a progress bar to Fiction pages
    * add a hide option to the fics which will hide the fic from ever listing
    * add a sort/filter bar
    * add bookmark tag display 
    * do the settings at the end of page thingie    
    * make this work on community pages, too.
    * [IMPORTANT] add a system that can asynchronously load details of fanfiction.net links anywhere on web
    * do something about that final width change thing as it wont work now
- Bugs 
    * proper last read system.
- Performance

## Refactoring
* remove all references to Edwin(my name)

## [Unreleased]
### Added
### Changed
### Removed

## [0.8.1] - 2017-11-22
### Added
* add a titlebar so that we can see the chapter name and current progress
* added a progressbar to the titlebar
### Changed
* enable to reload the extension without having to reload page
* scroll handler run at scroll end, made it much faster
* extracted css in the mainfile to outside
* started using scss and gulp
* made the titlebar look good in dark theme
### Removed

## [0.8.0] - 2017-11-17
### Changed
* Converted to WebExtensions
### Removed
* Deleted unused code
* removed underscorejs

## [0.7.1] - 2017-11-13
### Added
* User Page; show the completion badge
* User and Fiction Page; show the Read/Unread badge
* Added selectability to Story Text

## [0.7.0] - 2017-11-13
### Added
- Features
    * decorated the fic info bar
### Removed
- Bugs 
    * sorting out the  scroll memory not working on single chaps
