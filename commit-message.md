# Commit Message Guidelines

## Format
A commit message should have the following format:
```
<Type>(<Scope>): <Message>

[...]
```
- **Type:** Describes the purpose of the commit.
- **Scope:** Specifies the module, component or area of the project affected by the commit (required if possible).
- **Message:** Provides a concise and clear description of the changes introduced by the commit.

## Commit Types
Choose the appropriate type from the following list:
- **feat:** A new feature.
- **fix:** A bug fix.
- **docs:** Documentation changes.
- **style:** Code style changes (formatting, indentation).
- **refactor:** Code refactoring without changing its behavior.
- **test:** Adding or modifying tests.
- **chore:** Routine tasks, maintenance or tooling changes.

## Additional Tips
- Keep messages clear, concise and in the present tense.
- Use the imperative mood for the message.
- Limit the length of the first line to around 72 characters.

## Examples
feat(auth): implement user registration<br>
fix(api): resolve issue with incorrect response format<br>
docs(readme): update installation instructions<br>
style: improve code formatting<br>
refactor(auth): improve user registration performance<br>
test(auth): add unit tests for user authentication<br>
chore(dependencies): update third-party libraries