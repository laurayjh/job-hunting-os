# Job Hunting Playbook

Version: v0.1

---

# Mission

Build a structured, transparent, and continuously improving job hunting system.

This playbook is designed to support job applications in Mainland China while remaining adaptable to other regions in the future.

The objective is not only to obtain job offers, but also to establish a repeatable decision-making workflow for long-term career development.

---

# Core Principles

### 1. AI is an advisor, not a decision maker.

AI provides analysis, recommendations, and supporting evidence.
It must never make irreversible decisions on behalf of the user.

---

### 2. Laura makes every final decision.

All application decisions, resume revisions, and career choices require explicit approval from Laura.

---

### 3. Every recommendation must be evidence-based.

Recommendations should always explain:

- Why this recommendation is made.
- Which information supports it.
- What assumptions are being used.

---

### 4. Accuracy is more important than speed.

It is preferable to provide fewer high-quality recommendations than many low-quality ones.

When uncertainty exists, it should be clearly stated instead of hidden.

---

### 5. Keep the workflow simple and maintainable.

The system should minimize unnecessary complexity.

Automation should only be introduced after a workflow has been validated manually.

---

### 6. Every output should be actionable.

Every recommendation should include:

- A concise summary
- Supporting evidence
- Original source(s)
- Direct link(s)
- Recommended next action

The goal is to allow Laura to understand the context and make a decision within a short time without repeating the information gathering process.

### 7. Prioritize clarity over completeness.

The system should present only the most relevant information.

Large amounts of information should be summarized before being presented.

When possible, recommendations should be ranked and limited to a manageable number (e.g., Top 3 or Top 5), allowing Laura to make decisions without information overload.

---

# Design Philosophy

The purpose of this system is not to replace human judgment.

The purpose is to reduce repetitive work while preserving human decision-making.

AI handles information.

Laura makes decisions.


---

# Job Hunting Loop

The job hunting loop is a repeatable, weekly cycle designed to keep momentum, reduce anxiety, and continuously improve the quality of applications and interviews.

---

## Overview

The loop runs on a weekly cadence and consists of five phases:

1. **Explore** — Discover and evaluate new opportunities
2. **Apply** — Prepare and submit targeted applications
3. **Follow-up** — Track progress and maintain relationships
4. **Interview Prep** — Research and practice before each interview
5. **Reflect & Improve** — Review outcomes and update the system

---

## Phase 1: Explore

**Goal:** Identify a shortlist of high-quality opportunities that align with Laura's target role, industry, and values.

**Suggested cadence:** 2–3 times per week

**Steps:**

- Define and maintain a clear target role profile (title, seniority, industry, location, company size).
- Source opportunities from a diverse set of channels: job boards, company career pages, LinkedIn, referrals, and professional communities.
- For each opportunity, perform a quick fit assessment before investing time in an application:
  - Does the role match the target profile?
  - Is the company financially stable and culturally aligned?
  - Is the expected compensation range acceptable?
- Move qualified opportunities into the Application Tracker with status `To Apply`.
- Deprioritize or discard roles that clearly do not fit — do not apply out of anxiety.

**Output:** A weekly shortlist of 3–5 high-fit opportunities ready to enter Phase 2.

---

## Phase 2: Apply

**Goal:** Submit targeted, high-quality applications — not high-volume, low-quality ones.

**Suggested cadence:** 3–5 targeted applications per week during active search periods.

The goal is to maintain consistent momentum without turning the process into mass applications. Quality matters, but the pace should still be realistic for entry-level roles in Mainland China.

**Steps:**

- Research the target company deeply before writing anything:
  - Business model, recent news, products, team structure, and pain points.
  - Review the job description carefully and identify the top 3 requirements the hiring manager cares most about.
- Customize the resume and cover letter for each application:
  - Lead with the most relevant experience and achievements.
  - Mirror the language and framing used in the job description where authentic.
  - Quantify impact wherever possible.
- Have AI review the tailored materials before submission and flag any gaps or weak signals.
- Submit the application and immediately update the tracker with the submission date.
- Record a brief note on why this role was chosen — this will help during interviews and retrospectives.

**Output:** Submitted application with all materials archived in the tracker.

---

## Phase 3: Follow-up

**Goal:** Maintain visibility with recruiters and hiring managers without being intrusive.

**Steps:**

- If no response within 7–10 business days, send a single, polite follow-up message.
- Keep follow-up messages concise: one sentence reaffirming interest, one sentence offering value, and a clear call to action.
- For referrals or warm contacts, update them on the application status and express gratitude.
- Move stale applications (no response after 3+ weeks) to `Closed / No Response` in the tracker.
- Do not send more than two follow-ups per application.

**Output:** Updated tracker statuses and any responses logged.

---

## Phase 4: Interview Prep

**Goal:** Enter every interview well-prepared, confident, and with a clear narrative.

**Steps:**

- As soon as an interview is scheduled, begin a dedicated prep session:
  - Reread the job description and your submitted application materials.
  - Research the interviewer(s) on LinkedIn if names are provided.
  - Prepare 5–7 STAR-format behavioral stories that cover the most common competency areas.
  - Prepare 3–5 specific, informed questions to ask the interviewer.
- For technical or case interviews, identify the most likely question types and practice accordingly.
- Conduct at least one mock interview session (with AI or a peer) before the real interview.
- Prepare a clear, 2-minute self-introduction that is tailored to the company and role.
- After each interview round, immediately write down:
  - What questions were asked.
  - How you answered.
  - What you would improve.

**Output:** Interview prep notes archived per company, and a post-interview debrief entry.

---

## Phase 5: Reflect & Improve

**Goal:** Treat every week as a learning sprint. Use outcomes to continuously improve the system.

**Suggested cadence:** Once per week (e.g., every Sunday evening)

**Weekly reflection questions:**

- How many opportunities were explored? How many passed the fit filter?
- How many applications were submitted? Were they high quality?
- Were any interviews completed? What went well? What needs improvement?
- Is the target role profile still accurate, or does it need adjustment?
- Are there patterns in rejections or non-responses that suggest a systemic issue?
- What is one specific thing to improve next week?

**Continuous improvement actions:**

- Update the resume or cover letter template based on feedback received.
- Refine the target role profile if the market signals a mismatch.
- Add new behavioral stories to the story bank as experiences are uncovered.
- Identify gaps in skills or knowledge and create a lightweight learning plan.
- Update this playbook if a new pattern or best practice is discovered.

**Output:** A brief weekly retrospective note (3–5 bullet points max) stored in the tracker or a dedicated log.

---

## Application Tracker Fields

Each tracked opportunity should include the following fields at minimum:

| Field | Description |
|---|---|
| Company | Company name |
| Role | Job title |
| Source | Where the opportunity was found |
| Date Added | When it was added to the tracker |
| Date Applied | Submission date |
| Status | To Apply / Applied / Interview / Offer / Closed |
| Fit Score | Subjective 1–5 rating of role-to-profile fit |
| Next Action | What needs to happen next and by when |
| Notes | Key context, referrals, red flags, or interview notes |

---

## Anti-patterns to Avoid

- **Spray and pray:** Submitting large numbers of generic applications. This wastes time and signals low intent to recruiters.
- **Passive waiting:** Submitting applications and doing nothing until a response arrives. Keep exploring and improving in parallel.
- **Skipping reflection:** Without retrospectives, the same mistakes repeat and the system stagnates.
- **Over-optimizing before starting:** Perfecting the resume for weeks before applying. Good enough and submitted beats perfect and delayed.
- **Ignoring weak signals:** If multiple interviewers ask the same unexpected question, it is a signal — investigate and adapt.
