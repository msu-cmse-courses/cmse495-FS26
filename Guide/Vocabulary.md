---
layout: guide
title: "Vocabulary"
order: 2
mode: "guide"
---
# Vocabulary

The following concepts appear throughout the course.

## Data and Analysis

### Data Bibliography

A data bibliography is a curated list of data sources that may be useful for a project.

A strong data bibliography typically includes:

- The data source
- A description of its contents
- How the data may support project goals
- Limitations or concerns
- How the data can be accessed

Teams often develop data bibliographies before committing to a specific dataset or technical approach.

### Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) is the process of examining project data and other available resources to better understand what information is available, how it is organized, and what questions it may help answer.

EDA often includes:

- Reviewing the structure and schema of a dataset
- Examining examples of records, files, documents, or other project resources
- Creating summary statistics, tables, graphs, and visualizations
- Identifying patterns, limitations, and data quality concerns
- Discovering questions that require further investigation

The goal of EDA is not to build a final solution. The goal is to develop an informed understanding of the project's starting point so that future decisions, success criteria, and project plans are based on evidence rather than assumptions.

### Schema (aka Data Dictionary)

A schema describes the structure of a dataset or information source.

Depending on the project, a schema may describe:

- Variables and columns
- Data types
- Relationships between records
- File organization
- Metadata
- Units and measurement conventions

Understanding a schema is often an important step in exploratory data analysis and project planning.

## Project Management

### Minimum Viable Product (MVP)

A Minimum Viable Product (MVP) is the simplest version of a solution that demonstrates the core functionality of a project.

An MVP is not a final product. Instead, it serves as an early proof of concept that can be tested, evaluated, and improved.

An MVP should:

- Solve a small but meaningful part of the problem
- Demonstrate end-to-end functionality
- Be usable for evaluation and feedback
- Provide a foundation for future improvements

Successful teams typically build a simple MVP early and then improve it iteratively rather than attempting to build a complete solution all at once.

### Open Loops

Every project contains uncertainties.

An **open loop** is a question, assumption, risk, or unresolved issue that could affect project success.

Examples include:

- Unknown data quality issues
- Missing community partner requirements
- Technical uncertainties
- Evaluation methods
- Access to resources
- Questions about project scope
- Success criteria that have not yet been fully defined

Strong teams identify open loops early and develop plans to close them throughout the semester.

Avoid both extremes:

- Ignoring open loops and hoping they resolve themselves
- Spending all available time investigating open loops while making no progress on known tasks

The goal is to balance discovery and execution.

### Selection Matrix

A selection matrix is a decision-making tool used to compare multiple options against a common set of criteria.

Teams may use selection matrices when evaluating:

- Technical approaches
- Software tools
- Datasets
- Design alternatives
- Project priorities

The goal is not to find a perfect answer, but to make decisions transparent and justifiable.

### Success Criteria

Success criteria describe how a team will determine whether the project is making meaningful progress and how the final solution will be evaluated.

Success criteria should focus on outcomes rather than activities. The best success criteria are specific, measurable when possible, and connected to community partner needs.

## Software Development

### Reproducibility

Reproducibility is the ability for another person to obtain the same results using the same data, code, and documented procedures.

In software projects, reproducibility means that someone outside the team can install the software, run it, and observe the expected behavior without relying on undocumented knowledge. In data science and scientific research, reproducibility means that another person can regenerate the analyses, figures, tables, results, and conclusions that support a project's findings.

Reproducibility is important because it builds trust. If a result cannot be recreated, it is difficult to verify, maintain, improve, or build upon. Many course milestones, including installation instructions, documentation, data analysis workflows, and figure-generation procedures, are designed to improve the reproducibility of your project.

### Robustness

Robustness is the ability of a system to work reliably under a variety of reasonable conditions.

Robust software continues to function when inputs change, datasets grow, users make mistakes, or the software is executed in different environments. Robust systems are not expected to handle every possible situation perfectly, but they should fail gracefully and provide useful feedback when something goes wrong.

A project may be reproducible without being robust. For example, software that only works for a specific dataset or on a single computer may be reproducible if all steps are documented, but it is not robust. Strong projects strive to be both reproducible and robust.

### Application Programming Interface (API)

An Application Programming Interface (API) is a defined way for one piece of software to interact with another.

An API specifies what functionality is available, what inputs are expected, and what outputs will be returned. Well-designed APIs allow software components to be used without requiring users to understand their internal implementation.

In this course, the term API may refer to several different types of interfaces.

#### Python Package API

A Python package API consists of the functions, classes, methods, and modules that a developer can import and use within their own code.

For example:

```python
import pandas as pd

df = pd.read_csv("data.csv")
```

The functions and classes provided by Pandas are part of the Pandas API.

Many course projects focus on developing reusable Python package APIs because they make functionality easier to test, document, maintain, and reuse.

#### Web API

A Web API provides functionality over a network using web protocols such as HTTP.

Instead of importing a package, software communicates with the API by sending requests and receiving responses.

Examples include:

- Weather services
- Mapping services
- AI services
- Database-backed applications

Web APIs are useful when multiple applications, systems, or users need shared access to the same functionality.

#### Relationship Between Package APIs and Web APIs

Students sometimes assume that "develop an API" means creating a web service. In most course projects, this is not the case.

A well-designed software project often begins by building a reusable package API that contains the project's core functionality.

If remote access is needed later, a Web API can be built on top of the package API.

A common architecture looks like:

```text
Application Logic
        ↓
    Package API
        ↓
      Web API
        ↓
 External Users or Applications
```

This approach avoids duplicating code and allows the same functionality to be used both locally and over a network.

Unless there is a clear requirement for network communication, teams should generally focus on developing a clean package API before considering a Web API.

<!-- TOC_START -->
<div class="page-toc">
<h2>On this page</h2>

<details>
<summary>Vocabulary</summary>
<ul>

<li><a href="#data-and-analysis">Data and Analysis</a></li>
<ul>
<li><a href="#data-bibliography">Data Bibliography</a></li>
<li><a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a></li>
<li><a href="#schema-aka-data-dictionary">Schema (aka Data Dictionary)</a></li>
</ul>
<li><a href="#project-management">Project Management</a></li>
<ul>
<li><a href="#minimum-viable-product-mvp">Minimum Viable Product (MVP)</a></li>
<li><a href="#open-loops">Open Loops</a></li>
<li><a href="#selection-matrix">Selection Matrix</a></li>
<li><a href="#success-criteria">Success Criteria</a></li>
</ul>
<li><a href="#software-development">Software Development</a></li>
<ul>
<li><a href="#reproducibility">Reproducibility</a></li>
<li><a href="#robustness">Robustness</a></li>
<li><a href="#application-programming-interface-api">Application Programming Interface (API)</a></li>
</ul>
</ul>
</details>
</div>
<!-- TOC_END -->
