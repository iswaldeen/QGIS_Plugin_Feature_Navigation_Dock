# QGIS Plugin - Feature Navigator

Feature Navigator is a QGIS plugin for efficiently navigating through features in a selected vector layer.

The plugin supports both manual and automatic feature navigation workflows, allowing users to move forwards and backwards through features, navigate selected features only, automatically zoom to the active feature, visually track navigation progress using an optional navigation slider bar, and quickly access plugin settings and help directly from the QGIS Plugins menu.

Feature Navigator is designed for compatibility with modern QGIS versions and includes forward-compatible support for Qt6 and upcoming QGIS 4.x environments.

<img src="feature_navigator/icons/feature_navigator_icon.png" width="100" height="100">

## Features

* Navigate forwards and backwards through layer features
* Navigate through selected features only
* Automatically zoom to active features
* Autoplay mode for sequential feature navigation
* Optional looping navigation mode
* Optional navigation slider bar
* Quick slider-based feature navigation
* Live slider position updates during navigation and autoplay
* Spacebar play/pause shortcut support
* Automatically updates when features are added or removed
* Automatically enables hidden layers during navigation
* End-of-layer navigation notifications
* Integrated help documentation
* Direct access to Settings and Help from the QGIS Plugins menu
* Theme-aware UI and menu icon support for both light and dark QGIS themes
* Modernized PyQt / Qt compatibility handling
* Improved robustness for layer and feature state changes
* Improved cleanup handling for deleted layers and projects
* Forward-compatible design for:

  * QGIS 3.x
  * QGIS 4.x
  * Qt5
  * Qt6

## Compatibility

Feature Navigator is actively developed and tested for:

* QGIS 3.28+
* PyQt5 / Qt5
* Forward compatibility with Qt6 and QGIS 4.x APIs where possible

The plugin avoids deprecated Qt and QGIS API usage where practical to support long-term maintainability.

## License

All content is licensed under the <a href="https://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Attribution-ShareAlike 3.0 licence (CC BY-SA)</a>.