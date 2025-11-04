---
layout: project
title: "Final Project"
due: 2025-12-5
duedate: 2025-12-5
permalink: /projects/final
categories: assignment project
---

The final project is worth **15%** of the overall course
grade. Generally, the final project should involve roughly as much
work as the harder course projects: plan for 10-15 days of focused
work, depending on your working style (maybe working a bit each day,
maybe a big sprint and then a few small bursts of debugging).

The goal of the final project is either:

(a) meaningfully extend the course project--starting with your
solution to *project five*--into another project of roughly the same
size / complexity.

or, (b) something of similar complexity, but not relating to the
course compiler. The topic must be relating to compilers in general,
and you need to make a pitch for how you are leveraging the material
we learned in this class.

You should submit a **proposal** via email (kkmicins@syr.edu), which
is due to me by 11/21 (the day after the second midterm). Your
proposal should consists of a few paragraphs, and should answering the
following question:

- What is your final project topic?

- What is the amount of rough time you are budgeting for the various
  tasks of the project? Write a breakdown of the high-level aspects
  you will need to tackle, and make a plan for how to achieve those
  goals.

- How do you measure success? In general, I expect exhaustive
  testing--of the kind that I provided for CIS531 this semester. I
  understand that not every student will construct extremely
  exhaustive test suites in practice, but a few hand-performed tests
  will not cut it: you need to make an argument for how you will
  systematically test and evaluate the correctness of your solution. 

- What codebase will you be extending? If it is the class
  compiler--are you done with project 5 so far (or will you be soon)?


A few example topics include the following:

- Implementing a garbage collection algorithm, and extending the
  compiler to hook in calls to your garbage collector. 

- Extend the language to include several important builtin types,
  including lists, hash tables, strings, and symbols.

- Extend the language with pattern matching, including list patterns,
  Klenne star patterns, variable binding (along with unification),
  literals, and other relevant features.

- Extend the language with objects, either using classes or
  prototypes.

- Implement a static type system (or even program analysis of an
  untyped language), along with runtime tagging, to enable well-typed
  access to vectors. our approach should try to determine the index
  statically (e.g., by constant propagation), and--when
  possible--should optimize the program to elide the check of the
  dynamic tag (or, when possible--the vector length).

- Develop a new syntax for the language, and add a parser. Since this
  is a smaller project, I may ask you to combine it with other things
  (e.g., pattern matching) depending on your skill level.

- Extend the language to support continuations, via compilation to
  CPS. Your implementation should support (at least) call/cc, if not
  other features such as delimited continuations or algebraic effects.

Your project ambition should match your perceived skill. But in
**every** case, you should err on the side of caution. Students often
choose far too ambitious a project idea, hoping to do something truly
transformative. However, transformative work generally doesn't happen
over 10-15 days--it is more important to pick a project which will
allow you to have an exploratory, open-ended experience. The most
important part is that you have the experience of going from a feature
sketch, to implementation, to exhaustive, end-to-end tests that firmly
demonstrate the correctness of the project.

As for deliverables, you will submit the following (due date on course website): 

- All project code and testcases, along with a certification that the
  code actually works for you. Half-broken code may receive a serious
  penalty: it is significantly more important to deliver something
  that _works_, compared to a lot of effort on something that
  _doesn't_ work. Thus, if there is **any** concern that you do not
  have the skill necessary to finish your project, you should choose
  something easier.

- A project report (3-6 pages, PDF) describing your project,
  consisting of the main approach, your experiences, and your
  results. You must have *some* way of quantifying your results in a
  measureable way (tests passed, performance improved, casts
  eliminated, etc.).

- A single slide, which you will email to me in PDF form before the
  last day of class. Each student gets only a *single* slide to
  present, which should serve as a "visual aid." You will talk,
  briefly (several minutes) about the key ideas in your project, and
  you will give an update of the rough status (how it is going, what
  your plans are to turn it in on time, major results, etc.).

Best wishes. Again, remember my key advice:

It is far better to pick something a bit boring (and finish it
completely) than to pick something a bit more ambitious which you
never materialize into working testcases. The point of the project
isn't to push you to do a PhD in compiler design, it is to push you to
complete some end-to-end task, **complete with high-quality test
infrastructure**, arguing that you really nailed the small project you
did accomplish.

Project proposals DUE November 21, 2025

One-page slide DUE before last day of class

Full projects DUE after the end of class (exact end date TBD)

-- Kris Micinski (kkmicins@syr.edu)


