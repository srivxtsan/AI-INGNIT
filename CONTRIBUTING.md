# Contributing to Smart Agriculture Dashboard

Thank you for your interest in contributing to the Smart Agriculture Dashboard! This document provides guidelines and information for contributors.

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or bun package manager
- Git

### Development Setup
1. Fork the repository
2. Clone your fork: `git clone https://github.com/your-username/smart-agriculture-dashboard.git`
3. Install dependencies: `npm install`
4. Start development server: `npm run dev`

## 📝 How to Contribute

### Reporting Bugs
1. Check existing issues to avoid duplicates
2. Use the bug report template
3. Include steps to reproduce, expected behavior, and screenshots if applicable

### Suggesting Features
1. Check existing feature requests
2. Use the feature request template
3. Provide clear use cases and benefits

### Code Contributions

#### Branch Naming Convention
- `feature/description` - for new features
- `fix/description` - for bug fixes
- `docs/description` - for documentation updates
- `refactor/description` - for code refactoring

#### Commit Message Format
```
type(scope): description

[optional body]

[optional footer]
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

Example:
```
feat(dashboard): add crop stage detection feature

- Implement image upload functionality
- Add AI-powered crop stage recognition
- Update UI with detection results
```

#### Pull Request Process
1. Create a feature branch from `main`
2. Make your changes with clear, descriptive commits
3. Add tests if applicable
4. Update documentation if needed
5. Ensure all tests pass: `npm run test`
6. Run linting: `npm run lint`
7. Submit a pull request with:
   - Clear title and description
   - Link to related issues
   - Screenshots for UI changes

## 🎨 Code Style Guidelines

### TypeScript/React
- Use TypeScript for all new code
- Follow React functional component patterns
- Use custom hooks for reusable logic
- Implement proper error boundaries

### Styling
- Use Tailwind CSS utility classes
- Follow the existing design system
- Ensure responsive design
- Maintain accessibility standards

### File Organization
```
src/
├── components/     # Reusable components
├── pages/         # Page components
├── hooks/         # Custom hooks
├── lib/           # Utilities
├── types/         # Type definitions
└── constants/     # App constants
```

## 🧪 Testing

### Running Tests
```bash
npm run test        # Run all tests
npm run test:watch  # Run tests in watch mode
npm run test:coverage # Generate coverage report
```

### Writing Tests
- Write unit tests for utilities and hooks
- Write integration tests for components
- Use React Testing Library for component tests
- Aim for >80% code coverage

## 📚 Documentation

### Code Documentation
- Add JSDoc comments for functions and components
- Include prop types and descriptions
- Document complex logic and algorithms

### README Updates
- Update README.md for new features
- Include setup instructions for new dependencies
- Add examples for new functionality

## 🔍 Code Review Process

### For Reviewers
- Check code quality and style
- Verify functionality works as expected
- Ensure tests are adequate
- Review documentation updates
- Test on different devices/browsers

### For Contributors
- Respond to feedback promptly
- Make requested changes in separate commits
- Update PR description if scope changes
- Rebase if requested

## 🏷️ Release Process

### Versioning
We follow [Semantic Versioning](https://semver.org/):
- MAJOR: Breaking changes
- MINOR: New features (backward compatible)
- PATCH: Bug fixes (backward compatible)

### Release Checklist
- [ ] All tests pass
- [ ] Documentation updated
- [ ] CHANGELOG.md updated
- [ ] Version bumped in package.json
- [ ] Git tag created
- [ ] Release notes prepared

## 🤝 Community Guidelines

### Code of Conduct
- Be respectful and inclusive
- Welcome newcomers and help them learn
- Focus on constructive feedback
- Respect different opinions and approaches

### Communication
- Use clear, professional language
- Be patient with questions and feedback
- Provide helpful, actionable suggestions
- Celebrate contributions and achievements

## 📞 Getting Help

- **Issues**: Create a GitHub issue for bugs or questions
- **Discussions**: Use GitHub Discussions for general questions
- **Email**: Contact maintainers at dev@smartagriculture.com

## 🎯 Priority Areas

We're especially looking for contributions in:
- IoT sensor integrations
- Mobile responsiveness improvements
- Accessibility enhancements
- Performance optimizations
- Internationalization (i18n)
- Test coverage improvements

Thank you for contributing to sustainable agriculture technology! 🌱