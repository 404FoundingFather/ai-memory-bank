# AI Interaction Guidelines

**Last Updated:** April 10, 2025

This document outlines guidelines for working with AI assistants on this project, including preferences for communication style, code formatting, and areas where AI assistance is most valuable.

## General Communication Preferences

### Response Style
- [Preferred level of detail (concise vs. comprehensive)]
- [Technical depth preference]
- [Communication formality preference]
- [Include/exclude explanations with code]

### Context Sharing
- [Guidelines for how to share project context with AI]
- [What information is most helpful to include in prompts]
- [Any project-specific context that should always be mentioned]

## Code Style Preferences

### Clean Code Requirements

All code generated or suggested by AI assistants MUST adhere to Clean Code principles:

1. **Readability First**: Prioritize human readability over cleverness or conciseness
   - Use clear variable and function names
   - Maintain consistent formatting
   - Avoid excessive nesting

2. **Simplicity**: Write simple, straightforward code
   - Solve the problem directly
   - Avoid premature optimization
   - Prefer explicit over implicit approaches

3. **Self-Documenting Code**: Code should primarily explain itself
   - Choose descriptive names over comments
   - Use comments only for "why" not "what"
   - Structure code logically to tell a story

4. **DRY (Don't Repeat Yourself)**: Avoid duplication
   - Extract repeated code into reusable functions
   - Maintain single sources of truth
   - Create abstractions only when they reduce duplication

5. **SOLID Principles**:
   - Single Responsibility: Each component does one thing well
   - Open/Closed: Open for extension, closed for modification
   - Liskov Substitution: Subtypes must be substitutable for base types
   - Interface Segregation: Many specific interfaces are better than one general interface
   - Dependency Inversion: Depend on abstractions, not implementations

6. **Small Units**: Keep functions and classes small and focused
   - Functions should do one thing
   - Classes should have a single responsibility
   - Files should be organized around a cohesive concept

7. **Meaningful Names**: Use intention-revealing names
   - Variables tell what they contain
   - Functions tell what they do
   - Classes tell what they represent

8. **Minimal Dependencies**: Limit coupling between components
   - Create clear boundaries between modules
   - Minimize shared state
   - Use dependency injection where appropriate

9. **Error Handling**: Handle errors meaningfully
   - Be specific about error types
   - Provide useful error messages
   - Fail fast and visibly

10. **Testable Code**: Generate code with testing in mind
    - Avoid global state
    - Make side effects explicit
    - Design for easy mocking/stubbing

### General Formatting
- [Indentation preference (tabs/spaces)]
- [Line length limits]
- [Casing conventions (camelCase, snake_case, etc.)]
- [File/folder naming conventions]

### Language-Specific Standards
- **[Language 1]**: [Specific style preferences]
- **[Language 2]**: [Specific style preferences]
- **[Language 3]**: [Specific style preferences]

### Documentation Standards
- [Comment style preference]
- [Documentation format (JSDoc, docstrings, etc.)]
- [Required documentation elements]

## AI Assistance Guidelines

### Recommended Use Cases
- [Areas where AI assistance is most valuable in this project]
- [Types of tasks where AI should be consulted]
- [Complex areas where AI can provide insights]

### Limited Use Cases
- [Areas where human judgment should prevail]
- [Types of code that should be human-written/reviewed]
- [Security-sensitive areas]

### Prompt Engineering Tips
- [Effective prompt structures for this project]
- [Example prompts that work well]
- [How to ask for specific types of assistance]

## Review Process

### AI-Generated Code Review
- [Process for reviewing AI-generated code]
- [Specific aspects to verify]
- [Common issues to watch for]

### Feedback Loop
- [How to provide feedback on AI responses]
- [Tracking AI assistance effectiveness]
- [Continuous improvement process]

## Project-Specific Guidelines

### Domain Knowledge
- [Key domain concepts the AI should understand]
- [Terminology specific to this project]
- [Industry standards or regulations to be aware of]

### Technical Context
- [Architecture considerations for AI recommendations]
- [Important technical constraints]
- [Performance considerations]

### Tools Integration
- [How AI should interact with project tools]
- [CI/CD considerations]
- [Testing framework awareness]

## Memory Bank Updates

### Recommended Update Frequency
- [How often AI interaction guidelines should be updated]
- [Triggers for updating these guidelines]

### Documentation of AI Contributions
- [How to attribute AI-generated content]
- [Where to document significant AI contributions]
- [Tracking impact of AI assistance]

## Best Practices

- Always adhere to Clean Code principles in all generated code
- When suggesting code refactoring, explain how it improves adherence to Clean Code principles
- Prioritize readability and maintainability over clever or highly optimized solutions
- Balance Clean Code standards with project-specific requirements
- When in doubt about a code pattern, prefer the simpler, more readable approach
- [Project-specific best practices for AI collaboration]
- [Dos and don'ts for effective AI assistance]
- [Balancing AI assistance with developer growth]