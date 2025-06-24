# SAR_Report_Prompt

## Overview

This project provides a comprehensive Specification and Requirements (SAR) document for conducting code reviews of web applications and APIs using Large Language Model (LLM) assistance. The SAR defines a standardized process and scoring system for evaluating code quality, security, performance, maintainability, testing, and documentation in modern web development projects.

## Document Purpose

The SAR document outlines requirements and best practices for reviewing both frontend and backend code, including configuration, build, and deployment files. It is designed to help teams identify technical debt, security vulnerabilities, and improvement opportunities using a structured, industry-aligned approach.

## Key Review Areas

- **Code Quality Assessment**: Complexity analysis, code duplication detection, readability, and adherence to style guides.
- **SOLID Principles Evaluation**: Scoring and recommendations for Single Responsibility, Open-Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion principles.
- **Testing Evaluation**: Coverage requirements, test quality, missing test areas, and maintainability.
- **Security Assessment**: OWASP Top 10 compliance, API-specific security, and vulnerability summary.
- **Performance Considerations**: Web and API performance, optimization opportunities, and resource utilization.
- **Documentation Review**: API and component documentation, README completeness, and architecture diagrams.

## Output Specifications

The SAR includes a detailed markdown report template with:
- Executive summary
- Critical issues summary table
- Detailed analysis by category
- Recommendations and next steps (by priority)
- Severity summary and definitions
- Appendices for code examples and metrics

## Usage

1. Review the SAR document in `prompt.txt` for detailed requirements and the report template.
2. Use the SAR as a checklist and scoring guide when performing code reviews of web applications and APIs.
3. Generate reports following the provided markdown structure, ensuring all required sections are completed.

## File Naming Convention
- Format: `CodeReview_[RepoName]_[YYYY-MM-DD].md`
- Include metadata header with generation timestamp and review parameters

## Technologies & Scope

The SAR is designed for modern web technologies, including but not limited to:
- Frontend: React, Vue, Angular
- Backend: Node.js, Express, Django, Flask
- APIs: REST, GraphQL
- Tooling: ESLint, Prettier, OpenAPI/Swagger, CI/CD

## Quality Assurance

Before finalizing a report, verify:
- All required sections are completed
- Severity ratings and recommendations are accurate
- Code examples are correct
- The report follows the markdown template

## License

See repository for license information.