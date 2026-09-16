# PRD — Product Requirements Document / Engineering Artifact

## 2.1 Product Vision

Build a responsive personal portfolio website that positions Habiba Ziedan as an AI & Machine Learning graduate focused on building practical intelligent solutions.

## 2.2 Product Goals

1. Present a clear AI/ML professional identity.
2. Showcase relevant technical skills.
3. Demonstrate practical AI/ML projects.
4. Present education and experience clearly.
5. Make professional contact information accessible.
6. Work across desktop, tablet, and mobile.
7. Be deployed publicly.
8. Be maintained through a GitHub repository.

## 2.3 Non-Goals

- User authentication
- Database
- Admin dashboard
- Blog/CMS
- E-commerce
- Portfolio chatbot
- Complex backend
- User-generated content

## 2.4 EPIC-01 — Build Personal AI/ML Portfolio Website

**Goal:** Create a professional digital platform that communicates Habiba's AI/ML identity and showcases her education, experience, skills, and projects.

---

### STORY-01 — Homepage & Personal Identity

**User Story:** As a visitor, I want to immediately understand who Habiba is and what she specializes in so that I can determine whether her profile is relevant to me.

**Tasks**
- TASK-01-01 — Create homepage structure
- TASK-01-02 — Add name
- TASK-01-03 — Add professional title
- TASK-01-04 — Add AI/ML positioning statement
- TASK-01-05 — Add primary CTA buttons
- TASK-01-06 — Create navigation structure

**Acceptance Criteria**
- Name is visible.
- AI/ML specialization is immediately clear.
- Main sections are accessible.
- CTA buttons work.

---

### STORY-02 — About & Education

**User Story:** As a visitor, I want to understand Habiba's background and education so that I can understand her professional direction.

**Tasks**
- TASK-02-01 — Create About section
- TASK-02-02 — Write professional biography
- TASK-02-03 — Add Computer Science degree
- TASK-02-04 — Add relevant professional interests

**Acceptance Criteria**
- About section is accessible.
- Information is accurate.
- AI/ML direction is clear.

---

### STORY-03 — Technical Skills

**User Story:** As a recruiter, I want to see the candidate's technical skills so that I can evaluate her technical background.

**Tasks**
- TASK-03-01 — Create Skills section
- TASK-03-02 — Categorize skills
- TASK-03-03 — Add AI/ML skills
- TASK-03-04 — Add programming skills
- TASK-03-05 — Add supporting technologies

**Acceptance Criteria**
- Skills are readable.
- Skills are categorized.
- AI/ML skills receive appropriate emphasis.

---

### STORY-04 — Experience

**User Story:** As a recruiter, I want to see relevant experience so that I can understand the candidate's practical exposure.

**Tasks**
- TASK-04-01 — Create Experience section
- TASK-04-02 — Add relevant internships
- TASK-04-03 — Add organizations and dates
- TASK-04-04 — Add responsibilities
- TASK-04-05 — Review experience accuracy

**Acceptance Criteria**
- Experience is clearly presented.
- Dates and organizations are visible.
- Descriptions accurately represent the experience.

---

### STORY-05 — AI/ML Projects

**User Story:** As a recruiter, I want to explore the candidate's AI/ML projects so that I can evaluate practical technical ability.

**Tasks**
- TASK-05-01 — Create Projects section
- TASK-05-02 — Add Dalil project
- TASK-05-03 — Add ML project
- TASK-05-04 — Add NLP project
- TASK-05-05 — Add Computer Vision project
- TASK-05-06 — Add technologies for each project
- TASK-05-07 — Write project descriptions
- TASK-05-08 — Add GitHub/demo links

**Acceptance Criteria**
- Projects are clearly separated.
- Each project explains the problem and solution.
- Technologies are identified.
- Relevant links work.
- Dalil demonstrates practical RAG/AI experience.

---

### STORY-06 — Contact & Professional Links

**User Story:** As a recruiter, I want to easily contact Habiba and access her professional profiles.

**Tasks**
- TASK-06-01 — Create Contact section
- TASK-06-02 — Add email
- TASK-06-03 — Add LinkedIn
- TASK-06-04 — Add GitHub
- TASK-06-05 — Add CV

**Acceptance Criteria**
- Contact information is easy to find.
- Email is correct.
- Links work.
- CV can be accessed.

---

### STORY-07 — Responsive Experience

**User Story:** As a visitor, I want to use the website on different devices so that the portfolio remains accessible.

**Tasks**
- TASK-07-01 — Implement responsive layout
- TASK-07-02 — Test desktop
- TASK-07-03 — Test tablet
- TASK-07-04 — Test mobile
- TASK-07-05 — Test mobile navigation
- TASK-07-06 — Check readability

**Acceptance Criteria**
- No major layout problems occur on supported screen sizes.
- Navigation works on mobile.
- Content remains readable.

---

### STORY-08 — Testing & Debugging

**User Story:** As the developer, I want to test and debug the website so that the final product works reliably.

**Tasks**
- TASK-08-01 — Test navigation
- TASK-08-02 — Test external links
- TASK-08-03 — Test CV
- TASK-08-04 — Test responsive behavior
- TASK-08-05 — Record bugs
- TASK-08-06 — Investigate root causes
- TASK-08-07 — Implement fixes
- TASK-08-08 — Retest fixes

**Acceptance Criteria**
- Major functionality has been tested.
- Bugs are documented.
- Fixes are retested.
- No known critical bugs remain.

---

### STORY-09 — GitHub & Deployment

**User Story:** As the project owner, I want the development process to be tracked in GitHub so that the relationship between planning and implementation is traceable.

**Tasks**
- TASK-09-01 — Create repository
- TASK-09-02 — Create project structure
- TASK-09-03 — Commit development work
- TASK-09-04 — Map commits to PRD tasks
- TASK-09-05 — Create README
- TASK-09-06 — Deploy website
- TASK-09-07 — Verify deployment

**Acceptance Criteria**
- Repository exists.
- Commit history is meaningful.
- Commits correspond to tasks.
- README exists.
- Website is deployed.
- Deployment is tested.

## 2.5 Definition of Done

1. Implementation is finished.
2. The requirement is satisfied.
3. The result has been tested.
4. Bugs have been addressed.
5. The relevant GitHub commit has been created.

## 2.6 Requirement Traceability

`BRD → Epic → Story → Task → Commit → Test`

**Example:** BR-05 Showcase AI/ML projects → EPIC-01 → STORY-05 AI/ML Projects → TASK-05-02 Add Dalil → `feat: add Dalil AI project` → Test project information and links.

This traceability ensures that implementation remains connected to the original business requirement.
