# Testing Guidelines

Robust tests ensure the stability of the project.

- Use `pytest` for all unit and integration tests.
- Place tests under `tests/` mirroring the package structure.
- Provide fixtures or sample data when necessary to keep tests deterministic.
- Run `make -C schema test` to execute the schema validation suite before committing.
- Prefer automated tests over manual verification and keep test output clean.
- Address failing tests immediately and strive for high coverage of critical code.
