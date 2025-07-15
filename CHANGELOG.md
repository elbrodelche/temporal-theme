# Change Log

All notable changes to the "temporal-theme" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [0.1.0] - 2025-07-15

### Added

- **Light Theme Variant**: Complete light theme implementation (`Temporal Theme Light`)
- **Dual Theme Support**: Users can now choose between dark and light versions
- **Light Theme Features**:
  - Clean white editor background with excellent readability
  - Light gray sidebar and UI elements with proper contrast
  - Maintains the same blue accent system (`#2563EB`) as the dark theme
  - Optimized syntax highlighting colors for light backgrounds
  - Consistent branding and color philosophy across both themes

### Changed

- **Theme Labels**: Updated theme names for clarity
  - `Temporal Theme UI` → `Temporal Theme Dark`
  - Added `Temporal Theme Light` as new option
- **Package Description**: Updated to reflect dual theme support
- **Version Bump**: Updated to 0.1.0 to reflect significant new feature
- **Documentation**: Updated README with light theme information and dual activation instructions

### Technical Updates

- Added `temporal-light-theme.json` with complete light theme configuration
- Updated `package.json` contributes section to include both themes
- Enhanced keywords for better marketplace discoverability

## [0.0.1] - 2024-12-15

### Initial Release

- **Initial Release**: First version of Temporal Theme UI for Visual Studio Code
- **Dark Theme**: Complete dark theme implementation with sophisticated slate color palette
- **UI Components**: Full styling for all VS Code interface elements including:
  - Activity Bar with blue accent borders and proper contrast
  - Editor with deep blue background (`#0F172A`) for reduced eye strain
  - Sidebar with consistent dark theming
  - Status Bar with elegant styling
  - Tabs and panels with proper visual hierarchy
- **Syntax Highlighting**: Comprehensive token colorization for all programming languages
- **Color Palette**: Carefully curated color scheme featuring:
  - Primary blue accent: `#3B82F6`
  - Background: `#0F172A` (deep slate)
  - Secondary background: `#1E293B`
  - Text colors optimized for readability
- **Assets**: Custom icon and branding assets
- **Documentation**: Complete README with installation instructions and screenshots
- **License**: MIT License for open source distribution
- **Keywords**: Comprehensive tagging for marketplace discoverability

### Features

- Modern dark design with excellent contrast ratios
- Reduced eye strain with carefully chosen background colors
- Vibrant accent colors for important UI elements
- Consistent theming across all VS Code components
- Optimized for long coding sessions

### Technical Implementation

- Compatible with VS Code version 1.102.0 and above
- Proper JSON schema validation for theme configuration
- Structured file organization for maintainability
- Repository setup with version control

### Planned

- Light theme variant
- Additional color accent options
- Customization settings

