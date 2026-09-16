# AI Usage & Evaluation Methodology

## 5.1 Overall Process

AI is used as a supporting tool rather than an autonomous decision-maker.

`Prompt → AI Output → Human Evaluation → Correction/Refinement → Final Output`

---

## AI-01 — Business Requirements

**Objective:** Generate an initial understanding of requirements for a personal AI/ML portfolio.

**Prompt:** *"Act as a business analyst. I am an AI and Machine Learning graduate building a personal portfolio website. Identify the business objectives, target users, problems the website should solve, desired digital identity, scope, and success criteria. Do not generate code."*

**Evaluation / Decision:** The output was useful for identifying objectives and users but was too generic. It was refined to focus on AI/ML recruiters, practical AI projects, digital identity, and positioning.

---

## AI-02 — Positioning

**Objective:** Develop a professional positioning statement.

**Prompt:** *"Based on an AI and Machine Learning graduate who has experience with machine learning, NLP, computer vision, and a RAG-based graduation project, suggest professional positioning statements for a personal portfolio."*

**Evaluation / Decision:** The selected statement is: *AI & Machine Learning Graduate focused on building practical intelligent solutions.*

---

## AI-03 — PRD Generation

**Objective:** Transform approved business requirements into an engineering artifact.

**Prompt:** *"Convert the following approved business requirements into one Epic containing multiple user stories. Each story should contain concrete tasks and testable acceptance criteria. Ensure every requirement can be traced from the BRD to implementation."*

**Evaluation / Decision:** The result was checked for one Epic, multiple Stories, Tasks, Acceptance Criteria, and traceability. Task IDs were added for GitHub mapping.

---

## AI-04 — User Flow

**Objective:** Design the main recruiter journey.

**Prompt:** *"Create a simple user flow for a recruiter visiting an AI/ML graduate's personal portfolio. The main goal is for the recruiter to understand the candidate, review evidence of skills, and find contact information."*

**Evaluation / Decision:** The flow was evaluated to keep the path short and focused on professional evidence and contact.

---

## AI-05 — Development Assistance

**Objective:** Assist with individual implementation tasks after requirements are approved.

**Prompt:** *"Implement only [specific PRD task] based on the approved requirements. Do not modify unrelated sections."*

**Evaluation / Decision:** Generated code should be reviewed for requirement compliance, correctness, maintainability, responsiveness, and unintended changes.

---

## AI-06 — Debugging

**Objective:** Investigate bugs without blindly generating a complete replacement.

**Prompt:** *"Here is the expected behavior: [behavior]. Here is the actual behavior: [behavior]. Here is the relevant code: [code]. Here is the error/message: [error]. Identify the likely root cause, explain it, and propose a minimal fix. Do not modify unrelated functionality."*

**Evaluation / Decision:** The proposed solution should be understood, intentionally applied, and tested against the original bug.

---

## 5.2 AI Usage Principle

AI-generated output is considered a proposal, not an automatically accepted solution. The final implementation is approved only after human review and testing.
