# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [1.0.0] - 2015-12-16
### Added
* New top level method `createStream` takes in a geojson stream and returns a stream of the object transformed by OGR2OGR
### Changed
* Changed project name to GeoXForm
* Renamed each exported method to `createStream`
* Methods return transform streams instead accepting input  as a parameter and returning a readable stream

## [0.0.2] - 2015-12-14
### Changed
* Removed extraneous files related to jobs

## [0.0.1] - 2015-12-14
### Added
* Initial release: API supports creating VRTs, Geojson, shapefile, kml and csv

[unreleased]: https://github.com/koopjs/geoxform/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/koopjs/geoxform/compare/v0.0.2...v1.0.0
[0.0.2]: https://github.com/koopjs/geoxform/compare/v0.0.1...v0.0.2
[0.0.1]: https://github.com/koopjs/geoxform/releases/tag/v0.0.1