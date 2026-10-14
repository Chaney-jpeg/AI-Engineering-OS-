# Code Review

## Purpose

Review AI-generated or manually written code for correctness,
security, maintainability, and consistency with the project.

The goal is to catch problems early and help me understand
the code I am building.

## Review Instructions

Act as a careful software engineer reviewing an existing
implementation.

### Context

Project: [PROJECT NAME]

Feature: [FEATURE NAME]

Expected behaviour:
[DESCRIBE WHAT THE CODE SHOULD DO]

Relevant code:
[PASTE CODE OR IDENTIFY ACCESSIBLE FILES]

### Review Checklist

#### 1. Correctness
- Does the code implement the expected behaviour?
- Are there logical errors or incorrect assumptions?
- Are edge cases handled?
- Are there potential runtime errors?

#### 2. Security
- Is user input validated?
- Are secrets or credentials exposed?
- Are authentication and authorization handled correctly?
- Are there injection or data exposure risks?

#### 3. Maintainability
- Is the implementation unnecessarily complicated?
- Are functions and variables clearly named?
- Is logic duplicated unnecessarily?
- Does the code follow existing project conventions?

#### 4. Integration
- Does the code fit the existing architecture?
- Could it break other features?
- Are API contracts and data structures consistent?
- Are dependencies used correctly?

#### 5. Testing
- What tests already exist?
- What important cases are not tested?
- Which verification steps should be performed?

Do not claim to have run tests unless they were actually run.

## Response Format

### Overall Assessment
Briefly describe the implementation's condition.

### Issues Found
For each issue, provide:
- Severity: Critical, High, Medium, or Low.
- Relevant file or code location.
- Explanation of the problem.
- Why it matters.
- A recommended correction.

Do not invent problems merely to fill this section.

### Suggested Improvements
List worthwhile improvements separately from actual bugs.

### Verification Plan
Describe the tests or checks needed to establish correctness.

### Learning Notes
Explain the most important technical lesson in simple language.

## Constraints

- Review before modifying.
- Do not rewrite the entire implementation unnecessarily.
- Preserve working functionality.
- Distinguish confirmed defects from possible risks.
- Prioritize correctness and security over stylistic preferences.
- Explain important findings without overwhelming me.