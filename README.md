<a id="top"></a>

# AI-Augmented Software Engineering

**Instructor:** Rodrigo Martins Pagliares  
**Institution:** Universidade Federal de Alfenas (UNIFAL-MG), Brazil  
**Course:** Computer Science

<a id="course-description"></a>

## Course Description

This repository contains the learning materials and resources for the **AI-Augmented Software Engineering** course.

The course explores how Artificial Intelligence (AI) can augment software engineering activities throughout the **Software Development Life Cycle (SDLC)**. Students will study and apply Generative AI, Large Language Models (LLMs), AI coding assistants, agentic systems, Retrieval-Augmented Generation (RAG), local AI models, and AI-powered development environments.

The course combines theoretical foundations with hands-on software engineering activities. Students will use AI to support requirements engineering, software design, implementation, testing, documentation, maintenance, project workflows, and software delivery. These practices will be explored in both **greenfield development**, where new systems are built from scratch, and **brownfield development**, where existing systems are understood, maintained, and evolved.

Particular attention will be given to the **evaluation of AI-generated software artifacts**. Students will learn that AI-generated outputs must not be accepted automatically. Instead, they must be reviewed, tested, corrected, and justified based on software requirements, quality criteria, architectural constraints, and professional judgment.

The course also addresses the limitations and risks of AI-augmented development, including hallucinations, security vulnerabilities, privacy concerns, intellectual property issues, excessive automation, loss of developer understanding, and overreliance on AI-generated outputs. **Human accountability, responsible AI use, and appropriate human oversight and approval** are therefore treated as essential principles of AI-augmented software engineering.

By the end of the course, students will be prepared not only to use modern AI development tools but also to select appropriate techniques, critically evaluate their results, and responsibly integrate them into systematic software engineering processes.


[Back to top](#top)

<a id="course-statistics"></a>

## Course Statistics

- **Units:** 5
- **Modules:** 15
- **Theoretical video lessons:** 78
- **Greenfield and brownfield hands-on demonstrations:** 30
- **Greenfield and brownfield home-exercise introduction videos:** 30
- **Total planned video lessons:** 138
- **Estimated video-based instruction:** 60 hours (4 hours per week; recording estimates subject to revision)
- **Independent home exercises:** 60 hours (4 hours per week)
- **Total student workload:** 120 hours (15 weeks × 8 hours)


[Back to top](#top)

## Table of Contents

- [Course Description](#course-description)
- [Course Statistics](#course-statistics)
- [Course Structure](#course-structure)
  - [Unit 1 — Foundations of AI-Augmented Software Engineering](#unit-1)
    - [Module 1 — Introduction to AI-Augmented Software Engineering](#module-1)
    - [Module 2 — Foundations of Generative AI and Large Language Models](#module-2)
    - [Module 3 — Prompt and Context Engineering for Software Engineers](#module-3)
  - [Unit 2 — AI Across the Software Development Life Cycle](#unit-2)
    - [Module 4 — AI-Assisted Requirements Engineering](#module-4)
    - [Module 5 — AI-Assisted Software Architecture and Design](#module-5)
    - [Module 6 — AI Coding Assistants and AI-Powered Development Environments](#module-6)
    - [Module 7 — Verification and Evaluation of AI-Generated Software Artifacts](#module-7)
    - [Module 8 — AI-Assisted Testing and Quality Assurance](#module-8)
  - [Unit 3 — Human–AI Collaboration and Agentic Development](#unit-3)
    - [Module 9 — Human–AI Collaboration and Developer Control](#module-9)
    - [Module 10 — AI Agents](#module-10)
    - [Module 11 — Agentic Workflows, Human Oversight, and MCP](#module-11)
  - [Unit 4 — Building and Delivering AI-Augmented Applications](#unit-4)
    - [Module 12 — Building AI-Augmented Applications](#module-12)
    - [Module 13 — Local and Open Models](#module-13)
    - [Module 14 — AI-Assisted DevOps, Software Delivery, and Operational Reliability](#module-14)
  - [Unit 5 — Responsible Practice and Future Directions](#unit-5)
    - [Module 15 — Responsible AI-Augmented Software Engineering and Future Trends](#module-15)
- [Learning Objectives](#learning-objectives)
- [Target Audience](#target-audience)
- [Weekly Workload](#weekly-workload)
- [Running Examples](#running-examples)
- [Hands-On Activities](#hands-on-activities)
- [Living Book](#living-book)
- [Course Website](#course-website)

<a id="course-structure"></a>

## Course Structure

The course is organized into **5 units, 15 modules, and 138 planned video lessons**, progressing from foundational concepts to the responsible development, delivery, and evolution of AI-augmented software systems. Each module includes theoretical instruction, two instructor-led hands-on demonstrations (greenfield and brownfield), and two short videos introducing the corresponding home exercises. The estimated weekly workload is **4 hours of video instruction plus 4 hours of independent exercises**. The lesson durations are recording estimates and may be refined during production; longer hands-on lessons may be split into shorter recordings.

<a id="unit-1"></a>

### Unit 1 — Foundations of AI-Augmented Software Engineering

**Modules 1–3** introduce the AI-augmented software engineering paradigm, the foundations of Generative AI and Large Language Models (LLMs), and prompt engineering techniques applied to software engineering.

<a id="module-1"></a>

#### Module 1 — Introduction to AI-Augmented Software Engineering (~4h video + 4h home exercises)

<details>
<summary><strong>Module Description</strong></summary>

This module introduces AI-Augmented Software Engineering as the systematic use of Artificial Intelligence to support software engineering activities while preserving human understanding, verification, decision-making, and accountability.

Students will examine how Generative AI and related technologies can assist requirements engineering, software architecture and design, implementation, testing, documentation, maintenance, project workflows, deployment, and software evolution. The module distinguishes AI augmentation from deterministic automation and more autonomous agentic execution.

The module also introduces the greenfield and brownfield running examples that will be revisited throughout the course. These examples illustrate how AI-augmented practices must be adapted to the characteristics, evidence, constraints, and risks of each development context.

</details>

1.1 Course Overview, Learning Approach, and Assessment (~8 min)  
1.2 From Traditional Software Engineering to AI-Augmented Practice (~12 min)  
1.3 Generative AI Across the Software Development Life Cycle (~10 min)  
1.4 Levels of AI Involvement: Augmentation, Automation, Autonomy, and Human Accountability (~12 min)  
1.5 Introducing the Greenfield and Brownfield Examples (~10 min)  
1.6 Greenfield Hands-On: Map AI Involvement Across the BlueVelvet Development Lifecycle (~90 min)  
1.7 Brownfield Hands-On: Identify AI Assistance Opportunities and Human Responsibilities in Sparkling Waters (~88 min)  
1.8 Greenfield Home Exercise: Exploring AI-Augmented Greenfield Development (~5 min)  
1.9 Brownfield Home Exercise: Exploring AI-Augmented Brownfield Development (~5 min)


<a id="module-2"></a>

#### Module 2 — Foundations of Generative AI and Large Language Models (~4h video + 4h home exercises)

<details>
<summary><strong>Module Description</strong></summary>

This module introduces the technical foundations necessary to understand and responsibly use Generative AI systems in software engineering. Students will distinguish among Artificial Intelligence, Machine Learning, Deep Learning, and Generative AI and examine the fundamental principles underlying Large Language Models (LLMs).

The module presents a practical mental model of how LLMs are trained, process contextual input, and generate outputs through probabilistic token prediction. It also distinguishes the language model itself from the surrounding application, which may provide user interfaces, conversation history, external knowledge, retrieval mechanisms, tools, and execution environments.

Students will study tokens, context windows, embeddings, non-deterministic behavior, hallucinations, and other limitations that affect the correctness and reliability of AI-assisted software engineering activities.

</details>

2.1 Artificial Intelligence, Machine Learning, Deep Learning, and Generative AI (~12 min)  
2.2 How Large Language Models Are Trained and Generate Outputs (~14 min)  
2.3 Tokens, Context Windows, Embeddings, and Retrieval Foundations (~14 min)  
2.4 Capabilities, Reasoning Behavior, Hallucinations, and Limitations (~12 min)  
2.5 Greenfield Hands-On: Investigate LLM Capabilities and Hallucinations Using BlueVelvet Scenarios (~90 min)  
2.6 Brownfield Hands-On: Test LLM Code Explanations Against Evidence from the Sparkling Waters Repository (~88 min)  
2.7 Greenfield Home Exercise: Investigating LLM Behavior in Greenfield Development (~5 min)  
2.8 Brownfield Home Exercise: Investigating LLM Behavior in Brownfield Development (~5 min)


<a id="module-3"></a>

#### Module 3 — Prompt and Context Engineering for Software Engineers (~4h video + 4h home exercises)

<details>
<summary><strong>Module Description</strong></summary>

This module introduces prompt and context engineering techniques for software engineering tasks. Students will learn to define objectives, assign relevant roles, communicate constraints, provide examples, request structured outputs, and progressively refine interactions with AI systems.

Particular attention will be given to context selection. Students will learn to identify and provide relevant requirements, source code, documentation, architectural decisions, coding conventions, test results, and other task-specific information without unnecessarily overloading the model's context window.

The module also emphasizes that prompts and contextual materials are integral parts of an engineering process. Their effectiveness should be evaluated based on the quality, correctness, relevance, reproducibility, and verifiability of the resulting software artifacts.

</details>

3.1 Task Framing and Prompt Design Principles (~10 min)  
3.2 Context Selection and Repository Instructions (~12 min)  
3.3 Structured Outputs, Templates, and Constraints (~10 min)  
3.4 Prompt Patterns, Task Decomposition, and Iterative Refinement (~12 min)  
3.5 Greenfield Example: Prompting for New Software Development (~10 min)  
3.6 Brownfield Example: Prompting with Existing Code and Documentation (~10 min)  
3.7 Greenfield Hands-On: Engineer Prompts and Context for BlueVelvet Feature Planning (~85 min)  
3.8 Brownfield Hands-On: Build Repository-Aware Prompts for Sparkling Waters Code Comprehension (~81 min)  
3.9 Greenfield Home Exercise: Prompt and Context Engineering for Greenfield Development (~5 min)  
3.10 Brownfield Home Exercise: Prompt and Context Engineering for Brownfield Development (~5 min)


[Back to top](#top)

<a id="unit-2"></a>

### Unit 2 — AI Across the Software Development Life Cycle

**Modules 4–8** explore how AI can support requirements engineering, software architecture and design, implementation, software artifact evaluation, testing, and quality assurance.

<a id="module-4"></a>

#### Module 4 — AI-Assisted Requirements Engineering (~4h video + 4h home exercises)

<details>
<summary><strong>Module Description</strong></summary>

This module examines how AI can support requirements engineering without replacing stakeholder participation, domain expertise, or human decision-making. Students will use AI to assist with requirements elicitation and discovery, question generation, information organization, user-story development, acceptance-criteria definition, ambiguity detection, conflict analysis, prioritization, validation, and traceability.

The module emphasizes that AI-generated requirements are proposals rather than authoritative statements of stakeholder needs. Requirements must be grounded in reliable evidence, reviewed for correctness and feasibility, and approved by the appropriate stakeholders or responsible members of the development team.

Greenfield and brownfield contexts will be examined separately. In greenfield development, AI may help transform an initial problem or product idea into progressively refined requirements. In brownfield development, AI may assist with recovering requirements from source code, tests, documentation, interfaces, issue trackers, and observed system behavior.

</details>

4.1 AI-Supported Requirements Elicitation and Discovery (~10 min)  
4.2 User Stories, Acceptance Criteria, and Quality Requirements (~12 min)  
4.3 Requirements Analysis: Ambiguity, Conflicts, Gaps, and Prioritization (~10 min)  
4.4 Requirements Validation, Traceability, and Human Approval (~10 min)  
4.5 Greenfield Example: Developing Requirements for a New System (~10 min)  
4.6 Brownfield Example: Recovering and Validating Existing Requirements (~10 min)  
4.7 Greenfield Hands-On: Elicit and Validate BlueVelvet User Stories and Acceptance Criteria (~85 min)  
4.8 Brownfield Hands-On: Recover and Validate Sparkling Waters Requirements from Existing Behavior (~83 min)  
4.9 Greenfield Home Exercise: AI-Assisted Greenfield Requirements Engineering (~5 min)  
4.10 Brownfield Home Exercise: AI-Assisted Brownfield Requirements Engineering (~5 min)


<a id="module-5"></a>

#### Module 5 — AI-Assisted Software Architecture and Design (~4h video + 4h home exercises)

<details>
<summary><strong>Module Description</strong></summary>

This module examines how AI can support software architecture and design activities. Students will use AI to explore architectural alternatives, create and review software models, identify applicable design patterns, analyze trade-offs, and document design decisions.

The module emphasizes that AI-generated architectures and models are proposals that must be evaluated against functional requirements, quality attributes, technological constraints, organizational context, and existing system evidence. Students will learn to verify the consistency of generated diagrams and descriptions rather than accepting visually plausible models without critical analysis.

Greenfield and brownfield development will be considered separately. In greenfield development, AI can assist with exploring and comparing alternative designs. In brownfield development, AI can support architecture recovery, dependency analysis, identification of design problems, and planning of incremental improvements.

</details>

5.1 Architecture Drivers, Constraints, and AI-Generated Alternatives (~12 min)  
5.2 UML and System Modeling with AI Assistance (~12 min)  
5.3 Design Patterns, Responsibilities, and Trade-Offs (~12 min)  
5.4 Architecture Evaluation, Decision Records, and Human Review (~10 min)  
5.5 Greenfield Example: Designing a New Software Architecture (~10 min)  
5.6 Brownfield Example: Architecture Recovery and Design Improvement (~10 min)  
5.7 Greenfield Hands-On: Compare AI-Generated Architecture and Design Alternatives for BlueVelvet (~80 min)  
5.8 Brownfield Hands-On: Recover and Evaluate the Sparkling Waters Architecture (~84 min)  
5.9 Greenfield Home Exercise: AI-Assisted Greenfield Architecture and Design (~5 min)  
5.10 Brownfield Home Exercise: AI-Assisted Brownfield Architecture and Design (~5 min)


<a id="module-6"></a>

#### Module 6 — AI Coding Assistants and AI-Powered Development Environments (~4h video + 4h home exercises)

<details>
<summary><strong>Module Description</strong></summary>

This module examines how AI coding assistants and AI-powered development environments support software implementation and maintenance.

Representative tools may include GitHub Copilot, Cursor, Claude Code, Codex, Google Antigravity, Google Jules, and other systems available during the course offering. The emphasis is placed on transferable software engineering practices, including context preparation, task decomposition, code comprehension, code review, verification, debugging, refactoring, and responsible acceptance of AI-generated changes.

</details>

6.1 AI Coding Assistants and Development Environments (~10 min)  
6.2 Context-Aware Code Generation and Completion (~12 min)  
6.3 Code Comprehension, Debugging, and Refactoring (~12 min)  
6.4 Documentation Generation and Maintenance (~8 min)  
6.5 Greenfield Example: Implementing a New Feature with AI Assistance (~9 min)  
6.6 Brownfield Example: Understanding and Improving Existing Code (~9 min)  
6.7 Greenfield Hands-On: Implement and Review a BlueVelvet Feature with an AI Coding Assistant (~90 min)  
6.8 Brownfield Hands-On: Debug, Refactor, and Document a Sparkling Waters Component with AI Assistance (~80 min)  
6.9 Greenfield Home Exercise: AI-Assisted Greenfield Software Implementation (~5 min)  
6.10 Brownfield Home Exercise: AI-Assisted Brownfield Software Maintenance (~5 min)


<a id="module-7"></a>

#### Module 7 — Verification and Evaluation of AI-Generated Software Artifacts (~4h video + 4h home exercises)

<details>
<summary><strong>Module Description</strong></summary>

This module examines how software engineers verify and evaluate artifacts produced or modified with AI assistance.

Students will learn to identify inaccuracies, omissions, unsupported assumptions, inconsistencies, security weaknesses, and quality problems in AI-generated requirements, designs, source code, tests, and documentation.

The module emphasizes systematic human review, traceability among software artifacts, execution-based verification, and the collection of evidence supporting the acceptance, correction, or rejection of AI-generated outputs.

</details>

7.1 Why Verification Matters in AI-Augmented Development (~10 min)  
7.2 Evaluating AI-Generated Requirements (~10 min)  
7.3 Evaluating AI-Generated Architectures and Designs (~10 min)  
7.4 Evaluating AI-Generated Code and Tests (~15 min)  
7.5 Human Review, Traceability, and Verification Evidence (~15 min)  
7.6 Greenfield Hands-On: Audit AI-Generated BlueVelvet Requirements, Design, and Code (~80 min)  
7.7 Brownfield Hands-On: Verify AI-Proposed Sparkling Waters Changes Against Repository Evidence (~90 min)  
7.8 Greenfield Home Exercise: Evaluating AI-Generated Greenfield Artifacts (~5 min)  
7.9 Brownfield Home Exercise: Evaluating AI-Generated Brownfield Artifacts (~5 min)


<a id="module-8"></a>

#### Module 8 — AI-Assisted Testing and Quality Assurance (~4h video + 4h home exercises)

<details>
<summary><strong>Module Description</strong></summary>

This module examines how AI can support software testing and quality assurance while preserving the need for systematic verification and professional judgment. Students will use AI to assist with test design, test-case generation, automated test implementation, regression testing, failure analysis, and test maintenance.

The module also addresses the limitations of AI-generated tests. Students will evaluate whether generated tests reflect intended requirements, contain meaningful assertions, cover relevant boundary conditions, and avoid merely reproducing the assumptions of the implementation being tested.

Students will also be introduced to testing strategies for software features that rely on LLMs or other non-deterministic AI components. Such features may require evaluation datasets, quality criteria, repeated execution, tolerance-based assertions, human evaluation, and monitoring rather than relying exclusively on traditional exact-output assertions.

</details>

8.1 AI-Assisted Test Design and Test Case Generation (~10 min)  
8.2 Unit, Integration, and Regression Testing with AI Assistance (~12 min)  
8.3 Evaluating AI-Generated Tests and Test Oracles (~10 min)  
8.4 Testing Non-Deterministic and LLM-Enabled Features (~10 min)  
8.5 Greenfield Example: Designing and Implementing a Test Strategy (~10 min)  
8.6 Brownfield Example: Characterization Testing and Increasing Legacy Test Coverage (~10 min)  
8.7 Greenfield Hands-On: Generate and Critically Evaluate BlueVelvet Automated Tests (~80 min)  
8.8 Brownfield Hands-On: Create Characterization and Regression Tests for Sparkling Waters (~88 min)  
8.9 Greenfield Home Exercise: AI-Assisted Testing for Greenfield Development (~5 min)  
8.10 Brownfield Home Exercise: AI-Assisted Testing for Brownfield Development (~5 min)


[Back to top](#top)

<a id="unit-3"></a>

### Unit 3 — Human–AI Collaboration and Agentic Development

**Modules 9–11** address human–AI collaboration, vibe coding, AI agents, agentic workflows, tool integration, human oversight and approval, and the Model Context Protocol (MCP).

<a id="module-9"></a>

#### Module 9 — Human–AI Collaboration and Developer Control (~4h video + 4h home exercises)

<details>
<summary><strong>Module Description</strong></summary>

This module examines how software engineers collaborate with AI systems while retaining understanding, control, and responsibility for software outcomes. Students will analyze different levels of AI assistance, ranging from suggestions and pair-programming interactions to more autonomous development workflows.

Vibe coding will be examined as an approach in which developers rely heavily on natural-language interactions and AI-generated implementations. Students will evaluate contexts in which rapid AI-assisted experimentation may be useful, as well as situations in which insufficient understanding, verification, or control can introduce unacceptable risks.

The module also considers how AI assistance affects productivity, software quality, learning, technical skill development, and developers' ability to explain, maintain, and evolve the resulting systems.

</details>

9.1 Models of Human–AI Collaboration in Software Engineering (~10 min)  
9.2 Human-in-the-Loop Development, Approval, and Developer Control (~10 min)  
9.3 Vibe Coding: Characteristics, Appropriate Uses, and Risks (~10 min)  
9.4 Productivity, Quality, Learning, and Skill Retention (~10 min)  
9.5 Greenfield Hands-On: Compare Controlled AI Assistance and Vibe Coding on a BlueVelvet Task (~95 min)  
9.6 Brownfield Hands-On: Evaluate Developer Control and Understanding During Sparkling Waters Maintenance (~95 min)  
9.7 Greenfield Home Exercise: Evaluating Human–AI Collaboration in Greenfield Development (~5 min)  
9.8 Brownfield Home Exercise: Evaluating Human–AI Collaboration in Brownfield Development (~5 min)


<a id="module-10"></a>

#### Module 10 — AI Agents (~4h video + 4h home exercises)

<details>
<summary><strong>Module Description</strong></summary>

By the end of this module, students will be able to explain the core components and architectural patterns of AI agents, distinguish agents from conventional LLM applications, and design a simple tool-using agent for a greenfield or brownfield software context.

Particular attention will be given to agent state, environmental interactions, tool access, permissions, verification, and human oversight.

</details>

10.1 From LLM Applications to AI Agents (~10 min)  
10.2 Core Agent Components: Models, Instructions, State, and Environment (~12 min)  
10.3 Tool Use and Function Calling (~12 min)  
10.4 Agent Architectures: Reactive, Planning, Single-Agent, and Multi-Agent Systems (~12 min)  
10.5 Greenfield Example: Creating an Agent for a New Application (~7 min)  
10.6 Brownfield Example: Introducing an Agent into an Existing System (~7 min)  
10.7 Greenfield Hands-On: Configure a Multi-Agent Software Development Team for BlueVelvet (~90 min)  
10.8 Brownfield Hands-On: Configure Repository-Aware AI Agent Roles for Sparkling Waters Evolution (~80 min)  
10.9 Greenfield Home Exercise: Configuring AI Agents for Greenfield Development (~5 min)  
10.10 Brownfield Home Exercise: Configuring AI Agents for Brownfield Development (~5 min)


<a id="module-11"></a>

#### Module 11 — Agentic Workflows, Human Oversight, and MCP (~4h video + 4h home exercises)

<details>
<summary><strong>Module Description</strong></summary>

This module examines how AI agents, deterministic operations, external tools, and human decisions can be combined into structured agentic workflows.

The emphasis is placed on task decomposition, orchestration, execution control, approval points, feedback mechanisms, failure handling, and the use of the Model Context Protocol (MCP) to connect AI systems with external tools and contextual resources.

</details>

11.1 Workflows Versus Agents (~10 min)  
11.2 Task Decomposition, Orchestration, and Execution Control (~12 min)  
11.3 Human Approval, Feedback Loops, and Guardrails (~10 min)  
11.4 Agentic Software Development Workflows (~12 min)  
11.5 Introduction to the Model Context Protocol (MCP) (~8 min)  
11.6 MCP Servers, Tools, and Development Environments (~8 min)  
11.7 Greenfield Hands-On: Orchestrate AI Agents to Implement a BlueVelvet Requirement with Human Approval (~90 min)  
11.8 Brownfield Hands-On: Orchestrate AI Agents to Refactor or Evolve Sparkling Waters with Human Approval (~80 min)  
11.9 Greenfield Home Exercise: Agentic Workflows for Greenfield Development (~5 min)  
11.10 Brownfield Home Exercise: Agentic Workflows for Brownfield Development (~5 min)


[Back to top](#top)

<a id="unit-4"></a>

### Unit 4 — Building and Delivering AI-Augmented Applications

**Modules 12–14** cover the development of applications that integrate AI capabilities, Retrieval-Augmented Generation (RAG), local and open-weight models, AI-assisted DevOps, and software deployment and delivery.

<a id="module-12"></a>

#### Module 12 — Building AI-Augmented Applications (~4h video + 4h home exercises)

<details>
<summary><strong>Module Description</strong></summary>

By the end of this module, students will be able to design, prototype, and evaluate AI-augmented software applications by integrating LLM APIs, Retrieval-Augmented Generation (RAG), and user-facing AI capabilities.

The module emphasizes appropriate architectural and integration patterns, reliability mechanisms, observability practices, and human-centered interface design. Students will also explore AI-assisted UI/UX design, rapid prototyping, and the generation and evaluation of front-end applications.

</details>

12.1 LLM APIs and Application Integration (~12 min)  
12.2 Retrieval-Augmented Generation (RAG) (~14 min)  
12.3 Designing AI Features in Software Products (~10 min)  
12.4 Integration Patterns, Reliability, and Observability (~12 min)  
12.5 AI-Assisted UI/UX Design and Rapid Prototyping (~8 min)  
12.6 Generating and Evaluating Front-End Applications with AI (~10 min)  
12.7 Greenfield Hands-On: Prototype a BlueVelvet LLM Feature with Retrieval and a User Interface (~85 min)  
12.8 Brownfield Hands-On: Design and Prototype a Repository-Grounded AI Assistance Feature for Sparkling Waters (~79 min)  
12.9 Greenfield Home Exercise: Developing AI-Augmented Greenfield Applications (~5 min)  
12.10 Brownfield Home Exercise: Integrating AI Capabilities into Brownfield Applications (~5 min)


<a id="module-13"></a>

#### Module 13 — Local and Open Models (~4h video + 4h home exercises)

<details>
<summary><strong>Module Description</strong></summary>

This module introduces open-weight models and local AI development environments. Students will distinguish among open-weight, open-source, and proprietary models and examine how licensing conditions, model availability, and deployment choices affect software engineering decisions.

Using representative tools such as Ollama and LM Studio, students will learn how models can be downloaded, configured, executed, evaluated, and exposed to software applications in local environments.

The module also examines trade-offs involving privacy, confidentiality, hardware requirements, performance, model quality, context capacity, licensing, operational costs, maintenance, and deployment complexity.

</details>

13.1 Open-Weight, Open-Source, and Proprietary Models (~10 min)  
13.2 Running and Managing Local Models with Ollama (~12 min)  
13.3 Exploring and Serving Local Models with LM Studio (~10 min)  
13.4 Model Selection and Deployment Trade-Offs (~12 min)  
13.5 Greenfield Hands-On: Evaluate a Local Model for BlueVelvet Development Tasks (~90 min)  
13.6 Brownfield Hands-On: Evaluate Local-Model Use for Privacy-Aware Sparkling Waters Code Analysis (~96 min)  
13.7 Greenfield Home Exercise: Evaluating Local Models for Greenfield Development (~5 min)  
13.8 Brownfield Home Exercise: Evaluating Local Models for Brownfield Development (~5 min)


<a id="module-14"></a>

#### Module 14 — AI-Assisted DevOps, Software Delivery, and Operational Reliability (~4h video + 4h home exercises)

<details>
<summary><strong>Module Description</strong></summary>

This module examines how AI can support software integration, delivery, deployment, and operational activities. Students will explore AI assistance in Git workflows, pull-request analysis, CI/CD pipeline configuration, quality checks, release preparation, deployment planning, monitoring, and incident investigation.

The module emphasizes that AI should complement rather than replace deterministic build, testing, security, and deployment controls. AI-generated pipeline configurations, review comments, release notes, and deployment recommendations must be validated before being incorporated into operational workflows.

Particular attention will be given to traceability, least-privilege access, human approval, rollback mechanisms, and the protection of credentials, source code, logs, and other sensitive operational information.

</details>

14.1 AI in Git Workflows, Issues, and Pull Requests (~12 min)  
14.2 AI-Assisted CI/CD Pipeline Development and Maintenance (~12 min)  
14.3 Quality Gates, Security Checks, and Release Readiness (~14 min)  
14.4 Deployment, Release Management, Monitoring, and Rollback (~14 min)  
14.5 Greenfield Hands-On: Build and Validate a CI/CD Pipeline for BlueVelvet (~85 min)  
14.6 Brownfield Hands-On: Improve Sparkling Waters CI Checks and Plan Safe Release and Rollback (~93 min)  
14.7 Greenfield Home Exercise: AI-Assisted DevOps for Greenfield Development (~5 min)  
14.8 Brownfield Home Exercise: AI-Assisted DevOps for Brownfield Development (~5 min)


[Back to top](#top)

<a id="unit-5"></a>

### Unit 5 — Responsible Practice and Future Directions

**Module 15** examines security, privacy, intellectual property, ethics, governance, and the future of software engineering in the context of AI-augmented development.

<a id="module-15"></a>

#### Module 15 — Responsible AI-Augmented Software Engineering and Future Trends (~4h video + 4h home exercises)

<details>
<summary><strong>Module Description</strong></summary>

This module examines the broader responsibilities associated with adopting AI in software engineering. Students will analyze security and privacy risks, copyright and licensing concerns, organizational governance, ethical responsibilities, and the effects of AI on professional roles and practices.

The module concludes by examining how software engineers can adapt to technological change while preserving foundational engineering principles, technical understanding, human accountability, and responsibility for software outcomes.

</details>

15.1 Security Risks of AI-Augmented Development (~12 min)  
15.2 Privacy, Copyright, Licensing, and Intellectual Property (~12 min)  
15.3 Governance, Ethics, and Responsible Professional Practice (~14 min)  
15.4 The Future of Software Engineering Work and Education (~12 min)  
15.5 Greenfield Hands-On: Assess Security, Privacy, Licensing, and Governance Risks in BlueVelvet (~85 min)  
15.6 Brownfield Hands-On: Audit AI-Assisted Sparkling Waters Evolution for Responsible Engineering Risks (~95 min)  
15.7 Greenfield Home Exercise: Responsible AI-Augmented Greenfield Development (~5 min)  
15.8 Brownfield Home Exercise: Responsible AI-Augmented Brownfield Development (~5 min)


The **greenfield and brownfield running examples** are revisited throughout the five units, allowing students to explore how AI-augmented software engineering practices apply to both new software development and the maintenance and evolution of existing systems.


[Back to top](#top)

<a id="learning-objectives"></a>

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


[Back to top](#top)

<a id="target-audience"></a>

## Target Audience

This course is intended for **undergraduate Computer Science students** who have completed introductory courses in programming and software engineering. It is particularly suitable for students who are comfortable reading, writing, testing, and modifying software systems.

**No prior experience with Artificial Intelligence (AI), Machine Learning (ML), Large Language Models (LLMs), or AI coding assistants is required.** The necessary conceptual foundations and practical techniques will be introduced progressively throughout the course.


[Back to top](#top)

<a id="weekly-workload"></a>

## Weekly Workload

The course spans **15 weeks**, with an expected workload of **8 hours per week**, totaling **120 hours**. Each week allocates approximately **4 hours to video-based instruction** and **4 hours to independent home exercises**.

The video component includes theoretical lessons, a greenfield hands-on demonstration using BlueVelvet Music Store, a brownfield hands-on demonstration using Sparkling Waters Hostel, and two short videos introducing the respective home exercises.

The independent exercises provide opportunities to apply the techniques to students' own greenfield and brownfield projects. Students may also work on BlueVelvet or Sparkling Waters, provided they select requirements, features, defects, or improvements different from those developed in the instructor demonstrations. **The combined workload for both home-exercise contexts is approximately 4 hours per week**, not 4 hours each.

Depending on the module, students may produce **prompts, requirements, user stories, architectural models, source code, automated tests, documentation, evaluation reports, or working software increments**. Students are expected to document **how AI outputs were reviewed, verified, corrected, and refined**, including relevant engineering decisions. Complete exercise statements and submission details will be available through the course website.

[Back to top](#top)

<a id="running-examples"></a>

## Running Examples

Throughout the course, two instructor-led examples will demonstrate the practical application of AI-augmented software engineering techniques:

- **BlueVelvet Music Store (Greenfield):** Development of selected, prioritized features of a new e-commerce application from scratch.
- **Sparkling Waters Hostel (Brownfield):** Analysis, maintenance, and evolution of selected features of an existing hostel management and reservation system, including guest management, authentication, and role-based authorization.

These examples will be revisited across multiple course modules to illustrate how AI can support different activities throughout the Software Development Life Cycle (SDLC). Students will apply similar techniques to their own greenfield and brownfield projects, which may involve different application domains and technologies. They may also extend either running example through distinct features or improvements not implemented in the instructor demonstrations.

### Greenfield Development: BlueVelvet Music Store

**BlueVelvet Music Store** is a new e-commerce application whose selected, prioritized features will be developed from scratch. It will demonstrate how AI can support requirements elicitation and refinement, software architecture and interface design, implementation, automated testing, documentation, deployment, and software evolution.

Because the application starts without an existing codebase, this example will illustrate how developers can use AI to explore alternatives, generate initial software artifacts, evaluate proposed solutions, and progressively transform requirements into a working software product.

### Brownfield Development: Sparkling Waters Hostel

**Sparkling Waters Hostel** is an existing hostel management and reservation system developed using Spring Boot and front-end technologies, including HTML, CSS, JavaScript, and Bootstrap. The system includes basic guest management, authentication, and role-based authorization functionality, providing a foundation for software maintenance and evolution activities.

This example will demonstrate how AI can support program comprehension, requirements and architecture recovery, codebase exploration, debugging, refactoring, test generation, documentation improvement, and feature enhancement. Potential evolution activities include improving the existing software design and implementing or enhancing guest reservation management.

The brownfield example will also emphasize that **AI-generated recommendations and changes must be validated** against the existing codebase, architecture, requirements, and tests before being accepted.

The running examples may be updated in future course offerings while preserving their complementary greenfield and brownfield perspectives.


[Back to top](#top)

<a id="hands-on-activities"></a>

## Hands-On Activities

Each module provides **two recorded instructor-led hands-on demonstrations**—one greenfield and one brownfield—followed by **two brief home-exercise introduction videos**. The demonstrations combine guided experimentation, critical evaluation of AI-generated software artifacts, and incremental development of the running examples. Students then apply the demonstrated techniques independently to selected greenfield and brownfield project work.

Depending on the module, students may be asked to:

- Design, compare, and refine prompts for software engineering tasks.
- Generate and evaluate requirements, user stories, acceptance criteria, and software models.
- Use AI coding assistants to implement, understand, debug, refactor, and document software.
- Generate, execute, and evaluate automated tests.
- Examine AI-generated artifacts for errors, unsupported assumptions, security vulnerabilities, and quality issues.
- Design and implement workflows involving AI agents, external tools, APIs, Retrieval-Augmented Generation (RAG), or local AI models.
- Evaluate alternative solutions based on software quality, privacy, security, cost, and maintainability.
- Apply AI-augmented software engineering techniques to their own greenfield or brownfield project components.

Hands-on activities may be completed **individually or collaboratively**, depending on their learning objectives. Some activities will be exploratory and formative, while others will produce software artifacts that contribute directly to project milestones.

Students are expected to retain relevant **evidence of AI-assisted development**, including prompts, generated outputs, source-code changes, test results, reviews, corrections, and engineering decisions.

The purpose of this evidence is **not to document every interaction with an AI system**, but to demonstrate meaningful AI assistance, critical evaluation, verification, and student accountability for the resulting software artifacts.


[Back to top](#top)

<a id="living-book"></a>

## Living Book

A **living book on AI-Augmented Software Engineering** is being developed alongside the course. It will progressively consolidate and expand the concepts, techniques, tools, examples, and practical insights introduced throughout the 15 modules.

Unlike a traditional textbook, the living book is intended to evolve as AI technologies and software engineering practices advance. Its content will be reviewed and refined as new developments and lessons learned become available.

The living book will complement the video lessons, hands-on activities, and greenfield and brownfield projects. It is intended as an evolving reference for students, educators, and software engineering practitioners.

**Status:** Under development. Access details will be provided when the initial chapters are available.


[Back to top](#top)

<a id="course-website"></a>

## Course Website

The course website will serve as the primary instructional hub for detailed hands-on activities, semester-specific greenfield and brownfield assignments, assessment guidelines, schedules, technical setup instructions, and academic integrity policies.

This GitHub repository complements the website by providing the course overview, module outline, source code, running examples, and technical artifacts.

**Status:** In development. The website link will be added when available.

[Back to top](#top)


