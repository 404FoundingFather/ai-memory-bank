# Memory Bank - Project Documentation Templates

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-April%2010%2C%202025-brightgreen.svg)](https://github.com/yourusername/memory-bank)

A comprehensive, framework-agnostic project documentation template system that creates a structured "memory bank" for your projects. Designed to improve collaboration between developers and AI assistants by maintaining a persistent knowledge base.


## 📋 Overview

Memory Bank provides a structured approach to documenting all aspects of a project, ensuring that information is accessible, maintainable, and useful for both human developers and AI assistants. When used properly, these files create a persistent knowledge base that improves collaboration and maintains continuity across development sessions.

## Usage Pattern

1. Create a fresh context with the AI Assistant

2. prompt:  `review all files in the memory-bank directory. Let's work on the kanban task: [copy text from 07-kanban.md]`

3. After task is complete, reviewed and tested, to the AI Assistant:  `update the appropriate memory-bank files for the work just completed`.  This **must** be part of your routine.  The AI Assistants (at least in 20205) won't consistently update the memory-bank automatically.  Giving the Assistant this direct prompt yields in high quality memory-bank updates.

4. git add / commit / push

5. **Important**: Start a fresh context for the next task.  This prevents bloated contexts and reduces the tendancy for the AI Assistant to drift and hallunicate.

Code review what is generated.  Always.


## 🚀 Getting Started

### Installation

```bash
# Clone this repository
git clone https://github.com/404FoundingFather/ai-memory-bank.git

# Copy the templates to your project
cp -r ai-memory-bank/memory-bank/ your-project/
```

### File Structure

```
memory-bank/
├── 00-index.md                   # Navigation and overview
├── 01-product-vision.md          # Project goals and scope
├── 02-techContext.md             # Technologies and dependencies
├── 03-systemPatterns.md          # Architectural patterns
├── 04-database.md                # Data models and relationships
├── 05-uidesign.md                # UI components and design system
├── 06-developmentPlan.md         # Development roadmap
├── 07-kanban.md                  # Current tasks and priorities
├── 08-changelog.md               # Version history
├── 09-environment.md             # Setup and deployment
├── 10-ai-interaction-guidelines.md # AI assistant guidelines
├── 11-code-snippets.md           # Useful code patterns
├── 12-decisions.md               # Decision records
└── 13-quick-reference.md         # Commands and resources
```

### How to Use These Templates

1. Copy the entire `memory-bank` directory to your new project's root
2. Systematically go through each file (starting with 00-index.md) and replace the placeholder content with information specific to your project
3. Update the "Last Updated" date whenever you make significant changes to a file

## 🤖 Using AI Assistants to Populate Memory-Bank Files

AI coding assistants can help you efficiently populate your memory-bank files. Below are example prompts to help customize these templates for your specific project.

### General Project Setup

```
"I've set up a new [project type] using [technologies]. Can you help me populate my memory-bank files with relevant information based on the project structure and technologies? I already have the templates in place in the memory-bank directory."
```

### Technology-Specific Examples

#### For a Next.js Project

```
"I'm working on a Next.js project with a PostgreSQL database and Prisma ORM. Can you help me fill out the following memory-bank files based on this tech stack:
1. 02-techContext.md - Include Next.js, React, PostgreSQL, and Prisma details
2. 03-systemPatterns.md - Include common Next.js patterns and architecture
3. 04-database.md - Include Prisma model definitions and relationships
4. 09-environment.md - Include typical Next.js environment setup"
```

#### For a Django Project

```
"I've created a Django project with a PostgreSQL database. Please help me populate these memory-bank files:
1. 02-techContext.md - Include Django, Python, and PostgreSQL details
2. 03-systemPatterns.md - Include Django MVT architecture patterns
3. 04-database.md - Help me document my Django models
4. 13-quick-reference.md - Include common Django management commands"
```

#### For a Mobile App Project

```
"I'm developing a React Native mobile app with Firebase backend. Please help me populate these memory-bank files:
1. 02-techContext.md - Include React Native and Firebase details
2. 03-systemPatterns.md - Include mobile app architecture patterns
3. 09-environment.md - Include mobile development environment setup
4. 10-ai-interaction-guidelines.md - Help me set guidelines for mobile app development with AI"
```

### File-Specific Prompts

#### For Product Vision (01-product-vision.md)

```
"Based on this project idea: [brief project description], help me populate the product-vision.md file with a compelling problem statement, solution approach, and key features."
```

#### For Technical Context (02-techContext.md)

```
"My project uses these technologies: [list technologies and versions]. Help me populate the techContext.md file with relevant information, including setup instructions and resource links."
```

#### For Database Documentation (04-database.md)

```
"Based on these database models [describe models or share code], help me populate the database.md file with proper documentation of fields, relationships, and query patterns."
```

#### For UI Design (05-uidesign.md)

```
"My application has these main screens: [list key screens]. Help me document the UI components and design principles in the uidesign.md file."
```

#### For Code Snippets (11-code-snippets.md)

```
"Based on my project's code, help me identify and document common patterns and helper functions for the code-snippets.md file."
```

### Using AI to Update Memory-Bank Files

```
"I've made significant changes to my project, including [describe changes]. Help me update the following memory-bank files to reflect these changes: [list files]."
```

### Analyzing Existing Project for Memory-Bank Population

```
"I have an existing [project type] with [technologies]. I've just added memory-bank templates. Can you analyze my project structure and help me populate these templates based on what you can infer about my project?"
```

## 🛠️ Customization Guidelines for Each File

### 00-index.md
- Update file references if you rename or add files
- Modify the reading order if needed for your project's context

### 01-product-vision.md
- Define your specific problem statement
- Outline your solution approach
- Set clear user experience goals
- Specify key features and target audience

### 02-techContext.md
- List all technologies, frameworks, and libraries used
- Document development environment requirements
- Include links to relevant documentation

### 03-systemPatterns.md
- Describe your application's architecture
- Document design patterns and principles
- Outline code organization strategy

### 04-database.md
- Detail your data model
- Include entity relationship diagrams if applicable
- Document database technology choices

### 05-uidesign.md
- Define UI/UX principles for your project
- Include wireframes or mockup references
- Document component structure

### 06-developmentPlan.md
- Create a roadmap with milestones
- Define the development workflow
- Prioritize features and tasks

### 07-kanban.md
- Set up your kanban board structure
- Define priorities and categories
- Keep this updated as tasks move through your workflow

### 08-changelog.md
- Document the version history format
- Set guidelines for what constitutes a changelog entry

### 09-environment.md
- Document setup procedures
- Include configuration details
- Document deployment processes

### 10-ai-interaction-guidelines.md
- Define how AI tools should interact with the project
- Set code style preferences
- Document communication preferences

### 11-code-snippets.md
- Create templates for common patterns
- Document reusable code snippets
- Include usage examples

### 12-decisions.md
- Format for recording architectural decisions
- Include decision-making criteria

### 13-quick-reference.md
- Create a glossary of project-specific terms
- Document frequently used commands
- List key file locations

## 📊 Best Practices

1. **Consistency**: Maintain consistent formatting across all files
2. **Currency**: Keep information up-to-date, especially as the project evolves
3. **Clarity**: Write clear, concise content that both humans and AI can easily understand
4. **Completeness**: Fill in all sections, even if minimally at first
5. **Continuity**: Reference between files when appropriate to create a cohesive documentation system

## 👥 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-idea`)
3. Commit your changes (`git commit -am 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-idea`)
5. Create a new Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.