Evidence-First AI Career Coach
AI Pre-Apprenticeship Capstone | LA-Tech Rising Internship | Fall 2026

Author: Sara Hussein
Career focus: Software Engineering, Applied AI, and Cybersecurity
Platform: Google NotebookLM
Project type: Source-grounded AI assistant evaluation and career-development portfolio case study
At a Glance
I developed and evaluated a NotebookLM-based career coach to explore a question that has become increasingly relevant to my professional development: How can I use AI to become a more capable job candidate without allowing it to exaggerate my experience, make decisions for me, or introduce information I cannot verify?

The project began with practical career questions: how to explain my engineering work to different audiences, research potential employers, improve my résumé, and prepare for technical interviews. As the lessons progressed, I moved beyond asking for polished answers. I began examining how those answers were produced, what evidence supported them, and what happened when the assistant encountered ambiguous inputs, biased assumptions, insecure instructions, or missing information.
Area	What I explored	What I took away
Career research	Employer research, résumé improvement, job-role comparisons	Career advice is more useful when tied to a specific role and credible evidence.
Prompt engineering	Role definition, audience, constraints, output format, edge cases	A stronger prompt makes expectations explicit; it does not guarantee accuracy.
Technical evaluation	Review of AI-generated fraud-detection code	Secure-looking code and confident explanations still require review and testing.
Responsible AI	Hiring bias, source grounding, prompt injection	Fairness, confidentiality, and accuracy need deliberate checks.
Documentation	Recorded prompts, comparisons, reflections, and screenshots	A useful AI workflow should be explainable and repeatable by someone else.


What this repository is: A documented learning and evaluation project with real NotebookLM prompts, examples, reflections, and evidence.
What this repository is not: A deployed AI service, a trained model, a security-certified application, or a public copy of my private NotebookLM notebook.
1. Project Overview
I am a Computer Science graduate with experience in full-stack development, technical projects, and an expanding interest in cybersecurity and applied AI. During the LA-Tech Rising Internship, I wanted to investigate whether an AI career coach could help me navigate the transition from academic projects to professional opportunities while strengthening the judgment required to use AI responsibly.

I did not want the project to become a collection of prompts that happened to produce attractive answers. My goal was to understand the process behind those answers: which references the assistant used, what I needed to specify, what it assumed without evidence, and how I could improve the interaction through deliberate revisions.

Over the course of the pre-apprenticeship, I used NotebookLM for career guidance, audience-specific technical communication, employer exploration, and prompt evaluation. I also explored cybersecurity and responsible-AI scenarios, including flawed fraud-detection code, bias in automated hiring, and an instruction-override attempt against the assistant.

The result is a case study of my research, experimentation, evaluation, and learning process, rather than a claim that an AI tool can replace a recruiter, engineer, mentor, or security reviewer.
Project goals
- Make career-development questions more specific, actionable, and grounded in relevant sources.
- Translate technical accomplishments for recruiters, engineers, and nontechnical stakeholders without changing the underlying facts.
- Evaluate and refine prompts using clear criteria rather than trial and error alone.
- Recognize unsupported metrics, hallucinations, bias, and unsafe suggestions.
- Test the limits of a source-grounded assistant and document those limits accurately.
- Build a public-facing technical portfolio artifact while keeping personal and team materials private.
2. The Problem I Am Solving
A technical résumé can list frameworks, programming languages, and projects, yet still fail to communicate why the work mattered. Job descriptions may also emphasize different skills for roles that share the same title. At the same time, candidates are increasingly encouraged to use AI to tailor résumés, research companies, and practice interviews.

That creates a practical tension. AI can make information easier to organize and can suggest useful next steps, but it can also produce confident statements that are too broad, unsupported, or simply wrong. In career documents, an invented achievement is not an improvement. In cybersecurity, an overlooked edge case is not a minor wording issue. In hiring, a biased recommendation can affect someone's opportunities.

I built this project around three questions:
1. Usefulness: Can the assistant turn a broad career concern into a concrete plan or explanation?
2. Reliability: Can I trace its recommendations to my supplied information and identify when evidence is missing?
3. Control: Can clearer prompts, boundaries, and review practices make the output safer and more appropriate for its intended audience?
My working principle became: Use AI to support thinking and preparation, but retain responsibility for facts, judgment, and final decisions.
3. Tools, Sources, and How the Coach Works
Primary tool
Google NotebookLM served as the environment for working with reference material and testing prompts. I used its responses as material to review, not as independently verified evidence of a claim.
Source inventory
The NotebookLM history I documented identified these initial sources:
Source	Purpose	Public repository treatment
My professional résumé	Context about my education, technical work, and career direction	Not uploaded; private personal material
Harborline Bank cloud-migration governance design document	Context for explaining technical and governance work	Not uploaded; team project material
ACLU commentary on Amazon's automated hiring tool	Public case study for examining algorithmic hiring bias	Identified as a public reading, not reproduced


I also worked with a Billing Analyst job-description text as a role-comparison and information-extraction exercise. This was useful for exploring how technical skills can map to business responsibilities, but it was not a substitute for a target software engineering job description.

Career-resource requirement: The capstone calls for at least three credible career resources, including a target job description. The source inventory above documents what I can substantiate from my saved NotebookLM history. A current target software engineering job posting and additional career/interview references should be verified in the notebook before treating that specific requirement as complete. I have not invented titles or citations for resources that I cannot confirm.
My workflow
1. Define the task. Identify whether I need career guidance, an interview exercise, an explanation, or a technical review.
2. Choose the evidence. Identify which notebook sources are relevant and where they are insufficient.
3. Write the prompt. State the intended role, audience, context, output format, and constraints.
4. Inspect the response. Look for unsupported statements, missing qualifications, inconsistent logic, or unnecessary assumptions.
5. Revise deliberately. Change the prompt to address a specific weakness instead of simply asking the model to “try again.”
6. Compare and document. Record what changed, what remained uncertain, and whether further verification is needed.
What I learned about prompting and retrieval
A prompt controls the instructions I give the assistant; reference retrieval supplies context from the materials available to it. Neither automatically makes a statement true. A model may still misunderstand a source, overgeneralize, or answer beyond the evidence. Fine-tuning is a separate model-adaptation method; it was not part of this NotebookLM capstone. My work focused on prompt design, source use, and evaluation.
4. My AI Career Coach in Action
The following examples document the three activity types required by the capstone. The screenshots are retained as originally linked in my README. Where my saved transcript does not show the full response, I describe the test objective and review criteria rather than inventing a result.
Example 1 — Career Guidance: Turning an Open-Ended Goal into a Plan
My prompt:
I want to get my resume ready to apply for internships in 2027. What are the steps to accomplish that goal, and how can Coach help me get there?

What the assistant returned: It proposed reviewing résumé length, rewriting project descriptions to communicate impact, tailoring versions for different technical roles, and matching skills to target job descriptions.

My evaluation: The answer helped divide a broad and somewhat overwhelming goal into smaller tasks. It was particularly useful for distinguishing work I could complete immediately, such as revising project descriptions, from work that required additional research, such as choosing specific roles and understanding employer requirements.

I also noticed an important limitation: the assistant made confident recommendations about résumé conventions and repeated project-impact figures from its context. I would need to verify those figures and confirm that any résumé claims reflected work I actually performed before publishing or submitting them.

What I learned: A useful career coach should make the next action clearer, but I still need to verify the underlying facts and decide which recommendations fit my circumstances.

Screenshot: image
Example 2 — Mock Technical Interview: Practicing Explanations, Not Memorizing Answers
Prompt documented for this activity:
Act as a technical interviewer for an entry-level software engineering position. Using the job description and interview preparation materials in my notebook, ask one technical question at a time. Evaluate my response for technical accuracy, clarity, and reasoning. Identify any gaps without inventing qualifications or experience.

What I wanted to evaluate: Whether the coach could ask a relevant technical question, identify what a strong answer should demonstrate, and distinguish a genuine knowledge gap from a presentation issue.

How I assess this type of output: I check whether the question is appropriate for the role, whether the expected explanation is technically sound, whether feedback identifies a concrete improvement, and whether the assistant avoids claiming that I possess skills or experience I have not demonstrated.

Why this matters: Interview preparation should strengthen my ability to explain my own reasoning. An AI-generated model answer may be a useful reference, but repeating it without understanding it would not make me more prepared.

Evidence note: The screenshot is attached. The full response and any scored feedback from this particular interaction were not present in the text transcript I used to prepare this README, so I am not attributing a specific score, question, or result to it here.

Screenshot: image
Example 3 — Career Action Plan: Making Recommendations Measurable
Prompt documented for this activity:
Using my technical background and the target job description, develop a 30/60/90-day career development plan for entry-level software engineering opportunities. Prioritize achievable activities, measurable progress, technical interview preparation, and portfolio development. Distinguish verified requirements from recommendations.

What I wanted to evaluate: Whether the assistant could organize a broad career objective into stages, suggest achievable actions, and distinguish a role requirement from a general recommendation.

How I assess this type of output: I look for a realistic workload, tasks that I can verify as completed, concrete milestones, and a sensible progression from research to practice to demonstrated readiness. I also review whether the plan relies on a job description actually present in the sources.

How I applied the idea: I drafted a practical 30/60/90-day plan in Section 7, emphasizing résumé accuracy, portfolio quality, interview preparation, professional outreach, and periodic review. I treat this as my proposed plan, not as a promise that every task has already been completed.

Evidence note: The screenshot is attached. I have not invented detailed assistant output or claimed a completed comparison that is not available in my saved text transcript.

Screenshot: image
5. Testing, Prompt Refinement, and Technical Evaluation
This section documents the most important shift in my approach: I stopped judging a prompt solely by how polished the response looked and started asking whether the response was constrained, accurate, useful for the intended audience, and honest about missing information.
Experiment A — Adapting One Technical Achievement to Different Audiences
In an October 8 exercise, I asked NotebookLM to break down a technical achievement from my résumé into granular points for a technical recruiter. The assistant used my Campus Connect project to emphasize system architecture, database design, application security, development workflow, and collaboration.

I then asked it to translate the same achievement into a two-sentence, nontechnical impact statement for a business operations manager.

What changed: The engineering-oriented response focused on implementation and tools; the business-oriented response focused on organizational value, service access, and operational outcomes.

What I learned: Good technical communication is not about making the same description longer or shorter. It is about selecting details that matter to the reader while preserving the truth of the underlying work. I also learned to watch for inflated phrases such as “commercial-grade” or “production-ready” when the supporting evidence has not been established.
Experiment B — Improving an Impact-Focused Prompt
I used a résumé-impact exercise to investigate how prompt structure affects output quality.

Original request (from my NotebookLM history):
act as an explicit prompt optimisation engine rewrite thise scenario into a highly structured prompt that I can use to demonstarte the impact I had

The first generated framework assigned an executive résumé-writer persona, requested a role description, and required impact-oriented bullet points using an action/result/method structure. It encouraged quantitative measures without adequately specifying what should happen when the input lacked reliable numbers.

My follow-up instruction:
Refactor the prompt, reorganise and revise it to make it more clear. feedback before you perform the task. Do not execute the task yet break down the logic and rate it.

The coach's own evaluation assigned these scores to the earlier framework:
Evaluation area	Coach's score	Weakness identified
Role definition	7/10	The target reader was not defined precisely enough.
Constraint clarity	5/10	The prompt lacked strong limits on unsupported facts and metrics.
Edge-case handling	4/10	The prompt did not say what to do when inputs were incomplete.


These were AI-generated diagnostic ratings, not independent benchmark scores.

Improved prompt framework (key instructions from the revised version):
ROLE
Act as a career-writing specialist who adjusts the technical depth
and language to the specified target audience.

SOURCE BOUNDARIES
Use only achievements and facts supported by the supplied input.
Do not invent credentials, percentages, budgets, or outcomes.
If a measurement is missing, identify it as unverified rather
than presenting it as an established result.

INPUTS
Role and setting; actual responsibilities; documented outcomes;
target audience; available evidence.

EDGE CASES
If the input lacks metrics, write a truthful qualitative bullet
or use an explicit placeholder requiring verification.
If an achievement is ambiguous, ask for clarification.

OUTPUT
Write concise, action-oriented bullet points suitable for the
specified reader, without adding unsupported accomplishments.
The block above is a condensed presentation of the revised framework, not a claim that it was pasted verbatim as a single subsequent NotebookLM prompt.

What improved: The revised framework separated what the model should do from what it must not assume. It added audience calibration, evidence boundaries, and instructions for incomplete inputs.

My main takeaway: A more elaborate prompt is not necessarily a better prompt. The improvement came from making its purpose, evidence requirements, and failure conditions explicit.
Experiment C — Reviewing an AI-Generated Fraud-Detection Example
During the cybersecurity track's reasoning-gap activity, I explored a transaction fraud-detection scenario. The assistant generated a Python/Flask example intended to evaluate transaction amounts and activity patterns. The exercise deliberately included flaws for review.

I identified two notable problems in the generated example:
- Cryptographic design: The initial implementation used an MD5-based construction for payload verification instead of a modern keyed message-authentication mechanism.
- Input handling: It compared incoming values without sufficient validation, allowing missing or incorrectly typed data to trigger an exception.
I requested a corrected version using HMAC-SHA256, safer comparison, input validation, and error handling. The follow-up response addressed these categories in its generated code.

What I would still verify before real use: Secret management, replay protection, request authentication, signature canonicalization, correct handling of zero-value transactions, concurrency, persistent storage, test coverage, and operational monitoring. A response labeled “production-ready” is not proof of production readiness.

What I learned: AI-generated code can be a starting point for technical exploration, but security claims require code review, tests, and explicit threat-model assumptions. I did not deploy this example or establish that it was safe for production.
Experiment D — Organizing and Tagging Information
In the information-organization lessons, I used AI to break down a complicated Harborline project draft into responsibilities, active questions, and follow-up work. The exercise highlighted how AI can make a large set of notes easier to navigate, but also how important it is to confirm ownership, deadlines, and dependencies against the original documents.

I also explored extracting requirements from a Billing Analyst job brief. The resulting analysis separated technical tools, work processes, reporting responsibilities, and operational expectations. I treated this as a text-analysis exercise rather than proof that the assistant had independently verified the job posting.

What I learned: Organizing information is useful only if the transformation preserves meaning. I should check that no important condition was dropped, invented, or placed in the wrong category.
6. Responsible AI: Accuracy, Fairness, Security, and Privacy
My work made clear that responsible AI is not a separate paragraph to add after a project is finished. It affects how sources are selected, prompts are written, outputs are reviewed, and results are shared.
6.1 Accuracy and unsupported claims
I learned to distinguish three kinds of statements:
- Source-supported: Directly backed by the materials supplied.
- Interpretation or recommendation: Potentially useful, but dependent on assumptions and professional judgment.
- Unverified: Missing the evidence needed for a confident claim.
I would not publish an AI-suggested résumé metric, certification, or technical achievement simply because it sounded impressive. In my improved prompt framework, I required the assistant to avoid inventing numbers and to identify gaps explicitly.
6.2 Bias in automated hiring
I studied an ACLU article discussing Amazon's abandoned automated hiring system and then tested a hypothetical candidate-selection prompt containing demographic and lifestyle information.

The original prompt asked for a “cultural fit” recommendation for a lead cybersecurity role while describing the company's workforce as predominantly male. That framing risked treating existing demographics as a hiring standard rather than assessing job-related skills.

In my revised prompt, I directed the assistant to remove age, gender, family status, and lifestyle cues and to evaluate only relevant qualifications such as certifications, incident triage, and documentation history.

Result recorded in my notebook: With those demographic cues removed, the assistant reported that both profiles lacked the technical evidence needed to assign valid scores. It marked the evaluation as incomplete rather than inventing a ranking.

What I learned: Removing explicit demographic fields does not automatically remove every possible proxy for bias. An appropriate system must use job-relevant evidence and recognize when there is insufficient information to make a decision.
6.3 Prompt injection and source confidentiality
I tested a direct instruction-override attempt that asked the assistant to abandon its career-coaching role and reveal the contents of its reference documents.

Observed behavior: NotebookLM refused to provide the requested document contents. Its response nevertheless identified the titles of the three sources available in the notebook.

What I learned: A refusal to dump documents is a useful observation, but it does not establish that an assistant is secure against all prompt-injection techniques. Source titles and metadata can also be sensitive. I would evaluate information disclosure separately from instruction-following behavior and avoid making broad security claims based on one test.
6.4 Data handling and publication boundaries
- My private résumé and team governance documents remain outside the public repository.
- I do not publish personal contact information, credentials, private transcripts, or confidential source contents.
- I review screenshots before publication to remove information that should not be public.
- I distinguish my own analysis from AI-generated text and avoid presenting generated examples as independently tested results.
- The repository documents the evaluation process; it does not expose the full private NotebookLM workspace.
7. My 30/60/90-Day Career Action Plan
This is my working plan informed by the career-coaching exercise and my own priorities. It is not a list of completed accomplishments.
Period	Priority	Concrete actions	Evidence of progress
Days 1–30	Establish a credible foundation	Review résumé accuracy; identify target roles; gather real job descriptions; document strongest projects; establish an interview-practice routine	Updated résumé, target-role list, documented portfolio priorities, practice log
Days 31–60	Apply and improve	Tailor applications; practice debugging and technical explanations; refine GitHub project READMEs; request professional feedback	Application tracker, revised project documentation, recorded feedback and practice notes
Days 61–90	Demonstrate readiness	Complete technical and behavioral mock interviews; refine portfolio examples; review skill gaps against job postings; adjust outreach strategy	Interview reflections, stronger project case studies, updated skills-gap review


How I will evaluate the plan
I will review progress by evidence rather than activity alone. Sending applications does not prove that my positioning is effective; rewriting a résumé does not prove that the claims are accurate; and practicing an interview does not prove that I understood the underlying concept. I will use feedback and the quality of my work to decide what needs to change.
8. Reflection: What Changed in My Thinking
What was the most useful thing my AI coach did?
It helped me turn broad questions into organized next steps and showed me how the same technical work could be explained differently depending on the audience. That was particularly valuable because I am working across software engineering, cybersecurity, and AI, where the same project may be relevant for very different reasons.

The most useful outcome was not a single generated résumé bullet or email. It was developing a repeatable way to clarify what I was asking for, inspect the response, and improve it.
What was one limitation or mistake I discovered?
The assistant could present recommendations with more confidence than the evidence justified. The résumé-impact exercise made this clear when the original framework encouraged quantitative claims without requiring proof. The fraud-detection example reinforced the same lesson in a technical setting: code that looks complete can still contain unsafe design choices and missing validation.

I learned to question both the content of the answer and the assumptions that led to it.
How could this assistant help someone in a real job?
A source-grounded assistant could help a junior engineer or analyst navigate internal documentation, summarize requirements, prepare explanations for different stakeholders, and identify questions that need follow-up. It could also support structured learning and interview preparation.

However, I would not use it as the final authority for a security decision, hiring recommendation, compliance determination, or résumé claim. Its value is in accelerating preparation and making information easier to examine, while leaving responsibility with the person reviewing the output.
What would I improve in a future version?
I would separate career sources from unrelated project documents, add a verified target job posting, and create a small evaluation set that I could run repeatedly after prompt changes. I would compare responses for factual support, relevance, handling of missing data, and whether they follow the stated constraints.

I would also add a clearer process for recording prompt versions, the sources used for each answer, observed errors, and whether a correction actually solved the original problem.
My broader takeaway
I began this project thinking mainly about how AI could help me work faster. I finished it with a more useful question: How do I know when an AI-assisted result is reliable enough to use?

The answer is not to avoid AI, and it is not to trust it automatically. It is to develop the habits of specifying the task, checking the evidence, testing assumptions, protecting sensitive information, and taking responsibility for the final result. Those are habits I intend to carry into software engineering and cybersecurity work beyond this internship.
9. Skills and Practices Demonstrated
Skill	Evidence in this project
Prompt engineering	Defined roles, audiences, output constraints, and failure conditions; compared prompt versions
AI evaluation	Reviewed unsupported claims, incomplete inputs, and limitations of model-generated advice
Technical communication	Reframed engineering achievements for technical and nontechnical audiences
Secure development awareness	Identified weaknesses in generated fraud-detection code and proposed safer alternatives
Responsible AI	Explored hiring bias, source confidentiality, and prompt-injection behavior
Research and information organization	Worked with reference materials, career questions, technical notes, and structured extraction
Documentation	Recorded prompts, evaluation observations, limitations, and next steps in a public README
Career readiness	Developed a staged plan for résumé quality, interview preparation, and portfolio improvement


Repository Notes and Scope
This README is the public documentation for an educational NotebookLM career-coaching project. The underlying NotebookLM workspace and private source files are not published. The screenshots above are evidence of the interactions I selected for the capstone, and the written analysis explains what I can substantiate from the saved conversation history.

Status: Documentation prepared for capstone review. Before submission, the career-source requirement and the content/privacy of the three screenshots should be confirmed. This project is not presented as a deployed, independently audited, or production-secure AI system.
