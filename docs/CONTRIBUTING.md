# Contributing Guide
#
# This file contains guidelines for contributing to the project
#
# Code Style and Standards:
# - Follow PEP 8 for Python code
# - Use 4 spaces for indentation
# - Write descriptive variable and function names
# - Add docstrings to functions and classes
# - Keep lines under 100 characters
# - Use type hints where possible
#
# Commit Messages:
# - Use clear, descriptive commit messages
# - Format: "[TYPE] Brief description"
# - Types: feat, fix, docs, refactor, test, chore
# - Example: "[feat] Add collaborative filtering model"
#
# Pull Request Process:
# 1. Create a new branch for your feature
#    git checkout -b feature/your-feature-name
#
# 2. Make your changes
#    - Write clean, well-commented code
#    - Add tests for new functionality
#    - Update documentation
#
# 3. Test your changes
#    pytest tests/
#    flake8 backend/
#    black backend/
#
# 4. Commit your changes
#    git add .
#    git commit -m "[TYPE] Description"
#
# 5. Push to remote
#    git push origin feature/your-feature-name
#
# 6. Create Pull Request on GitHub
#    - Write clear PR description
#    - Reference any related issues
#    - Wait for code review
#
# 7. Address review comments
#    - Make requested changes
#    - Commit and push updates
#
# 8. Merge after approval
#
# Testing:
# - Write unit tests for new functions
# - Write integration tests for API endpoints
# - Aim for 80%+ code coverage
# - Run tests before committing
#
# Documentation:
# - Update README for new features
# - Update API docs for new endpoints
# - Update Architecture docs if structure changes
# - Add comments for complex logic
#
