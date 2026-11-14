# Case Study: AI-Assisted Résumé Tailoring for a Workforce Management Position

## 1. Project Objective

Evaluate how a custom Google Gemini Gem applies structured prompt instructions to tailor a professional résumé for a specific job opportunity, while maintaining factual accuracy, relevant terminology, and human oversight.

**Target employer:** Devoted Health  
**Target position:** Workforce Management Real Time Analyst  
**AI platform:** Google Gemini Gems  
**Deliverable evaluated:** Two-page tailored résumé  
**Evaluation approach:** Qualitative comparison of the job description, generated résumé, and configured workflow instructions.

This case study documents an actual résumé generated using the custom Gem. Personal contact information and the original application documents are intentionally excluded.

## 2. The Business Problem

Tailoring a résumé to a specific position requires translating an employer's job requirements into accurate descriptions of a candidate's existing experience.

Common challenges include:

- Identifying the most relevant responsibilities and qualifications.
- Aligning terminology without copying job descriptions verbatim.
- Preserving factual accuracy and avoiding invented accomplishments.
- Maintaining consistent formatting and a reasonable document length.
- Producing an application that communicates qualifications clearly to both automated systems and human reviewers.

The objective was to use a repeatable AI workflow to reduce manual rewriting while preserving human control over the final application.

## 3. Workflow Design

The Gem was configured with four stages:

**Stage 1 — Job Analysis and Strategy**

Review the target posting, identify key requirements, compare those requirements against a baseline résumé, examine potential posting warning signs, and propose relevant adjustments.

**Stage 2 — Content Preview and Approval**

Present tailored résumé and cover-letter content for human review before creating final documents.

**Stage 3 — Document Generation**

Generate standardized Word and PDF application materials following user approval, where the platform's tools support file generation.

**Stage 4 — Job Search Support**

Provide relevant job-search links and research assistance after application materials are finalized.

The configuration also includes explicit instructions prohibiting fabricated experience, limiting unsupported technical claims, and keeping the résumé within two pages.

The completed résumé provides evidence of a generated output. This artifact alone does not independently verify execution of every configured workflow stage.

## 4. Job Requirements Analysis

The Devoted Health posting emphasized real-time workforce management for member services, telesales, and outreach operations.

Major responsibilities included:

- Monitoring intraday call volume, average handle time, shrinkage, and staffing performance.
- Managing real-time schedule adherence and operational adjustments.
- Recommending overtime, schedule changes, and resource reallocations.
- Creating standard operating procedures based on forecasted call volumes.
- Preparing reports and communicating operational insights to leadership.
- Collaborating with cross-functional stakeholders.
- Using workforce management systems and spreadsheet-based staffing models.

Additional preferences included Google Sheets experience, strong communication skills, and the ability to work in a fast-moving environment.

## 5. Generated Résumé Evaluation

The Gem produced a two-page résumé with a targeted professional headline, summary, competency sections, technical proficiencies, and detailed work experience.

The following comparison evaluates how the actual generated document reflected the posting.

| Job Requirement | Evidence in Generated Résumé | Assessment |
|---|---|---|
| Real-time queue management | Summary and professional experience emphasized queue operations | Strong alignment |
| Forecasting and capacity planning | Experience bullets highlighted staffing forecasts, shrinkage, and occupancy | Strong alignment |
| Intraday performance monitoring | Schedule adherence, handle times, and trend monitoring were described | Strong alignment |
| Standard operating procedures | SOP development and workforce training were included | Strong alignment |
| Operational reporting | Automated reporting and leadership recommendations were described | Strong alignment |
| Schedule adjustments | Real-time staffing changes and scheduling exceptions were documented | Strong alignment |
| Cross-functional collaboration | Work with supervisors and operations leadership was emphasized | Strong alignment |
| Google Sheets | Listed under technical proficiencies | Included; requires baseline verification |
| Fast-paced environment | Operational incident response was described | Partial alignment |
| Enterprise Technology collaboration | Reporting automation was mentioned, but direct IT partnership was not established | Limited evidence |
| Looker Explore | Not included | Optional qualification not demonstrated |

This comparison assesses visible requirement coverage, not an employer-verified ATS compatibility score.

## 6. Instruction Adherence

Several elements of the generated résumé were consistent with the Gem's configured requirements.

### Role-Specific Language

The summary and experience sections highlighted real-time monitoring, staffing adjustments, forecasting, and service-level management.

### Source-of-Truth Guardrails

The Gem was explicitly instructed not to invent qualifications or accomplishments.

However, compliance with that instruction cannot be fully established from the generated résumé alone. Numerical claims and listed technologies must be checked against the baseline document.

### Technical Skill Restrictions

SQL training appeared under Professional Development rather than being presented as a primary competency, consistent with a specific configuration rule.

### Document Length

The résumé was delivered as a two-page document, meeting the configured maximum length.

## 7. Quality Assurance Findings

Reviewing the actual output identified several opportunities for improvement.

### Finding 1: Incomplete Job Title Alignment

The posting used the title **Workforce Management Real Time Analyst**, while the generated résumé used **Workforce Management Analyst**.

Although the titles are closely related, the workflow could more consistently preserve the employer's exact advertised role title when doing so accurately reflects the application.

### Finding 2: Proofreading Issues

The résumé contained a spacing error in the phrase `tobalance`, along with minor punctuation inconsistencies in the credentials section.

This demonstrates the need for a final proofreading checkpoint before document delivery.

### Finding 3: Unsupported-Claim Verification

Some accomplishment metrics and technical proficiencies require comparison with the verified baseline résumé.

A stronger workflow should explicitly validate each quantitative claim and technical skill before finalization.

### Finding 4: ATS Scoring Limitations

The Gem was designed around an 85% keyword-alignment target.

However, this threshold is a user-defined goal rather than a validated prediction of how an employer's applicant tracking system will evaluate the document.

A more defensible approach would be to calculate a transparent requirement-coverage score using a documented checklist.

### Finding 5: Incomplete Workflow Observability

The final résumé does not establish whether application-platform research, potential ghost-job screening, or all approval checkpoints were successfully performed.

Future evaluations should capture evidence of each completed stage separately.

## 8. Lessons Learned

This case study illustrates several practical lessons in AI workflow development.

**Structured prompts improve consistency.** Clearly defined stages and output requirements help guide generative AI toward repeatable results.

**Guardrails need verification.** Instructions to avoid fabrication are important, but final outputs still require comparison with authoritative source material.

**Human approval remains essential.** Reviewing content before finalization can identify omissions, unsupported claims, and language that does not accurately reflect the candidate.

**Output quality is multidimensional.** A résumé can match many job requirements while still containing formatting mistakes, missing details, or unverified claims.

**Testing should measure observable results.** Documented requirements coverage and proofreading results provide stronger evidence than unsupported claims of ATS scores.

## 9. Recommended Workflow Improvements

Based on this evaluation, future iterations should include:

1. An explicit job-title consistency check.
2. A final spelling, grammar, and spacing validation step.
3. A source-by-source verification check for accomplishments and technical proficiencies.
4. A transparent scoring rubric for job-requirement coverage.
5. A stage-completion checklist documenting which research and review steps were actually performed.

These are recommended enhancements and should not be interpreted as features already implemented.

## 10. Conclusion

The generated résumé demonstrated substantial alignment with the Devoted Health job description, particularly in real-time workforce management, capacity planning, operational reporting, and scheduling.

The evaluation also identified opportunities to strengthen accuracy verification, proofreading, and workflow observability.

The broader value of the project lies in designing a structured AI-assisted process, testing its output against defined requirements, identifying weaknesses, and using those findings to guide further refinement.

---

**Case Study Type:** Real-world AI workflow evaluation  
**Platform:** Google Gemini Gems  
**Evaluation Method:** Qualitative requirements-coverage review  
**Privacy:** Original résumé and personal contact information are not publicly included.

*This independent portfolio project is not affiliated with or endorsed by Devoted Health or Google.*
