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

  Main Textbooks
  - Parameterized Algorithms, Marek Cygan, Fedor V. Fomin, Lukasz Kowalik, Daniel Lokshtanov, Dániel Marx, Marcin Pilipczuk, Michał Pilipczuk and Saket Saurabh, Springer 2015, https://www.mimuw.edu.pl/~malcin/book/parameterized-algorithms.pdf
  - Exact Exponential Algorithms, Fedor Fomin and Dieter Kratsch, Springer 2010, https://link.springer.com/book/10.1007/978-3-642-16533-7
  - Approximation Algorithms, Vijay Vazirani, Springer 2001 https://link.springer.com/book/10.1007/978-3-662-04565-7

  References.
  - Graph Theory, Reinhard Diestel, Graph Theory (Graduate Texts in Mathematics, 173) 5th edition, Springer 2016/2017. [Free online](https://diestel-graph-theory.com/)
  - The design of Approximation Algorithms, David P. Williamson, David B. Shmoys, Cambridge University Press 2011. [Free online](https://www.designofapproxalgs.com/).

 
Course Plan (liable to be adjusted)
------------
- 4, 9, 11 March: Introduction. Branching-based algorithm. Chapter 3.1-3.4 from Cygan et al.
- 16 March:  Kernelization for Vertex Cover, crown decomposition. Chapter 2.1-2.3 from Cygan et al.
