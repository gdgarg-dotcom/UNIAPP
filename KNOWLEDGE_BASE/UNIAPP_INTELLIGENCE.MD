# RESUME_INTELLIGENCE_FRAMEWORK

# Purpose

The Resume Intelligence Framework is the decision layer between the Job Description and resume generation.

Its purpose is to intelligently interpret the Job Description, determine resume customization priorities, validate the generated resume, and ensure the final output meets recruiter, ATS, and writing quality standards.

It does not own career facts, positioning strategy, ATS vocabulary, writing standards, or runtime orchestration.

---

# Responsibilities

The Resume Intelligence Framework is responsible for:

- Interpreting Job Descriptions.
- Identifying customization opportunities.
- Applying adaptive resume rules.
- Validating resume quality.
- Scoring the final resume.
- Recommending optimization opportunities.

---

# Knowledge Base Ownership

### CAREER_KNOWLEDGE_BASE.md

Owns factual career information.

---

### POSITIONING_SYSTEM.md

Owns positioning strategy.

---

### ATS_LIBRARY.md

Owns ATS and recruiter vocabulary.

---

### RESUME_WRITING_GUIDE.md

Owns writing standards.

---

### SYSTEM_INSTRUCTIONS_v3.md

Owns runtime execution and workflow orchestration.

---

### RESUME_INTELLIGENCE_FRAMEWORK.md

Owns resume intelligence, adaptive customization, validation, and quality assurance.

---

# JD Intelligence

For every Job Description, identify:

## Position

- Job Title
- Seniority
- Leadership Scope
- Functional Area

---

## Experience

- Minimum Experience
- Preferred Experience
- Domain Experience

---

## Skills

- Required Skills
- Preferred Skills
- Mandatory Technologies
- Preferred Technologies

---

## Business Context

- Industry
- Products
- Customers
- Geographic Scope

---

## Employment Details

- Location
- Work Mode
  - Remote
  - Hybrid
  - Onsite
- Employment Type
- Travel Requirement
- Work Authorization (if specified)

---

# Adaptive Resume Rules

## Job Title

Tailor the Executive Headline and Executive Summary to the advertised role while preserving factual accuracy.

---

## Location

If the advertised location differs from the candidate's current location:

Resume:

Open to Relocation – <Location>

---

## Remote

If the role is remote:

Resume:

Open to Remote Opportunities

Highlight experience working across distributed global teams where supported.

---

## Hybrid

If the role is hybrid:

Resume:

Open to Hybrid Opportunities

---

## Experience

Never modify chronology or years of experience.

Instead:

- Prioritize the most relevant experience.
- Reorder emphasis.
- Increase or reduce detail based on JD relevance.

---

## Required Skills

Prioritize them in:

- Executive Summary
- Core Expertise
- Executive Highlights
- Experience
- Projects

---

## Preferred Skills

Use only when supported by evidence in the Career Knowledge Base.

---

## Projects

Increase or reduce project visibility based on JD relevance.

Include projects only when they strengthen the application.

---

## AI

If AI capabilities are emphasized in the JD:

Increase visibility of AI initiatives, AI projects, AI tools, and AI-enabled business outcomes.

---

## Leadership

For leadership-focused roles:

Increase visibility of:

- Team leadership
- Stakeholder management
- Budget ownership
- Cross-functional leadership
- Regional and global responsibilities

---

# Resume Validation Standards

Every generated resume should satisfy the following:

- Correct positioning selected.
- Resume tailored to the JD.
- Resume limited to two pages.
- Executive Summary within writing guide limits.
- Core Expertise aligned to JD.
- Executive Highlights prioritized correctly.
- Correct experience heading selected.
- Projects included only when relevant.
- Education positioned last.
- ATS keywords naturally integrated.
- Metrics supported by evidence.
- No unsupported claims.
- Resume and cover letter aligned.

---

# Resume QA Scorecard

Evaluate every generated resume.

| Category | Score |
|----------|------:|
| JD Understanding | /10 |
| Positioning Accuracy | /10 |
| Executive Summary | /5 |
| Core Expertise Alignment | /5 |
| Executive Highlights | /10 |
| Experience Relevance | /15 |
| Project Relevance | /5 |
| Business Impact | /10 |
| ATS Keyword Coverage | /10 |
| Writing Quality | /10 |
| Metrics Usage | /5 |
| Resume Structure | /5 |
| Formatting Compliance | /5 |
| Two-page Compliance | /5 |
| Cover Letter Alignment | /5 |

Total Score:

100

---

# Resume QA Report

Display after every resume build or optimization.

Resume Score

Overall Score: XX / 100

Strengths

- …

Opportunities

- …

Recommendations

- …

Status

Ready for Submission

or

Further Optimization Recommended

---

# Optimization Principles

Optimize only when improvements are supported by evidence.

Never optimize by:

- Fabricating achievements
- Fabricating metrics
- Altering chronology
- Altering responsibilities
- Adding unsupported technologies
- Introducing irrelevant keywords

Optimization should improve:

- Relevance
- Readability
- ATS alignment
- Executive positioning
- Business impact

while preserving factual integrity.

---

# Guiding Principle

The Resume Intelligence Framework exists to answer one question:

**"Is this the strongest possible resume that can be produced from the available evidence for this specific Job Description?"**

If the answer is no, identify the gaps and recommend improvements before finalization.