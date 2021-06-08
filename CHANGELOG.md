# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### Added
- All shader versions for basic, phong, lambert and standard from r76 to r129
- Examples (dissolve, fresnel, texture sampling)

### Fixed
- Get node preview propagation
- Boolean not being applied to shader
- Boolean and Color types in .d.ts
- const formatting when exporting
- texture export
- color export


## [0.0.3] - 2021-06-2
### Added
- version option when exporting

### Fixed
- const vector export
- decompose deletion
- background aliasing
- color preview bug 

## [0.0.2] - 2021-05-27
### Added
- Compose node
- Export

### Removed
- Swizzle node
- Groups UI

### Fixed
- Set/Get node
- Material list UI
- Preview material clipping
- Preview background config indicator
- Preview background config color picker _(via react-color 2.17.3)_
- Copy style
- List filter
- Workspace and preview focus
- Bool switching issue
- Color picker performance
- Get node not connected to set wont break the shader
- Set node without input connection wont break the shader


### Changed
- Mapped panning to middle mouse button
- Cursor feedback when interacting with nodes

