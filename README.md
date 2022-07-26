---
date: "Version 1: 25 July, 2022"
---

*_Note:_ Please check the class site in ICON for current assignments*


## Course Information

|                                     | _                                     |
|-------------------------------------|------------------------------------:|
|Instructor:                          |                     Jonathan Templin|
|email:                               |           jonathan-templin@uiowa.edu|
|Course website:                      | https://jonathantemplin.com/bayesian-psychometric-modeling-fall-2022/    |
|Office:                              |               S210B Lindquist Center|
|Office Phone: | 319-335-6429 |
|Classroom:                           |                S302 Lindquist Center|
|Course Meeting Time:                 |               W & F 12:30-13:45|
|Course Office Hours:                 |   W 14:00-16:00 or by appointment|
|                                     |                                     |
 

### Course Objectives, Materials, and Prerequesites

In this course, a unified Bayesian modeling approach will be presented across traditionally separate families of psychometric models. Focusing more directly how to use Bayesian methods in psychometrics, this course will to cover Bayesian theory along with applied treatments of popular psychometric models, including confirmatory factor analysis (CFA), item response theory (IRT), latent class analysis, diagnostic classification models, and Bayesian networks. The focus of this course will be on model building directly in Bayesian programs (i.e., _stan_ and _JAGS_) rather than the use of packages that build such code automatically. 
Time permitting, multilevel models and multilevel psychometric models will be presented. 

As class will begin promptly at 12:30pm each Wednesday and Friday, I ask that you arrive by that time so as to ensure we have enough time to cover all materials.

## Tentative Course Schedule

| Date        | Topic                               | 
|-------------|-------------------------------------|
| 24 Aug      | Course Introduction and Foundational Bayesian Concepts  | 
| 26 Aug      | Introduction to Psychometric Modeling  |
| 31 Aug      | Bayesian Estimation and an introduction to MCMC | 
| 2 Sep       | Bayesian Confirmatory Factor Analysis | 
| 7 Sep       | Introduction to JAGS, Gibbs Sampling, and the Metropolis-Hastings Algorithm  |
| 9 Sep       | Bayesian Confirmatory Factor Analysis | 
| 14 Sep      | MCMC Convergence Diagnostics |  
| 16 Sep      | Bayesian Psychometric Model Fit Assessment |  
| 21 Sep      | Introduction to Stan and the Hamiltonian Monte Carlo Algorithm |
| 23 Sep      | Bayesian Item Response Theory (Binary Item Models) |
| 28 Sep      | Missing Data in MCMC Estimation | 
| 30 Sep      | Model Fit for Categorical Item Models | 
| 5 Oct       | Bayesian Model Comparison using Information Criteria |
| 7 Oct       | Bayesian Item Response Theory (Graded Response Models) |
| 12 Oct      | Class Via Video: Model fit with Graded Item Response Models |
| 14 Oct      | Class Via Video: Model fit with Nominal Item Response Models |
| 19 Oct      | Psychometric Models for Count Data |
| 21 Oct      | Psychometric Models for Censored or Truncated Data |
| 26 Oct      | Latent Class Models |
| 28 Oct      | Diagnostic Classification Models |
| 2 Nov       | Bayesian Structural Equation Models |
| 4 Nov       | Bayesian Networks | 
| 9 Nov       | Bayesian Multilevel Models |
| 11 Nov      | Bayesian Multilevel Models Continued |
| 16 Nov      | Bayesian Multilevel Structural Equation Modeling | 
| 18 Nov      | Bayesian Multilevel Structural Equation Modeling Continued | 
| 23 Nov      | No Class: Fall Break | 
| 25 Nov      | No Class: Fall Break | 
| 30 Nov      | Project Lab Time or Spillover Time |
| 2 Dec       | Project Lab Time or Spillover Time |
| 7 Dec       | Project Presentations |
| 9 Dec       | Project Presentations |

## Course Website/Technology
ICON *will* be used for grades, submission of assignments, disseminating course readings, and course communications. 

ICON *will not* be used for lecture materials. Instead, we will use freely available commercial software for communication and dissemination of course materials. Course lecture slides, lecture examples, video files, assignments, and information are available on the website, https://jonathantemplin.com/bayesian-psychometric-modeling-fall-2022/. Additionally, all course materials will be available using the course Git repository at: https://github.com/jonathantemplin/Bayesian-Psychometric-Modeling-Course-Fall2022.

All lectures will be archived on YouTube (my YouTube channel is https://www.youtube.com/channel/UC6WctsOhVfGW1D9NZUH1xFg). 

### Statistical Computing
The course will use the R statistical package with the R Studio development suite along with a set of R packages (both Bayesian and Non-Bayesian). Additionally, two open-source Bayesian Monte Carlo estimation programs will be used: Just Another Gibbs Sampler (JAGS) and stan. R and R Studio work with JAGS and stan by using a series of downloadable packages which will be used throughout the course. 

R, R Studio, and JAGS are available for free from the following websites:
R: https://www.r-project.org/
R Studio: https://www.rstudio.com/
JAGS: https://mcmc-jags.sourceforge.net
stan: https://mc-stan.org/

The University of Iowa enables access for many of these programs through their research computing resources: 
R Studio Notebooks: https://notebooks.hpc.uiowa.edu/
High Performance Computing: https://hpc.uiowa.edu/

Although this software is available at the University of Iowa, I ask that you install all versions on your local computer as campus resources can be difficult to use for many analyses.

## Homework, Formative Assessments, and Course Project
Student evaluation will be made based three components: (1) homework assignments (60/% of course grade), (2) formative assessments (20/% of course grade), and (3) a course project (20/% of course grade).

### Homework Assignments
There will be a set of homework assignments, the number to be determined. For each assignment, students will have a minimum of two weeks to complete the assignment. Homework assignments will weighted equally with respect to the 60%/ of the course grade accounted for by homework.

All assignments must be completed in R, using R Markdown as a file format, and submitted via ICON. Although students are encouraged to work together on the concepts underlying homework, all answers must be from student’s own work (writing and syntax) and not be copied or paraphrased from anyone else’s answers. So long as a student attains a grade of 50/% or better on a homework assignment, students can revise and resubmit their homework for a better grade. Homework revisions will have a unique deadline for submission. Grammar and writing will be assessed by each homework and will factor into the homework grade.

In order to be able to provide the entire class with prompt feedback, late homework assignments will not be accepted. However, extensions may be granted as needed for extenuating circumstances (e.g., conferences, family obligations) if requested at least three weeks in advance of the due date. Additionally, late homework due to emergencies will be accepted with documentation of the circumstances of the emergency.

### Formative Assessments
Each week, students will take a short formative assessment in ICON. The purpose of the formative assessment is to help students obtain a picture of their understanding of course materials. All genuine attempts (i.e., not haphazard answers) at completion will receive full credit. All formative assessments will be weighted equally with respect to the 20%/ of the course grade.

### Course Project

To help reinforce practice with the material in this course, a course project, as assessed in several parts, is required. You may (and are encouraged to) work collaboratively in groups of up to two on all parts of the project. Ideally, the project would lead to a publishable paper that would be submitted following the semester. All non-presentation parts of the project should be written in R Markdown.

Your project may be on nearly any aspect of Bayesian Psychometric Models, including any data you may have that you wish to analyze. A list of project ideas will also be presented where you can select one.

#### Part 1: Introduction and Research Questions/Hypotheses (Due October 7th)

Part one of the project should provide a brief literature review of the area of research that your project addresses and provide a set of research questions and/or hypotheses you seek to answer with your study. Please keep this section to no more than 10 pages of double-spaced text (not including the title page, figures, tables, or references) that comes from the output of the Markdown document. 

You may wish to preregister your hypotheses: https://www.cos.io/initiatives/prereg. 

#### Part 2: Project Presentation (Presentations During Last Week of Class)

Part two is a project presentation where you present your research findings to the class in a 20-minute presentation. A slide deck is due on December 2nd and you will deliver your during the last week of class.

#### Part 3: Final Project Paper (Due December 14th)

Your final project paper is due on Wednesday, December 14th. It must have your (brief) literature review, research questions/hypotheses, methods, results, and discussion sections. Please limit your paper to 20 pages of double-spaced text (not including the title page, figures, tables, or references) that comes from the output of the R Markdown document. 

### Course Grading System

| Point Total                                    | Letter Grade                                     |
|-------------------------------------|:------------------------------------|
|100 and Above | A+ |
|99-93 | A |
|92-90 | A- |
|89-87 | B+ |
|86-83 | B |
|82-80 | B- |
|79-77 | C+ |
|76-73 | C |
|72-70 | C- |
|69-60 | D |
|Below 60 | F |
|                                     |                                     |



## University of Iowa Syllabus Addenda

### Free Speech and Expression
The University of Iowa supports and upholds the First Amendment protection of freedom of speech and the principles of academic and artistic freedom. We are committed to open inquiry, vigorous debate, and creative expression inside and outside of the classroom. Visit the Free Speech at Iowa website (https://freespeech.uiowa.edu/) for more information on the university’s policies on free speech and academic freedom.

### Accommodations for Students with Disabilities
The University is committed to providing an educational experience that is accessible to all students.  If a student has a diagnosed disability or other disabling condition that may impact the student’s ability to complete the course requirements as stated in the syllabus, the student may seek accommodations through Student Disability Services (SDS). SDS is responsible for making Letters of Accommodation (LOA) available to the student. The student must provide a LOA to the instructor as early in the semester as possible, but requests not made at least two weeks prior to the scheduled activity for which an accommodation is sought may not be accommodated.  The LOA will specify what reasonable course accommodations the student is eligible for and those the instructor should provide. Additional information can be found on the SDS website (https://sds.studentlife.uiowa.edu/students/)

### Absences for Religious Holy Days
The University is prepared to make reasonable accommodations for students whose religious holy days coincide with their classroom assignments, test schedules, and classroom attendance expectations.  Students must notify their instructors in writing of any such Religious Holy Day conflicts or absences within the first few days of the semester or session, and no later than the third week of the semester.  If the conflict or absence will occur within the first three weeks of the semester, the student should notify the instructor as soon as possible.  See Operations Manual 8.2 Absences for Religious Holy Days for additional information (https://opsmanual.uiowa.edu/human-resources/paid-absences/religious-diversity-and-university-calendar). 

### Classroom Expectations 
Students are expected to comply with University policies regarding appropriate classroom behavior as outlined in the Code of Student Life (https://dos.uiowa.edu/policies/code-of-student-life/).  While students have the right to express themselves and participate freely in class, it is expected that students will behave with the same level of courtesy and respect in the virtual class setting (whether asynchronous or synchronous) as they would in an in-person classroom. Failure to follow behavior expectations as outlined in the Code of Student Life may be addressed by the instructor and may also result in discipline under the Code of Student Life policies governing E.5 Disruptive Behavior or E.6 Failure to Comply with University Directive.

### Non-Discrimination Statement 
The University of Iowa prohibits discrimination and harassment on the basis of race, creed, color, religion, national origin, age, sex, pregnancy, disability, genetic information, status as a U.S. veteran, service in the U.S. military, sexual orientation, gender identity, associational preferences, or any other classification that deprives a person of consideration as an individual (https://opsmanual.uiowa.edu/community-policies/human-rights). For more information, contact the Office of Equal Opportunity and Diversity (https://diversity.uiowa.edu/eod, or 319-335-0705, or diversity@uiowa.edu). Students may share their pronouns and chosen/preferred names in MyUI, which is accessible to instructors and advisors.

### Sexual Harassment /Sexual Misconduct and Supportive Measures 
The University of Iowa prohibits all forms of sexual harassment, sexual misconduct, and related retaliation. The Policy on Sexual Harassment and Sexual Misconduct (https://opsmanual.uiowa.edu/community-policies/interim-policy-sexual-harassment-and-sexual-misconduct) governs actions by students, faculty, staff and visitors. Incidents of sexual harassment or sexual misconduct can be reported to the Title IX and Gender Equity Office (https://osmrc.uiowa.edu/report-problem-0) or to the Department of Public Safety (https://police.uiowa.edu/). Students impacted by sexual harassment or sexual misconduct may be eligible for academic supportive measures and can learn more by contacting the Title IX and Gender Equity Office. Information about confidential resources can be found at https://osmrc.uiowa.edu/confidential-resources. Watch the video at https://www.youtube.com/watch?v=Jfjo6v6_b3Y&feature=youtu.be for an explanation of these resources. 

Please note that as of July 25, 2022 (when this draft syllabus was made), the links in this paragraph were inoperable and no other links have been provided. 

### Mental Health 
Students are encouraged to be mindful of their mental health and seek help as a preventive measure or if feeling overwhelmed and/or struggling to meet course expectations. Students are encouraged to talk to their instructor for assistance with specific class-related concerns. For additional support and counseling, students are encouraged to contact University Counseling Service (UCS). Information about UCS, including resources and how to schedule an appointment, can be found at http://counseling.uiowa.edu. Find out more about UI mental health services at: http://mentalhealth.uiowa.edu. 

### Basic Needs and Support for Students 
Student Care & Assistance provides assistance to University of Iowa students experiencing a variety of crisis and emergency situations, including but not limited to medical issues, family emergencies, unexpected challenges, and sourcing basic needs such as food and shelter. More information on the resources related to basic needs can be found at: https://basicneeds.uiowa.edu/resources/. Students are encouraged to contact Student Care & Assistance in the Office of the Dean of Students (Room 135 IMU, dos-assistance@uiowa.edu or 319-335-1162) for support and assistance with resources.

### Sharing of Class Recordings 
Some of the sessions in this course will be recorded or live-streamed. These recordings are the intellectual property of the faculty and they may not be shared or reproduced without the explicit, written consent of the faculty member. Further, students may not share these sessions with those not in the class or upload them to any other online environment. Doing so would be a breach of the Code of Student Conduct, and, in some cases, a violation of state and federal law, including the Federal Education Rights and Privacy Act (FERPA).

