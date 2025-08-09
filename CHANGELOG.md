# 📝 Changelog

All notable changes to imdb-on-netflix will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [4.0.0] - 2024-12-19

### Added
- **Multi-Source Ratings**: Support for IMDb, Rotten Tomatoes, and Metascore ratings
- **OMDB API Integration**: Real ratings from trusted sources via free OMDB API
- **Metascore Support**: Additional critic ratings from Metacritic
- **Enhanced UI**: New overlay design showing multiple rating sources
- **Improved Popup**: Updated interface with rating source information
- **Better Documentation**: Comprehensive README and setup guides

### Changed
- **Rating Display**: Now shows multiple ratings simultaneously
- **API Architecture**: Switched from single IMDb API to multi-source OMDB API
- **Cache System**: Updated to handle multiple rating sources
- **Visual Design**: New color scheme and icons for different rating sources

### Fixed
- **Fake Ratings Issue**: Replaced simulated RT ratings with real data
- **API Reliability**: More robust error handling and rate limiting
- **Performance**: Optimized concurrent API requests

### Technical
- **Code Structure**: Refactored for better maintainability
- **Error Handling**: Improved error recovery and user feedback
- **Rate Limiting**: Enhanced API request management

## [3.0.0] - 2024-12-18

### Added
- **Platform Agnostic Architecture**: Single codebase for all streaming platforms
- **Advanced Fuzzy Matching**: Multi-algorithm title matching system
- **Smart Caching**: 30-day cache with automatic cleanup
- **Rate Limiting**: Built-in API rate limiting and retry logic
- **Enhanced UI**: Modern overlay design with hover effects

### Changed
- **Code Organization**: Modular design with separate components
- **Performance**: Concurrent request processing
- **Reliability**: Better error handling and recovery

### Fixed
- **Title Extraction**: Improved accuracy across platforms
- **Memory Usage**: Reduced memory footprint with WeakSet tracking
- **Loading Speed**: Faster initial load with debounced updates

## [2.0.0] - 2024-12-17

### Added
- **Multi-Platform Support**: Netflix, Hotstar, Prime Video, Disney+
- **Real IMDb Ratings**: Integration with IMDb API
- **Basic Caching**: Simple cache system for performance
- **Extension Popup**: Basic popup interface

### Changed
- **Architecture**: Moved from single-platform to multi-platform
- **UI Design**: Improved overlay appearance

## [1.0.0] - 2024-12-16

### Added
- **Initial Release**: Basic IMDb ratings for Netflix
- **Simple Overlay**: Basic rating display
- **Chrome Extension**: Initial extension structure

---

## 🔮 Upcoming Features

### Planned for v4.1.0
- [ ] **Customization Options**: User-configurable overlay appearance
- [ ] **Additional Platforms**: Support for more streaming services
- [ ] **Performance Improvements**: Further optimization

### Planned for v4.2.0
- [ ] **User Preferences**: Save user settings
- [ ] **Advanced Filtering**: Filter by rating thresholds
- [ ] **Export Features**: Export rating data

### Planned for v5.0.0
- [ ] **Mobile Support**: Chrome mobile extension
- [ ] **Advanced Analytics**: Usage statistics
- [ ] **Social Features**: Share ratings with friends

---

## 📊 Version Compatibility

| Version | Chrome | Netflix | Hotstar | Prime Video | Disney+ |
|---------|--------|---------|---------|-------------|---------|
| 4.0.0   | 88+    | ✅      | ✅      | ✅          | ✅      |
| 3.0.0   | 88+    | ✅      | ✅      | ✅          | ✅      |
| 2.0.0   | 88+    | ✅      | ✅      | ✅          | ✅      |
| 1.0.0   | 88+    | ✅      | ❌      | ❌          | ❌      |

---

## 🐛 Known Issues

### Version 4.0.0
- **API Rate Limits**: OMDB API has 1,000 requests/day limit
- **Title Matching**: Some foreign titles may not match perfectly
- **Mobile Chrome**: Extension doesn't work on mobile Chrome

### Version 3.0.0
- **Cache Size**: Large cache may impact performance
- **Memory Usage**: High memory usage on pages with many cards

---

## 🔧 Migration Guide

### From v3.0.0 to v4.0.0
1. **Get OMDB API Key**: Visit [omdbapi.com](http://www.omdbapi.com/)
2. **Update API Key**: Replace `YOUR_OMDB_API_KEY` in `content.js`
3. **Reload Extension**: Refresh the extension in Chrome
4. **Clear Cache**: Clear old cache data if needed

### From v2.0.0 to v3.0.0
1. **Backup Settings**: Save any custom configurations
2. **Update Extension**: Load the new version
3. **Test Platforms**: Verify functionality on all platforms

---

## 📞 Support

For issues, questions, or feature requests:
- **GitHub Issues**: [Report a Bug](https://github.com/Shailshahvt/imdb-on-netflix/issues)
- **GitHub Discussions**: [Ask a Question](https://github.com/Shailshahvt/imdb-on-netflix/discussions)
- **Contact**: [@Shailshahvt](https://github.com/Shailshahvt)

---

**Made with ❤️ for the streaming community**
