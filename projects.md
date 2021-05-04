# Projects

### Boolean Circuits! (5/3/2021)
My most recent project is an investigation into Boolean circuits. Not only is this model of computation exceedingly easy to reason about and work with, but it can be harnessed to help prove some of the most essential theorems and tackle some of the biggest questions in theoretical computer science. For the final project of [15-251](http://www.cs.cmu.edu/~15251/), I wrote a paper investigating and showcasing some of the central proofs related to Boolean circuits. I also came up with a few interesting exercises! You can view the document [here](http://torink.me/SERVER/Boolean%20Circuits!.pdf).
* * *
### Maze Maker (1/2/2021) 
Graphs are one of the most essential data structures in computer science, and can be found in tons of applications in the real world, from search engines to GPS navigation to recommender systems. One fun application of graphs is that by generating trees (a type of graph that fulfills certain requirements), we can create mazes. By the nature of trees, these mazes we generate only have a single solution! Using Python and a simple graphics library, I was able to quickly implement a maze generator:
![small maze](http://torink.me/images/small-maze.png)

As we increase the number of vertices in our tree, we increase the size of the maze. In a matter of minutes, we can create mind-bogglingly large mazes!

![large maze](http://torink.me/images/large-maze.png)

* * *
### Numerical Linear Algebra (12/15/2020)
For the final project of [21-241](http://coursecatalog.web.cmu.edu/schools-colleges/melloncollegeofscience/departmentofmathematicalsciences/courses/), Matrices and Linear Transformations, my partner and I decided to investigate the area of numerical linear algebra, specifically building iterative methods to compute eigenvectors and singular vectors. From scratch using the [Julia](https://docs.julialang.org/en/v1/) language, we implemented the Power, Inverse Power, and QR methods to efficiently and accurately generate eigenvalues and eigenvectors. Specifically, I worked on:
* Implementing multiple incrementally more efficient methods for QR decomposition to implement the QR method.
* Implementing the Inverse Power method to hone our estimations for eigenvectors.
* Investigating the efficiency of the QR method versus the Power method for sparse and dense matrices.
* Using our eigen-finding code to build an algorithm to generate singular vectors and find singular value decomposition (SVD).
* Using the SVD algorithm to build a lossy compression algorithm.
* Using the SVD algorithm to build a steganographic algorithm which could hide/retrieve a binary message from a given image with indiscernible difference in the image.

You can find the final paper and Julia code [here](http://torink.me/SERVER/eigenfinding.pdf).

* * *
### PiMafia (3/15/2020)
PiMafia is a client-server structured network and software that allows its users to play a game of Mafia with each other. It can be run between devices on any Local Area Network (LAN). You can find a full write-up on the project [here](https://torink2.github.io/pimafia.html). Also, the GitHub page for the project can be found [here](https://github.com/TorinK2/PiMafia).
* * *
### Iliac Vein Compression Model (10/15/2020)

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTk2ODMyNDY1LC0xNDc4ODIzMjI3LC05Nj
k5Mjg2MjMsLTIwNTU0MjMyNTAsMTYzMzA1NzMwMiwxMDIyNzkx
NDAyLDEyMDUxNjcyMSwtMTc4OTY1MTk2M119
-->