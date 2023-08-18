---
title: Syllabus
layout: default
--- 

## Programming Languages: Theory and Practice
(*CIS 352* at Syracuse U)

**Note**: parts of this syllabus are subject to change with adequate
notice to students.

An introduction to the design and implementation of programming
languages, focused on operational semantics and interpreters. This
course is heavily project-focused, and a specific emphasis will be
placed upon training in algorithmic thinking and programming strategy.

<b>Instructors:</b>
- Kris Micinski, Asst. Prof at Syracuse ECS
  - Office hours for **programming-related** questions: Wednesday, 2 to 3:30
  - Office hours, 5min questions or less (no debugging help): 30min after class
- Additional TAs to be announced

**Workload**:
  - Asynchronous video lecture units (at most ~80min per week)
    - I assume you have watched the videos before class; but no big
      pressure to understand everything, I will recap during
      class. However, please think of recorded lectures as "the book."
  - 4 projects
  - 2 midterms, no final
  - 1 coding exam
  - This will be a project-focused course. Approximately 3-5 hours per
    week outside of class is expected. I recommend against taking this
    course concurrent with other project-heavy courses.

##### Monday Labs

Monday labs will be run by TAs, and will be used for
programming-related help. You are **not** required to attend Monday
labs. We recommend that you attend Monday labs if you are (a) looking
to be more checked in or (b) looking to get help with a tricky aspect
of the project.

##### Wednesday debugging hours

The professor will be available on Wednesdays, from 2PM to 3:30
PM. Time must be scheduled in either 5, 10, or 15-minute windows. If
you plan to take more than 15 minutes, you may be asked to share time
with other students.

This time is for debugging and to get critique on your code
style. Please be mindful of the collaboration policy below--it is fine
to watch in office hours, but be careful not to use it as a crutch to
develop your own solution. 

I will try to avoid canceling Wednesday debugging
hours. Unfortunately, sometimes I do get busy on Wednesdays with
research-related work or deadlines from other service obligations. In
the event I do need to cancel, please email me and we can set up a
mutually-agreeable time to help you with debugging your code.

##### After-class office hours

The professor will generally make himself available for up to 30
minutes after class. Please avoid asking code related questions at the
end of lecture. This would be a good time to come if you have
content-related questions that can be addressed at the whiteboard or
just via talking, without looking at your code.

## Grading

- **Exams -- 40%**
  - Two midterms. Midterm 1 will be partially after the mid-point, and
   midterm 2 (the "final") will be on the last day of class. Each exam
   is worth 20%. Focus topics will be announced via electronic
   announcement (e.g., on Slack) a day or two before the
   exam. Students are allowed a handwritten, one-sided, US
   letter-sized note sheet.
  - For the both exams, students are allowed to write corrections and
   get back 50% for each problem on which they made a "good faith
   attempt" (some not-insignificat effort towards a solution).

- **In-class Coding Midterm -- 10%**
  - There will be a programming midterm which will be worth 10% of the
    course grade.
  - The coding midterm will be given out near the end of the semester.

- **Projects -- 50%**
  - Five projects, worth 10% each.

- **Bonus Course notes -- up to +4% BONUS**
  - You may turn in course notes for the previous week on each
    subsequent Tuesday, and *only* that Tuesday: no late notes will be
    accepted without an approved accomodation.
  - Each set of notes will receive either +0, +1/6, or +1/3
  - You may earn up to +4% bonus points in this category. That equates
    to 12 perfectly-scoring set of notes.
  - See detailed rules below on course notes

Final grades will be assigned as follows. A small "bump" may be given
in practice, but is not guaranteed--this will be announced at the end
of the course, and not before the final.

 - A  -- 92%
 - A-  -- 90%
 - B+ -- 87%
 - B  -- 84%
 - B- -- 78%
 - C+ -- 74%
 - C  -- 70%
 - C- -- 65%
 - D  -- 60%
 - &lt; D -- &lt; 60%

### Topics

- Functional programming in Racket/Scheme
- Forms and callsites
- Lexical environments and scoping
- Textual reduction semantics
- Structural recursion over inductively-defined lists
- Higher order functions (lambdas) and their properties
- Cons diagrams and boxes
- Quasiquoting and pattern matching
- Tail calls and tail recursion
- Metacircular interpreters
- Natural deduction
- Small-step semantics
- Lambda calculus
- Reduction strategies
- Closure-creating interpreters
- Church numerals, church encoding
- Fixed points and fixed point combinators
- Simply-typed lambda calculus
- Nominal type systems for object orientation

#### Projects

There are *four programming projects* in Racket. Projects will
generally have deadlines of roughly 14 calendar days from their
assignment (though this may be adjusted at times). Projects will be
graded using an *autograder* whose URL is
[https://autograde.org](https://autograde.org). You will receive
credentials for the autograder--if you have not received these by the
second week of class, let the professor know. You are expected to
learn how to use the Git interface to the autograder--the autograder
will technically accept archives, but the instructors strongly prefer
students (and will exclusively help support) using Git.

##### Project Late Policy

- Projects turned in within 72 hours of the deadline will receive a 15
  percent penalty. Projects turned in after 72 hours and until the end
  of the course will receive a 25 percent penalty.

#### Exams (40%)

Exams explicitly measure your ability to materialize solutions to
questions regarding relevant course content in an open-ended
fashion. There will be two midterms both with roughly five questions
each. Questions will be drawn from the learning objectives at the top
of the page.

We realize exams can be stressful. The instructors strongly encourage
students to look into the resources provided by the Barnes Center
(such as extended exam time) if a student thinks their academic
performance is impeded by exam-related stress. We are happy to provide
accomodations for exams, but the instructors request at least 72 hours
notice for each exam so that we may upload the necessary material to
the student testing center.

#### Coding Midterm (10%)

There will be a coding exam, the exam will be in class, but you will
be allowed to access the internet. 

#### Collaboration and the Honor Code

- Projects and exams must be completed alone, without exception.
- Specifically, you must *never* send your code to anyone or allow
  anyone to watch you code, obtain your code, study your code, copy
  your code, etc... We expect you will take reasonable precautious to
  ensure the secrecy of your solutions (e.g., closing your laptop
  before leaving your apartment, if living with other students).
- The autograder employs elaborate cheat-detection techniques,
  including advanced static analyses. These techniques will compare
  your code to other students' submissions, along with students from
  previous semesters. The TAs and instructor will be using these
  features to periodically scan for students who are cheating. Past
  experience shows us that this system is very robust, and has allowed
  us to detect several large clusters of collaborating students; all
  violations ever reported in CIS352 have been upheld by the Syracuse
  University academic integrity council.
- All apparent cases (with credible evidence, as determined by lead
  instructor) of academic dishonesty will be reported, even if the
  student believes they made an honest mistake, or no mistake at
  all. We understand honor violations are stressful processes, and
  thus we strive to only submit academic integrity cases when we
  believe there is clear evidence that the academic integrity board
  should review our findings independently.
- You may collaborate, to any degree you want, with anyone (even
  outside of your group) on in-class or self-study exercises. These
  will be clearly labeled, and are specifically not the course
  projects (which explicitly disallow any form of collaboration).
- While we recommend you discuss the project specification with your
  peers, you should basically never be getting help from peers about
  your code. In particular, you should never be showing another
  student your project code. If you do discuss coding about the
  project with another student, it should only be in the abstract
  (e.g., "can you use operator overloading to implement that?" or "do
  you think it would be sensible to implement this with `map`?") and
  not particularized to your codebase. We understand that this can be
  a challenging line to walk, and thus, we recommend the following
  heuristic: when talking to other students about code, discuss mostly
  the in-class exercises and participation coding exercises.
- You may not "hard code" solutions to tests for projects. The TAs and
  professor will audit all student solutions, and use automated static
  analysis tools, to check for potential hard-coding or other
  practices that circumvent the spirit of our automated
  tests--hard-coding solutions is considered a particularly offensive
  violation and will be immediately reported to the academic integrity
  board.
- Cite all help other than the professor, T.A., and
  required/recommended text (you are allowed to cite those if you
  wish, but it is not required unless you are specifically told
  otherwise). Proper citation is not sufficient to avoid any charge of
  academic dishonesty (e.g., citing another student's work from a
  previous semester), but we will not be particularly focused on
  copyright law and it is permissible to use small snippets of code
  from Stack Overflow (or related sources such as books and notes)
  that do not tangibly complete the substance of the project for you.
  **Again**: You should **never** share code with another
  student. This includes both sending a file to another student and
  "over the shoulder" copying (even when, e.g., variable names are
  changed, etc..). In the eyes of the instructor, these are both
  equally bad. You should never be sitting and helping another along
  by writing their code. By doing so you are both violating the honor
  policy and disadvanting the student you are helping (as they may not
  then properly learn the material).
- If a student is found (by the university academic integrity council)
  to have violated the academic integrity policy, the instructor
  reserves the right to impose any grade-related sanction they see
  fit, up to and including course failure--regardless of the level
  suggested by the academic integrity council.

## Student Support

Syracuse University values diversity and inclusion; we are committed
to a climate of mutual respect and full participation. There may be
aspects of the instruction or design of this course that result in
barriers to your inclusion and full participation in this course. I
invite any student to meet with me to discuss strategies and/or
accommodations (academic adjustments) that may be essential to your
success and to collaborate with the Office of Disability Services
(ODS) in this process.

If you would like to discuss disability-accommodations or register
with ODS, please visit their website at
http://disabilityservices.syr.edu. Please call (315) 443-4498 or email
disabilityservices@syr.edu for more detailed information.

ODS is responsible for coordinating disability-related academic
accommodations and will work with the student to develop an access
plan. Since academic accommodations may require early planning and
generally are not provided retroactively, please contact ODS as soon
as possible to begin this process.

## Accreditation

As part of the regular ABET accreditation process for the
undergraduate program in computer science, we may be collecting
samples of students' work in each of our undergraduate classes.  As a
result, some of your labs/homeworks/exams may be photocopied/scanned
(or electronically copied) to be presented for accreditation at some
later point.

## Student Mental Health

Mental health and overall well-being are significant predictors of
academic success. As such it is essential that during your college
experience you develop the skills and resources effectively to
navigate stress, anxiety, depression and other mental health
concerns. Please familiarize yourself with the range of resources the
Barnes Center provides (https://ese.syr.edu/bewell) and seek out
support for mental health concerns as needed. Counseling services are
available 24/7, 365 days a year, at 315.443.8000.

## Discrimination and Harassment

The University does not discriminate and prohibits harassment or
discrimination related to any protected category including creed,
ethnicity, citizenship, sexual orientation, national origin, sex,
gender, pregnancy, disability, marital status, age, race, color,
veteran status, military status, religion, sexual orientation,
domestic violence status, genetic information, gender identity, gender
expression or perceived gender.

Any complaint of discrimination or harassment related to any of these
protected bases should be reported to Sheila Johnson-Willis, the
University's Chief Equal Opportunity & Title IX Officer. She is
responsible for coordinating compliance efforts under various laws
including Titles VI, VII, IX and Section 504 of the Rehabilitation
Act. She can be contacted at Equal Opportunity, Inclusion, and
Resolution Services, 005 Steele Hall, Syracuse University, Syracuse,
NY 13244-1120; by email: titleix@syr.edu; or by telephone:
315-443-0211.

If you notice any incidents of harassment or discrimination in class
or related venues (Zulip, other chats with students), however minor,
please email me. You may wish to use an anonymous email service such
as https://anonymousemail.me/. Please feel free to tell me as much as
you feel comfortable.  As a notice: I am a mandatory Title IX reporter
and thus am legally-compelled to report incidents such as sexual
harassment, relationship violence, stalking, etc...

## Slack

Slack is a messaging platform for teams. We'll be using it for most
course management. This is the best place to get in touch with me for
one-off questions, ask for an appointment for office hours,
etc.. Email me if you have not been invited to the course Slack.
