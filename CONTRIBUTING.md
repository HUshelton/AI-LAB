# Contributing to AI-LAB

Thank you for your interest in contributing to the AI-LAB project! This document provides guidelines for contributing to this repository.

## How to Contribute

### Reporting Issues

- Check if the issue already exists
- Use a clear and descriptive title
- Provide detailed information about the problem
- Include steps to reproduce the issue
- Share your environment details (OS, Python version, etc.)

### Suggesting Enhancements

- Use a clear and descriptive title
- Provide a detailed description of the proposed enhancement
- Explain why this enhancement would be useful
- Include examples if applicable

### Pull Requests

1. **Fork the repository** and create your branch from `main`
2. **Follow the code style** of the project
3. **Add tests** for new functionality
4. **Update documentation** as needed
5. **Ensure all tests pass** before submitting
6. **Write clear commit messages**

## Development Setup

1. Clone your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/AI-LAB.git
   cd AI-LAB
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## Code Style Guidelines

- Follow PEP 8 style guide for Python code
- Use meaningful variable and function names
- Add comments for complex logic
- Write docstrings for functions and classes
- Keep functions focused and modular

## Testing

- Write unit tests for new functionality
- Ensure all existing tests pass
- Aim for good test coverage
- Run tests before submitting PR:
  ```bash
  python -m pytest
  ```

## Documentation

- Update README.md if adding new features
- Add docstrings to new functions/classes
- Update relevant documentation in the `docs/` directory
- Include examples where helpful

## Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters
- Reference issues and pull requests where applicable

## Code Review Process

- All submissions require review before merging
- Reviewers may request changes
- Address feedback and update your PR
- Maintain a respectful and constructive dialogue

## Questions?

Feel free to open an issue for questions or concerns about contributing.

Thank you for contributing to AI-LAB! 🎉
