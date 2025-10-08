# Tests

This directory contains test files for ensuring code quality and correctness.

## Running Tests

To run all tests:
```bash
python -m pytest
```

To run tests with coverage:
```bash
python -m pytest --cov=.
```

## Test Organization

- Unit tests for individual functions and classes
- Integration tests for complete workflows
- Test fixtures and sample data

## Writing Tests

Follow these guidelines:
- Write descriptive test names
- Test both success and failure cases
- Use appropriate assertions
- Keep tests independent and isolated
