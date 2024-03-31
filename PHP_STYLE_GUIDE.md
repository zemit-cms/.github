# Zemit PHP Style Guide

This style guide outlines the coding conventions for PHP development in the Zemit project.

## General Principles

- **Readability and Clarity**: Write code that is clear and easy to understand.
- **Consistency**: Follow the established patterns in the codebase.
- **Practicality Over Purity**: Practicality should be preferred over adhering strictly to theoretical purity.

## Coding Standards

### PHP-FIG Standards

Adhere to [PHP-FIG](https://www.php-fig.org/) standards, specifically:
- [PSR-1: Basic Coding Standard](https://www.php-fig.org/psr/psr-1/)
- [PSR-12: Extended Coding Style](https://www.php-fig.org/psr/psr-12/)

### Naming Conventions

- **Classes**: PascalCase.
- **Methods/Functions**: camelCase.
- **Variables**: camelCase; be descriptive.
- **Constants**: UPPERCASE_WITH_UNDERSCORES.

### File Structure

- Follow one class per file. The filename should match the class name.
- Use `<?php declare(strict_types=1);` at the top of each PHP file for strict typing.

### Indentation and Whitespace

- Use 4 spaces for indentation, not tabs.
- Place a single blank line after namespace declarations.
- Method and function calls should have no spaces between the method name, the opening parenthesis, and the first parameter; spaces between commas and each parameter, and no space between the last parameter, the closing parenthesis, and the semicolon.

### Comments and Documentation

- Use `/** ... */` for docblocks and `//` for inline comments.
- Every class and method should have a docblock that describes its purpose.
- Avoid obvious comments; comment to explain the "why," not the "how."

### Control Structures

- Use braces to indicate control structure body.
- Place the opening brace on the same line as the control statement and the closing brace on its own line.

### Error Handling

- Use exceptions rather than error handling functions.
- Always handle exceptions at the appropriate level in your application.

## Best Practices

- **DRY (Don't Repeat Yourself)**: Reuse code where possible.
- **YAGNI (You Aren't Gonna Need It)**: Don't write code that isn't necessary.
- **KISS (Keep It Simple, Stupid)**: Avoid unnecessary complexity.
- **Separation of Concerns**: Organize code into distinct layers.

## Code Reviews

All contributions to the Zemit project are subject to code reviews to ensure compliance with this style guide.
