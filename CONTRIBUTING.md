# Contributing to Modern Calculator

First off, thank you for considering contributing to Modern Calculator! 🎉

## How Can I Contribute?

### 🐛 Reporting Bugs

Before creating bug reports, please check the issue list as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps to reproduce the problem**
- **Provide specific examples** to demonstrate the steps
- **Describe the behavior you observed** and what you expected
- **Include screenshots** if possible
- **Include your browser version** and operating system

### 💡 Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

- **Use a clear and descriptive title**
- **Provide a detailed description** of the suggested enhancement
- **Explain why this enhancement would be useful**
- **List some examples** of how it would work

### 🔨 Pull Requests

1. Fork the repo and create your branch from `main`
2. Make your changes
3. Test thoroughly in multiple browsers
4. Update the README.md if needed
5. Issue the pull request!

#### Code Style Guidelines

**HTML:**
- Use semantic HTML5 elements
- Keep proper indentation (2 spaces)
- Add comments for complex sections

**CSS:**
- Use CSS custom properties for colors and spacing
- Keep selectors simple and specific
- Group related styles together
- Add comments for complex styles

**JavaScript:**
- Use ES6+ features (const, let, arrow functions)
- Add JSDoc comments for functions
- Keep functions small and focused
- Use descriptive variable names

#### Example Pull Request

```markdown
## Description
Added dark mode toggle feature

## Changes
- Added theme switcher button
- Created dark theme CSS variables
- Added localStorage to save preference
- Updated README with dark mode info

## Testing
- [x] Tested in Chrome
- [x] Tested in Firefox
- [x] Tested in Safari
- [x] Mobile responsive
- [x] Keyboard navigation works

## Screenshots
[Add screenshots here]
```

### 📝 Commit Messages

- Use present tense ("Add feature" not "Added feature")
- Use imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit first line to 72 characters
- Reference issues and pull requests

Examples:
```
feat: Add dark mode toggle
fix: Prevent multiple decimal points
docs: Update installation instructions
style: Format code according to guidelines
refactor: Simplify calculation logic
```

## Development Setup

1. **Clone your fork:**
   ```bash
   git clone https://github.com/yourusername/modern-calculator.git
   cd modern-calculator
   ```

2. **Create a branch:**
   ```bash
   git checkout -b feature/my-new-feature
   ```

3. **Make changes and test:**
   Open `index.html` in multiple browsers

4. **Commit your changes:**
   ```bash
   git add .
   git commit -m "feat: Add my new feature"
   ```

5. **Push to your fork:**
   ```bash
   git push origin feature/my-new-feature
   ```

6. **Create Pull Request** on GitHub

## Testing Checklist

Before submitting a PR, please ensure:

- [ ] Code works in Chrome, Firefox, Safari, and Edge
- [ ] Responsive design works on mobile (320px+)
- [ ] Keyboard navigation works
- [ ] No console errors
- [ ] All calculations are accurate
- [ ] Error handling works correctly
- [ ] Code is properly commented
- [ ] README updated if needed

## Feature Ideas

Looking for ideas? Here are some features we'd love to see:

- **Easy:**
  - [ ] Percentage button
  - [ ] Plus/minus toggle (±)
  - [ ] Different color themes
  
- **Medium:**
  - [ ] Memory functions (M+, M-, MR, MC)
  - [ ] Calculation history
  - [ ] Dark mode
  - [ ] Sound effects
  
- **Advanced:**
  - [ ] Scientific calculator mode
  - [ ] Unit converter
  - [ ] Currency converter
  - [ ] Graph plotter

## Questions?

Feel free to open an issue with the `question` label!

## Code of Conduct

Be respectful, inclusive, and constructive. We're all here to learn and build something cool together! 🚀

---

Thank you for contributing! ⭐