Algorithms for NP-hard Problems (KAIST CS492), Spring 2026
====================


<span style="color:red">NEWS</span>
---------------------
- 6 April: Please bring lunch to the exam. You can have lunch between 12h-13h during the exam; you can use the lounge next to the classroom for lunch.
- 30 March: Midterm exam will take place on 18th April (Saturday), from 9am till 5pm at Room 1101 in E3-1. Feel free to bring notes on at most 3 sheets of A4 paper. No electronic device allowed during the exam. 
You can bring snacks and beverages, as long as they don’t make too much noise. 
- 16 March: Homework 1 is available at KLMS. Lecture note is available on the website: [link](https://github.com/ssimplexity/CS492_spring2026/blob/main/Lecture_Note_CS492.pdf).

LOGISTICS
---------------------
- Lecturer: Eunjung KIM, eunjung.kim@kaist.ac.kr
- Lecture Room: 1101 in Building E3-1
  
- Teaching Assistants
  - Seokbeom Kim (seokbeom@kaist.ac.kr)
  - Jemin Hwang (hwangjemin@kaist.ac.kr)

- Office hour with the lecturer: after each lecture or upon arrangement.

- Office hour with the TAs: 16:30-17:30 Thursday, Office 307 at KRAFTON x SoC building.
  
- Schedule: 
  - On-site lectures, Monday and Wednesday 9:00-10:30.
  - Midterm exam schedule: 9h-17h on 18th April (Saturday), at Room 1101 in E3-1.
  - Final exam schedule: TBD
     
- Grading: 
  - Homeworks, Participation, Quiz, Project 30%, Midterm exam 35%, Final exam 35%.

 
- Others:
  - The official language in the class is English. 
  - Homework assignments will be announced on KLMS. The solutions to homeworks should be written either in latex (highly recommended) or in a text editor, e.g. MS Word. The assignment needs to be submitted before the indicated deadline. 
Hand-written solutions or submissions after the deadline are not accepted.
  - A strict policy against dishonest behaviors will be applied; expect an "F" grade. 


Course Description
-------------------
Most computational problems are NP-hard, and we cannot expect to solve them (i) optimally (ii) in polynomial-time (iii) on all instances. In this course, we study algorithm design paradigms which relax some of the criteria (i)-(iii) for a desirable algorithm. Specifically, we present techniques for designing and analyzing algorithms in the frameworks of parameterized complexity, approximation and exact exponential algorithms. We examine how such techniques are implemented as algorithms for concrete problems using the structure of a problem instance or a solution. The notions of hardness, which says that there is a limit on how efficiently some problems can be solved under some computational complexity assumption, are introduced as well.

- Recommended Prerequisite: 
Discrete Mathematics (CS204), Data Structure (CS206), Introduction to Algorithms (CS300).

- Course Materials.

  Main Material
  - Lecture Note, Eunjung Kim. [Available online](https://github.com/ssimplexity/CS492_spring2026/blob/main/Lecture_Note_CS492.pdf).
  - Parameterized Algorithms, Marek Cygan, Fedor V. Fomin, Lukasz Kowalik, Daniel Lokshtanov, Dániel Marx, Marcin Pilipczuk, Michał Pilipczuk and Saket Saurabh, Springer 2015, [Available online](https://www.mimuw.edu.pl/~malcin/book/parameterized-algorithms.pdf).
  - Approximation Algorithms, Vijay Vazirani, Springer 2001, [Available online](https://link.springer.com/book/10.1007/978-3-662-04565-7).

  Supplementary.
  - Exact Exponential Algorithms, Fedor Fomin and Dieter Kratsch, Springer 2010, [Available online](https://link.springer.com/book/10.1007/978-3-642-16533-7).
  - Graph Theory, Reinhard Diestel, Graph Theory (Graduate Texts in Mathematics, 173) 5th edition, Springer 2016/2017. [Available online](https://diestel-graph-theory.com/).
  - The design of Approximation Algorithms, David P. Williamson, David B. Shmoys, Cambridge University Press 2011. [Available online](https://www.designofapproxalgs.com/).
  - Lecture Note for CS 583: Approximation Algorithms, Chandra Chekuri, [Available online](https://courses.grainger.illinois.edu/cs583/fa2021/approx-algorithms-lecture-notes.pdf).
 
Course Plan (liable to be adjusted) - the main material for all lectures is the lecture note. 
------------
- 4, 9, 11 March: Introduction. Branching-based algorithm. Chapter 3.1-3.4 from Cygan et al.
- 16 March:  Kernelization for Vertex Cover, crown decomposition. Chapter 2.1-2.3 from Cygan et al.
- 18, 23 March: Quadratic kernel for Feedback Vertex Set. Chapter 9.1 from Cygan et al.
- 25 March: Quadratic kernel for Feedback Vertex Set continues. Interative compression. Chapter 4.1, 4.3 from Cygan et al.
- 30 March: Randomized technique for FPT algorithm. Chapter 4.4, 5.1-5.3 from Cygan et al.
- 1 April: Randomized technique for FPT algorithm continues.
- 6, 8, 13 April: Tree-decomposition. Chapter 7.1-7.4, 7.6 from Cygan et al.
- 15 April: Dynamic programming over subsets.
- 20-24 April: Mid-term exam period. 
- 27 April: IE-based algorithms and Matrix Tree Theorem. Chapter 10.1 from Cygan et al. Chapter 4.2 from [Fomin and Kratsch' textbook](https://link.springer.com/book/10.1007/978-3-642-16533-7))
- 29 April: Hardness in parameterized complexity. Chapter 13 from Cygan et al. For details on the class NP and NP-completeness, check Chapter 2 of [Arora and Barak](https://theory.cs.princeton.edu/complexity/book.pdf). One can find a more comprehensive treatement on W-hierarchy in [Flum and Grohe](https://link.springer.com/book/10.1007/3-540-29953-X) and [Downey and Fellows](https://link.springer.com/book/10.1007/978-1-4612-0515-9).
- 4 May: Algorithms for CNF-SAT. Chapter 8.1 from [Fomin and Kratsch' textbook](https://link.springer.com/book/10.1007/978-3-642-16533-7)
- 6 May: (S)ETH-based lower bound. Chapter 14 from Cygan et al. 
- 11 May: Introduction to approximation algorithms. Chapter 3 from Vazirani. Chapter 1 and 2.1 from [Chekuri's Lecture Note](https://courses.engr.illinois.edu/cs583/fa2021/approx-algorithms-lecture-notes.pdf).
- 13 May: Layering technique. Chapter 2.2 and 6 from Vazirani. 
- 18 May: Approximation for cut problems. Chapter 4 from Vazirani.
- 20 May: Approximation for cut problems. LP-based rounding. Chapter 12 from Vazirani.
- 25 May: No lecture. Public holiday. 
- 27 May: More on cut problems. LP-based rounding. 
- 1 June: LP-based rounding. Chapter 1.7 and 5.1-5.5 from Williamson and Shmoys.
- 3 June: No lecture. Election day.
- 8 June: Primal-dual method. Chapter 7.3 from Williamson and Shmoys, and Chapter 13.1 from Vazirani. 
- 10 June: Primal-dual method. Chapter 7.4 from Williamson and Shmoys, and Chapter 18 from Vazirani.
- 15-19 June: Final exam period. 
