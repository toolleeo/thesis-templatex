# Progress tracking of the thesis

- Type: Master Thesis
- Student: Family name, Name
- [https://gitlab-rbl.unipv.it/robolab/thesis-templatex](Repository on Gitlab)

# Status

Number | Chapter        | Version | Status  | Responsibility
------ | -------------- | ------- | ------- | --------------
0      | Abstract       | v1      | WRITING | Student
1      | Intro          | v1      | WRITING | Student
2      | SOTA           | v1      | WRITING | Student
3      | Tools          | v1      | WRITING | Student
4      | Implementation | v1      | WRITING | Student
5      | Results        | v1      | WRITING | Student
6      | Conclusions    | v1      | WRITING | Student

# The `status` field

The `status` field can take one of the following values:

- `WRITING` (responsibility: Student): Initial writing contents are required to be completed by the student.
- `REVIEW` (responsibility: Professor): Contents of the chapter are complete; nothing more to add by the student; chapter is ready to be revised or it is already under revision.
- `FIXING` (responsibility: Student): Review was done by the Professor; there are observations and comments to address/fix by the student.
- `FINAL`: The chapter is completed; no more changes are required.

# How to track the progress

1. Until the content is completed, the chapter stays in the `WRITING` state; responsibility to Student.
2. Once the content of the chapter is completed, the status moves to `REVIEW`; responsibility to Professor. IMPORTANT: in `REVIEW` state the Student **MUST NOT EDIT** the chapter until he/she receives a notification from the Professor.
3. Once the revision is done, the Professor changes the status to `FIXING`, increases the version number, and notifies the Student; the Student is required to address the observations/comments; responsibility is of the Student.
4. Once the changes are made by the Student, the chapter returns to status `REVIEW` state by the Student, so that the Professor can check the updates; responsibility to Professor.
5. If the chapter does not need any further change, the Professor moves the chapter in the `FINAL` state; otherwise the state becomes `FIXING` and the process restart from (3).

NOTES:

- Every change of the status must be notified by email or other channel by the responsible.
- During the update stage, each comment must be properly addressed and a short note shall be reported within the Tex file or in an email.
- During the `FIXING`, the student does not delete the comments; this will be done by the Professor once the comment is deemed as fixed.

# Detailed structure

Abstract
- Title: Introduction
- File: `abstract.inc.tex`
- Content: Abstract (see the template for guidelines).

Chapter 1
- Title: Introduction
- File: `chapter_intro.inc.tex`
- Content: Context; goals; organization of the document.

Chapter 2
- Title: State of the art
- File: `chapter_sota.inc.tex`
- Content: References to existing works and papers.

Chapter 3
- Title: Tools and Frameworks
- File: `chapter_tools.inc.tex`
- Content: List of tools and frameworks used in the thesis.

Chapter 4
- Title: Implementation
- File: `chapter_imlementation.inc.tex`
- Content: Description of the implementation; code and its organization.

Chapter 5
- Title: Results
- File: `chapter_results.inc.tex`
- Content: Tables and graphs showing the results.

Chapter 6
- Title: Conclusions
- File: `chapter_conclusions.inc.tex`
- Content: Conclusions and future works.

