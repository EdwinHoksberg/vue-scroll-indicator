# Changelog

All notable changes to `vue-scroll-indicator` will be documented in this file.

## [0.1.2] - TBA

### Added
- Add component name.

## [0.1.1] - 2018-04-09

### Changed
- Replace mounted `scrollHandler()` in favor of `EventListener('load')`.

### Fixed
- Rename data `document` > `docHeight`.

## [0.1.0] - 2018-03-19

### Changed
- Refactor code/plugin using [spatie/skeleton-vue](https://github.com/spatie/skeleton-vue).
- Rename prop `indicator-color` > `color`.
- Rename prop `bg-color` > `background`.

### Fixed
- Add `destroyed()` lifecycle hook (`window.removeEventListener`).
