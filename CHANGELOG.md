# Changelog
All notable changes to crunchy-hugo-theme will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Develop]

### Added

### Changed

### Removed

### Fixed

## [2.2.2] - 2019-05-16

### Fixed

- Bugfix: Bring theme up-to-date with Hugo deprecation errors beginning with Hugo version 0.55.x. 

## [2.2.1] - 2019-04-26

### Fixed

- Bugfix: Submenu navigation styles greater than 2 nested children implemented a list-style-type and a Font Awesome chevron

<img width="148" alt="screen_shot_2019-04-25_at_3 34 43_pm" src="https://user-images.githubusercontent.com/8406707/56821861-5400b080-6804-11e9-8401-1cfff984396a.png">

## [2.2.0] - 2019-02-23

### Removed

- Removed references to a Highlight JavaScript file which was not in use.

### Fixed

- The chevron FontAwesome icons on the side navigation menu for the crunchy-containers and postgres-operator projects were originally "not found" on page load of specifically parent pages with children, and the icons would not show as expected. They now load as expected.

- A jQuery scroll fix was added; when clicking on an anchor, the header for that section no longer hides behind the top sticky navigation menu.
