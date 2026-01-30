# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-01-30

### Added
- 🎉 Initial release of Rich Text to Markdown Converter
- ✅ Real-time conversion from rich text to Markdown
- ✅ Split-view interface with editor and output panels
- ✅ Comprehensive formatting toolbar with buttons for:
  - Bold, Italic, Underline, Strikethrough
  - Headers (H1-H6)
  - Ordered and unordered lists
  - Links and images
  - Code blocks
  - Blockquotes
  - Horizontal rules
- ✅ Copy to clipboard functionality
- ✅ Download as .md file feature
- ✅ Clear editor button
- ✅ Keyboard shortcuts (Ctrl+B, Ctrl+I, Ctrl+U)
- ✅ Responsive design for mobile, tablet, and desktop
- ✅ Professional gradient UI with Tailwind CSS
- ✅ Toast notifications for user actions
- ✅ Comprehensive SEO optimization
- ✅ Open Graph and Twitter Card meta tags
- ✅ Schema.org structured data
- ✅ PWA manifest for installability
- ✅ Detailed documentation (README, CONTRIBUTING, DEPLOY guides)
- ✅ FAQ section
- ✅ Features showcase section
- ✅ Use cases examples
- ✅ What is Markdown educational content
- ✅ Privacy-first approach (all processing in browser)
- ✅ No dependencies on external JavaScript libraries
- ✅ robots.txt for SEO
- ✅ sitemap.xml for search engines
- ✅ MIT License

### Technical Details
- Built with vanilla JavaScript (ES6+)
- Uses ContentEditable API for rich text editing
- Custom HTML to Markdown parser
- Clipboard API for copy functionality
- Blob API for file downloads
- Tailwind CSS for styling (via CDN)
- Font Awesome icons (via CDN)

### Browser Support
- Chrome/Edge (latest) ✅
- Firefox (latest) ✅
- Safari (latest) ✅
- Mobile browsers ✅

---

## [Unreleased]

### Planned Features
- [ ] Table support for Markdown tables
- [ ] Dark mode toggle
- [ ] Additional keyboard shortcuts
- [ ] Syntax highlighting for code blocks
- [ ] Export to PDF/HTML
- [ ] Markdown to Rich Text (reverse conversion)
- [ ] Internationalization (i18n)
- [ ] Undo/Redo functionality
- [ ] Save/Load drafts from localStorage
- [ ] More formatting options (superscript, subscript, etc.)
- [ ] Drag and drop file upload
- [ ] Image upload and embedding
- [ ] Live preview mode
- [ ] Split screen adjustment
- [ ] Custom themes
- [ ] Accessibility improvements (WCAG AA compliance)

---

## Version History

### Version Naming Convention
- **Major version** (1.x.x): Breaking changes or major new features
- **Minor version** (x.1.x): New features, backward compatible
- **Patch version** (x.x.1): Bug fixes and minor improvements

### How to Contribute to Changelog
When contributing, please update this file with your changes in the [Unreleased] section following this format:

```markdown
### Added
- New features

### Changed
- Changes to existing features

### Deprecated
- Features that will be removed in future versions

### Removed
- Removed features

### Fixed
- Bug fixes

### Security
- Security improvements
```

---

[1.0.0]: https://github.com/muhammad-waqas1/rich-text-markdown-converter/releases/tag/v1.0.0