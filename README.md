# 💻 AI Prompts for Developers

A curated collection of AI prompts specifically designed for software developers and engineers. Use these prompts with ChatGPT, GitHub Copilot, and other AI tools to boost your coding productivity.

## 📚 Categories

- **[Code Generation](#code-generation)** - Generate boilerplate, functions, and components
- **[Debugging & Testing](#debugging--testing)** - Debug code, write tests, fix issues
- **[Code Review & Refactoring](#code-review--refactoring)** - Review code, improve quality, optimize
- **[Documentation](#documentation)** - Generate docs, comments, READMEs
- **[Architecture & Design](#architecture--design)** - System design, patterns, architecture
- **[Learning & Explanation](#learning--explanation)** - Learn concepts, understand code
- **[Performance & Optimization](#performance--optimization)** - Optimize code, improve performance
- **[DevOps & Deployment](#devops--deployment)** - CI/CD, Docker, deployment configurations

---

## 🔧 Code Generation

### Function Generator
```
Generate a [language] function that [describes what it should do].
Requirements:
- Input: [describe parameters]
- Output: [describe return value]
- Edge cases: [list any edge cases to handle]
Include error handling and comments.
```

### Component Generator
```
Create a [framework] component called [component_name] that [describes functionality].
The component should:
- Accept props: [list props and types]
- Render: [describe UI/output]
- Handle: [describe interactions/events]
```

### API Endpoint Generator
```
Generate a [framework/language] API endpoint for [purpose].
- HTTP Method: [GET/POST/PUT/DELETE]
- Route: [/path/to/endpoint]
- Request body: [describe expected input]
- Response: [describe expected output]
- Authentication: [describe auth requirements]
Include error handling and validation.
```

### SQL Query Generator
```
Write a SQL query to [describe what you need].
Database: [MySQL/PostgreSQL/MongoDB/etc]
Tables: [list relevant tables]
Expected output: [describe the result]
```

### Boilerplate Generator
```
Generate boilerplate code for a [type of project] in [language/framework].
Include:
- Project structure
- Configuration files
- Basic setup
- Package dependencies
```

---

## 🐛 Debugging & Testing

### Code Debugger
```
I'm getting this error when running the following code:
Error: [paste the error message]
Code:
[paste your code]

What's wrong and how do I fix it?
```

### Unit Test Generator
```
Write unit tests for this [language] function using [testing framework]:
[paste your function]
Include tests for:
- Happy path
- Edge cases
- Error conditions
```

### Integration Test Generator
```
Generate integration tests for [component/endpoint description].
Testing framework: [Jest/Pytest/etc]
Mock: [describe what needs mocking]
Expected behavior: [describe what should happen]
```

### Performance Debugger
```
This code is running slowly. Help me optimize it:
[paste your code]
Current performance: [describe the issue]
Constraints: [any limitations or requirements]
Suggest optimizations with explanations.
```

---

## 📋 Code Review & Refactoring

### Code Review Assistant
```
Please review this [language] code for:
- Code style and best practices
- Performance issues
- Security vulnerabilities
- Maintainability concerns

[paste your code]

Provide specific suggestions for improvement.
```

### Refactoring Assistant
```
Help me refactor this [language] code to be more [readable/maintainable/performant]:
[paste your code]
Current issues: [describe what you want to improve]
Constraints: [any limitations]
```

### TypeScript Converter
```
Convert this [language] code to TypeScript with proper types:
[paste your code]
Include:
- Proper type annotations
- Interface definitions
- Type safety improvements
```

### Legacy Code Modernizer
```
Modernize this [language] code written in [year/style]:
[paste your code]
Update to use:
- Modern syntax and features
- Current best practices
- Current libraries/frameworks
```

---

## 📝 Documentation

### README Generator
```
Generate a professional README.md for my [project type] project:
- Project name: [name]
- Description: [what it does]
- Key features: [list features]
- Tech stack: [technologies used]
- Installation: [brief setup steps]
Include sections for usage, contributing, and license.
```

### API Documentation
```
Generate documentation for this API endpoint in [format/style]:
Endpoint: [describe endpoint]
Method: [HTTP method]
Path: [/path]
Request: [describe request]
Response: [describe response]
Include examples and error codes.
```

### Code Comments Generator
```
Add clear, concise comments to this code to explain the logic:
Language: [programming language]
[paste your code]
Focus on the "why" not the "what".
```

### Docstring Generator
```
Generate docstrings for this [language] function:
[paste your code]
Format: [Google/NumPy/JSDoc style]
Include description, parameters, return value, and examples.
```

---

## 🏗️ Architecture & Design

### System Design Prompt
```
Design a system for [describe the problem/feature].
Requirements:
- Scale: [number of users/requests]
- Performance: [latency/throughput requirements]
- Availability: [uptime requirements]
- Data: [data size and type]

Provide:
- Architecture diagram (text-based)
- Component descriptions
- Technology recommendations
- Scalability considerations
```

### Design Pattern Advisor
```
I need to implement [feature/problem]. 
What design pattern would be best?
Context: [describe your situation]
Constraints: [any limitations]
Provide examples of the pattern in [language].
```

### Database Schema Design
```
Design a database schema for [application/feature].
Requirements:
- Entities: [list what you need to store]
- Relationships: [describe relationships]
- Scale: [expected data volume]
- Queries: [common queries needed]

Provide:
- ER diagram (text format)
- Table definitions
- Indexes needed
```

### Microservices Architect
```
Break down this [monolithic application/feature] into microservices.
Current system: [describe existing system]
Goal: [describe desired outcome]
Constraints: [team size, technology, budget]
Provide service breakdown and communication patterns.
```

---

## 🎓 Learning & Explanation

### Concept Explainer
```
Explain [concept/technology] to me like I'm a [junior/mid-level/senior] developer.
Context: [what I'm trying to do]
Provide:
- Simple explanation
- Real-world example
- Code example in [language]
- Common mistakes to avoid
```

### Technology Deep Dive
```
Explain how [technology/library/framework] works under the hood.
Focus on: [specific aspect]
Level: [beginner/intermediate/advanced]
Include:
- How it works internally
- When to use it
- Performance implications
- Alternatives
```

### Code Walkthrough
```
Walk me through this code step-by-step and explain what's happening:
[paste your code]
Language: [programming language]
I'm a [skill level] developer.
Explain each section and what the overall code does.
```

### Interview Question Helper
```
Help me prepare for a [company/role] interview.
Topic: [data structures/system design/etc]
Difficulty: [easy/medium/hard]
Provide:
- Question explanation
- Approach/solution strategy
- Code solution in [language]
- Follow-up questions
```

---

## ⚡ Performance & Optimization

### Performance Analyzer
```
Analyze the performance of this code and suggest optimizations:
Language: [programming language]
Current bottleneck: [describe the issue]
[paste your code]

Provide:
- Root cause analysis
- Optimization suggestions
- Before/after comparison
- Complexity analysis (Big O)
```

### Database Query Optimizer
```
Optimize this [database type] query:
[paste your query]
Current issue: [slow/inefficient]
Tables and volume: [describe your data]

Suggest optimizations including:
- Query rewrites
- Index recommendations
- Query plan improvements
```

### Memory Leak Detector
```
I suspect there's a memory leak in this [language] code:
[paste your code]
Symptoms: [describe the issue]
Framework/runtime: [what you're using]

Help me identify and fix the memory leak.
```

---

## 🚀 DevOps & Deployment

### Docker Configuration
```
Generate a Dockerfile for my [language/framework] application:
- Application: [describe app]
- Dependencies: [list key dependencies]
- Runtime: [Node/Python/Java/etc]
- Port: [exposed port]
Include production-ready best practices.
```

### GitHub Actions Workflow
```
Create a GitHub Actions workflow for:
- Trigger: [when should it run]
- Actions: [what should it do - test/build/deploy]
- Language: [programming language]
- Services: [databases/services needed]
Include:
- Linting
- Testing
- Building
```

### Environment Configuration
```
Generate environment configuration files for [application type]:
- Development setup
- Staging setup
- Production setup
Include:
- Environment variables
- Database configs
- API endpoints
- Security considerations
```

### Deployment Strategy
```
Design a deployment strategy for [application type]:
- Current setup: [describe current state]
- Goals: [zero-downtime/fast rollback/etc]
- Infrastructure: [AWS/GCP/Azure/Docker]
- Team size: [describe your team]

Provide:
- Step-by-step deployment process
- Rollback strategy
- Monitoring points
```

---

## 🚀 Getting Started

1. **Choose a prompt** from the categories above
2. **Copy and customize** it for your specific use case
3. **Use with AI tools**: ChatGPT, GitHub Copilot, Claude, etc.
4. **Share with your team** and learn together

## 💡 Tips for Better Results

- **Be specific** - Include actual code, error messages, or requirements
- **Provide context** - Describe your tech stack, constraints, and goals
- **Ask follow-ups** - Refine prompts based on initial responses
- **Iterate** - Better prompts = better AI assistance
- **Copy code carefully** - Always review and test AI-generated code

## 📚 Learn More

Expand your skills with structured courses and video tutorials:

- **YouTube Channel**: [youtube.com/channel/UCqgi3TTpWwO22hIxzPOLhWw](https://youtube.com/channel/UCqgi3TTpWwO22hIxzPOLhWw)
  - Software development tutorials
  - AI/Coding tips and tricks
  - Project walkthroughs

- **Udemy Courses**: [udemy.com/user/emmanuel-tweneboah-2](https://udemy.com/user/emmanuel-tweneboah-2)
  - Complete developer courses
  - In-depth learning paths
  - Hands-on projects

## 📝 Contributing

Have a great prompt? Found an improvement? Contribute to this collection and help other developers! 

---

**Happy coding! 🚀**

*Last updated: 2026-08-30*
