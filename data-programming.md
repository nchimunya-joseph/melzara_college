---
layout: page
title: "Data Programming"
paramlink: /dpp/
---

# Syllabus for CSE 140: Data Programming

# Welcome to CSE 140!

[Lecture List](https://courses.cs.washington.edu/courses/cse140/13wi/calendar/lecturelist.html)
Computational methods permeate the sciences, engineering, and even the humanities. You need a foundational understanding of computation and practical data analysis in order to be successful in science, engineering, business, and other professions.

CSE 140, “Introduction to Data Programming with Applications”, is an introductory programming class that meets this need. You will learn to write small programs in the Python programming language to solve real-world scientific and engineering problems. This will be useful in your classes, your research, and your jobs.
Goals

In CSE 140:

    You will learn computational problem-solving. After the class, if you are given a data source and a problem description, you will be able to write a complete, useful program to solve the problem. You will learn to manage data and algorithmic complexity.
    You will learn Python, a popular and easy-to-use general-purpose programming language that includes excellent libraries for data manipulation, scientific computing, and visualization.
    Assignments will use real datasets from astronomy, biology, linguistics, oceanography, open government, social networks, and more. You will see that it is easy to process, and that doing so yields insight.
    You will learn the joy and power of being able to extract understanding and insight from a mass of data.

Class logistics: times and staff

Lectures: MWF 1:30-2:20, in SAV 260
Sections: Th 12:30-1:20, room MGH 248, or Th 1:30-2:20, room MGH 082A
The calendar lists readings, lecture topics and assignment due dates, with links to the materials.
CSE 190D is an optional credit/no-credit Java seminar associated with CSE 140. It meets Tuesdays 1:30-2:20 in EEB 003. If you take the seminar, then you will complete the quarter knowing how to program in both Python and Java. You will also be more ready to take CSE 143, which requires a knowledge of Java.

Forum (bulletin board): https://catalyst.uw.edu/gopost/board/mernst/30707/.
You may use the forum to ask questions — and to give help to other students. You can optionally subscribe to forum notificatons, so that you receive email whenever a new posting is made on the forum.

Staff:
Instructor: Michael Ernst
TAs: Dun-Yu Hsiao, David Mah, Allison Obourn (for CSE 190d), Isaac Reynolds, Jackson Roberts
Staff email: cse140-staff@cs.washington.edu
If you have questions, please ask us! We want to help you, but we are bad at reading minds.
Please use the forum or the staff email alias: you are likely to get a faster and more authoritative response than if you send email to just one staff member. We will answer as quickly as possible, typically within 24 hours. You can also send anonymous email if you are more comfortable with that, though it does not let us interact with you to better understand and solve your problem.
Office hours are listed on the course calendar. You are also welcome to set up additional meeting times with the course staff. For example, see Michael Ernst's calendar for available times.

When using the staff email alias (but not the forum), it is always a good idea to attach the current version of your code to your message, so that the staff can better understand and reproduce your problem. In every message, always be explicit about the exact thing you did, exactly what the result was, and what you had expected to happen. (For example, cut and paste or attach the exact output, rather than just saying “something went wrong” or describing it vaguely.) This will enable us to help you more effectively.
Resources: books and software

The class uses three books. Two are freely available on the Internet, and the third is $25 at the bookstore.

    The Python Tutorial, available from the Python website. This is good for explaining the nuts and bolts of how Python works.
    Think Python, 2nd edition. Freely available online in HTML and PDF. Also available for purchase as a printed book, but don't buy the first edition.
    This book introduces more conceptual material, motivating computational thinking.
    There is an interactive version of “How to Think Like a Computer Scientist” (the first edition of “Think Python”), which lets you type and run Python code directly while reading the book.
    Introduction to Computation and Programming Using Python is a book about computational problem-solving that only incidentally uses the Python programming language.
    Note: This book is available at the University Bookstore as of 1/11.
    The CSE 140 staff will prepare handouts. Examples are:
        Python Evaluation Rules
        Debugging a Python program
        How do I use the command-line shell?
        How do I interact with files in Python?
        Usage of csv.DictReader
        Python style and example programs

Readings from all three books are assigned for each lecture — see the calendar or the lecture list for details. Please do the readings before the lecture, so that we can make better use of lecture time, answer your questions about the readings, and discuss more advanced topics. There is a brief reading quiz due before lecture (see each quiz for its exact due time), as a Catalyst survey that should take you only a few minutes to complete, if you have done the reading. We expect you to complete nearly all of them and to get a score above 50% on most of the quizzes. After the quiz closes, you can view the quiz again to see your score and the correct answers.

The assigned readings are a great place to get started, but you will also need to use other materials to master Python. We also encourage you to use the many Python resources that are available on the Web. Start with the official Python documentation, whose most useful components include a beginner's guide, a tutorial, a list of all the functions built into Python, and searchable online documentaton.

Software: Please see the CSE 140 computing resources webpage for information about using Python on UW computers or installing Python on your own computer.

Tools: Philip Guo's Python Tutor lets you execute a program line by line, and it draws the variables and data structures that the program creates during execution.

After CSE 140: If you wish to learn more beyond what CSE 140 teaches you, see the self-study suggestions.
Why another programming class?

UW offers a variety of excellent introductory programming classes. No one of them is best for all students. We provide a webpage to help you decide among them. That webpage also contains information about substituting CSE 140 for other UW requirements.

Some characteristics of CSE 140 include:

    By the end of the quarter, students will be able to take a data source and a problem description and independently write a complete, useful program to solve the problem. Students will learn problem-solving and produce end-to-end solutions.
    All assignments will use real scientific data, at realistic scale and complexity.
    We use the Python programming language. Python is simple to learn and to use. Python has excellent libraries for data processing, scientific computing, and numerical methods. Python is widely used across the sciences, engineering, and beyond.
    Students will learn enough programming concepts to permit them to continue to more advanced computer science classes such as CSE 143, if desired. However, students will be independent enough not to need that for simple day-to-day data analysis and manipulation.

Why Python?

Many programming languages and computational tools exist to help you analyze data. These include Excel, MATLAB, R, C/C++, Java, and others. Python is a particularly good choice. It is a complete programming language. It is simple to learn and easy to write and read. You can get started with it right away. It comes with excellent libraries that will simplify your programs.
Topics

The Goals section described the high-level goals of the class. Its real objective is to teach you basic problem analysis and computational thinking, and to enable you to apply them in practice to extract meaning from a dataset. Doing so requires you to logically organize data; to design algorithms; to formulate them in a way that computers can execute; to test, identify problems, and find solutions; and to communicate the results.

At a lower level, here are the topics that the class teaches to help you achieve the course's goals. The calendar and the lecture list show the specific order of topics during the term.

Python concepts:
    Expressions, values, types, variables, programs & algorithms, control flow, file I/O, the Python execution model
Data structures:
    List, set, dictionary (mapping), tuple, graph (from a third-party library)
    List slicing (sublist), list comprehension (shorthand for a loop)
    Mutable and immutable data structures
    Distinction between identity and (abstract) value
Functions:
    Procedural abstraction, functions as values, recursion, function design methodology
Data abstraction (introduction only, no in-depth coverage):
    Modules, objects
Testing and debugging:
    Test design, coverage, & adequacy
    Debugging strategies: divide & conquer, the scientific method
Speed of algorithms
Statistical hypothesis testing
Visualization (graphing/plotting results)
Program decomposition

Assignments and grading

Assignments are available from the calendar and also, redundantly, on a separate homework webpage.

Assignment submission forms are linked to on their respective specification documents.

Your grade is determined by:

    Assignments 60%
    Exams 30%
    Participation 10%

You will complete one programming assignment each week. There are often some written questions on each assignment as well. In addition to the weekly assignments, there are often finger exercises that you are required do do before lecture, to prime you for the lecture and prompt questions.

We urge you in the strongest possible terms to get started on your assignments early. This approach will take you much less time overall than if you try to do all the work at once at the last minute. An efficient approach is to start work, then take a break when needed. This lets your subconscious continue to work on the problem, or enables you to return to it with a fresh perspective and renewed energy. Furthermore, you will be able to ask for and receive help.

The exam grade will be determined by:

    periodic, short, in-class, closed-book diagnostic quizzes. These are not necessarily announced in advance.
    one or two written, in-class, closed-book exams

You will complete a brief reading quiz before every day of lecture as a Catalyst survey. See the calendar or the lecture list for details.

Your participation grade includes instructor discretion, particularly if the course staff feels your grades do not accurately reflect your true understanding of the material. If the course staff does not know who you are, this will not reflect well on your participation grade.
Grading on a “curve”

Grading for this class is not curved in the sense that the average is set at (say) 3.0 and half of the class must receive a grade lower than that. If everyone does well and shows mastery of the material, everyone can receive an A. If no one does well (this is unlikely), then everyone can receive a C. Furthermore, your grade is not affected by someone else dropping the class — whether that person was doing better or worse than you.

Grading for this class is curved in the sense that we do not have a pre-defined mapping from homework and exam scores to a final GPA. There is no pre-determined score (e.g., 90% of all possible points) that earns a 4.0 or a 3.5 or a 2.0 or any other grade. Rather, the staff discusses each student individually. To determine the final grade, we will ask questions like “Did this student master the material?”, and the English descriptions in the Sample UW Grading Guidelines.
Late work

Assignments are generally due at 11pm on Thursdays.

Each student is permitted 4 late days to use during the quarter. Each late day permits you to submit an assignment up to 24 hours late. You may use up to 2 late days per assignment. Each late day is atomic; for example, you cannot use 8 hours of a single late day on each of three assignments.

Important: To submit work late, email cse140-lateday@cs.washington.edu before the due date (either original or extended by a previous late day) and request to use a late day.

It is up to you to allocate your late days in the manner most advantageous to you. You may wish to reserve some in case of unexpected emergencies.

Except as extended in advance by one of your 4 late days, or in case of hospitalization, late work will receive no credit.
If you run out of late days but cannot complete an assignment, turn in what you have for partial credit.
Academic honesty

Integrity is a crucial part of your character and is essential for a successful career. We expect you to demonstrate integrity in CSE 140 and elsewhere. In particular, your assignments must represent your own work and understanding. Academic misconduct such as plagiarism is grounds for failing the class.

The following guidelines apply unless an assignment specifically states otherwise. If you have any questions about acceptable behavior, please ask the course staff. We will be happy to answer your questions!

You are encouraged to talk to your classmates about problem solutions ideas, and you may reuse those ideas, but you may not examine nor reuse any other student's code. You are not allowed to copy code from any source — other students, acquaintances, the Web, etc. (Copying is forbidden via cut-and-paste, via dictation or transcription, via viewing and memorizing, etc.) Your solution may utilize Python libraries that are available in EPD (Enthought Python Distribution). You are encouraged to use books, the Internet, your friends, etc. to get solution ideas, but you may not copy/transcribe/transliterate code: get the idea, close the other resource, and then (after enough time that the idea is in your long-term, not short-term, memory) generate the code based on your own understanding.
Examining other people's code

You may sometimes find it useful to do a web search to find snippets of Python code that performs some particular operation, and paste it into your own programs. This can be an acceptable short-term strategy if it helps you get past a particular roadblock. However, you must later go back, remove the code you did not write yourself, and write the replacement on your own, from scratch. Recall that the class policy is that you must write everything that you turn in. Violating this is academic dishonesty (cheating), which can lead to a variety of negative consequences for you, including failing the class.

It is your responsibility to understand everything that you turn in. We reserve the right to ask you to explain any part of your homework assignment. If you are not able to explain what it means and why you chose it, that is presumed evidence of copying/cheating.

Later, when you are writing your own programs after you complete CSE 140, it's fine to copy others' code if the license permits such use. (Copying one or two lines is usually acceptable regardless of the license.) However, in your future career, please remember two things:

    It is your ethical duty to properly cite the source of any code that you did not write yourself. Give credit where credit is due.
    You should still understand the code that you copied. Otherwise, if and when the code does not work (for example, maybe the original author made an assumption that is not true in your program), you will lose more time debugging than you saved by copying.

The key idea in all this is that we want you to understand. Sometimes you can achieve that by examining and understanding other people's code. But you can never achieve that by copying alone.
Prerequisites

The only prerequisite for the class is high school math.

The class does not assume any previous programming experience. — in fact, if you have already taken any 300-level CSE class, you are not allowed to take CSE 140.

We assume that you are familiar with basic computer usage — you are comfortable running applications, navigating the file system (say, with a tool like Windows Explorer), editing documents with a word processor or text editor, and so forth.

Any student can succeed in CSE 140. But, CSE 140 is not an easy class. To succeed requires you to work diligently, to be organized and systematic, to follow and give instructions precisely, and to ask questions when you are confused. The staff knows you can succeed, and we will help you succeed.
Caveat

All of the information in this document is subject to change throughout the quarter. The course staff will announce any substantive changes.
