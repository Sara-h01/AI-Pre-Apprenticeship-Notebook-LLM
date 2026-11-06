# AI-Pre-Apprenticeship-Notebook-LLM
# Evidence-First AI Career Coach

### AI Pre-Apprenticeship Capstone | LA-Tech Rising Internship | Fall 2026

**Developed by:** Sara Hussein  
**Career Pathway:** Software Engineering, Applied AI, and Cybersecurity  
**Primary Platform:** Google NotebookLM  
**Focus:** Career Research, Prompt Engineering, AI Evaluation, and Responsible AI

---

## 1. Project Overview

This project documents my development and evaluation of an AI-assisted career coach using Google NotebookLM as part of the LA-Tech Rising Internship's AI Pre-Apprenticeship.

As a Computer Science graduate navigating opportunities across software engineering, cybersecurity, and applied AI, I wanted to explore how AI could support career development without replacing independent research or professional judgment.

Throughout the program, I experimented with adapting technical information for different audiences, researching employers, refining prompts, identifying inaccurate AI-generated recommendations, and evaluating potential security and ethical risks.

Rather than treating the assistant as an authoritative source, I approached it as a tool whose outputs require verification, context, and continuous improvement.

## 2. The Problem I am Solving

Breaking into the technology industry involves more than possessing technical skills. Candidates must understand changing employer expectations, communicate their experience effectively, prepare for interviews, and identify meaningful areas for professional development.

AI tools can simplify these activities, but their responses may contain unsupported claims, fabricated metrics, outdated information, or recommendations that fail to account for individual circumstances.

I wanted to investigate whether a source-grounded AI assistant could make this process more structured while remaining transparent about its limitations.

**Project objectives:**

- Research technical career opportunities and employer expectations.
- Translate technical experience for different professional audiences.
- Improve prompts through structured evaluation and revision.
- Support interview preparation and career planning.
- Identify misleading, biased, or unsupported AI responses.
- Document responsible AI practices and opportunities for improvement.

## 3. How My AI Career Coach Works

### Platform and Research Materials

I used Google NotebookLM to explore how an AI assistant could respond using reference documents and supporting research.

My initial notebook included:

- **Professional résumé:** Private reference material used to provide context about my education, technical skills, and projects.
- **Harborline Cloud Migration Governance Document:** Private project material used to explore technical explanations, governance, and cybersecurity concepts.
- **ACLU article on Amazon's automated hiring system:** A public resource used to examine algorithmic bias in recruitment.

For the final career-coaching evaluation, I am supplementing these materials with a target software engineering job description and public career/interview preparation resources.

Private documents remain outside this public repository.

### My Approach

1. Identify a specific career-related problem.
2. Select relevant reference material.
3. Write a prompt with a defined objective and audience.
4. Examine the assistant's response for clarity, accuracy, and relevance.
5. Identify missing assumptions, unsupported claims, or unclear recommendations.
6. Refine the prompt and compare the resulting output.
7. Document what improved and what still requires independent verification.

## 4. My AI Career Coach in Action

### Example 1: Career Guidance

**Objective:** Understand how to improve my résumé and prepare for technical opportunities.

**Prompt used:**

"I want to get my resume ready to apply for internships in 2027. What are the steps to accomplish that goal, and how can Coach help me get there?"

**What I observed:**

The assistant recommended reviewing résumé length, improving technical project descriptions, preparing role-specific versions, and aligning experience with job requirements.

I found the structured recommendations useful because they converted a broad career goal into smaller actions.

However, I also recognized that some recommendations were overly general and that AI-generated claims about project impact or hiring expectations should not be accepted without supporting evidence.

**Screenshot:** <img width="1559" height="767" alt="image" src="https://github.com/user-attachments/assets/b5c2941b-b723-45d5-a195-169b50e32819" />

### Example 2: Mock Technical Interview

**Objective:** Evaluate whether my coach can help me prepare for a software engineering interview using credible reference materials.

**Planned test:**

"Act as a technical interviewer for an entry-level software engineering position. Using the job description and interview preparation materials in my notebook, ask one technical question at a time. Evaluate my response for technical accuracy, clarity, and reasoning. Identify any gaps without inventing qualifications or experience."

**Evidence to add:** The completed NotebookLM interaction, feedback received, and my reflection on its usefulness.

**Screenshot:** <img width="1559" height="767" alt="image" src="https://github.com/user-attachments/assets/c3843d8b-6905-4586-8b8d-7cb917ba8d4b" />

### Example 3: Career Action Plan

**Objective:** Develop a realistic 30/60/90-day professional development plan.

**Planned test:**

"Using my technical background and the target job description, develop a 30/60/90-day career development plan for entry-level software engineering opportunities. Prioritize achievable activities, measurable progress, technical interview preparation, and portfolio development. Distinguish verified requirements from recommendations."

**Evidence to add:** The completed NotebookLM response and any revisions made to the plan.

**Screenshot:** <img width="1559" height="767" alt="image" src="https://github.com/user-attachments/assets/83b7c80e-706f-448b-a969-c82e4889fd34" />

## 5. Testing and Improving My Assistant

One of my most useful exercises involved refining how the assistant translated professional experience into meaningful résumé achievements.

### Initial Approach

I asked the assistant to rewrite experience using an impact-focused résumé framework.

The original instructions emphasized strong action verbs, quantitative outcomes, and professional presentation.

### Problem Identified

The response demonstrated a limitation: emphasizing numerical impact without sufficient evidence could encourage invented percentages or unsupported performance claims.

I also noticed that the original prompt did not adequately address differences between technical and nontechnical audiences.

### Improved Approach

I revised the prompt to introduce:

- Explicit source-grounding requirements.
- Restrictions against fabricated metrics or credentials.
- Audience-specific language and technical detail.
- Clear output-length and formatting constraints.
- Instructions for handling missing or incomplete information.

### What Changed

The revised prompt provided clearer boundaries for the assistant and made it easier to distinguish documented achievements from information that still needed verification.

This exercise reinforced an important lesson: effective prompt engineering is not simply about producing more persuasive writing. It is about improving the reliability and usefulness of the output.

### Additional Technical Evaluation

During a cybersecurity exercise, I examined an AI-generated fraud-detection implementation containing an outdated hashing approach and inadequate input validation.

The exercise involved identifying weaknesses, requesting corrections, and comparing the initial response with the revised implementation.

The generated corrections still required further review before any production use. This highlighted the importance of validating AI-generated code rather than assuming that a polished explanation indicates a secure implementation.

## 6. Responsible AI

Responsible AI was a central consideration throughout my work.

### Accuracy and Hallucinations

I reviewed outputs for unsupported assumptions, questionable metrics, and claims that were not clearly grounded in the available reference material.

My approach was to request clarification, strengthen source constraints, and distinguish verified information from suggestions requiring additional research.

### Bias and Fairness

I explored algorithmic hiring bias using an ACLU case study and an exercise involving two hypothetical cybersecurity candidates.

The initial scenario included age, gender, family circumstances, and lifestyle information that should not determine technical suitability.

I revised the assessment criteria to focus on job-related qualifications, incident response capabilities, and documentation experience.

The exercise demonstrated that an AI system should not produce confident candidate rankings when relevant qualification data is missing.

### AI Security

I tested an instruction-override prompt intended to make the assistant abandon its career-coaching role and disclose source documents.

The assistant refused to provide the requested document contents, although its response identified the source document titles.

This distinction matters: refusing a request does not automatically establish that an assistant has passed every confidentiality or prompt-injection security test.

### Privacy and Data Protection

I do not publish private résumés, internal project documents, personal contact information, credentials, or confidential source material in this repository.

Screenshots must be reviewed and redacted before publication.

The public repository documents my learning process without exposing the private NotebookLM workspace.

## 7. My 30/60/90-Day Career Plan

The following is my proposed career development plan. I will compare it with the assistant-generated plan after completing the final evaluation.

### First 30 Days — Strengthen My Foundation

- Review and update my technical résumé.
- Identify target software engineering and applied AI roles.
- Evaluate job descriptions for recurring technical requirements.
- Organize my GitHub repositories and improve project documentation.
- Establish a consistent technical interview preparation routine.

### Days 31–60 — Apply and Improve

- Practice coding, debugging, and technical explanations.
- Tailor applications to relevant positions.
- Continue developing and documenting portfolio projects.
- Seek professional feedback on my résumé and technical presentation.
- Track applications and identify recurring areas for improvement.

### Days 61–90 — Demonstrate Readiness

- Complete mock technical and behavioral interviews.
- Refine my strongest portfolio projects.
- Review progress against the skills identified in target job descriptions.
- Strengthen professional networking and outreach.
- Reassess my career strategy based on feedback and measurable progress.

## 8. Reflection

### What was the most useful thing my AI coach did?

The most useful aspect was its ability to organize complex information and adapt technical explanations for different audiences.

Working with the same underlying experience and changing the intended reader helped me understand how communication affects the way technical accomplishments are interpreted.

### What was one limitation or mistake I discovered?

One significant limitation was the assistant's tendency to present confident recommendations without always distinguishing verified information from assumptions.

The résumé improvement and cybersecurity exercises showed why source verification, input validation, and explicit constraints are necessary.

### How could this assistant help someone in a real job?

A source-grounded assistant could support professional development, research, documentation, and technical preparation by making reference material easier to navigate.

However, its recommendations would still require human review, particularly in cybersecurity, recruitment, and other contexts where inaccurate decisions can have meaningful consequences.

### What would I improve in a future version?

I would improve the assistant's source-selection process, introduce more systematic evaluation criteria, and develop repeatable tests for factual accuracy and prompt-injection resistance.

I would also create a structured feedback process to track which prompt changes genuinely improve the assistant's performance.

## 9. Skills Demonstrated

- Prompt engineering and iterative refinement
- Source-grounded AI research
- Technical communication and audience adaptation
- AI-generated code review
- Responsible AI and bias awareness
- Prompt-injection testing
- Research organization and critical evaluation
- Career development and technical interview preparation
- GitHub documentation

---

**Project context:** LA-Tech Rising Internship — AI Pre-Apprenticeship, Fall 2026.

**Repository scope:** This repository documents an educational AI career-coaching prototype and its evaluation. It does not contain a deployed AI model, a public NotebookLM knowledge base, or confidential source documents.
