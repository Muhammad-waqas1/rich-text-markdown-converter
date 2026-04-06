# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2026-04-06

### Added
- ✨ **Custom Modal System** - Replaced default browser alerts with beautiful, professional modals
- 🖼️ **Image Upload Feature** - Users can now upload images from their local computer in addition to using URLs
- 🎨 **Tabbed Image Insert** - Switch between "From URL" and "Upload Image" tabs
- 📤 **Drag & Drop Support** - Drag and drop images directly into the upload area
- 🖼️ **Image Preview** - Preview uploaded images before inserting
- 💬 **Professional Dialogs** - All prompts (link, image, code) now use custom modals with better UX
- ⌨️ **Keyboard Support** - Press Enter to confirm in modals, Escape to close
- 🎯 **Better Validation** - Visual feedback for required fields
- 📝 **Language Support in Code Blocks** - Optional language specification for syntax highlighting

### Changed
- 🔄 Improved modal animations with smooth slide-up effects
- 🎨 Enhanced visual design for all input dialogs
- 💾 Base64 image support in markdown output
- ✨ Better user feedback with backdrop blur on modals

### Improved
- 📱 Better mobile experience for modal interactions
- 🎭 More professional and polished UI/UX
- 🔒 Click outside modal or press Escape to close
- 💡 Clearer labels and placeholders in all forms

### Technical
- Implemented reusable `createModal()` function
- Added tab switching system for multi-option inputs
- File reader API integration for image uploads
- Enhanced markdown conversion to handle base64 images
- Improved code block detection with language classes

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
- [ ] Syntax highlighting for code blocks in preview
- [ ] Export to PDF/HTML
- [ ] Markdown to Rich Text (reverse conversion)
- [ ] Internationalization (i18n)
- [ ] Undo/Redo functionality
- [ ] Save/Load drafts from localStorage
- [ ] More formatting options (superscript, subscript, etc.)
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

[1.1.0]: https://github.com/yourusername/rich-text-markdown-converter/releases/tag/v1.1.0
[1.0.0]: https://github.com/yourusername/rich-text-markdown-converter/releases/tag/v1.0.0