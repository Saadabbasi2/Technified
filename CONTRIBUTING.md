# Contributing to Trexa

Thank you for your interest in contributing to the Trexa project! This document provides guidelines and best practices for collaborating on this project.

## 🌿 Branching Strategy

We follow a simplified Git Flow workflow:

### Main Branches
- **`main`**: Production-ready code. Always stable.
- **`develop`**: Integration branch for features. Latest development changes.

### Supporting Branches
- **`feature/*`**: New features (e.g., `feature/add-pricing-page`)
- **`bugfix/*`**: Bug fixes (e.g., `bugfix/fix-navigation-mobile`)
- **`hotfix/*`**: Urgent production fixes (e.g., `hotfix/fix-broken-link`)

### Branch Naming Convention
```
feature/short-description
bugfix/issue-description
hotfix/critical-fix
```

## 📝 Commit Message Guidelines

Write clear, descriptive commit messages following this format:

```
<type>: <subject>

<body (optional)>
```

### Types
- **feat**: New feature
- **fix**: Bug fix
- **docs**: Documentation changes
- **style**: Code formatting, missing semicolons, etc.
- **refactor**: Code refactoring
- **test**: Adding tests
- **chore**: Maintenance tasks

### Examples
```
feat: add pricing section to homepage

fix: resolve mobile menu not closing on link click

docs: update README with new installation steps

style: format CSS files and fix indentation
```

## 🔄 Pull Request Process

1. **Create a Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make Your Changes**
   - Write clean, readable code
   - Follow existing code style
   - Test your changes thoroughly

3. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "feat: add your feature description"
   ```

4. **Push to Remote**
   ```bash
   git push origin feature/your-feature-name
   ```

5. **Create Pull Request**
   - Provide a clear title and description
   - Reference any related issues
   - Request review from team members

6. **Code Review**
   - Address feedback promptly
   - Make requested changes
   - Keep discussions professional and constructive

7. **Merge**
   - Once approved, merge into `develop`
   - Delete the feature branch after merging

## 💻 Coding Standards

### HTML
- Use semantic HTML5 elements
- Maintain proper indentation (2 spaces)
- Include alt text for images
- Use meaningful class names
- Keep markup clean and readable

### CSS
- Follow BEM naming convention when applicable
- Group related properties together
- Use CSS variables for colors and common values
- Comment complex styles
- Maintain consistent formatting

### JavaScript
- Use meaningful variable and function names
- Comment complex logic
- Avoid global variables
- Keep functions small and focused
- Handle errors appropriately

## 🧪 Testing Requirements

Before submitting a pull request:

1. **Browser Testing**
   - Test in Chrome, Firefox, Safari, and Edge
   - Verify mobile responsiveness
   - Check different screen sizes

2. **Functionality Testing**
   - Test all interactive elements
   - Verify links work correctly
   - Ensure forms validate properly

3. **Performance**
   - Optimize images before committing
   - Minimize CSS/JS when possible
   - Check page load times

## 🐛 Reporting Bugs

When reporting bugs, please include:

1. **Description**: Clear description of the issue
2. **Steps to Reproduce**: Detailed steps to recreate the bug
3. **Expected Behavior**: What should happen
4. **Actual Behavior**: What actually happens
5. **Screenshots**: If applicable
6. **Environment**: Browser, OS, screen size

## 💡 Feature Requests

To request a new feature:

1. Check if it's already been requested
2. Provide a clear use case
3. Explain the expected behavior
4. Include mockups if applicable

## 📋 Code Review Checklist

Reviewers should verify:

- [ ] Code follows project standards
- [ ] Changes are well-tested
- [ ] Documentation is updated
- [ ] No unnecessary files are committed
- [ ] Commit messages are clear
- [ ] No merge conflicts exist
- [ ] Code is properly commented

## 🤝 Communication

- Be respectful and professional
- Provide constructive feedback
- Ask questions when unclear
- Help other team members
- Share knowledge and best practices

## 📚 Resources

- [Git Documentation](https://git-scm.com/doc)
- [HTML Best Practices](https://github.com/hail2u/html-best-practices)
- [CSS Guidelines](https://cssguidelin.es/)
- [JavaScript Style Guide](https://github.com/airbnb/javascript)

## ✅ Getting Started

1. Clone the repository
2. Create a new branch for your work
3. Make your changes
4. Test thoroughly
5. Submit a pull request
6. Respond to feedback

Thank you for contributing to Trexa! 🎉
