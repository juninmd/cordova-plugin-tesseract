```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure consistent, maintainable, and high-quality code within the AGENTS repository. Adherence to these principles is critical for collaborative development and long-term success.

**1. DRY (Don't Repeat Yourself)**

*   **Module Reuse:**  All reusable components, helper functions, and data structures must be encapsulated in modules.  Each module should have a single, well-defined purpose.
*   **Abstraction:**  Avoid unnecessary code duplication.  Create abstraction layers to represent complex concepts.
*   **Single Responsibility Principle:**  Each class, function, or module should have a single, focused responsibility.

**2. KISS (Keep It Simple, Stupid)**

*   **Code Clarity:**  Prioritize readability and understandability.  Favor simple, declarative code over complex, implicit logic.
*   **Minimize Complexity:**  Avoid overly clever or convoluted solutions.  Strive for straight-forward solutions.
*   **Small Functions:** Keep functions short and focused.  Aim for functions that perform a single, well-defined task.

**3. SOLID Principles**

*   **Single Responsibility:** Each class should have a single reason to change.
*   **Open/Closed Principle:**  Classes should be open for extension but closed for modification.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:**  Clients should not be forced to know about methods they don't use.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules.

**4. YAGNI (You Aren't Gonna Need It)**

*   **Avoid Feature Creep:**  Do not add functionality that is not currently required.  Focus on delivering the core functionality first.
*   **Refactor Based on Requirements:**  Refactor code only when requirements change.  Don't introduce new functionality for the sake of it.

**5. Code Style & Formatting**

*   **Consistent Formatting:** Follow a single, consistent code style (e.g., Google Style, PEP 8).  Use a linter (e.g., `flake8`, `pylint`) to enforce style.
*   **Indentation:** Use 2 spaces for indentation.  Don't mix tabs and spaces.
*   **Line Length:** Keep lines under 120 characters.
*   **Naming Conventions:** Adhere to established naming conventions (e.g., camelCase for functions, PascalCase for classes).
*   **Comments:**  Provide concise, helpful comments where necessary, but avoid unnecessary comments. Focus on explaining *why* the code is doing something, not *what* it's doing.

**6. Testing & Coverage**

*   **Unit Tests:**  All code must have at least 80% code coverage through unit tests.
*   **Test-Driven Development:**  Write tests before writing code.
*   **Test Data:**  Use realistic, well-defined test data. Avoid fake/mock implementations.  Mocking should be used *only* for testing, not as part of the core logic.
*   **Test Structure:** Organize tests into logical groups and suites.

**7. File Limits**

*   **Maximum Code Length:** Each file must have a maximum of 180 lines of code.  Extensions are allowed, but must be justifiable.
*   **File Structure:**  Organize code into logical modules and components, with clear separation of concerns.

**8. Development Practices**

*   **Code Reviews:**  All code must be reviewed by at least one other developer.
*   **Version Control:**  Use Git for version control. Commit frequently with meaningful messages.
*   **Documentation:**  Keep documentation up-to-date.
*   **Collaboration:**  Foster a collaborative environment where developers can share knowledge and best practices.

**9.  Specific Considerations (AGENTS.md - General)**

*   All components, classes, and functions must be accessible via standard Python libraries.
*   Error handling must be implemented consistently.
*   Logging must be implemented for all critical operations.
*   Data structures and algorithms must be well-documented.
```