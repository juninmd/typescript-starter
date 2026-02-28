```markdown
# AGENTS.md - AI Coding Agent Guidelines

These guidelines outline the specific requirements and principles for all development of this AGENTS.md file. Adherence to these principles is mandatory for all code produced within this repository.

## 1. DRY (Don't Repeat Yourself)

- Every function, class, or module should have a single, well-defined purpose.
- Avoid duplication of logic or code.
- Refactor code to eliminate redundancy whenever possible.
- Use interfaces or abstract classes to define common behavior.

## 2. KISS (Keep It Simple, Stupid)

- Strive for the simplest possible solution that meets the requirements.
- Minimize complexity and unnecessary elements.
- Avoid overly elaborate solutions.
- Prioritize readability and maintainability.

## 3. SOLID Principles

- **Single Responsibility Principle:** Each class or module should have one, and only one, reason to change.
- **Open/Closed Principle:** The system should be extensible without modifying the existing code.
- **Liskov Substitution Principle:** Subclasses should be able to replace their base classes without breaking the correctness of the program.
- **Interface Segregation Principle:** Client code should not be forced to depend on methods it doesn't use.
- **Dependency Inversion Principle:** High-level modules should not depend on low-level modules; they should depend on abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

- Avoid implementing features or code that is not currently required.
- Focus solely on the tasks required for the current phase of development.
- Resist the urge to add functionality before it is explicitly needed.

## 5. Testing & Coverage

- **All development must be productive.** Do not deviate from the core purpose of the code.
- **Mocks ONLY for tests.** Use mocks for unit and integration testing.  No real implementations are permitted within this repository.
- Testing coverage must be at least 80%. Utilize automated testing tools to verify code functionality.
- Write clear and concise tests that validate expected behavior.
- Test edge cases and boundary conditions.

## 6. Code Length & Structure

- Each file shall not exceed 180 lines of code.
- Code should be well-formatted and consistently styled.
- Use comments liberally to explain complex logic and non-obvious design choices.
- Use meaningful variable and function names.
- Ensure proper indentation for readability.
-  Maintain consistent coding style throughout the repository.

## 7. File Structure & Organization

- Create a logical folder structure for each module or component.
- Organize files within folders based on their purpose.
- Use a naming convention for files and variables.
- Maintain a clear hierarchy of files and subdirectories.

## 8. Data Handling

- Data should be managed consistently throughout the system.
- Use appropriate data structures for different data types.
- Implement clear validation and error handling.
- Avoid unnecessary data transformations.

## 9. API Definition (Example)

-  Each API should have a documented specification, including parameters, return values, and potential exceptions.
-  Use a consistent API naming convention.
-  Provide clear examples of how to use the API.

## 10.  Documentation Requirements

-  All classes, functions, and modules must have a clear docstring explaining their purpose, parameters, and return values.
-  Include relevant examples in the docstring.
-  Keep documentation up-to-date with the code.

## 11.  Maintainability Considerations

-  Design for easy modification and extension.
-  Use version control (Git) effectively.
-  Implement logging for debugging and monitoring.

## 12.  Framework/Library Specific Guidelines (Example - Adapt to your framework)**

-  [Framework Name] - Follow the recommended design patterns for [Specific Pattern].
-  [Library Name] - Utilize the latest version of [Library Name] for best performance.

These guidelines are subject to change as the AGENTS.md repository evolves.  All modifications must be reviewed and approved by the lead developer.
```