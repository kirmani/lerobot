# CLAUDE.md - LeRobot Coding Guidelines

## Commands
- Install dev dependencies: `pip install -e ".[dev,test]"`
- Run tests: `pytest tests/`
- Run single test: `pytest tests/path_to_file.py::test_function_name`
- End-to-end tests: `make test-end-to-end`
- Lint code: `ruff check .`
- Format code: `ruff format .`
- Run all checks: `pre-commit run --all-files`

## Code Style
- License header: Include Apache 2.0 header in all files
- Imports: Standard lib → Third-party → Project imports, alphabetically ordered
- Type hints: Always use modern syntax (Python 3.10+: `list[str]` not `List[str]`)
- Naming: `snake_case` for functions/variables, `CamelCase` for classes
- Line length: 110 characters max
- Docstrings: Include description, Args, Returns, and Raises sections
- Error handling: Use specific exception types with descriptive messages
- TODO comments: Include owner names (`TODO(username):`)
- Factory pattern: Use for creating instances of complex objects
- Dataclasses: Use for configuration objects

Contact the LeRobot team on [Discord](https://discord.gg/s3KuuzsPFb) for questions.