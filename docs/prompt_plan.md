# AI Prompt Planning Document

## Overview

This document provides guidelines and strategies for creating effective prompts when working with Cursor AI. Well-crafted prompts lead to better AI-generated code, documentation, and solutions.

## Prompt Structure Guidelines

### Basic Prompt Structure

```
[Context] - Provide relevant background information
[Task] - Clearly state what you want the AI to do
[Format] - Specify the desired output format
[Constraints] - Mention any limitations or requirements
[Examples] - Provide examples if helpful
```

### Example:

```
[Context] I'm building a React component for a todo list application.
[Task] Create a TodoItem component that displays a task with a checkbox for completion status.
[Format] Use TypeScript and functional components with hooks.
[Constraints] The component should be accessible and follow best practices.
[Examples] Similar to how Material UI implements list items.
```

## Prompt Types for Different Tasks

### Code Generation Prompts

- Be specific about language, framework, and patterns
- Include expected inputs and outputs
- Mention error handling requirements
- Specify performance considerations

### Debugging Prompts

- Describe the expected behavior
- Explain the actual behavior
- Include relevant error messages
- Provide context about the surrounding code

### Refactoring Prompts

- Explain the current code structure
- Describe the desired improvements
- Mention any patterns or principles to follow
- Specify what should remain unchanged

### Documentation Prompts

- Specify the documentation style (JSDoc, README, etc.)
- Mention the target audience
- Include the level of detail needed
- Request examples if applicable

## Prompt Refinement Strategies

### Iterative Prompting

1. Start with a basic prompt
2. Review the AI's response
3. Refine your prompt based on the response
4. Repeat until satisfactory

### Chunking Complex Tasks

Break down complex tasks into smaller, manageable prompts:

1. Architecture design
2. Component implementation
3. Testing strategy
4. Documentation

## Common Pitfalls to Avoid

- **Vague requests**: "Make this better" vs. "Optimize this function for readability"
- **Overloading**: Asking for too many things in one prompt
- **Lack of context**: Not providing enough background information
- **Inconsistent requirements**: Contradicting yourself within the prompt

## Prompt Templates

### Feature Implementation Template

```
I need to implement [feature name] in [language/framework].

Context:
- [Describe the current system]
- [Explain relevant components]

Requirements:
- [List specific requirements]

Technical constraints:
- [Mention any technical limitations]

Please provide:
- [Code structure]
- [Implementation details]
- [Testing approach]
```

### Bug Fix Template

```
I'm encountering a bug in my [language/framework] code.

Expected behavior:
- [Describe what should happen]

Actual behavior:
- [Describe what is happening]

Error messages:
- [Include any error messages]

Relevant code:
- [Include the problematic code]

What I've tried:
- [List debugging attempts]

Please help me identify and fix the issue.
```

## Measuring Prompt Effectiveness

Track the following metrics to improve your prompting skills:

- Number of prompt iterations needed
- Accuracy of AI-generated code
- Time saved compared to manual implementation
- Learning value from AI explanations

## Project-Specific Prompt Guidelines

[Add project-specific guidelines here] 