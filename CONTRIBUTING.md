# Contributing to Rich Text to Markdown Converter

First off, thank you for considering contributing to Rich Text to Markdown Converter! 🎉

## How Can I Contribute?

### Reporting Bugs 🐛

Before creating bug reports, please check the existing issues to avoid duplicates. When you create a bug report, include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps to reproduce the problem**
- **Provide specific examples** (paste text that causes the issue)
- **Describe the behavior you observed** and what you expected
- **Include screenshots** if possible
- **Mention your browser and OS version**

### Suggesting Features 💡

Feature suggestions are welcome! Please:

- **Use a clear and descriptive title**
- **Provide a detailed description** of the suggested feature
- **Explain why this feature would be useful** to most users
- **Provide examples** of how the feature would work

### Pull Requests 🔧

1. **Fork the repository** and create your branch from `main`
2. **Make your changes** with clear, descriptive commits
3. **Test your changes** in multiple browsers
4. **Update documentation** if needed (README.md, comments, etc.)
5. **Submit a pull request** with a clear description

## Development Guidelines

### Code Style

- Use **meaningful variable and function names**
- Add **comments** for complex logic
- Follow the existing **code formatting** style
- Keep functions **small and focused**
- Use **ES6+ JavaScript** features

### Testing

Before submitting a PR, please test:

- ✅ Different types of formatted text
- ✅ Edge cases (empty input, very long text, special characters)
- ✅ All formatting buttons work correctly
- ✅ Copy and download features work
- ✅ Responsive design on mobile/tablet/desktop
- ✅ Different browsers (Chrome, Firefox, Safari, Edge)

### Commit Messages

Write clear commit messages:

```
Add support for table formatting

- Implement HTML table to Markdown table conversion
- Add table button to toolbar
- Update tests and documentation
```

### Areas We'd Love Help With

- 📊 **Table Support** - Convert HTML tables to Markdown tables
- 🎨 **Dark Mode** - Add a dark theme toggle
- ⌨️ **Keyboard Shortcuts** - More keyboard shortcuts for formatting
- 🌍 **Internationalization** - Support for multiple languages
- 📱 **Mobile Improvements** - Better mobile editing experience
- 🎨 **Syntax Highlighting** - Code syntax highlighting in preview
- 📥 **Import Options** - Import from various file formats
- 🔄 **Markdown to Rich Text** - Reverse conversion feature
- ♿ **Accessibility** - ARIA labels, keyboard navigation improvements
- 📝 **More Examples** - Add example formatted text for users to try

## Project Structure

```
rich-text-markdown-converter/
├── index.html              # Main application file
│   ├── <head>             # Meta tags, SEO, styles
│   ├── <header>           # Hero section
│   ├── <main>             # Converter and content sections
│   └── <script>           # All JavaScript functionality
├── README.md              # Project documentation
├── CONTRIBUTING.md        # This file
├── LICENSE               # MIT License
└── other config files    # robots.txt, sitemap.xml, etc.
```

## JavaScript Functions

Key functions you might want to modify:

- `convertToMarkdown()` - Main conversion function
- `htmlToMarkdown(html)` - HTML to Markdown parser
- `processNode(node, listLevel)` - Recursive node processor
- `formatText(command)` - Handles formatting commands
- Various insert functions for links, images, code blocks, etc.

## Getting Started

1. Fork and clone the repository
2. Open `index.html` in your browser
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## Questions?

Feel free to open an issue with the `question` label if you have any questions about contributing!

## Code of Conduct

- Be respectful and constructive
- Welcome newcomers and help them learn
- Focus on what is best for the community
- Show empathy towards other community members

Thank you for contributing! 🙏