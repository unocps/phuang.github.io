---
title: "CSCI8530 Advanced Operating Systems (Spring 2022)"
collection: teaching
type: Graduate course
permalink: /teaching/2022-spring-teaching-2
venue: UNO
date: Jan 24, 2022 - May 13, 2022
time: MW 12:00PM - 1:15PM
location: Remote Learning
---

The course introduces the design and structure of computer operating systems, and also considers advanced operating system topics and exposes students to recent developments in operating systems research. The course involves the concepts, principles, functionality, trade-offs, and implementation of systems that support concurrent processing. The individual components of an operating system (Xinu) will be examined in detail at the source code level, and students will be expected to complete various assignments on real hardware (Intel Galileo board or Raspberry Pi 2B (or 3B) or Beagle Bone Black. Others are NOT recommended.). At a minimum, you will need a board, a memory card, a USB-micro cable, and a USB-serial adapter. Some of these assignments will involve simple “follow the steps'' activities, while others will require the design of new or modified system components and application programs. Lectures will closely follow the expected readings which are indicated in the class schedule on the class web pages.

# Administrative Information
* Instructor: Pei-Chi Huang
* Email: phuang at unomaha dot edu
* Office Hour: Wednesday 1:15 - 2:30 PM, PKI 173 Building or by appointment
* Class Info: MW 12:00PM - 1:15PM, Remote Learning
* [Course Schedule](#schedule)      

## Prerequisites:    
This course assumes students have a good understanding of basic operating system principles similar to that provided by a traditional introductory undergraduate operating systems course. In particular, the major functions of an operating system should be familiar, as should the basic algorithms and techniques used to implement them. Concepts of concurrent programming, including processes, threads, and various mechanisms for interprocess communication should be familiar. It is expected that students will have familiarity with the API for a traditional UNIX/Linux operating system, including such things as input/output and process management. All of the programming for the course will be done using the C programming language. Familiarity with the concepts of assembly language for some machines is expected, although it is unlikely that any assembly language code will need to be written for the programming assignments.

## Recommended Textbook
The primary textbook: Operating System Design: The Xinu Approach (second edition) by Douglas Comer, 2015, CRC Press.

### Supplemental materials
* [Raspberry Pi](https://www.raspberrypi.org/)
* [Upgrading Embedded Xinu for the Raspberry Pi 3](https://reu.cs.mu.edu/index.php/Upgrading_Embedded_Xinu_for_the_Multi-Core_Raspberry_Pi_3)
* The online book [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/) by Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau
* Tanenbaum, A.S., 2009. Modern operating system. Pearson Education, Inc.
* Daniel, P. and Marco, C., 2007. Understanding the Linux kernel.
* Schimmel, C., 1994. UNIX systems for modern architectures: symmetric multiprocessing and caching for kernel programmers. Addison-Wesley.

## Grading

* Homework and Quizzes (Individual): 20%
* Programming Assignments (Teamwork, 1-3 for each group): 30%
* Midterm: 20%
* Final (Teamwork, 1-3 for each group): 30%


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

Contact the instructor in case of a medical emergency, and a written proof from your doctor is required.

## Academic Integrity
You may discuss the homeworks and assignments with anyone and use any reference materials, but provided you do not copy any other person's work. We will follow the University Policy on Academic Integrity regarding any cheating and plagiarism. Take the time to familiarize yourself with the contents of this page, as you are responsible for its contents.

## Accommodations
Reasonable accommodations are provided for students who are registered with Accessibility Services Center (ASC) and make their requests sufficiently in advance. For more information, contact ASC (Location: 104 H&K, Phone: 402.554.2872, Email: unoaccessibility@unomaha.edu)

---------------------------------------------------------------------------------------------------------------
# Schedule
This schedule, and the links contained in it, are subject to change during the semester. Exam dates, however, are final.
Readings from additional sources are linked from the schedule. All reading assignments are required and are expected to be completed before class on the scheduled day.

| Date |           |               Topic                 | Assignment <br>(to be completed before class) |
|:----:|:----------|:------------------------------------|:----------------------------------------------|
| Mon  | Jan. 24  |  [Introduction & Themes] |    |
| Wed | Jan. 26  | [Hardware and Xinu]| Reading: ch.1 <br> [Announcement of Final Project] |
| Mon  | Jan. 31  | [Xinu on Intel Galileo User Manual] <br> [Xinu Setup Procedure] | [Galileo System Receipt] <br> Reading: ch.2  |
| Wed | Feb. 2  | [Organization of an Operating System] | Reading: ch.3 <br> <span style="color:red"> Submit Project Topics </span>  |
| Mon  | Feb. 7  | [Organization of an Operating System]  | Reading: Ch.4  <br> <a href="" style="color: blue"> Homework 1 Available</a>  |
| Wed | Feb. 9  | [Hardware Architecture and Runtime Systems] | Reading: ch.5 <br>  <a href="" style="color: blue">Program 1 Available</a> <br> [stack_frame] |
| Mon  | Feb. 14  | [Hardware Architecture and Runtime Systems] | Reading: ch.5 <br> <span style="color:red"> Homework 1 Due (upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 1 Solution</a> |
| Wed | Feb. 16  | [Process Management]   | Reading: ch.6 <br> <a href="" style="color: blue">Homework 2 Available</a> |
| Mon  | Feb. 21 | [Process Management]   | Reading: ch.6 |
| Wed | Feb. 23 | [Process Management]  | Reading: ch.7 |
| Mon  | Feb. 28  | [Process Coordination and Synchronization] <br> <a href="" style="color: red">Project Progress Report</a> (3 mins presentation and 1 page section submission each team, [word], [pdf] )    | Reading: ch.7 <br> <span style="color:red"> Homework 2 Due (upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 2 Solution</a> |
| Wed | Mar. 2  | [Process Coordination and Synchronization]    | Reading: ch.8 |
| Mon  | Mar. 7  | [Inter-Process Communication]    | Reading: ch.9  <br> <a href="" style="color: blue">Homework 3 Available</a> |
| Wed | Mar. 9 | [Low-level Memory Management]  | Reading: ch.9,10 <br> <span style="color:red"> **Program 1 Due, 11:59pm**</span> |
| Mon  | March 14  |  Spring Break  |
| Wed | March 16  |   Spring Break  |
| Mon  | March 21 | [Low-level Memory Management]  | Reading: ch.10 <br> <a href="" style="color: blue">Program 2 Available</a>  |
| Wed | March 23 |  [High-level Memory Management]  |  Reading: ch.10, 11, 12 <br> <span style="color:red"> Homework 3 Due (upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 3 Solution</a> |
| Mon  |  March 28  |  [High-level Memory Management] | Reading: ch.12, 13 |
| Wed |  March 30  |  [High-level Memory Management] <br> <span style="color:red"> **Project Progress Report** <span style="color:black"> (1 page section submission each team)  |   Reading: ch.13   |
| Mon  |  Apr. 4  |  <span style="color:red"> **Midterm** </span>  |   <span style="color:red"> **Anytime** </span>  |
| Wed | Apr. 6 | [Device Management]  |   Reading: ch.13 <br>  <a href="">Program 3 Available</a> |
| Mon  |  Apr. 11  |   [Device Management] | <span style="color:red"> **Program 2 Due, 11:59pm**</span>  <br> <a href="" style="color: blue">Homework 4 Available</a>  |
| Wed  |  Apr. 13 | <span style="color:red"> **Project Progress Report** <span style="color:black"> (3 mins presentation and 1 page section submission each team) | Reading: ch.14   |
| Mon  | Apr. 18 |   [Clock and Timer Management] | Reading: ch.14 |
| Wed | Apr. 20 |   [Clock and Timer Management] <br> [High-level Synchronous Message Passing]   |  Reading: ch.15 <br>  <span style="color:red"> Homework 4 Due (upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 4 Solution</a> <br> <a href="" style="color: blue">Homework 5 Available</a>  |
| Mon  | Apr. 25 | [High-level Synchronous Message Passing] | Reading: ch.15 |
| Wed | Apr. 27 | [Networking and Protocol Implementation]   | Reading: ch. 16|
| Mon  | May 2 | [Networking and Protocol Implementation] | Reading: ch. 17|
| Wed | May 4 | Presentation | <span style="color:red"> Homework 5 Due (upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 5 Solution</a>  |
| Mon  | May 9 | Presentation           |         |
| Wed | May 11 | Presentation              | <span style="color:red"> **Program 3 Due, 11:59pm** </span> |
| Friday | May 13  | Report and Demo Due | [Report Template](https://www.ieee.org/conferences/publishing/templates.html) <br> Report and Demo Due 11:59pm <br> Submission: 1) A report, 2) Presentation slides, 3) Presentation video, and 4) Demo video. |