This repository contains a multi-component Python CLI utility that integrates an Abstract Syntax Tree (AST)-based static code analyzer, a SQLite-backed cache for storing and retrieving analysis results, and an asynchronous concurrency tester to simulate API load under different conditions. The project is organized into the following components:

1. **src/core.py**: Contains the core business logic for the static code analyzer, cache operations, and concurrency tester.
2. **src/cli.py**: Provides a rich terminal interface for interacting with the core components.
3. **tests/test_core.py**: Includes deterministic, self-contained unit tests to ensure the correctness of the core components.

The architecture is modular, with clear separation of concerns, making it maintainable and easy to extend.