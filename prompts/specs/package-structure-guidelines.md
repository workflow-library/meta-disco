# Package Structure Guidelines

These conventions keep the repository organized and easy to navigate.

- Place source code under `src/` followed by the package name.
- Use clear, snake_case module names and CamelCase for classes.
- Keep top-level packages small and factor large areas into subpackages.
- Avoid circular imports; factor shared utilities into a common submodule.
- Include an `__init__.py` in each package to define its public API.
- Mirror the package layout in `tests/` so each module has corresponding tests.
- Add a brief README or module docstring describing the purpose of each package.
