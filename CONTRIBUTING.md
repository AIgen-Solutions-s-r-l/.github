# Contributing to Algen Solutions Projects

Thank you for your interest in contributing to Algen Solutions! We welcome contributions from the community and are grateful for your support.

## How to Contribute

### Reporting Issues

If you find a bug or have a suggestion:

1. **Search existing issues** to avoid duplicates
2. **Create a new issue** with a clear title and description
3. **Provide details**:
   - Steps to reproduce (for bugs)
   - Expected vs. actual behavior
   - Environment details (OS, Python version, etc.)
   - Screenshots or logs if applicable

### Suggesting Enhancements

We love new ideas! When suggesting enhancements:

1. **Check existing feature requests** first
2. **Clearly describe the feature** and its use case
3. **Explain the benefits** and potential implementation approach
4. **Consider the scope** - is this aligned with the project's goals?

### Pull Requests

We actively welcome your pull requests:

1. **Fork the repository** and create your branch from `main`
2. **Follow the project's code style**:
   - Use meaningful variable and function names
   - Write clear comments for complex logic
   - Follow PEP 8 for Python projects
3. **Write or update tests** for your changes
4. **Update documentation** if needed
5. **Ensure all tests pass** before submitting
6. **Write a clear commit message** describing your changes

#### Pull Request Process

1. Update the README.md or relevant documentation with details of changes
2. Add any new dependencies to requirements.txt or setup.py
3. The PR will be merged once you have the approval of at least one maintainer
4. Follow the code review feedback and make necessary adjustments

## Development Setup

### Prerequisites

- Python 3.8 or higher
- Git
- Virtual environment (recommended)

### Local Development

```bash
# Clone the repository
git clone https://github.com/algensolutions/[repository-name].git
cd [repository-name]

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Install development dependencies
pip install -r requirements-dev.txt  # if available

# Run tests
pytest
```

## Code Style

### Python

- Follow PEP 8 style guide
- Use type hints where applicable
- Maximum line length: 100 characters
- Use docstrings for functions and classes

```python
def calculate_risk(portfolio: dict, threshold: float = 0.05) -> float:
    """
    Calculate the risk metric for a given portfolio.

    Args:
        portfolio: Dictionary containing portfolio positions
        threshold: Risk threshold value (default: 0.05)

    Returns:
        Calculated risk value as float
    """
    pass
```

### Commit Messages

Follow the conventional commits format:

- `feat:` New feature
- `fix:` Bug fix
- `docs:` Documentation changes
- `style:` Code style changes (formatting, etc.)
- `refactor:` Code refactoring
- `test:` Adding or updating tests
- `chore:` Maintenance tasks

Example:
```
feat: add real-time portfolio monitoring

- Implement WebSocket connection for live data
- Add portfolio risk calculation
- Update UI with live updates
```

## Testing

- Write unit tests for new features
- Ensure all existing tests pass
- Aim for high code coverage (>80%)
- Include integration tests for critical paths

## Documentation

- Update README.md for user-facing changes
- Add docstrings to new functions and classes
- Update inline comments for complex logic
- Consider adding examples for new features

## Community Guidelines

- Be respectful and inclusive
- Help others learn and grow
- Give constructive feedback
- Follow our [Code of Conduct](CODE_OF_CONDUCT.md)

## Questions?

Feel free to reach out:

- Open a discussion in the repository
- Email us at [info@aigensolutions.it](mailto:info@aigensolutions.it)
- Check existing documentation and issues

## License

By contributing, you agree that your contributions will be licensed under the same license as the project (typically MIT License).

---

Thank you for contributing to Algen Solutions!
