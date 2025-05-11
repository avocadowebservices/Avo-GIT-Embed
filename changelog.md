# Changelog

## [1.2.5] - 2025-05-11
### Changed
- Replaced custom Download ZIP button with official shields.io badge
- Perfect visual alignment with other badges (no CSS styling required)

## [1.2.4] - 2025-05-11
### Fixed
- Download ZIP badge now perfectly matches shields.io style
- Font, padding, and vertical alignment fully polished

## [1.2.3] - 2025-05-11
### Changed
- Styled the Download ZIP badge with GitHub-like appearance
- Applied dark background and monospace font to resemble shield badges

## [1.2.2] - 2025-05-11
### Fixed
- Replaced badge table row with inline `<span>` containers for correct layout
- Placed Download ZIP in same line as other badges (badge-row)

## [1.2.1] - 2025-05-11
### Changed
- Converted the large Download ZIP button into a badge-style element
- Moved the badge inline next to other repo badges

## [1.2.0] - 2025-05-11
### Changed
- Download ZIP button now shown by default (no shortcode needed)

## [1.1.9] - 2025-05-11
### Added
- `show_download="yes"` shortcode attribute to enable a Download ZIP button
- Download links directly to GitHub archive ZIP

## [1.1.8] - 2025-05-11
### Fixed
- Removed excessive spacing below repo title
- Improved badge layout and spacing

## [1.1.7] - 2025-05-11
### Added
- External CSS file for easier styling and theme compatibility
- `show_release="yes"` attribute to display GitHub latest release info

## [1.1.6] - 2025-05-11
### Changed
- Rendered GitHub badges in a single-row table for perfect inline alignment

## [1.1.5] - 2025-05-11
### Fixed
- Replaced `<div>` wrappers with `<span>` for badges to prevent vertical stacking

## [1.1.4] - 2025-05-11
### Changed
- Experimented with `<div>` badge containers (caused spacing issue later)

## [1.1.3] - 2025-05-11
### Fixed
- Attempted badge layout fix with `<div>` wrappers (still caused stacking)

## [1.1.2] - 2025-05-11
### Fixed
- Improved badge image layout with CSS to display them inline

## [1.1.1] - 2025-05-11
### Added
- Badge rendering using Parsedown to support Markdown shield images

## [1.1.0] - 2025-05-11
### Added
- Markdown rendering of README.md using Parsedown
- CSS layout for repo display
- GitHub API caching via WordPress transients

## [1.0.0] - 2025-05-10
### Initial Release
- Basic shortcode support: `[avogitembed user="..." repo="..."]`
- Fetch GitHub repo title, description, stars, forks, updated date
- Fetch and display raw `README.md` from main branch
