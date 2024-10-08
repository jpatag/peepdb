---
title: Contributing
layout: default
---

# 🤝 Contributing to peepDB

Contributions to peepDB are welcome! Whether you're fixing bugs, improving documentation, or proposing new features, your efforts are appreciated. Here's how you can contribute:

## Steps to Contribute

1. Fork the repository on GitHub.
2. Clone your forked repository to your local machine.
3. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature/AmazingFeature
   ```
4. Make your changes and commit them with a clear commit message:
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
5. Push your changes to your fork on GitHub:
   ```bash
   git push origin feature/AmazingFeature
   ```
6. Open a Pull Request from your fork to the main peepDB repository.

## Setting Up Development Environment

1. Clone the repository:
   ```bash
   git clone https://github.com/evangelosmeklis/peepdb.git
   cd peepdb
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the package in editable mode with development dependencies:
   ```bash
   pip install -e .[dev]
   ```

## Code Style

- Follow PEP 8 guidelines for Python code.
- Use meaningful variable and function names.
- Add comments to explain complex logic.
- You can use tools like `flake8` or `black` to ensure your code adheres to the style guide.

## Testing

- Add unit tests for new features or bug fixes.
- Ensure all existing tests pass before submitting a pull request.
- Run the test suite using pytest:
  ```bash
  pytest
  ```

## Documentation

- Update the README.md file if you're adding or changing functionality.
- Add or update docstrings for new or modified functions and classes.

## Reporting Issues

If you find a bug or have a suggestion for improvement:

1. Check the GitHub Issues to see if it has already been reported.
2. If not, open a new issue, providing as much detail as possible.

Thank you for contributing to peepDB!
