## Review guidelines

- **Flag typos and grammar issues as P0 issues.**
- **Flag potential missing documentation as P1 issues.**
- **Flag missing tests as P1 issues.**

### Code Quality & Readability Standards
- **Conciseness (P1):** Ensure the code is as concise as possible without sacrificing clarity. Avoid redundant logic or "boilerplate" that doesn't add value.
- **Function Length & Modularity (P0):** Any function exceeding **30 lines** must be refactored into smaller, separate functions to maintain high readability and testability.
- **Readability Over Complexity (P0):** Prioritize simple, readable code over clever or "over-engineered" syntax. If a junior developer cannot easily follow the logic, suggest a simpler implementation.

### Flask Specifics
- Ensure business logic is separated from route definitions (keep View functions slim).
- Verify that variable naming is explicit and follows Pythonic conventions (PEP 8).