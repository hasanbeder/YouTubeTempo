# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.1] - 2025-10-09

### Removed
- **Volume Booster Feature**: The entire volume booster functionality has been completely removed from the script. This includes the associated audio processing logic (`AudioContext`, `GainNode`) and the "Volume Boost" slider in the settings panel.

### Fixed
- **Performance**: Resolved a significant performance issue that caused slow video start-up times. This delay was particularly noticeable when navigating from YouTube Shorts back to a regular video page, as the now-removed audio processing API was causing initialization latency.

## [1.0.0] - 2025-07-18

### Added
- Initial release of YouTubeTempo.
- Precision playback speed control buttons (Slower, Reset, Faster).
- Clickable speed indicator to open the settings menu.
- Fully customizable settings:
    - Speed Step, Min/Max Speed.
    - Customizable keyboard shortcuts.
    - Volume Booster.
    - Remaining time display toggle.
    - Click sound effects toggle.
- Collapsible sections within the settings menu for better organization.
- Support and project links in the settings menu.
