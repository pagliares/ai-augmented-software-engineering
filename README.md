# AI-Augmented Software Engineering

**Instructor:** Rodrigo Martins Pagliares  
**Institution:** Universidade Federal de Alfenas (UNIFAL-MG), Brazil  
**Course:** Computer Science

## Course Description

This repository contains the learning materials and resources for the **AI-Augmented Software Engineering** course.

The course explores how Artificial Intelligence (AI) can augment software engineering activities throughout the **Software Development Life Cycle (SDLC)**. Students will study and apply Generative AI, Large Language Models (LLMs), AI coding assistants, agentic systems, Retrieval-Augmented Generation (RAG), local AI models, and AI-powered development environments.

The course combines theoretical foundations with hands-on software engineering activities. Students will use AI to support requirements engineering, software design, implementation, testing, documentation, maintenance, project workflows, and software delivery. These practices will be explored in both **greenfield development**, where new systems are built from scratch, and **brownfield development**, where existing systems are understood, maintained, and evolved.

Particular attention will be given to the **evaluation of AI-generated software artifacts**. Students will learn that AI-generated outputs must not be accepted automatically. Instead, they must be reviewed, tested, corrected, and justified based on software requirements, quality criteria, architectural constraints, and professional judgment.

The course also addresses the limitations and risks of AI-augmented development, including hallucinations, security vulnerabilities, privacy concerns, intellectual property issues, excessive automation, loss of developer understanding, and overreliance on AI-generated outputs. **Human accountability, responsible AI use, and appropriate human oversight and approval** are therefore treated as essential principles of AI-augmented software engineering.

By the end of the course, students will be prepared not only to use modern AI development tools but also to select appropriate techniques, critically evaluate their results, and responsibly integrate them into systematic software engineering processes.

## Target Audience

This course is intended for **undergraduate Computer Science students** who have completed introductory courses in programming and software engineering. It is particularly suitable for students who are comfortable reading, writing, testing, and modifying software systems.

**No prior experience with Artificial Intelligence (AI), Machine Learning (ML), Large Language Models (LLMs), or AI coding assistants is required.** The necessary conceptual foundations and practical techniques will be introduced progressively throughout the course.

## Prerequisites

### Required Prerequisites

Students should have:

- Foundational knowledge of **object-oriented programming**.
- Foundational knowledge of **software engineering principles** and the **Software Development Life Cycle (SDLC)**.
- Basic experience with **Git** and version control workflows.
- The ability to **build, run, debug, and modify** software written in at least one programming language.

### Recommended Prior Knowledge

Familiarity with the following topics is helpful but not required:

- Unit testing and automated software testing.
- Web applications and client-server architectures.
- REST APIs and data formats such as JSON.
- Command-line tools and dependency management.
- Relational databases and basic data persistence.

### Technical Environment and Access Requirements

Students need regular access to a computer capable of supporting software development activities, including source-code editing, dependency management, automated testing, version control, and application execution.

Practical activities may require:

- A modern web browser.
- A source-code editor or integrated development environment (IDE).
- Git and access to a Git-compatible repository hosting platform.
- Command-line tools.
- Programming language runtimes, build tools, and dependencies required by the selected projects.
- Access to at least one AI assistant or Large Language Model (LLM) interface.
- Additional tools, libraries, containers, APIs, or local AI model environments introduced in specific modules.

Detailed installation and configuration instructions will be provided for each activity. **Students are expected to maintain a functional development environment and verify the required installations before beginning each practical activity.**

### Tool Availability and Alternatives

The course does not require students to purchase commercial AI subscriptions. Whenever feasible, practical activities will support free tiers, educational access, institutionally provided services, open-weight models, or local alternatives.

When an activity demonstrates a specific commercial product, students may use an equivalent tool, subject to instructor approval, provided that it satisfies the learning objectives and activity requirements. The instructor may update the selected tools between course offerings based on technological developments, licensing conditions, availability, and institutional resources.

### Local Model Requirements

A dedicated graphics processing unit (GPU) is not a general prerequisite for the course. Activities involving local AI models will use model sizes and configurations appropriate to the available hardware.

If a student's computer cannot run a selected local model adequately, the instructor may offer an alternative model, shared laboratory environment, remote service, demonstration-based activity, or equivalent analysis task.

### Accounts, Credentials, and Costs

Students are responsible for protecting their accounts, access tokens, API keys, and repository credentials. **Secrets must never be committed to version-control repositories or exposed in submitted prompts, source code, screenshots, logs, or reports.**

Activities involving potential usage-based costs will specify expected limits and available alternatives in advance. Students will not be required to incur unannounced expenses to complete course activities.

### Software and Project Compatibility

Student-selected projects must be compatible with the available development environment and feasible within the course workload.

The instructor may restrict programming languages, frameworks, repository sizes, external dependencies, or deployment environments when necessary to ensure that projects remain technically feasible, adequately supported, and assessable.

## Running Examples

Throughout the course, two instructor-led examples will demonstrate the practical application of AI-augmented software engineering techniques:

- **BlueVelvet Music Store (Greenfield):** Development of selected, prioritized features of a new e-commerce application from scratch.
- **Sparkling Waters Hostel (Brownfield):** Analysis, maintenance, and evolution of selected features of an existing hostel management and reservation system, including guest management, authentication, and role-based authorization.

These examples will be revisited across multiple course modules to illustrate how AI can support different activities throughout the Software Development Life Cycle (SDLC). Students will apply similar techniques to their own greenfield and brownfield projects, which may involve different application domains and technologies.

### Greenfield Development: BlueVelvet Music Store

**BlueVelvet Music Store** is a new e-commerce application whose selected, prioritized features will be developed from scratch. It will demonstrate how AI can support requirements elicitation and refinement, software architecture and interface design, implementation, automated testing, documentation, deployment, and software evolution.

Because the application starts without an existing codebase, this example will illustrate how developers can use AI to explore alternatives, generate initial software artifacts, evaluate proposed solutions, and progressively transform requirements into a working software product.

### Brownfield Development: Sparkling Waters Hostel

**Sparkling Waters Hostel** is an existing hostel management and reservation system developed using Spring Boot and front-end technologies, including HTML, CSS, JavaScript, and Bootstrap. The system includes basic guest management, authentication, and role-based authorization functionality, providing a foundation for software maintenance and evolution activities.

This example will demonstrate how AI can support program comprehension, requirements and architecture recovery, codebase exploration, debugging, refactoring, test generation, documentation improvement, and feature enhancement. Potential evolution activities include improving the existing software design and implementing or enhancing guest reservation management.

The brownfield example will also emphasize that **AI-generated recommendations and changes must be validated** against the existing codebase, architecture, requirements, and tests before being accepted.

The running examples may be updated in future course offerings while preserving their complementary greenfield and brownfield perspectives.

## Learning Objectives

By the end of this course, students will be able to:

1. **Explain** the foundations, capabilities, and limitations of Generative AI and Large Language Models (LLMs).
2. **Design and evaluate** prompts, structured outputs, and reusable AI interaction patterns for software engineering tasks.
3. **Apply** AI coding assistants to support software implementation, debugging, refactoring, testing, and documentation.
4. **Use** AI agents, tools, and agentic workflows while incorporating appropriate human oversight, feedback, and approval mechanisms.
5. **Design and develop** software applications that integrate AI capabilities through LLM APIs, Retrieval-Augmented Generation (RAG), and local AI models.
6. **Critically evaluate** AI-generated software artifacts, including requirements, designs, source code, tests, and documentation.
7. **Assess** software quality, security, privacy, ethical, intellectual property, and governance implications of AI-augmented software engineering.
8. **Apply** AI-augmented software engineering practices to greenfield development and brownfield software maintenance and evolution.
9. **Document** AI tool usage, generated outputs, verification evidence, and human decisions concerning their review, correction, and acceptance.
10. **Develop and evaluate** software increments in greenfield and brownfield projects using responsible AI-augmented software engineering practices.
