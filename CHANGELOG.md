# Changelog
All notable changes to the Enhanced Claude Export Script will be documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.1.0] - 2025-05-26
### Added
- Auto-scroll functionality to load complete conversations
- Multiple detection strategies for robust element finding
- Progress notifications during export process
- Debug mode with detailed logging
- Message count in exported filenames
- Enhanced speaker detection using content patterns
- Support for very long conversations (500+ messages)
- Fallback methods when primary detection fails

### Changed
- Improved file naming: `claude-FULL-conversation-156msgs-2025-05-26.md`
- Button text changed to "📥 Export Full" to indicate enhanced functionality
- Better error handling and user feedback
- Enhanced UI with improved menu design and descriptions

### Fixed
- Fixed export format selector text visibility issues (white text on dark backgrounds)
- Resolved CSS conflicts causing invisible dropdown options
- Improved contrast and styling for export menu text
- Fixed conversation truncation issues
- Resolved problems with n8n-style data processing
- Better handling of Claude.ai UI changes

## [2.0.0] - 2025-05-25
### Added
- Multiple export formats (Markdown, Plain Text, JSON)
- Speaker identification between Human and Claude
- Metadata inclusion (timestamps, export date, message counts)
- Elegant dropdown menu interface
- Hover effects and improved styling
- JSON export with full conversation statistics
- Cross-browser compatibility improvements

### Changed
- Complete rewrite of conversation detection logic
- Improved UI design with gradient buttons and clean menus
- Enhanced error handling and validation

### Fixed
- Resolved element detection issues with Claude.ai updates
- Fixed export failures on long conversations
- Improved text cleaning and formatting
- Fixed auto-scroll mechanism for full conversation loading

## [1.1.0] - Based on TheAlanK & SAPIENT
### Added
- Basic conversation export functionality
- Simple text file output
- Compact design for small screens
- Core element detection using `.col-start-2` selector

### Features
- Single-format export (plain text)
- Basic conversation capture
- Minimal UI footprint

### Known Issues (Resolved in v2.0+)
- Limited to first 12 messages only
- No auto-scroll functionality
- Basic speaker detection

---

## Version Schema
**Major.Minor.Patch** (e.g., 2.1.0)
- **Major**: Breaking changes or complete rewrites
- **Minor**: New features, backwards compatible
- **Patch**: Bug fixes, small improvements

## Development Timeline
- **24-Hour Sprint**: v1.1 → v2.1 accomplished in rapid development cycle
- **Systematic Bug Resolution**: Each version addressed specific user-reported issues
- **Production Ready**: v2.1 achieved stable, enterprise-grade functionality

## Credits
- **v1.1**: Original script by [TheAlanK](https://github.com/TheAlanK) & SAPIENT
- **v2.0+**: Enhanced by [iikoshteruu](https://github.com/iikoshteruu)
