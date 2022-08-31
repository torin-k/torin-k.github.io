# Projects

### Torin & Roshan Question Generation (6/8/2022)
My friend Roshan and I made a 


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
### Myoelectric Interface for Neural Training (MINT) (2018-2020)
For three years, I worked with the [Slutzky Neuroprosthetics Laboratory](https://sites.northwestern.edu/slutzkylab/) to develop software used as a part of the  neurorehabilitation process for stroke survivors today.  This software returns biofeedback to stroke victims, whose muscles are connected to EMG signal sensors, in order to train these people regain motor function. This intelligent biofeedback system allows users to basically play a game by flexing and relaxing the muscles in their arms, and by doing so trains users to use their muscles again for daily activities.

Over the course of my time at the Slutzky Neuroprosthetics Laboratory, I rewrote their biofeedback system which used [Pygame](https://www.pygame.org/news) almost completely from scratch to:
* Add additional functionality to training (which has shown a positive increase in helping users regain motor function).
* Make the system easier for participants to interact with and use.
* Allow researchers to more easily modify settings, increases in difficulty, etc.
* Make the software less prone to bugs and crashing.
To do this, I used a variety of Python libraries as well as [Blender](https://www.blender.org/), a 3D creation suite.

The preliminary version of the MINT system was written about in the New York Post! You can see the article [here](https://nypost.com/2019/03/20/this-video-game-helps-stroke-victims-regain-movement/).

* * *
### Iliac Vein Compression Model (2019-2020)
Over the course of multiple years, the [Midwest Cardiovascular Research Foundation](http://www.mcrfmd.com/) (MCRF) worked to develop a predictive model to predict [iliac vein compression syndrome](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4663376/) using non-invasive studies and clinical variables (i.e. age, weight), as opposed to the current gold standard intravascular ultrasound, an invasive surgery. Working with the foundation, I helped develop this model and build a mobile application using Apache Cordova so that researchers can quickly and easily use this model on real patients in practice. You can find the app on the Google Play Store [here](https://play.google.com/store/apps/details?id=com.mcrfmd.iliac&hl=en_US&gl=US). You can find the publication on the model [here](https://pubmed.ncbi.nlm.nih.gov/33385981/).
* * *
### PiMafia (3/15/2020)
PiMafia is a client-server structured network and software that allows its users to play a game of Mafia with each other. It can be run between devices on any Local Area Network (LAN). You can find a full write-up on the project [here](https://torink2.github.io/pimafia.html). Also, the GitHub page for the project can be found [here](https://github.com/TorinK2/PiMafia).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTM3MTk2Mjg2MywtMTgwMDE5MTUxMSwxOD
AyMzg1NDgzLC02ODg4OTI4MzksLTE1MjU3MDg5MzMsLTE3NDMy
MTQ0MzcsLTE1Njg3MDczNTEsLTE0ODgyMDcwOTksLTE0Nzg4Mj
MyMjcsLTk2OTkyODYyMywtMjA1NTQyMzI1MCwxNjMzMDU3MzAy
LDEwMjI3OTE0MDIsMTIwNTE2NzIxLC0xNzg5NjUxOTYzXX0=
-->