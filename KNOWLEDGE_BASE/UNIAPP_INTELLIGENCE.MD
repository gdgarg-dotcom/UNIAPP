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

### CAREER_PROFILE.MD

Owns factual career information.

---

### POSITIONING_GUIDE.md

Owns positioning strategy.

---

### ATS_LIBRARY.MD

Owns ATS and recruiter vocabulary.

---

### WRITING_GUIDE.md

Owns writing standards.

---

### UNIAPP_PROMPT (main system prompt)

Owns runtime execution and workflow orchestration.

---

### UNIAPP_INTELLIGENCE.MD (this file)

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

Tailor the Title/Headline and Career Summary to the advertised role while preserving factual accuracy.

---

## New Role / Career Update Propagation

When a new role, employer change, or updated scope fact is added to CAREER_PROFILE.MD (e.g. a new current employer), any quantified scope fact tied to that role — team size, budget, region, tier structure, or a named scaling/focus phrase (e.g. "focused scaling across North America and APAC") — must be checked against every one of the 7 resume masters, not only the master the update was first drafted on. Reword per archetype's positioning (see POSITIONING_GUIDE.md), but the underlying fact must appear consistently everywhere it is relevant, not only in whichever resume happened to be edited first. Before closing out a career-update task across multiple resumes, diff the new role's bullets across all masters and flag any archetype where the fact is missing rather than assuming it propagated by copy-paste.

---

## Location

Current practice does not dynamically insert the advertised location into the resume. Instead, two fixed regional masters are maintained:

- **India resumes:** "Open to Relocation | Open to Remote Opportunities" — no city, no dynamic location text. Career Summary and role bullets exclude explicit non-India market mentions (drop APAC/EMEA/Americas from narrative text; quantified scope facts like "14+ APJC markets" may remain).
- **UAE/GCC resumes:** "Open to Relocation – GCC | Open to Remote Opportunities – GCC" — GCC mentioned once in the Career Summary; region lists in bullets simplified to "GCC and global markets."

If a JD's location doesn't match either master (e.g. a role in Singapore or Europe), select the closer-fit master (India or UAE) and flag the mismatch to the user rather than inventing a third region variant.

---

## Remote / Hybrid

Both relocation and remote availability are always stated together on the same line — never conditionally shown based on whether the JD is remote, onsite, or hybrid. There is no separate "Open to Hybrid Opportunities" variant in current practice; if a JD is explicitly hybrid, this can be noted in the cover letter instead of altering the resume headline.

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

- Career Summary
- Core Skills
- Career Highlights
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

If AI capabilities are emphasized in the JD, AI-related bullets and tools may be given slightly more visibility within their existing supporting role — but AI must never become the primary positioning or be elevated into a standalone specialization. Candidate does not position as an AI marketing specialist and does not pursue AI-focused roles, regardless of how strongly a JD emphasizes AI. If a JD is primarily an AI-specialist role, flag this to the user as a poor-fit application rather than rebuilding the resume around AI.

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

- Correct positioning selected, per POSITIONING_GUIDE.md.
- Resume tailored to the JD.
- All facts — company names, job titles, dates, metrics — match CAREER_PROFILE.MD exactly.
- Formatting, section order, and per-section rules verified against WRITING_GUIDE.md's Quality Checklist.
- ATS keywords naturally integrated, per ATS_LIBRARY.MD.
- No unsupported claims.
- Resume and cover letter aligned.

---

# Resume QA Scorecard

Evaluate every generated resume.

| Category | Score |
|----------|------:|
| JD Understanding | /10 |
| Positioning Accuracy | /10 |
| Career Summary | /5 |
| Core Skills Alignment | /5 |
| Career Highlights | /10 |
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

# Resume Delivery Format

Deliver the final ATS Match Score in one line alongside the files — no Strengths/Opportunities/Recommendations breakdown, no Status label. Example: "ATS Match Score: 87/100." A full scored breakdown (per the QA Scorecard above) is available only if the user asks for it.

---

# Optimization Principles

Optimize only when improvements are supported by evidence. Never optimize toward a target ATS score by fabricating content — a true, lower score is always correct over an inflated, false one.

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

# Current Resume Matrix (Reference)

The Discover stage should match JDs against these 7 existing masters rather than building from scratch:

**India:** Digital Marketing, Marketing (incl. Brand, Integrated Marketing), Demand Generation (incl. ABM, Growth Marketing), Performance Marketing, Paid Media

**UAE:** Digital Marketing, Marketing (incl. Brand, Integrated Marketing)

See POSITIONING_GUIDE.md for archetype-to-master mapping and consolidation notes.

---

# Guiding Principle

The Resume Intelligence Framework exists to answer one question:

**"Is this the strongest possible resume that can be produced from the available evidence for this specific Job Description?"**

If the answer is no, identify the gaps and recommend improvements before finalization.