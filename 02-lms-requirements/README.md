# Requirements for an Online School LMS: User Stories, Use Cases, Open Questions

**Task:** A programming school moves homework submission from Telegram to its own LMS. From a short case description, produce requirements: business goals, actors, user stories with acceptance criteria, use cases and a use case diagram.
**What I did:** Wrote 4 measurable business requirements and scope (in / out), a glossary, 7 actors (4 roles + 3 secondary). Wrote 7 user stories prioritized by MoSCoW with 22 acceptance criteria in Given–When–Then format, including negative cases. Detailed 4 use cases (submit homework, appeal a grade, issue certificates, revoke a certificate) with alternative and exception flows. Where the case gave no number, I did not invent one: the gap became one of 21 open questions to the customer, referenced in the criteria as [Qn].
**Tools:** User stories (INVEST, MoSCoW), Gherkin-style acceptance criteria, use cases (Cockburn template), traceability matrix.
**Result:** Every story and use case traces back to a business requirement and to the open questions it depends on; 4 more backlog stories are listed for the next iteration.

Individual work. Documents are in Russian.

## What is inside

| Section | Content |
|---|---|
| 1. Context and goals | 4 business requirements with success measures, scope, glossary |
| 2. Actors | 7 actors and their responsibilities |
| 3. User stories | 7 stories + 4 backlog stories, 22 acceptance criteria |
| 4. Use cases | UC-01 – UC-04 with main, alternative and exception flows |
| 5. Use case diagram | Actors, use cases, include / extend relations |
| 6. Open questions | 21 questions to the customer, each linked to dependent requirements |
| 7. Traceability | Business requirement → user story → use case → open questions |

## Example: US-02, late submission

> As a student, I want to submit my work after the deadline and see the penalty in advance, so that I get partial points instead of zero.
>
> **Given** the soft deadline has passed and the hard deadline has not [Q6], **when** the student clicks "Submit", **then** a warning with the penalty is shown before submission, and the attempt is created only after confirmation.

## Files

| File | Description |
|---|---|
| `lms-requirements.pdf` | Full requirements document, 15 pages (Russian) |
