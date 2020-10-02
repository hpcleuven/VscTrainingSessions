# VSC training sessions

This page provides an overview of the training sessions organized by the VSC.  These are descriptions of the contents and the prerequisites, for the actual schudule, please consult the [VSC training & events page](https://www.vscentrum.be/training).


## Linux intro (4 hours)

This course will give a short practical summary of the basic things one needs when using mainly the command line in Linux.
For details, see the [training session's website](https://hpcleuven.github.io/Linux-intro/).

Prerequisites: none


## HPC intro (4 hours)

This course will give a short practical summary of the basic things VSC users need to know to start working on the HPC cluster.
For details, see the [training session's website](https://hpcleuven.github.io/HPC-intro/).

Prerequisites: [Linux intro](https://hpcleuven.github.io/Linux-intro/)


## Linux scripting (4 hours)

This course will give an introduction to Linux scripting with an introduction to the mostly used loops while programming.
For details, see the [training session's website](https://hpcleuven.github.io/Linux-scripting/).

Prerequisites:
  * [Linux intro](https://hpcleuven.github.io/Linux-intro/)
  * [HPC intro](https://hpcleuven.github.io/HPC-intro/) if you plan to use VSC infrastructure


## Linux for HPC (4 hours)

This course will give a more detailed and HPC oriented summary of the basic command line related issues in Linux.
For details, see the [training session's website](https://hpcleuven.github.io/Linux-for-HPC/).

Prerequisites:
  * [Linux intro](https://hpcleuven.github.io/Linux-intro/)
  * [HPC intro](https://hpcleuven.github.io/HPC-intro/)


## Linux tools (4 hours)

This course will give an introduction to several useful Linux tools useful in academic research and everyday use of the system.
For details, see the [training session's website](https://hpcleuven.github.io/Linux-tools/).

Prerequisites:
  * [Linux intro](https://hpcleuven.github.io/Linux-intro/)
  * [HPC intro](https://hpcleuven.github.io/HPC-intro/) if you plan to use VSC infrastructure


## Make introduction (4 hours)

This course will give an introduction to creating/modifying Makefiles.
For details, see the [training session's website](https://hpcleuven.github.io/Makefile-intro/).

Prerequisites:
  * [Linux intro](https://hpcleuven.github.io/Linux-intro/)
  * [HPC intro](https://hpcleuven.github.io/HPC-intro/) if you plan to use VSC infrastructure


## C++ for scientific programming (14 hours)

This training focusses on using C++ for scientific programming and on
the way Bjarne Stroustrup advocates modern C++ in his book "A tour of
C++".  Some C++17 features and third party libraries will also be
discussed.
For detailed information, see: [https://gjbex.github.io/Scientific-C-plus-plus/](https://gjbex.github.io/Scientific-C-plus-plus/)


## Fortran for programmers

Fortran is used a lot in the context of HPC.  For many, it has a
reputation of being an old and ugly programming language.  However,
modern Fortran is a far cry from Fortran 77 that its detractors have
in mind.  Fortran 2003/2008 is a language that is well tailored
towards scientific computing.  This training introduces the language
and its features.

For detailed information, see: [https://gjbex.github.io/Fortran-for-programmers/](https://gjbex.github.io/Fortran-for-programmers/)


## Python training sessions

### Python as a second language (4 hours)

Python is an all-round programming language that has applications in
many domains.  This training session introduces the programming
language to participants who have programming experience with other
programming languages such as R, MATLAB, C/C++ or Fortran.

Subjects:

  * control flow statements (conditional, repetition)
  * functions
  * data types
  * file I/O

Prerequisites: experience in another programming language


### Python systems programming (4 hours)

Python is a very versatile programming language that has a wide range of
applications.  This training concentrates on interaction with the
operating system, the file system, other applications and the network.
This is useful for systems programming, but also when you want to use
Python as a coordination language for your workflows.
This training introduces modules that are useful in that context.
For detailed information, see: [https://gjbex.github.io/Python-for-systems-programming/](https://gjbex.github.io/Python-for-systems-programming/)

Prerequisites: Python as a second language


### Python software engineering (4 hours)

Quality of software matters, whether you share it with others or not.
Software should be easy to install, easy to use, and well documented.
This training will cover those aspects from the perspective of the
Python ecosystem.  However, it is also important that software is easy
to maintain, so coding style matters, API-level documentation should be
available, as well as a battery of tests to ensure the software's
integrity.  Of course, good design is at least as important.
For detailed information, see: [https://gjbex.github.io/Python-software-engineering/](https://gjbex.github.io/Python-software-engineering/)

Prerequisites: Python as a second language


### Scientific Python (4 hours)

Python is a nice programming language for scientific programming. Many
high quality libraries are available as building block in a wide variety
of scientific domains. In this training we will concentrate on the core
libraries, and give some examples of domain specific libraries.
For detailed information, see: [https://gjbex.github.io/Scientific-Python/](https://gjbex.github.io/Scientific-Python/)

Prerequisites: Python as a second language


### Python for data science (4 hours)

Python is one of the dominant languages in data science.  In this
training we will cover a number of modules that are useful for data
preparation, analyzing data, visualization, and machine learning.
For detailed information, see: [https://gjbex.github.io/Python-for-data-science/](https://gjbex.github.io/Python-for-data-science/)

Prerequisites: Python as a second language


### Python for machine learning (4 hours)

Python is one of the dominant languages in the area of machine learning
and AI.  This training will provide an introduction to machine learning
methodology for data preparation and machine learning, as well as some
machine learning algorithms.
For detailed information, see: [https://gjbex.github.io/Python-for-machine-learning/](https://gjbex.github.io/Python-for-machine-learning/)

Prerequisites: Python as a second language


### Python for HPC (4 hours)

Although vanilla Python is fairly slow and hence not a good candidate,
there are several options to significantly increase the efficiency of
Python programs.
For detailed information, see: [https://gjbex.github.io/Python-for-HPC/](https://gjbex.github.io/Python-for-HPC/)

Prerequisites:
  * Python as a second language
  * [Scientific Python](https://gjbex.github.io/Scientific-Python/](https://gjbex.github.io/Scientific-Python/)
  * C, C++ or Fortran programming experience is useful for some topics, but not required.


## Jupyter notebooks (2 hours)

Jupyter notebooks are a versatile tools for data exploration and
exploratory programming in a wide variety of programming languages. In this
session you will learn how to use Jupyter Notebooks effectively.

Subjects:

  * formatted text using MarkDown and LaTeX formulas
  * using Python/R code cells
  * mixing Python and R in a single notebook
  * interactive visualizations in notebooks
  * interactive data in notebooks
  * turning notebooks into slides
  * batch execution of notebooks
  * notebooks and version control

Prerequisites:

  * Familiarity with Python or R (note that most examples will be given in Python)


## Parallel programming

These courses have been developed by Rolf Rabenseifner (HLRS, Stuttgart,
Germany) and the training has followed Rolf's train-the-trainer program.

### MPI: Message Passing Interface (14 hours)

MPI is the de-facto standard for distributed parallel programming of
scientific applications.  It specifies language bindings for C and
Fortran.  This training covers the MPI 3.1 standard, but also
emphasizes potential pitfalls and best practices.

Subjects:

  * process model and language bindings
  * messages and point-to-point communication
  * non-blocking communication
  * collective communication
  * groups, communicators and virtual topologies
  * one-sided communication
  * shared memory
  * derived data types
  * parallel I/O
  * best practices

Prerequisites: experience in C, [C++](https://gjbex.github.io/Scientific-C-plus-plus/) or
      [Fortran](https://gjbex.github.io/Fortran-for-programmers/) programming


### OpenMP (7 hours)

OpenMP provides a very convenient programming model for scientific
applications that run multiple threads.  It is supported by C, C++ and
Fortran compilers.  Its main advantage is that it is mostly used through
annotation of code, which makes it easy to pick low hanging fruit when
starting to parallelize code. The training covers OpenMP 4.5, and
emphasizes pitfalls and best practices.

Subjects:

  * programming and execution model
  * worksharing directives
  * data environment
  * tasking
  * SIMD constructs
  * thread placement
  * pitfalls and best practices

Prerequisites: experience in C, [C++](https://gjbex.github.io/Scientific-C-plus-plus/) or
    [Fortran](https://gjbex.github.io/Fortran-for-programmers/) programming


### Threading Building Blocks (4 hours)

Threading Building Blocks (TBB) is a C++ template library for developing
shared memory applications.  It integrates well with the C++ Standard
Template Library (STL) and can be used with any modern C++ compiler.
TBB is especially suited for nested parallelism, and pipelining when
part of the application can use accelerator hardware.

Subjects:

  * programming and execution model
  * recap of required C++ features
  * algorithms: `parallel_for`, `parallel_reduce`, `parallel_do`
  * task based programming
  * dataflow programming, task graphs
  * pitfalls and best practices

Prerequisites: experience in [C++ programming](https://gjbex.github.io/Scientific-C-plus-plus/)


## Defensive programming and debugging (4 hours + 2 hours optional)

All code contains bugs, finding and fixing them is boring.  In this
training, best practices are presented to reduce the number of bugs
in your code.  You will also learn about debuggers and debugging
techniques to find bugs more efficiently.

Subjects:

  * best practices in coding, code style, error handling
  * using compiler options to warn about potential issues
  * unit and functional testing
  * using a debugger (breakpoints, inspection, watchpoints, tracing, ...)
  * zoo of bugs
  * optional: debugging parallel code

Prerequisites:

  * experience in C, [C++](https://gjbex.github.io/Scientific-C-plus-plus/) or
      [Fortran](https://gjbex.github.io/Fortran-for-programmers/) programming
  * [familiarity with the bash command line](https://hpcleuven.github.io/Linux-intro/)
  * optional: experience using MPI and/or OpenMP


## Code optimization (4 hours)

For HPC applications, performance is a major concern.  A thorough
understanding of the relevant hardware and software components is
required.  In this training, you will learn about a number of these
components, and how they influence the efficiency of you application.
You will also learn how to profile your application to identify
performance bottlenecks.
For detailed information, see: [https://gjbex.github.io/Code-optimization/](https://gjbex.github.io/Code-optimization/)

Prerequisites: experience in C, [C++](https://gjbex.github.io/Scientific-C-plus-plus/) or
      [Fortran](https://gjbex.github.io/Fortran-for-programmers/) programming


## Container for HPC (2 hours)

Singularity can be viewed as the Docker for HPC, i.e., a Singularity
image contains all the operating system/software components for your
application and can be deployed and run on HPC infrastructure, as well
as on your own laptop.
For detailed information, see: [https://gjbex.github.io/Containers-for-HPC/](https://gjbex.github.io/Containers-for-HPC/)

Prerequisites: [familiarity with the bash command line](https://hpcleuven.github.io/Linux-intro/)


## Version control with git (4 hours)

Version control is an essential part of the software development process
and is crucial for scientific application to help reproducibility.
You will learn how to use a version control system (either git or SVN)
to document the changes in your source code.  For the git version of this
training session, Gitlab and GUI clients are discussed as well.
For detailed information, see: [https://gjbex.github.io/Version-control-with-git/](https://gjbex.github.io/Version-control-with-git/)

Prerequisites: [familiarity with the bash command line](https://hpcleuven.github.io/Linux-intro/)
