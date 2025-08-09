# 🤝 Contributing to imdb-on-netflix

Thank you for your interest in contributing to imdb-on-netflix! This document provides guidelines and information for contributors.

## 🚀 Quick Start

1. **Fork the repository**
2. **Clone your fork**: `git clone https://github.com/yourusername/imdb-on-netflix.git`
3. **Create a branch**: `git checkout -b feature/amazing-feature`
4. **Make your changes**
5. **Test thoroughly**
6. **Commit**: `git commit -m 'Add amazing feature'`
7. **Push**: `git push origin feature/amazing-feature`
8. **Open a Pull Request**

## 🛠️ Development Setup

### Prerequisites
- Google Chrome browser
- Basic knowledge of JavaScript, HTML, and CSS
- Git

### Local Development
1. **Get an OMDB API key** from [omdbapi.com](http://www.omdbapi.com/)
2. **Update `content.js`** with your API key
3. **Load extension in Chrome**:
   - Go to `chrome://extensions/`
   - Enable "Developer mode"
   - Click "Load unpacked"
   - Select the imdb-on-netflix folder
4. **Test on streaming platforms**

## 📋 Contribution Guidelines

### Code Style
- **JavaScript**: Use ES6+ features, meaningful variable names
- **CSS**: Use BEM methodology, consistent spacing
- **HTML**: Semantic markup, accessibility-friendly
- **Comments**: Clear, concise comments for complex logic

### Commit Messages
Use conventional commit format:
```
feat: add support for new streaming platform
fix: resolve rating display issue on mobile
docs: update README with new features
style: improve overlay design
refactor: optimize API request handling
test: add unit tests for fuzzy matching
```

### Pull Request Guidelines
1. **Clear title** describing the change
2. **Detailed description** of what was changed and why
3. **Screenshots** for UI changes
4. **Test results** on multiple platforms
5. **Link to related issues** if applicable

## 🎯 Areas for Contribution

### High Priority
- **New Platform Support**: Add support for more streaming platforms
- **Performance Optimization**: Improve loading speed and efficiency
- **Bug Fixes**: Fix issues reported by users
- **Accessibility**: Improve accessibility features

### Medium Priority
- **UI/UX Improvements**: Better design and user experience
- **Additional Rating Sources**: Integrate more rating APIs
- **Customization Options**: Allow users to customize appearance
- **Analytics**: Add usage analytics (privacy-friendly)

### Low Priority
- **Documentation**: Improve docs and add examples
- **Testing**: Add unit tests and integration tests
- **Internationalization**: Support for multiple languages
- **Advanced Features**: Advanced filtering and sorting

## 🐛 Bug Reports

### Before Reporting
1. **Check existing issues** to avoid duplicates
2. **Test on different platforms** to isolate the problem
3. **Clear browser cache** and try again
4. **Check console errors** in DevTools

### Bug Report Template
```markdown
**Platform**: Netflix/Hotstar/Prime Video/Disney+
**Browser**: Chrome Version XX.X.XXXX.XX
**Extension Version**: 4.0.0
**API Key**: [Yes/No]

**Description**:
[Clear description of the issue]

**Steps to Reproduce**:
1. [Step 1]
2. [Step 2]
3. [Step 3]

**Expected Behavior**:
[What should happen]

**Actual Behavior**:
[What actually happens]

**Console Errors**:
[Any error messages from DevTools console]

**Screenshots**:
[If applicable]
```

## 💡 Feature Requests

### Before Requesting
1. **Check existing issues** for similar requests
2. **Think about implementation** complexity
3. **Consider user impact** and value

### Feature Request Template
```markdown
**Feature Description**:
[Clear description of the feature]

**Use Case**:
[Why this feature would be useful]

**Proposed Implementation**:
[How you think it could be implemented]

**Alternatives Considered**:
[Other approaches you've thought about]

**Additional Context**:
[Any other relevant information]
```

## 🧪 Testing

### Manual Testing Checklist
- [ ] Test on Netflix
- [ ] Test on Hotstar
- [ ] Test on Prime Video
- [ ] Test on Disney+
- [ ] Test on mobile Chrome (if applicable)
- [ ] Test with different API keys
- [ ] Test with slow internet connection
- [ ] Test with disabled cache

### Automated Testing
We're working on adding automated tests. For now, please:
- Test your changes thoroughly
- Document test cases
- Include test scenarios in PR descriptions

## 📚 Documentation

### Code Documentation
- **Functions**: JSDoc comments for complex functions
- **Classes**: Document class purpose and methods
- **Configuration**: Explain config options
- **API Integration**: Document API usage and limits

### User Documentation
- **README**: Keep updated with new features
- **SETUP.md**: Update setup instructions
- **Screenshots**: Update demo images when UI changes

## 🔒 Security

### API Keys
- **Never commit API keys** to the repository
- **Use environment variables** for local development
- **Document key requirements** clearly
- **Test with invalid keys** to ensure proper error handling

### Data Privacy
- **Minimize data collection** to what's necessary
- **Respect user privacy** in all features
- **Document data usage** clearly
- **Follow GDPR guidelines** if applicable

## 🏷️ Labels

We use the following labels for issues and PRs:
- `bug`: Something isn't working
- `enhancement`: New feature or request
- `documentation`: Improvements or additions to documentation
- `good first issue`: Good for newcomers
- `help wanted`: Extra attention is needed
- `platform`: Platform-specific issues
- `performance`: Performance improvements
- `ui/ux`: User interface improvements

## 🎉 Recognition

Contributors will be recognized in:
- **README.md** contributors section
- **Release notes** for significant contributions
- **GitHub contributors** page

## 📞 Getting Help

- **Issues**: [GitHub Issues](https://github.com/Shailshahvt/imdb-on-netflix/issues)
- **Discussions**: [GitHub Discussions](https://github.com/Shailshahvt/imdb-on-netflix/discussions)
- **Contact**: [@Shailshahvt](https://github.com/Shailshahvt)

## 📄 License

By contributing to imdb-on-netflix, you agree that your contributions will be licensed under the MIT License.

---

**Thank you for contributing to imdb-on-netflix!** 🎬✨
