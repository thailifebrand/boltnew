# Contributing to Innovation Dashboard

Thank you for your interest in contributing to the Innovation Dashboard! This document provides guidelines and information for contributors.

## 🚀 Getting Started

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/your-username/innovation-dashboard.git
   cd innovation-dashboard
   ```
3. **Install dependencies**:
   ```bash
   npm install
   ```
4. **Start the development server**:
   ```bash
   npm run dev
   ```

## 🔧 Development Setup

### Prerequisites
- Node.js 16 or higher
- npm or yarn
- Git

### Project Structure
```
src/
├── components/          # Reusable UI components
├── hooks/              # Custom React hooks
├── services/           # API and external service integrations
├── types/              # TypeScript type definitions
├── App.tsx             # Main application component
└── main.tsx           # Application entry point
```

## 📝 Code Style

We use ESLint and TypeScript for code quality. Please ensure your code:

- Follows the existing code style
- Includes proper TypeScript types
- Has meaningful variable and function names
- Includes comments for complex logic

### Running Linting
```bash
npm run lint
```

## 🧪 Testing

Currently, the project uses manual testing. When adding new features:

1. Test on different screen sizes (mobile, tablet, desktop)
2. Verify data loading and error states
3. Check chart interactions and responsiveness
4. Ensure accessibility standards are met

## 📋 Pull Request Process

1. **Create a feature branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes** following the code style guidelines

3. **Test thoroughly** on different devices and browsers

4. **Commit with clear messages**:
   ```bash
   git commit -m "Add: Brief description of your changes"
   ```

5. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Create a Pull Request** with:
   - Clear title and description
   - Screenshots if UI changes are involved
   - Reference to any related issues

## 🐛 Bug Reports

When reporting bugs, please include:

- **Clear description** of the issue
- **Steps to reproduce** the problem
- **Expected vs actual behavior**
- **Screenshots** if applicable
- **Browser and device information**
- **Console errors** if any

## 💡 Feature Requests

For new features:

- **Describe the feature** and its benefits
- **Explain the use case** and user story
- **Consider implementation complexity**
- **Check if similar features exist**

## 🎨 Design Guidelines

When contributing UI changes:

- Follow the existing design system
- Maintain consistent spacing (8px grid system)
- Use the established color palette
- Ensure proper contrast ratios for accessibility
- Test on different screen sizes

### Color Palette
- Primary: Blue (#3B82F6)
- Secondary: Purple (#8B5CF6)
- Accent: Teal (#06B6D4)
- Success: Green (#10B981)
- Warning: Yellow (#F59E0B)
- Error: Red (#EF4444)

## 📊 Data Integration

When working with data features:

- Maintain compatibility with Google Sheets API
- Handle loading and error states gracefully
- Ensure data validation and sanitization
- Consider performance implications
- Test with various data scenarios

## 🔒 Security Considerations

- Never commit API keys or sensitive data
- Use environment variables for configuration
- Validate all user inputs
- Follow security best practices for data handling

## 📚 Documentation

When adding features:

- Update README.md if necessary
- Add inline comments for complex logic
- Update type definitions
- Consider adding usage examples

## 🤝 Community Guidelines

- Be respectful and inclusive
- Provide constructive feedback
- Help others learn and grow
- Follow the code of conduct

## 📞 Getting Help

If you need help:

1. Check existing issues and documentation
2. Ask questions in issue discussions
3. Reach out to maintainers

## 🏆 Recognition

Contributors will be recognized in:
- README.md contributors section
- Release notes for significant contributions
- Project documentation

Thank you for contributing to make the Innovation Dashboard better! 🚀