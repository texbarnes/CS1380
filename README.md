# CSCI 1380 - 01 & 07 Computer Science I

<https://github.com/texbarnes/CS1380>

Section 01 Lecture: MW 12:15 pm - 1:30 pm (2.110)
Section 07 Lecture: MW 1:40 pm - 2:55 pm (2.110)

There's more to Computer Science than programming, but programming is a great way to learn about how computers "think", and how we can use them as tools to solve problems. In this course, we'll learn how to analyze real-world problems, identify the parts of the problem that a computer could solve much more efficiently than we can, and create a program, which is a set of instructions that tell a computer what to do.

We'll focus on what our textbook authors call the Design Recipe, which is a structured process to creating programs. This process will allow us to solve problems in a step-by-step manner, to produce a program that:

a. provably works  
b. can be easily modified to account for future changes  
c. is well documented so that programmers can understand what it's for  

We'll start the course learning the recipe using the programming language Racket, and then transition to C++ later in the term to prove that the recipe is transferrable to any programming language.

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Instructor](#instructor)
	- [Office hours](#office-hours)
- [Objectives](#objectives)
- [Course topics calendar](#course-topics-calendar)
- [Textbook](#textbook)
- [Software](#software)
	- [Racket](#racket)
	- [C++](#c)
- [Grading](#grading)
	- [In-class participation](#in-class-participation)
	- [Reading quizzes](#reading-quizzes)
	- [In-class exercises](#in-class-exercises)
	- [Homework](#homework)
- [Expectations](#expectations)
- [Course policies](#course-policies)
	- [Communication](#communication)
	- [Office hours](#office-hours)
	- [Submissions](#submissions)
	- [Academic honesty](#academic-honesty)
	- [In-class device policy](#in-class-device-policy)
- [UTRGV Policies](#utrgv-policies)
	- [Students with disabilities](#students-with-disabilities)
		- [Pregnancy, Pregnancy-related, and Parenting Accommodations](#pregnancy-pregnancy-related-and-parenting-accommodations)
		- [Student Accessibility Services](#student-accessibility-services)
	- [Mandatory course evaluation period](#mandatory-course-evaluation-period)
	- [Attendance](#attendance)
	- [Scholastic integrity](#scholastic-integrity)
	- [Sexual harassment, discrimination, and violence](#sexual-harassment-discrimination-and-violence)
	- [Course drops](#course-drops)
	- [Student services](#student-services)

<!-- /TOC -->

## Instructor

Dr. Michael C. Barnes
<michael.barnes01@utrgv.edu>

### Office hours

MW 8:00 am - 10:00 am  
EENGR 3.295
If lost, ask for "Lisa"

## Objectives

*(Adapted from CS111 by Sharon Tuttle in Humboldt State University)*

At the end of this course, you should be able to:

- Design, implement, test, and debug programs that use each of the following fundamental programming constructs: basic computation, standard conditional and iterative structures, and the definition of functions.
- Analyze the behavior of simple programs involving fundamental programming constructs.
- Choose appropriate conditional and iterative constructs for a programming task.
- Apply the techniques of structured (functional) decomposition to break a program into smaller pieces -- or, better yet, originally design it using such smaller pieces.
- Describe strategies that are useful in testing and debugging.
- Write clear comments that communicate to the reader what a function expects and what it produces.

## Course topics calendar

[Topics calendar is in a Google Sheet here.](https://docs.google.com/spreadsheets/d/1HtpLxEttdHF2lLJeFtqy-fk4xJKU39BsZCgQt3ENBus/edit?usp=sharing) Note: This is tentative! Expect topics to move around as we progress.

UTRGV important dates:

| Date             | Event                                                        |
|:-----------------|--------------------------------------------------------------|
| August 27        | First day of classes                                         |
| August 30        | Last day to add a course or register for fall 2018           |
| September 3      | Labor Day – NO classes                                       |
| November 14      | Last day to drop a course; will count toward the 6-drop rule |
| November 22 - 24 | Thanksgiving Holiday – NO classes                            |
| December 6       | Study Day – NO classes                                       |
| December 7 - 13  | Final Exams                                                  |
| December 14 – 15 | Commencement Exercises                                       |

## Textbook

["How to Design Programs", Second Edition, Felleisen, Findler, Flatt, and Krishnamurthi.](http://htdp.org/2018-01-06/Book/) Available free online

Optional (you do not need to buy this, and no assignments or readings will come from this text): any C++ reference, take your pick. Recommended are:

- ["Problem Solving with C++", Savitch](https://www.amazon.com/Problem-Solving-10th-Walter-Savitch/dp/0134448286)
- ["C++ Programming: Program Design Including Data Structures", Malik, D.S.](https://www.amazon.com/Programming-Program-Design-Including-Structures/dp/1133526322)

## Software

We'll be using two programming languages during this course – Racket and C++.

### Racket

DrRacket is the programming environment for Racket, which should already be installed in the labs. I recommend you install Racket on your personal computers, available here: <https://download.racket-lang.org>

### C++

We'll use VisualStudio later in the term, when we transition to C++. VS is in the labs as well. Get back to me on getting an educational license for VisualStudio, or whether the [free version](https://visualstudio.microsoft.com/free-developer-offers/) will be good enough.


## Grading

|                        | Percentage |
|------------------------|-----------:|
| In-class participation |        10% |
| Reading quizzes        |        10% |
| In-class exercises     |        10% |
| Homework               |        25% |
| Exam 1                 |      12.5% |
| Exam 2                 |      12.5% |
| Final Exam             |        20% |
| **Total**              |   **100%** |

| Percentage | Final grade |
|------------|-------------|
| 90-100%    |           A |
| 80-89%     |           B |
| 70-79%     |           C |
| 60-69%     |           D |
| 0-59%      |           F |


### In-class participation

[You'll need voting cards: Download them here.](https://github.com/jjlumagbas/csci1380-2018fall-6/blob/c97ae60db6f2558779f25bab0a1f392664a1aad6/lecture/abcde-voting-cards.pdf)

**TL;DR: Research shows that you'll do well in this class if you do the assigned readings, answer the online quizzes, and participate in class discussions.** (Who'd have thought?)

For objectivity sake, attendance will stand for in-class participation ('coz you better be sure I'm going to get you to participate if you're in the room).

We're adopting Peer Instruction, which is an active learning method that's been backed by [a lot of research](https://www.peerinstruction4cs.org/latest-research/). This is how it works ([or you can watch a video instead](https://www.youtube.com/watch?v=Rixx-Qtnt5I)):

1. I send you home with a reading assignment
2. You read the assignment
3. You then answer an [online quiz](#reading-quizzes) before coming in to class
4. We go over the assigned reading through a series of multiple choice questions (maybe 3-5 per class), that will follow the think-pair-share format:

	4a. Think: I reveal the multiple choice question and you think over it for a minute or two (no talking!), and then vote on which option you think is the right answer.  
	4b. Pair: You partner up and try and show your partner why your answer is obviously correct, and theirs is wrong.  
	4c. Share: We all vote again, then discuss the different options with the rest of the class.

Here's why I like this method, and why I think it works: Using peer instruction, we get over the **Curse of Knowledge**, which is a condition your instructor (every instructor) has: we just can't remember what it feels like not to know what we know. As a consequence, we (teachers) sometimes explain things in a way in which someone *who already knows the material* can understand, and get surprised when students don't get it. D'oh! The advantage of having a peer explain the concepts to you (who's just learning the concept themselves) is **peers can use the language of a novice, which you'll likely understand better**.

Further, thinking critically about a question and arguing with someone else about it reinforces the concept in your mind, facilitating deep learning. Like my pal [Bert](https://www.goodreads.com/quotes/19421-if-you-can-t-explain-it-to-a-six-year-old) says: [“If you can't explain it to a six year old, you don't understand it yourself.”](https://www.reddit.com/r/explainlikeimfive/) (Warning: Reddit link, do not click.)

You may be thinking, it we're doing all the work, then what are *you* good for then, Mr. Lumagbas? Well, I'd like to think that I see further ahead than you, so I can see which pitfalls or misconceptions programmers form when first starting out. It's my job to point these out (using questions in class), so that we can avoid (or remedy) them.

I'm happy to receive any feedback on this method, whether or not you think it's working. But let's give it a solid go first, yes?

### Reading quizzes

Reading quizzes for the next lecture will be posted after the current lecture, and submissions will be closed the night before the next lecture.

These are participation points! That means you don't have to get the right answers on the quiz, just convince me that you have read the material.

### In-class exercises

In-class exercises will be done in pairs, except potentially for one group (and only one!) who may work in a group of three. You may keep the same "lab partner" throughout the term.

Pair programming means:

- One monitor, one keyboard, one mouse
- One person "driving", which means taking control of keyboard and mouse
- While the other person "navigating", guiding the driver on what to type
- Pairs change roles regularly

Pair programming does not mean:

- One person does all the work
- While the other person scrolls through Instagram, and checks the clock periodically

Submissions have to be made during class time, except when otherwise noted, so show up to lectures!

### Homework

Homeworks are mini-projects that ask you to integrate different topics discussed in class. These are to be performed outside of class time (as the name implies).

Except for as noted (e.g. Homework 1) homeworks will be done in randomly-assigned pairs, a different pair each time. However, working in the pair is optional (although encouraged!). When the homework is released, we'll assign pairs during lecture time, and you can decide then to work together, or individually.


## Expectations

How to do well in this course:

- **Set a target grade!** Do it this week, week 1. Would you like to ace the course? Just barely pass? Plug some numbers into our [grading scheme](#grading) to see how much work (or how little) you'll actually need to do to hit your target.
- **Block off time weekly** (or daily!) to work on course requirements outside of class time. Budget at least 5 hours per week apart from the lectures to work on readings, homeworks, and studying for exams.
- **Programming is a skill**, like playing an instrument. You can't learn to play a guitar just by reading a book, same with programming. Run the examples from the readings and lectures on your own computer (or in the lab), modify them to see how the program behavior changes. Show up to all the lectures, and work on the assignments!
- **Start working on the homeworks early.** ([I know, this coming from a chronic procrastinator.](https://www.ted.com/talks/tim_urban_inside_the_mind_of_a_master_procrastinator) Do what I say, not what I do.) To this day I underestimate how long a programming problem is going to take, and if I'm going to get stuck on anything (and I always get stuck on *something*).
- **Ask for help.** If something's not clear in lecture, put your hand up. If you get stuck on something with the homeworks, send me an email. Meet me during office hours. It's my job to open opportunities for students to ask help, your job to take them.
- **When short on time, submit partial work** for partial credit. The emphasis of this course is on the process of problem solving, with the correct solution being a side effect of the process followed well. To that end, do what you can, and show me what you did in the time allotted.
- **Don't copy code!** Don't even look at someone else's code. [And especially don't turn in any code that's not your own.](#academic-honesty)
- **Exams will be easy** if you do all of the above.

## Course policies

### Communication

I'll send announcements through Blackboard, please check there every day.

Email me using your UTRGV email, and start the subject line like this "CSCI 1380 - 06"

### Office hours

If you'd like to see me at the office, please email me to set an appointment first. I'm also open to meeting outside of office hours if you set it up through email.

### Submissions

Submissions will be done through Blackboard. No email attachments please! I may give exceptions if there are problems with uploading attachments through Blackboard. In that case, [attach files to an email](#communication) and send it to me **before** the deadline.

Late submissions will not be accepted. You are responsible for starting assignments early, and to account for any [curve ball Murphy throws at you](https://en.wikipedia.org/wiki/Murphy%27s_law), for example: lost files, computer failure, power outages. Plan for the worst.

### Academic honesty

Collaboration is encouraged in this course: most exercises and homeworks will be done in pairs. Outside of those pairs, though, sharing of code is strictly not allowed. Do not send code to another pair, do not copy code off the internet, do not look at solutions of others to get clues on the solution.

If you're stuck on some syntax problems, ask during lecture times, or send me an email.

For any in-class exercise, homework, or exam, a score of 0 will be given to all parties involved in cheating.


### In-class device policy

Mobile phones are allowed only to [access voting cards](#in-class-participation) and use them in class.

I won't allow note-taking using laptops, sorry. [They've been found to be distracting, to you and to others](https://www.scientificamerican.com/article/students-are-better-off-without-a-laptop-in-the-classroom/). Besides, [taking notes with pen and paper makes you smarter](https://www.wsj.com/articles/can-handwriting-make-you-smarter-1459784659).

## UTRGV Policies

### Students with disabilities

Students with a documented disability (physical, psychological, learning, or other disability which affects academic performance) who would like to receive academic accommodations should contact Student Accessibility Services (SAS) as soon as possible to schedule an appointment to initiate services.  Accommodations can be arranged through SAS at any time, but are not retroactive.  Students who suffer a broken bone, severe injury or undergo surgery during the semester are eligible for temporary services.  

#### Pregnancy, Pregnancy-related, and Parenting Accommodations

Title IX of the Education Amendments of 1972 prohibits sex discrimination, which includes discrimination based on pregnancy, marital status, or parental status. Students seeking accommodations related to pregnancy, pregnancy-related condition, or parenting (reasonably immediate postpartum period) are encouraged to contact Student Accessibility Services for additional information and to request accommodations.

#### Student Accessibility Services

Brownsville Campus: Student Accessibility Services is located in Cortez Hall Room 129 and can be contacted by phone at (956) 882-7374 (Voice) or via email at ability@utrgv.edu.

Edinburg Campus: Student Accessibility Services is located in 108 University Center and can be contacted by phone at (956) 665-7005 (Voice), (956) 665-3840 (Fax), or via email at ability@utrgv.edu.

### Mandatory course evaluation period

Students are required to complete an ONLINE evaluation of this course, accessed through your UTRGV account (http://my.utrgv.edu); you will be contacted through email with further instructions.  Students who complete their evaluations will have priority access to their grades.  Online evaluations will be available on or about:

Module 1		October 4 – 10  
Module 2		November 29 – December 5  
Full Fall Semester	November 15 – December 5

### Attendance

Students are expected to attend all scheduled classes and may be dropped from the course for excessive absences.  UTRGV’s attendance policy excuses students from attending class if they are participating in officially sponsored university activities, such as athletics; for observance of religious holy days; or for military service. Students should contact the instructor in advance of the excused absence and arrange to make up missed work or examinations.

### Scholastic integrity

As members of a community dedicated to Honesty, Integrity and Respect, students are reminded that those who engage in scholastic dishonesty are subject to disciplinary penalties, including the possibility of failure in the course and expulsion from the University. Scholastic dishonesty includes but is not limited to: cheating, plagiarism (including self-plagiarism), and collusion; submission for credit of any work or materials that are attributable in whole or in part to another person; taking an examination for another person; any act designed to give unfair advantage to a student; or the attempt to commit such acts. Since scholastic dishonesty harms the individual, all students and the integrity of the University, policies on scholastic dishonesty will be strictly enforced (Board of Regents Rules and Regulations and UTRGV Academic Integrity Guidelines). All scholastic dishonesty incidents will be reported to the Dean of Students.

### Sexual harassment, discrimination, and violence

In accordance with UT System regulations, your instructor is a “Responsible Employee” for reporting purposes under Title IX regulations and so must report any instance, occurring during a student’s time in college, of sexual assault, stalking, dating violence, domestic violence, or sexual harassment about which she/he becomes aware during this course through writing, discussion, or personal disclosure. More information can be found at www.utrgv.edu/equity, including confidential resources available on campus. The faculty and staff of UTRGV actively strive to provide a learning, working, and living environment that promotes personal integrity, civility, and mutual respect that is free from sexual misconduct and discrimination. 

### Course drops

According to UTRGV policy, students may drop any class without penalty earning a grade of DR until the official drop date. Following that date, students must be assigned a letter grade and can no longer drop the class. Students considering dropping the class should be aware of the “3-peat rule” and the “6-drop” rule so they can recognize how dropped classes may affect their academic success. The 6-drop rule refers to Texas law that dictates that undergraduate students may not drop more than six courses during their undergraduate career. Courses dropped at other Texas public higher education institutions will count toward the six-course drop limit. The 3-peat rule refers to additional fees charged to students who take the same class for the third time.

### Student services

Students who demonstrate financial need have a variety of options when it comes to paying for college costs, such as scholarships, grants, loans and work-study. Students should visit the Students Services Center (U Central) for additional information.

U Central is located in BMAIN 1.100 (Brownsville) or ESSBL 1.145 (Edinburg) or can be reached by email (ucentral@utrgv.edu) or telephone: (888) 882-4026. In addition to financial aid, U Central can assist students with registration and admissions.

Students seeking academic help in their studies can use university resources in addition to an instructor’s office hours. University Resources include the Learning Center, Writing Center, Advising Center and Career Center. The centers provide services such as tutoring, writing help, critical thinking, study skills, degree planning, and student employment. Locations are:

Learning center: BSTUN 2.10 (Brownsville) or ELCTR 100 (Edinburg)  
Writing center: BLIBR 3.206 (Brownsville) or ESTAC 3.119 (Edinburg)  
Advising center: BMAIN 1.400 (Brownsville) or ESWKH 101 (Edinburg)  
Career center: BCRTZ 129 (Brownsville) or ESSBL 2.101 (Edinburg)
