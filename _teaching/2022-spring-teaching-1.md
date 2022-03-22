---
title: "CSCI4500 Operating Systems (Spring 2022)"
collection: teaching
type: Undergraduate course
permalink: /teaching/2022-spring-teaching-1
venue: UNO
date: Jan 24, 2022 - May 13, 2022
time: TTH 12PM - 1:15PM
location: Remote Learning
---

An operating system is an abstraction of computer system hardware; it manages the sharing of various hardware and software resources among the users of the computer system. The parallel history of hardware and operating system development introduces many key concepts including, for example, processor modes, direct memory access (DMA), device controllers, and virtual memory. Basic approaches to kernel organization and implementation are considered. This is often the first course in which students encounter concurrency and concurrent programs. Additional topic areas include system performance evaluation (particularly relating to processor and memory management), security, virtualization, resource allocation and scheduling, and file systems.

# Administrative Information
* Instructor: Pei-Chi Huang
* Email: phuang at unomaha dot edu
* Office Hour: Tuesday 1:15PM - 2:15PM via Zoom or by appointment
* Class Info: TTH 12PM - 1:15PM, Remote Learning
* [Course Schedule](#schedule)     

## Prerequisites:    
CSCI 3710 (Introduction to Digital Design and Computer Organization), CSCI 3320 (Data Structures), and MATH 1950 (Calculus I). CSCI 4350 (Computer Architecture) is recommended; open only to students in the School of Engineering and declared Computer Science minors.

## Recommended Textbook
Tanenbaum and Woodhull, Operating Systems: Design and Implementation (3rd edition), Prentice-Hall (2006)

### Supplemental materials
* The online book [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/) by Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau (indicated by OSTEP; this book is available for purchase at the site above if you prefer a print copy)
* Operating System Concepts 9th Edition, by Abraham Silberschatz, Peter B. Galvin, and Greg Gagne.

## Get Odin account
You need to apply for an account at Odin: IS&T Core Linux Server to finish your programs. More details are shown below:
[https://www.unomaha.edu/college-of-information-science-and-technology/about/odin.php](https://www.unomaha.edu/college-of-information-science-and-technology/about/odin.php). Please email to UNO IST support (Email: uno-ist-support at unomaha dot edu) if you have any questions about Odin. <span style="color:red"> **Please get one asap. Don't wait until the last-minute, always finish ahead of deadlines. ** </span>

## Grading
There will be six homeworks, three programming assignments, one midterm and one final.
The final course grade will be computed as follows:

* Homework and Quizzes: 18%
* Programming Assignments: 30%
* Midterm: 22%
* Final 30%

If you have questions regarding the grading of homework, programming assignments, midterms and final, you MUST come to see the instructor WITHIN ONE WEEK after the date your homework, programming assignments, or exams have been returned to you.

### Grading Type
 Letter grades will be determined using the weighted average of the various items used to evaluate students. A typical grade mapping is illustrated below.

|Points       | Grade |
|:---------|:------|
|97 – 100% | A+    |
|93 – 96%  | A     |
|90 – 92%  | A-    |
|87 – 89%  | B+    |
|83 – 86%  | B     |
|80 – 82%  | B-    |
|77 – 79%  | C+    |
|73 – 76%  | C     |
|70 – 72%  | C-    |
|67 – 69%  | D+    |
|63 – 66%  | D     |
|60 – 62%  | D-    |
|0 – 59%   | F     |

## Late Policy
Homeworks and Programming Assignments are subject to late penalty. Here is the point deduction policy: <span style="color:red"> **20% deduction (late by 1 day), 40% deduction (late by 2days), 80% deduction (late by 3 days), and no credit if late by more than three days.** </span>

Contact the instructor in case of a medical emergency, and a written proof from your doctor is required. <span style="color:red"> **You are allowed to extend one more day after the approval.** </span>

## Academic Integrity
You may discuss the homeworks and assignments with anyone and use any reference materials, but provided you do not copy any other person's work. We will follow [the University Policy](https://www.unomaha.edu/student-life/student-conduct-and-community-standards/policies/academic-integrity.php) on Academic Integrity regarding any cheating and plagiarism. Take the time to familiarize yourself with the contents of this page, as you are responsible for its contents.

### Accommodations
Reasonable accommodations are provided for students who are registered with Accessibility Services Center (ASC) and make their requests sufficiently in advance. For more information, contact ASC (Location: 104 H&K, Phone: 402.554.2872, Email: [unoaccessibility@unomaha.edu](unoaccessibility@unomaha.edu)


---------------------------------------------------------------------------------------------------------------
# Schedule
This schedule, and the links contained in it, are subject to change during the semester. Exam dates, however, are final.
Readings from additional sources are linked from the schedule. All reading assignments are required and are expected to be completed before class on the scheduled day.

| Date |           |               Topic                 | Assignment <br>(to be completed before class) |
|:----:|:----------|:------------------------------------|:----------------------------------------------|
| Tue   |  Jan. 25 |   [Introduction & Themes]   |                       |
| Thur  |  Jan. 27 |   [Introduction to Operating Systems & History]     | Reading: ch.1.1 - 1.2 |
| Tue   |  Feb. 1  |   [Introduction to Operating Systems & History]     | Reading: ch.1.3 - 1.4 |
| Thur  |  Feb. 3  |   [Basic Operating Systems Concepts]  | Reading: ch.1.4 - 1.5 |
| Tue   |  Feb. 8  |    [Processes and File Systems]     | Reading: ch.2.1  <br> <a href="" style="color:blue"> Homework 1 Available</a>  |
| Thur |  Feb. 10  |   [Processes and File Systems]    | Reading:  ch.2.2 <br> <a href="" style="color:blue">Program 1 Available</a>  |
| Tue  | Feb. 15 |   [Processes and File Systems]      | <span style="color:red"> Homework 1 Due (Upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 1 Solution</a> |
| Thur | Feb. 17 |   [Concurrency]    | Reading: OSTEP: [Common Concurrency Problems, pages 1-11](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-bugs.pdf) (stop at "Deadlock Avoidance via Scheduling") <br> <a href="" style="color: blue">Homework 2 Available</a> |
| Tue  | Feb. 22 |   [Communication & Synchronization - Part 1]  |   Reading: ch.2.3 <br> OSTEP [Lock](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks.pdf) (skip 28.8-28.11) |
| Thur | Feb. 24 |   [Communication & Synchronization - Part 1]  | Reading: OSTEP: [Monitors](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-monitors.pdf) <br> <span style="color:red"> Homework 2 Due (Upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 2 Solution</a> |
| Tue  |  Mar. 1  |  [Communication & Synchronization - Part 2]    | Reading: ch.2.4 <br> [The Multi-Level Feedback Queue](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-mlfq.pdf) |
| Thur |  Mar. 3  | [Communication & Synchronization - Part 2]     | Reading: ch.3.1  <br> <a href="" style="color: blue">Homework 3 Available</a> |
| Tue  |  Mar. 8  | [Classic Task Communication - Part 1]  | Reading: ch.3.2 |
| Thur |  Mar. 10  | [Classic Task Communication - Part 1] | Reading: ch.3.3 <br> <span style="color:red"> **Program 1 Due, 11:59pm**</span> |
| Tue  | Mar. 15  |  Spring Vacation (Student Holiday) - No classes |      |
| Thur | Mar. 17 |[Classic Task Communication - Part 2]  | <a href="" style="color: blue">Program 2 Available</a>  |
| Tue  | Mar. 22  | [Scheduling]   |  Reading: [CPU Scheduling](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched.pdf) <br>  <span style="color:red"> Homework 3 Due (Upload to Canvas)  </span>  <br>  <a href="" style="color: green">Homework 3 Solution</a> |
| Thur  | Mar. 24 | [Scheduling]   |  Reading: ch.4.1   |
| Tue   |  Mar. 29   | [Deadlock] | <!---[Review Notes](https://drive.google.com/file/d/1ck8nXZ-yrPi86NRrlHerbdLIEtxlYkWc/view?usp=sharing) <br>  --> <span style="color:red"> Anytime, 75 mins </span> |
| Thur  |  Mar. 31   |   [Deadlock]   | Reading: OSTEP [Address Spaces](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-intro.pdf)|
| Tue  |  Apr. 5   |   <span style="color:red"> **Midterm** </span> | <!---[Review Notes](https://drive.google.com/file/d/1ck8nXZ-yrPi86NRrlHerbdLIEtxlYkWc/view?usp=sharing) <br>  --> <span style="color:red"> Anytime, 75 mins </span> <br> Reading: ch.4.2 <br> <a href="" style="color: blue">Homework 4 Available</a>  |
| Thur |  Apr. 7    |  [Memory Overview - Part I: Memory Partition and Relocation]   | Reading: ch.4.3 |
| Tue   |  Apr. 12   |    [Memory Overview - Part II: Techniques and Swapping]  | Reading: ch.4.4 <br>  <span style="color:red"> **Program 2 Due, 11:59pm**</span> <br> <a href="" style="color:blue"> Program 3 Available</a>|
| Thur  |  Apr. 14   |  [Memory Overview - Part II: Techniques and Swapping]    | Reading: ch.4.5  <br> <span style="color:red"> Homework 4 Due (Upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 4 Solution</a>  |
| Tue   |  Apr. 19  |  [Virtual Memory - Part I: Mechanisms (Address Translation and Page Tables)] |  Reading: ch.5.1 <br> <a href="" style="color: blue">Homework 5 Available</a>  |
| Thur  |  Apr. 21  |  [Virtual Memory - Part II: Policies (Page Replacement Algorithms)]     | Reading: ch.5.2-5-3  |
| Tue   | Apr. 26   | [Input/Output Hardware]     | Reading: Distributed Systems for Fun and Profit, by Mikito Takada, [Chapter 2](http://book.mixu.net/distsys/abstractions.html) <br> <span style="color:red"> Homework 5 Due by Nov. 25 (Upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 5 Solution</a> <br> <a href="" style="color: blue">Homework 6 Available</a> |
| Thur  | Apr. 28 |  [Input/Output Software]   | Reading:  ch.5.3  <br> [Chapter 3](http://book.mixu.net/distsys/time.html), [The Google File System](https://ai.google/research/pubs/pub51)  |
| Tue | May 3 | [Put It All Together]   |    Reading: ch.5.4 <br>  <span style="color:red"> Homework 6 Due (Upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 6 Solution</a> <br> <span style="color:red"> **Program 3 Due  at 11:59pm** </span> |
| Thur | May 5 |  Study Days  |   Reading: textbook, supplemental materials, and all slides |
| Tue   | May 10  |   <span style="color:red"> [**Final Exam** ](https://www.unomaha.edu/registrar/students/after-enrollment/final-exam.php#tts2) </span> | Reading: textbook, supplemental materials, and all slides <br> <span style="color:red"> Anytime, 120 mins </span> |
