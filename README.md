Algorithms for NP-hard Problems (KAIST CS492), Spring 2026
====================


<span style="color:red">NEWS</span>
---------------------
- 16 March: Homework 1 is available at KLMS. Lecture note is available on the website.

LOGISTICS
---------------------
- Lecturer: Eunjung KIM, eunjung.kim@kaist.ac.kr
- Lecture Room: 1101 in Building E3-1
  
- Teaching Assistans
  - Seokbeom Kim (seokbeom@kaist.ac.kr)
  - Jemin Hwang (hwangjemin@kaist.ac.kr)

- Office hour with the lecturer: after each lecture or upon arrangement.

- Office hour with the TAs: 16:30-17:30 Thursday, Office 307 at KRAFTON x SoC building.
  
- Schedule: 
  - On-site lectures, Monday and Wednesday 9:00-10:30.
  - Midterm exam schedule: TBD
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
  - Lecture Note, Eunjung Kim.
  - Parameterized Algorithms, Marek Cygan, Fedor V. Fomin, Lukasz Kowalik, Daniel Lokshtanov, Dániel Marx, Marcin Pilipczuk, Michał Pilipczuk and Saket Saurabh, Springer 2015, https://www.mimuw.edu.pl/~malcin/book/parameterized-algorithms.pdf
  - Exact Exponential Algorithms, Fedor Fomin and Dieter Kratsch, Springer 2010, https://link.springer.com/book/10.1007/978-3-642-16533-7
  - Approximation Algorithms, Vijay Vazirani, Springer 2001 https://link.springer.com/book/10.1007/978-3-662-04565-7

  References.
  - Graph Theory, Reinhard Diestel, Graph Theory (Graduate Texts in Mathematics, 173) 5th edition, Springer 2016/2017. [Free online](https://diestel-graph-theory.com/)
  - The design of Approximation Algorithms, David P. Williamson, David B. Shmoys, Cambridge University Press 2011. [Free online](https://www.designofapproxalgs.com/).
  - Lecture Note for CS 583: Approximation Algorithms, Chandra Chekuri, [Free online](https://courses.grainger.illinois.edu/cs583/fa2021/approx-algorithms-lecture-notes.pdf).
 
Course Plan (liable to be adjusted) - the main material for all lectures is the lecture note. 
------------
- 4, 9, 11 March: Introduction. Branching-based algorithm. Chapter 3.1-3.4 from Cygan et al.
- 16 March:  Kernelization for Vertex Cover, crown decomposition. Chapter 2.1-2.3 from Cygan et al.
- 18 March: Quadratic kernel for Feedback Vertex Set.
- 23 March: Interative compression. Chapter 4.1, 4.3 from Cygan et al.
- 25 March: Randomized technique for FPT algorithm. Chapter 4.4, 5.1-5.3 from Cygan et al.
- 30 March: Tree-decomposition I. Chapter 7.1-7.2 from Cygan et al.
- 1 April: Tree-decomposition II. Chapter 7.3 from Cygan et al.
- 6 April: Tree-decomposition III. Chapter 7.4, 7.6 from Cygan et al. 
- 8 April: Dynamic programming over subsets and IE-based algorithm. Chapter 10.1 from Cygan et al.
- 13 April: More IE-based algorithms and Matrix Tree Theorem. Chapter 4.2 from [Fomin and Kratsch' textbook](https://link.springer.com/book/10.1007/978-3-642-16533-7)
- 15 April: (buffer)
- 20-24 April: Mid-term exam period. 
- 27 April: Mid-term exam revision.
- 29 April: Algorithms for CNF-SAT. Chapter 8.1 from [Fomin and Kratsch' textbook](https://link.springer.com/book/10.1007/978-3-642-16533-7)
- 4 May: Hardness in parameterized complexity. Chapter 13 from Cygan et al. For details on the class NP and NP-completeness, check Chapter 2 of [Arora and Barak](https://theory.cs.princeton.edu/complexity/book.pdf). One can find a more comprehensive treatement on W-hierarchy in [Flum and Grohe](https://link.springer.com/book/10.1007/3-540-29953-X) and [Downey and Fellows](https://link.springer.com/book/10.1007/978-1-4612-0515-9).
- 6 May: (S)ETH-based lower bound. Chapter 14 from Cygan et al. 
- 11 May: Introduction to approximation algorithms. Chapter 3 from Vazirani. Chapter 1 and 2.1 from [Chekuri's Lecture Note](https://courses.engr.illinois.edu/cs583/fa2021/approx-algorithms-lecture-notes.pdf).
- 13 May: Layering technique. Chapter 2.2 and 6 from Vazirani. 
- 18 May: Approximation for cut problems. Chapter 4 from Vazirani.
- 20 May: Approximation for cut problems. LP-based rounding. Chapter 12 from Vazirani.
- 25 May: No lecture. Public holiday. 
- 27 May: More on cut problems. LP-based rounding. 
- 1 June: LP-based rounding. Chapter 1.7 and 5.1-5.5 from Williamson and Shmoys.
- 3 June: No lecture. Election day.
- 8 June: Primal-dual method. Homework 4 out. Chapter 7.3 from Williamson and Shmoys and chapter 13.1 from Vazirani. 
- 10 June: Primal-dual method. Chapter 7.4 from Williamson and Shmoys, chapter 18 from Vazirani.
- 15-19 June: Final exam period. 
