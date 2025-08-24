# Contributing to NeuralMate

Thank you for your interest in contributing to NeuralMate! 🎉 We welcome contributions from developers of all skill levels and backgrounds.

## 🚀 Getting Started

### Prerequisites

- Node.js (v16.0.0 or higher)
- npm (v7.0.0 or higher)
- Git
- MongoDB (for backend development)

### Setting up the Development Environment

1. **Fork and Clone**
   ```bash
   # Fork the repository on GitHub first
   git clone https://github.com/your-username/NeuralMate.git
   cd NeuralMate
   ```

2. **Install Dependencies**
   ```bash
   # Frontend dependencies
   npm install
   
   # Backend dependencies
   cd backend
   npm install
   cd ..
   ```

3. **Environment Setup**
   ```bash
   cd backend
   cp .env.example .env
   # Edit .env with your configuration
   ```

## 🛠️ Development Workflow

### Making Changes

1. **Create a Branch**
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/bug-description
   ```

2. **Make Your Changes**
   - Follow the existing code style
   - Add comments for complex logic
   - Keep functions small and focused

3. **Test Your Changes**
   ```bash
   # Frontend
   npm run build
   npm run lint
   
   # Backend (if applicable)
   cd backend
   npm test
   ```

4. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "feat: add amazing new feature"
   # Follow conventional commit format
   ```

## 📝 Contribution Guidelines

### Code Style

- **JavaScript/JSX**: Follow the existing ESLint configuration
- **File naming**: Use camelCase for JS files, PascalCase for React components
- **Comments**: Add JSDoc comments for functions and complex logic
- **Variables**: Use descriptive names that explain the purpose

### Commit Messages

We use [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` - New features
- `fix:` - Bug fixes
- `docs:` - Documentation changes
- `style:` - Code style changes (formatting, etc.)
- `refactor:` - Code refactoring
- `test:` - Adding tests
- `chore:` - Maintenance tasks

### Pull Request Process

1. **Create a Pull Request**
   - Use a clear, descriptive title
   - Reference any related issues
   - Provide a detailed description of changes

2. **PR Template**
   ```markdown
   ## Description
   Brief description of changes

   ## Type of Change
   - [ ] Bug fix
   - [ ] New feature
   - [ ] Documentation update
   - [ ] Refactoring

   ## Testing
   - [ ] Tests pass locally
   - [ ] Added new tests (if applicable)

   ## Screenshots (if applicable)
   Add screenshots for UI changes
   ```

## 🐛 Reporting Issues

### Bug Reports

When reporting bugs, please include:

1. **Environment Information**
   - OS and version
   - Node.js version
   - Browser (if frontend issue)

2. **Steps to Reproduce**
   - Clear, numbered steps
   - Expected vs actual behavior
   - Screenshots/error messages

3. **Additional Context**
   - Console logs
   - Network tab information
   - Any relevant configuration

### Feature Requests

For feature requests, please include:

1. **Problem Description**
   - What problem does this solve?
   - Who would benefit from this feature?

2. **Proposed Solution**
   - Detailed description of the feature
   - How should it work?

3. **Alternatives Considered**
   - Other solutions you've thought about
   - Why is this the best approach?

## 🧪 Testing

### Frontend Testing

```bash
# Run linting
npm run lint

# Build for production
npm run build
```

### Backend Testing

```bash
cd backend

# Run any existing tests
npm test

# Manual testing with API endpoints
```

## 📚 Resources

### Helpful Links

- [React Documentation](https://react.dev/)
- [Express.js Guide](https://expressjs.com/)
- [MongoDB Documentation](https://docs.mongodb.com/)
- [Gemini API Documentation](https://ai.google.dev/)

### Project Structure

- `/src` - Frontend React application
- `/backend` - Node.js/Express server
- `/public` - Static assets
- `/docs` - Additional documentation

## 🏆 Recognition

Contributors will be:

- Added to the acknowledgements section
- Credited in release notes
- Given contributor badges (where applicable)

## 📞 Getting Help

Need help? Here are ways to get support:

1. **GitHub Issues** - For bugs and feature requests
2. **GitHub Discussions** - For questions and general discussion
3. **Documentation** - Check the README and code comments

## 🎉 Thank You!

Every contribution, no matter how small, helps make NeuralMate better for everyone. We appreciate your time and effort! 🙌

---

Happy coding! 🚀