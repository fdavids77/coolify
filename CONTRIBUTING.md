# Contributing to My First Coolify App

Thank you for your interest in contributing to this project! This guide will help you get started.

## 🚀 Getting Started

### Prerequisites
- Node.js (version 18 or higher)
- Git
- A GitHub account

### Setting up the Development Environment

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/my-first-coolify-app.git
   cd my-first-coolify-app
   ```

3. **Add the original repository as upstream**:
   ```bash
   git remote add upstream https://github.com/ORIGINAL_OWNER/my-first-coolify-app.git
   ```

4. **Install dependencies**:
   ```bash
   npm install
   ```

5. **Start the development server**:
   ```bash
   npm start
   ```

## 🔄 Development Workflow

### Making Changes

1. **Create a new branch** for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes** following the coding standards below

3. **Test your changes** locally:
   ```bash
   npm start
   ```

4. **Commit your changes**:
   ```bash
   git add .
   git commit -m "Add: brief description of your changes"
   ```

5. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Create a Pull Request** from your fork to the main repository

### Commit Message Format

Use clear, descriptive commit messages:
- `Add: new feature or functionality`
- `Fix: bug fixes`
- `Update: modifications to existing features`
- `Remove: deletion of code or features`
- `Docs: documentation changes`

Example: `Add: health check endpoint with uptime information`

## 📝 Coding Standards

### JavaScript Style
- Use ES6+ features when appropriate
- Use meaningful variable and function names
- Add comments for complex logic
- Follow consistent indentation (2 spaces)

### File Structure
```
my-first-coolify-app/
├── public/          # Static frontend files
├── server.js        # Main server file
├── package.json     # Dependencies and scripts
└── README.md        # Documentation
```

### API Guidelines
- Use RESTful endpoints
- Return JSON responses
- Include appropriate HTTP status codes
- Add error handling

## 🧪 Testing

### Manual Testing
1. Start the server: `npm start`
2. Test in browser: `http://localhost:3000`
3. Test API endpoints:
   - `GET /api/health`
   - `GET /api/info`

### Testing Checklist
- [ ] Application starts without errors
- [ ] All API endpoints respond correctly
- [ ] Frontend loads and displays properly
- [ ] Buttons and interactive elements work
- [ ] No console errors in browser

## 🐛 Reporting Issues

When reporting bugs, please include:
- **Clear description** of the problem
- **Steps to reproduce** the issue
- **Expected behavior** vs actual behavior
- **Environment details** (OS, Node.js version, etc.)
- **Error messages** if any

### Issue Template
```
**Bug Description:**
Brief description of the bug

**Steps to Reproduce:**
1. Step one
2. Step two
3. Step three

**Expected Behavior:**
What should happen

**Actual Behavior:**
What actually happens

**Environment:**
- OS: 
- Node.js version:
- Browser:
```

## 💡 Feature Requests

For new features:
- **Check existing issues** to avoid duplicates
- **Describe the feature** clearly
- **Explain the use case** and benefits
- **Consider implementation** complexity

## 🔍 Code Review Process

### Pull Request Requirements
- [ ] Clear description of changes
- [ ] All tests pass
- [ ] Code follows style guidelines
- [ ] Documentation updated if needed
- [ ] No unnecessary dependencies added

### Review Checklist
- Code quality and readability
- Functionality works as expected
- No security vulnerabilities
- Performance considerations
- Documentation accuracy

## 🤝 Community Guidelines

### Be Respectful
- Use welcoming and inclusive language
- Respect different viewpoints and experiences
- Accept constructive criticism gracefully
- Focus on what's best for the community

### Be Helpful
- Help newcomers get started
- Share knowledge and experience
- Provide constructive feedback
- Collaborate effectively

## 📚 Resources

### Documentation
- [Express.js Documentation](https://expressjs.com/)
- [Node.js Documentation](https://nodejs.org/docs/)
- [Coolify Documentation](https://coolify.io/docs/)

### Learning Resources
- [JavaScript MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Git Handbook](https://guides.github.com/introduction/git-handbook/)
- [GitHub Flow](https://guides.github.com/introduction/flow/)

## 🙏 Recognition

Contributors will be recognized in:
- README.md contributors section
- Release notes for significant contributions
- GitHub contributors page

## 📞 Getting Help

If you need help:
1. Check the [README.md](README.md) first
2. Look through existing issues
3. Create a new issue with the "help wanted" label
4. Be patient and provide detailed information

---

Thank you for contributing to make this project better! 🎉
