# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [0.1.6] - 2017-02-27
### Fixed
- Fixed incorrect information in README section that talks about path/routing
- Fixed the possibility of not returning from readAllItems if PLC initiates a disconnect

## [0.1.5] - 2016-11-13
### Fixed
- Bug fix for reading/writing bit arrays (thanks to Jotan)
- Bug fix for arrays of bits in long integers
- Improvements and documentation for NSTRING data type to read strings from Control/CompactLogix
- DropConnection improvements thanks to dom-white
- Fixed a bug writing odd length strings

### Added
- Experimental NString datatype support to allow reading strings from Control/CompactLogix that does not support ST files

## [0.1.4] - 2016-01-13
### Fixed
- Odd-length string bug fix (thanks to Julien Ledun).
- MIT license mentioned in package.json

### Added
- Experimental NString datatype support to allow reading strings from Control/CompactLogix that does not support ST files

## [0.1.3] - 2015-07-12
### Fixed
- Log error writing array of TIMER/COUNTER/CONTROL that has never been supported.
- Return a JS object with TIMER/COUNTER/CONTROL data (.PRE, .ACC etc) when an entire timer or counter or control is requested without a subelement or when an array is requested.
- Fix for timer/counter .PRE not working at all when requested individually

### Added
- String datatype support
- Control (R) structure datatype support

