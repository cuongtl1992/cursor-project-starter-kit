# Cursor AI Workflow Project Starter Kit

This repository contains a structured workflow for developing projects with Cursor AI. It includes templates for documentation, project management, and development guidelines to streamline the AI-assisted development process.

## Project Structure

```
cursor-project-starter-kit/
├── README.md                 # Project overview and documentation
├── docs/                     # Documentation directory
│   ├── prd.md                # Product requirements document
│   ├── tech_spec.md          # Technical specification template
│   ├── prompt_plan.md        # AI prompt planning document
│   ├── todo.md               # Project todo list
│   ├── cursor_rules.md       # Guide for Cursor AI rules
│   └── specs/                # Detailed specifications
│       └── feature_spec.md   # Feature specification template
├── src/                      # Source code
├── tests/                    # Test files
├── .cursor/                  # Cursor AI configuration
│   ├── settings.json         # Cursor AI settings
│   └── rules/                # Cursor AI project rules (Markdown format)
│       ├── general.mdc       # General development rules
|       ├── docs.mdc          # Documentation rules for maintaining consistency and quality
|       ├── project_plan.mdc  # Rules for project planning and task management
|       ├── review_code.mdc   # Guidelines for code review and feedback
|       ├── review_doc.mdc    # Guidelines for documentation review and feedback
├── .gitignore                # Git ignore rules
├── .cursorignore             # Cursor AI ignore rules
```

## Getting Started

1. Clone this repository
2. Install [Cursor AI](https://cursor.com/) if you haven't already
3. Open the project in Cursor AI
4. Review the documentation in the `docs/` directory
5. Start developing with AI assistance!

## Documentation Templates

The `docs/` directory contains templates for various project documents:

- **prd.md**: Product requirements document template
- **tech_spec.md**: Template for technical specifications
- **prompt_plan.md**: Guide for planning effective AI prompts
- **todo.md**: Project task tracking
- **status.md**: Document tracking the current status of the project
- **cursor_rules.md**: Guide for creating and managing Cursor AI rules
- **specs/feature_*.md**: Detailed feature specification templates, including technical details, user experience, and implementation plans

## Cursor AI Rules

The `.cursor/rules` directory contains organized rules in Markdown format for different aspects of development. The following files are included:

- **general.mdc**: General development rules for all files
- **docs.mdc**: Documentation rules for maintaining consistency and quality
- **project_plan.mdc**: Rules for project planning and task management
- **review_code.mdc**: Guidelines for code review and feedback
- **review_doc.mdc**: Guidelines for documentation review and feedback

Using Markdown format for rules makes them more readable and easier to edit than JSON.

## Configuration Files

- **.gitignore**: Standard Git ignore rules for various development environments
- **.cursorignore**: Rules for Cursor AI to ignore certain files and directories when indexing

## Cursor AI Workflow Best Practices

1. **Follow the AI Coding Flow**: Use `docs/prompts/ai-coding-flow.md` to guide your development process
	* **Step 1: Idea Honeing**: Refine your idea through iterative questioning
	* **Step 2: Wrap it to Tech Spec**: Compile findings into a comprehensive technical specification
	* **Step 3: Planning**: Break down the project into detailed, step-by-step plans for implementation
	* **Step 4: Build Todo**: Create a todo list to track progress and manage tasks
2. **Maintain project status**: Keep `status.md` updated to help with context management
3. **Track tasks**: Keep track of tasks in `todo.md`
4. **Document technical decisions**: Use `tech_spec.md` for architectural decisions

## Context Management

When working on large projects, Cursor AI may hit context limits. Use the `@{docs/status.md}` reference to quickly restore context:

```
You: Let's continue working on the authentication service  
Cursor: *Has no idea about previous implementation details because of context limit*  
You: @{docs/status.md} Let's continue with JWT implementation  
Cursor: *Now understands current state and can continue appropriately*
```

## Contributing

Please follow the guidelines in the documentation when contributing to this project.

## License

MIT
