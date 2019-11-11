CSCI-400 Programming Languages, Fall 2019
===================================================

## Course Information

- **Lecture** Time/Location: Lecture 8:00am-9:15am Tue Thu, Marquez Hall 226

## Instructor

[Jedidiah McClurg](https://www.jrmcclurg.com/), Assistant Professor of CS

- Contact: mcclurg (at) mines (dot) edu
- Office: Brown Hall 280C
- Office Hours: Tue Thu 9:30am-11am

## Teaching Assistant (TA)

Kepler Novotny

- Contact: knovotny (at) mymail (dot) mines (dot) edu
- Office Hours: Mon Wed 2pm-3pm in Brown Hall 136 (Linux Lab)

## Course Overview

In previous courses, you have examined how to write programs in individual languages such as Java or C.
In this class, we will take a broader view of programming languages, and study the key
concepts and techniques that allow developers to *implement* languages such as Java or C.
This will be a project-based course, and we will develop significant experience in this area,
by learning how to use *functional programming* (specifically the Scala language) to build
(over the course of the semester) a working interpreter for a non-trivial subset of JavaScript.
Ultimately, the course will improve your skill as a programmer, and will deepen your understanding
of how programming languages are designed and implemented.

## Prerequisites

The prerequisite is [CSCI-306 Software Engineering](http://cs-courses.mines.edu/csci306/index.html). As long as you have some programming experience (especially in Java), that should be sufficient.

## Online Community and Communication

**I would appreciate if all students could fill in their profile on Canvas,
including a clear passport-type photo.**
It is extremely difficult to learn names in a class
this size without student photographs.

We will use [Piazza](https://piazza.com/) in the class.
This is a great way to ask questions and communicate with the instructor
and your classmates. Participation on Piazza is **required**,
and will factor into the ``participation'' component of the grade.

The class Piazza link is:
[https://piazza.com/mines/fall2019/csci400/home](https://piazza.com/mines/fall2019/csci400/home)

I will use Piazza to communicate with the class. I also ask that if you have
questions about the course, you first do a quick search on the Piazza page,
to make sure your question has not already been answered there. If not, please
go ahead and post your question on Piazza so that I, the TA, or another student
can answer it publicly. This will help to streamline the communication.

NOTE: if you have a question you do not wish to publicize (e.g., about your
grades, etc.), please create a "private post" on Piazza. Email should only
be used in rare instances where use of Piazza would not be feasible.

## Textbook and Other Reading Materials

NOTE: the following resources are *recommended*, but **NOT REQUIRED**. I will assign
readings from these sources to supplement the lectures, but you are only responsible
for the information presented in lecture.

- *Essentials of Programming Languages (Third Edition)* by Friedman & Wand
- *Programming in Scala (Second Edition)* by Odersky, Spoon, and Venners
- [*The Semantics of Programming Languages* by Matthew Hennessy](https://piazza.com/class_profile/get_resource/jzivdlzovrv5w7/jzjecrz4e345v4)
- *Types and Programming Languages* by Benjamin Pierce

You may be able to obtain PDF versions of these texts for low cost.

## Class Notes

Class notes will be posted 1-2 days after the lecture.

There is a Github organization for the class:

[https://github.com/mines-csci400](https://github.com/mines-csci400)

## Grading

The following percentages show how final grades will be calculated.
I will *not* perform any rounding on the scores (e.g., a score of 92.999 will not be rounded up to 93).
I may or may not curve the overall
grades, depending on how well the class performs overall, however, *I expect each student to
work hard, and not rely on the curve!* 

| item             | percentage    |
| -----------------|---------------|
| labs             | 50%           |
| homeworks        | 10%           |
| exam 1           | 15%           |
| exam 2           | 15%           |
| participation    | 10%           |

Letter grades will be calculated based on the following intervals:

| range    | grade |
|----------|--------------|
| [93,100] | A |
| [90,93)  | A- |
| [87,90)  | B+ |
| [83,87)  | B |
| [80,83)  | B- |
| [77,80)  | C+ |
| [73,77)  | C |
| [70,73)  | C- |
| [67,70)  | D+ |
| [63,67)  | D |
| [60,63)  | D- |
| [0,60)   | F            |

## Attendance

Class attendance is not required, but is highly recommended.
If attendence drops beyond a reasonable threshold, I may
implement a less lenient policy regarding attendance.

## Collaboration

We will use GitHub for collaboration. We will use private team-specific
repositories to submit assignments. More details TBA.

## Respectfulness and Academic Honesty

I expect every student to show respect to me and the rest of the class. This course is preparation
for your future career, so make sure you are behaving with the same level of professionalism that
would be expected at a future full-time position. My general rule of thumb is:
**_informal_ is okay, but _disrespectful_ is not**.

- I prefer to be addressed by my first name ("Jed" or "Jedidiah"), but "Prof. McClurg" or "Dr. McClurg" is also fine.
- It is vital that you do your best to be participate in the class, and communicate with the instructor(s) about any course-related difficulties you are facing.

Plagiarism/cheating is NOT acceptable, and will be met with quick and harsh penalties.
I do not want to see any academic dishonesty in this class!

## Accommodation

The Colorado School of Mines is committed to ensuring the full participation of all students in its programs, including students with disabilities. If you anticipate or experience any barriers to learning in this course, please feel welcome to discuss your concerns with me. Students with disabilities may also wish to contact Disability Support Services (DSS) to discuss options to removing barriers in this course, including how to register and request official accommodations. Please visit their website at [https://disabilities.mines.edu](https://disabilities.mines.edu) for contact and additional information.  If you have already been approved for accommodations through DSS, please meet with me at your earliest convenience so we can discuss your needs in this course.

## Schedule

This schedule is tentative, and is subject to change.

| week | date   | topic                                                                | lecture                                                                                                                                        | reading / notes                                                                                                                                                                                                                                                                                                                       | homework                                                                                                                        | lab                                                                                                                               |
|------|--------|----------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| 1    | Aug 20 | functional programming                                               | intro to functional programming, git, github                                                                                                   | [Git Cheat Sheet](http://www.marcelofossrj.com/reference%20card/2017/07/26/git-reference.html), [lecture00](https://piazza.com/class_profile/get_resource/jzivdlzovrv5w7/jzmbct6b9ya6tc)                                                                                                                                              |                                                                                                                                 |                                                                                                                                   |
|      | Aug 22 | functional programming                                               | Scala / sbt crash course                                                                                                                       | [Scala Exercises](https://www.scala-exercises.org/scala_tutorial), [lecture01](https://piazza.com/class_profile/get_resource/jzivdlzovrv5w7/jztapst9b6m2tg)                                                                                                                                                                           |                                                                                                                                 |                                                                                                                                   |
| 2    | Aug 27 | functional programming                                               | Scala / sbt crash course                                                                                                                       | [Scastie](https://scastie.scala-lang.org), [Programming in Scala](https://www.artima.com/shop/programming_in_scala_3ed), [lecture02](https://piazza.com/class_profile/get_resource/jzivdlzovrv5w7/jzw6f0013nx62v)                                                                                                                     | [hw 1](https://github.com/mines-csci400/assignment-hw01) assigned                                                               |                                                                                                                                   |
|      | Aug 29 | functional programming                                               | inductive definitions, recursion                                                                                                               | [lecture03](https://piazza.com/class_profile/get_resource/jzivdlzovrv5w7/k03e0jlpky8221)                                                                                                                                                                                                                                              | [hw 1](https://github.com/mines-csci400/assignment-hw01) due                                                                    |                                                                                                                                   |
| 3    | Sep 3  | expression evaluation                                                | abstract data types, pattern matching                                                                                                          | [lecture04](https://piazza.com/class_profile/get_resource/jzivdlzovrv5w7/k069iokjl772h1)                                                                                                                                                                                                                                              | [hw 2](https://github.com/mines-csci400/assignment-hw02) assigned                                                               | [lab 1](https://github.com/mines-csci400/assignment-lab1) assigned                                                                |
|      | Sep 5  | expression evaluation                                                | syntax, grammars                                                                                                                               | [Scala Spec](https://scala-lang.org/files/archive/spec/2.12/13-syntax-summary.html), [lecture05](https://piazza.com/class_profile/get_resource/jzivdlzovrv5w7/k0gadhw3bkz4j8)                                                                                                                                                         |                                                                                                                                 |                                                                                                                                   |
| 4    | Sep 10 | *no class ([career day](https://www.mines.edu/careers/career-day/))* |                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                       | [hw 2](https://github.com/mines-csci400/assignment-hw02) due, [hw 3](https://github.com/mines-csci400/assignment-hw03) assigned |                                                                                                                                   |
|      | Sep 12 | expression evaluation                                                | lexing / parsing                                                                                                                               | [Lexing](https://courses.cs.washington.edu/courses/cse401/01sp/02-lexing.pdf), [Parsing](https://courses.cs.washington.edu/courses/cse401/01sp/03-parsing.pdf), [Parser Combinators](https://www.artima.com/pins1ed/combinator-parsing.html), [lecture06](https://piazza.com/class_profile/get_resource/jzivdlzovrv5w7/k0nb12waw3wuk) |                                                                                                                                 |                                                                                                                                   |
| 5    | Sep 17 | expression evaluation                                                | parser combinators                                                                                                                             | [Semantics of PL](https://piazza.com/class_profile/get_resource/jzivdlzovrv5w7/jzjecrz4e345v4) ch 1-2.3                                                                                                                                                                                                                               | [hw 3](https://github.com/mines-csci400/assignment-hw03) due                                                                    |                                                                                                                                   |
|      | Sep 19 | expression evaluation                                                | (work on homework/lab)                                                                                                                         |                                                                                                                                                                                                                                                                                                                                       |                                                                                                                                 | [lab 1](https://github.com/mines-csci400/assignment-lab1) due                                                                     |
| 6    | Sep 24 | simple interpreter                                                   | structural induction                                                                                                                           | [lecture07](https://piazza.com/class_profile/get_resource/jzivdlzovrv5w7/k10c2afcbk9md)                                                                                                                                                                                                                                               | [hw 4](https://github.com/mines-csci400/assignment-hw04) assigned                                                               | [lab 2](https://github.com/mines-csci400/assignment-lab2) assigned                                                                |
|      | Sep 26 | simple interpreter                                                   | operational semantics, JavaScript / node.js crash course                                                                                       | [lecture08](https://piazza.com/class_profile/get_resource/jzivdlzovrv5w7/k1a4s05g7ic5h3)                                                                                                                                                                                                                                              |                                                                                                                                 |                                                                                                                                   |
| 7    | Oct 1  | simple interpreter                                                   | big-step semantics                                                                                                                             | [lecture09](https://piazza.com/class_profile/get_resource/jzivdlzovrv5w7/k1a4s2zldmn5jo)                                                                                                                                                                                                                                              | [hw 4](https://github.com/mines-csci400/assignment-hw04) due, [hw 5](https://github.com/mines-csci400/assignment-hw05) assigned |                                                                                                                                   |
|      | Oct 3  | simple interpreter                                                   | small-step semantics                                                                                                                           | [lecture10](https://piazza.com/class_profile/get_resource/jzivdlzovrv5w7/k1hcakeem9b1h8)                                                                                                                                                                                                                                              |                                                                                                                                 |                                                                                                                                   |
| 8    | Oct 8  | simple interpreter                                                   | (exam review)                                                                                                                                  |                                                                                                                                                                                                                                                                                                                                       | [hw 5](https://github.com/mines-csci400/assignment-hw05) due                                                                    |                                                                                                                                   |
|      | Oct 10 | *no class (inclement weather)*                                       |                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                       |                                                                                                                                 | [lab 2](https://github.com/mines-csci400/assignment-lab2) due                                                                     |
| 9    | Oct 15 | *no class (holiday)*                                                 |                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                       |                                                                                                                                 | [lab 3](https://github.com/mines-csci400/assignment-lab3) assigned                                                                |
|      | Oct 17 | **midterm exam (in class)**                                          |                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                       |                                                                                                                                 |                                                                                                                                   |
| 10   | Oct 22 | higher-order functions                                               | scoping, binding                                                                                                                               | [lecture11](https://piazza.com/class_profile/get_resource/jzivdlzovrv5w7/k241ty7p6yk2fw)                                                                                                                                                                                                                                              |                                                                                                                                 |                                                                                                                                   |
|      | Oct 24 | higher-order functions                                               | scoping, binding                                                                                                                               | [lecture12](https://piazza.com/class_profile/get_resource/jzivdlzovrv5w7/k29luy7ib7w3z)                                                                                                                                                                                                                                               |                                                                                                                                 |                                                                                                                                   |
| 11   | Oct 29 | *no class (inclement weather)*                                       |                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                       |                                                                                                                                 |                                                                                                                                   |
|      | Oct 31 | higher-order functions                                               | recursion                                                                                                                                      | [lecture13](https://piazza.com/class_profile/get_resource/jzivdlzovrv5w7/k2lai4ryj7f5bo)                                                                                                                                                                                                                                              | [hw 6](https://github.com/mines-csci400/assignment-hw06) assigned                                                               |                                                                                                                                   |
| 12   | Nov 5  | higher-order functions                                               | closures                                                                                                                                       | [lecture14](https://piazza.com/class_profile/get_resource/jzivdlzovrv5w7/k2uv2wldxaq5bu)                                                                                                                                                                                                                                              |                                                                                                                                 | [lab 3](https://github.com/mines-csci400/assignment-lab3) due, [lab 4](https://github.com/mines-csci400/assignment-lab4) assigned |
|      | Nov 7  | *guest lecture*                                                      | [Saeid Tizpaz Niari](https://sites.google.com/a/colorado.edu/saeid-tizpaz-niari/) on *software confidentiality (a language-based perspective)* |                                                                                                                                                                                                                                                                                                                                       | [hw 6](https://github.com/mines-csci400/assignment-hw06) due                                                                    |                                                                                                                                   |
| 13   | Nov 12 | *no class*                                                           |                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                       |                                                                                                                                 |                                                                                                                                   |
|      | Nov 14 | type checking                                                        | typing rules                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                       | hw 7 assigned                                                                                                                   |                                                                                                                                   |
| 14   | Nov 19 | type checking                                                        | type inference                                                                                                                                 |                                                                                                                                                                                                                                                                                                                                       |                                                                                                                                 |                                                                                                                                   |
|      | Nov 21 | destructive update                                                   |                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                       | hw 7 due, hw 8 assigned                                                                                                         | [lab 4](https://github.com/mines-csci400/assignment-lab4) due                                                                     |
| 15   | Nov 26 | destructive update                                                   | mutable variables                                                                                                                              |                                                                                                                                                                                                                                                                                                                                       |                                                                                                                                 | lab 5 assigned                                                                                                                    |
|      | Nov 28 | *no class (holiday)*                                                 |                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                       | hw 8 due, hw 9 assigned                                                                                                         |                                                                                                                                   |
| 16   | Dec 3  | destructive update                                                   | references                                                                                                                                     |                                                                                                                                                                                                                                                                                                                                       |                                                                                                                                 |                                                                                                                                   |
|      | Dec 5  | destructive update                                                   |                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                       | hw 9 due                                                                                                                        |                                                                                                                                   |
| 17   | Dec 10 | *no class (final exam week)*                                         |                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                       |                                                                                                                                 |                                                                                                                                   |
|      | Dec 12 | *no class (final exam week)*                                         |                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                       |                                                                                                                                 | lab 5 due                                                                                                                         |

## Lab Topics

There will be 5 labs. Details TBA.

- [Lab 1: learning Scala, expression evaluation](https://github.com/mines-csci400/assignment-lab1)
- [Lab 2: basic JavaScript interpreter](https://github.com/mines-csci400/assignment-lab2)
- [Lab 3: implementing recursive (and higher-order) functions](https://github.com/mines-csci400/assignment-lab3)
- [Lab 4: closures and type checking](https://github.com/mines-csci400/assignment-lab4)
- Lab 5: type casting, mutable variables


## Homework

There will be approximately 1 homework per week, to help encourage you to keep up-to-date
on the course material. Details TBA.

## Acknowledgements

This course is based on [Bor-Yuh Evan Chang](http://www.cs.colorado.edu/~bec/)'s fantastic Programming Languages course.
Special thanks to Evan for his advice and assistance.
