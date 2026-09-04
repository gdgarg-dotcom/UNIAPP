# WRITING_STYLE_GUIDE

# Purpose

The Writing Style Guide defines how UniApp writes resumes and cover letters.

It establishes consistent writing standards, formatting rules, document structure, readability, and presentation. It does not define positioning strategy, ATS vocabulary, or runtime workflow.

---

# General Writing Principles

- Write for recruiters first and ATS second.
- Maintain an executive, business-first tone.
- Keep content concise, credible, and evidence-based.
- Prioritize relevance over completeness.
- Never fabricate responsibilities, metrics, technologies, certifications, or achievements.
- Use measurable business outcomes wherever supported.
- Prefer bullets over paragraphs.
- Avoid unnecessary adjectives, buzzwords, and marketing fluff.
- Maintain consistent formatting throughout the document.
- Role-specific, easy to scan, easy to customize, limited to two pages.

---

# Resume Structure

## Resume Length

- Maximum 2 pages.
- ATS-friendly, single-column layout.
- Clean hierarchy with consistent spacing.
- Avoid tables, graphics, icons, text boxes, headers, and footers that may affect ATS parsing.

---

## Resume Section Order

1. Name & Title & "Open to..." line & Contact Information
2. Career Summary
3. Core Skills
4. Career Highlights
5. Leadership Experience
6. Projects (when relevant)
7. Earlier Experience
8. Technology Proficiency
9. Certifications
10. Education

Note: Section names above are the current house style and intentionally differ from generic resume-writing convention (e.g. "Career Summary" not "Executive Summary", "Core Skills" not "Core Expertise", "Career Highlights" not "Executive Highlights", "Technology Proficiency" not "Technical Skills"). Use these exact headings — do not default to more generic/templated naming.

Projects always precedes Earlier Experience — Projects stems directly from the two most recent roles (Leadership Experience), so it stays adjacent to them; Earlier Experience is the deliberately deprioritized section and sits after.

Education and Certifications always sit at the end, in that order (Certifications before Education).

---

## Contact Information

Display at the top of the resume, centered, in this order:

1. Name (bold, navy, largest text on the page)
2. Title/headline line
3. "Open to Relocation | Open to Remote Opportunities" (or GCC-suffixed variant for UAE resumes) — on its own line, bold, above contact details, for visual impact
4. Contact line: Phone | Email | LinkedIn — no city/location, no GitHub (unless the target role is technical/developer-adjacent)

---

## Career Summary

- One consolidated paragraph (not two) — EXCEPTION: the Marketing / Head of Marketing archetype (Marketing.docx and UAE_Marketing.docx) uses two short paragraphs by design — a leadership/positioning paragraph followed by a capabilities paragraph. This is the only archetype permitted to use two paragraphs; all others stay to one.
- Business-first, tailored to the target role.
- Bold the key positioning keywords and terms within the paragraph (skills, credentials, numbers) for visual scanning impact — do not bold entire sentences. This applies via the bold-capable summary helper (e.g. `add_summary_segments` in common.py) — never write the Career Summary as a single unsegmented run of text, or bolding will be silently lost.
- Keep simple and short for impact — avoid stacking multiple qualifying clauses (e.g. do not combine "20 years total" with "15 years dedicated" in the same sentence). State "20 years of experience" only — no sub-tenure stacking in any archetype, including Digital and Paid Media.
- Avoid generic objectives or personal statements.
- For India resumes: no explicit non-India market list (drop APAC/EMEA/Americas mentions from this section).
- For UAE resumes: mention GCC once; drop the full APAC/EMEA/Americas list in favor of "GCC and global markets."

---

## Core Skills

- Use pipe-separated format only.
- Never use bullets.
- Prioritize capabilities based on JD relevance.
- Keep between 12–16 capabilities.
- Draw from digital-first, growth, demand-gen, brand, integrated marketing, paid media, performance, and leadership terms.

Example:

Growth Marketing | Demand Generation | GTM Strategy | Digital Marketing | Paid Media | Marketing Analytics | AI

---

## Career Highlights

Use the heading:

CAREER HIGHLIGHTS

- 6–7 concise bullets.
- Every bullet must carry a quantified metric — no unquantified statements.
- Lead with measurable business impact.
- Prioritize achievements most relevant to the target role.

---

## Leadership Experience

Use the heading:

LEADERSHIP EXPERIENCE

Used for both companies (Keysight Technologies Ltd, Cisco Systems Ltd) regardless of seniority level — this is the current house style, not conditional on role seniority.

### Bullet Guidelines

Keysight Technologies Ltd

- 6 bullets.

Cisco Systems Ltd

- 7–8 bullets. (Cisco carries more evidence given its longer tenure — team leadership, partner marketing, and executive engagement facts typically land here.)

Each bullet should ideally follow:

Action → Business Impact → Metric

Avoid long narrative bullets. When a bullet must combine two related facts (e.g. team size + a program name), keep it to one sentence with a semicolon, not a run-on paragraph.

---

## Projects

Include only when relevant to the target role.

- 3–4 projects.
- Every project must carry a quantified metric and outcome — do not fabricate one if no verified figure exists; note it as pending instead and flag it to the user.
- Objective-focused.
- Keep each project concise.
- Prioritize projects aligned with the JD.

---

## Earlier Experience

Use the heading:

EARLIER EXPERIENCE

Always positioned after Projects, not immediately after Leadership Experience — Projects stays adjacent to the recent roles it stems from; Earlier Experience is the deliberately deprioritized section.

- 2 concise bullets per role (Network18 Media Ltd, Bennett Coleman & Co Ltd).
- Metrics may be included where real, verified figures exist (see CAREER_PROFILE.MD) — this section is deprioritized in emphasis, not stripped of evidence.

---

## Technology Proficiency

Include by default on every resume, organized into labeled sub-rows (e.g. "Paid & Programmatic:", "CRM & Marketing Automation:") — not a flat unlabeled list.

Lead with the row most relevant to the resume's positioning (e.g. Paid Media resumes lead with "Paid & Programmatic"; Demand Generation leads with "Marketing Automation & CRM" and "ABM & Intent Data").

Include only technologies relevant to the target role. Avoid long, undifferentiated technology inventories — group by category instead.

---

## Certifications

Include relevant certifications only.

Avoid outdated or unrelated certifications.

---

## Education

Place at the bottom of the resume.

Keep concise.

---

# Character Guidelines

| Section | Recommended Maximum |
|----------|--------------------:|
| Title/Headline | 130 characters (may wrap to 2 lines; single line preferred where it fits) |
| Career Summary | 550 characters (one consolidated paragraph; up to 750 characters for the Marketing archetype's 2-paragraph exception) |
| Core Skills | 300 characters |
| Career Highlights | 900 characters |
| Leadership Experience — Keysight (6 bullets) | 900 characters |
| Leadership Experience — Cisco (7–8 bullets) | 1,300 characters |
| Projects (3–4 entries) | 700 characters |
| Earlier Experience (both roles combined) | 500 characters |
| Technology Proficiency | 400 characters |
| Certifications | 250 characters |
| Education | 150 characters |

Target total resume size:

Approximately 5,500–7,500 characters to comfortably fit within two pages. Page count (verified via PDF conversion) is the actual hard constraint — this character range is a planning heuristic, not a strict cap. Current resumes typically run 5,900–6,700 characters.

---

# Cover Letter Standards

- Maximum 150–200 words.
- Three concise paragraphs.
- Tailor to the target company and role.
- Focus on business value and role alignment.
- Avoid storytelling and generic enthusiasm.
- Mention relocation or remote preference only when applicable.

---

# ATS Writing Rules

- Integrate keywords naturally.
- Avoid keyword stuffing.
- Prefer complete business phrases over isolated keywords.
- Maintain consistent terminology throughout the document.
- Preserve ATS-friendly formatting.
- Avoid excessive abbreviations unless widely recognized.

---

# Quality Checklist

Before finalizing any resume:

□ Resume verified at exactly 2 pages via PDF conversion (not estimated from character count).

□ Correct section order: Career Summary → Core Skills → Career Highlights → Leadership Experience → Projects → Earlier Experience → Technology Proficiency → Certifications → Education.

□ "Open to..." line present on its own line, above contact details.

□ Contact line has no city and no GitHub (unless technical role).

□ Career Summary is one consolidated paragraph with bolded keywords (two paragraphs only for the Marketing archetype exception).

□ Core Skills uses pipe-separated format, 12–16 items.

□ Every Career Highlights bullet carries a quantified metric.

□ Leadership Experience uses correct company names ("Ltd" on Keysight Technologies and Cisco Systems) and correct current job titles.

□ Every Project carries a quantified metric — or is explicitly flagged as pending, never fabricated.

□ Earlier Experience uses correct company names (Network18 Media Ltd, Bennett Coleman & Co Ltd) and sits after Projects.

□ Technology Proficiency organized into labeled sub-rows, most-relevant row first.

□ Certifications placed before Education.

□ For India resumes: no explicit non-India market list in Career Summary or bullets.

□ For UAE resumes: GCC mentioned once; region lists simplified to "GCC and global markets."

□ ATS keywords naturally integrated.

□ Formatting consistent throughout.

□ No unsupported claims or fabricated information.

□ Resume and cover letter aligned.