---
layout: page
title: CV
group: navigation
---
{% include JB/setup %}

#### Background Information

<table border="0" width="100%" padding="5%" spacing="0">
<tr valign="top">
<td width="35%"><b>Position:</b></td><td>Professor, Department of Computer Science. Head of <a href="https://di.ku.dk/english/research/pltc/">PLTC Section</a>. Head of <a href="https://studier.ku.dk/bachelor/datalogi-oekonomi/">BSc education on Computer Science and Economics</a>.
</td></tr>
<tr valign="top">
<td width="35%"><b>Email:</b></td><td>mael at di.ku.dk</td>
</tr>
<tr valign="top">
<td width="35%"><b>Home page:</b></td><td><a href="http://elsman.com">http://elsman.com</a></td>
</tr>
<tr valign="top">
<td width="35%"><b>Address:</b></td><td>Universitetsparken 5, DK-2100 Copenhagen O, Denmark</td>
</tr>
<tr valign="top">
<td width="35%"><b>Mobile phone:</b></td><td>+45 2612 2212</td>
</tr>
<tr valign="top">
<td width="35%"><b>Date of Birth:</b></td><td>1969-12-22</td>
</tr>
</table>
<br/>
__Previous positions:__

<table border="0" width="100%" padding="5%" spacing="0">
<tr valign="top">
<td width="35%">May 2012 - December 2020</td><td>Associate Professor, Department of Computer Science, University of Copenhagen, Denmark. HIPERFIT Research Center Manager, HEAD of BSc education on computer-science and economics (from 2019).</td>
</tr>
<tr valign="top">
<td>May 2008 - April 2012</td><td>Chief System Development Consultant, Team Leader, <a href="http://www.simcorp.com">SimCorp</a>.</td>
</tr>
<tr valign="top">
<td>April 2003 - April 2008</td><td>Associate Professor at The IT University of Copenhagen (ITU). From March 2004 to August 2005, Vice Head of the Department of Innovation, ITU. From August 2005 to January 2006, Head of the Department of Innovation, ITU. From August 2007 - April 2008, Head of the SDT study programme.</td>
</tr>
<tr valign="top">
<td>February 2006 - August 2006</td><td>On leave from ITU: CTO at Zecure.</td>
</tr>
<tr valign="top">
<td>January 2000 - March 2003</td><td>Assistant Professor at The Royal Veterinary and Agricultural University of Denmark (part time at ITU).</td>
</tr>
<tr valign="top">
<td>January 1999 - December 1999</td><td>Postdoctoral research position at University of California, Berkeley.</td>
</tr>
<tr valign="top">
<td>May 1995 - December 1998</td><td>Ph.D. student at the Department of Computer Science, University of Copenhagen (DIKU).</td>
</tr>
</table>

#### Research and Development

I am Professor in the Programming Languages and Theory of Computation
section at the Department of Computer Science, University of
Copenhagen, where I serve as head of the <a
href="https://di.ku.dk/english/research/pltc/">PLTC Section</a> and
head of studies for the BSc education on Computer Science and Economics.

Until 2018, I served as Center Manager for the
HIPERFIT Research Center, which, with special attention to the finance
industry, focused on solving problems within the domains of
high-performance computing and big data.

From May 2008 to April 2012, I worked in SimCorp as Chief System
Development Consultant. From April 2009, I was team leader for the
SimCorp Instrument Modeling Language team. The team focused on
providing support for quick time-to-market financial instruments,
written in a domain specific ML-like programming language and
integrated into a .NET development platform [2014].

I have conducted research in the design and implementation of
high-level programming languages. My research interests have been in
the areas of module systems, platforms and type systems for Web
applications, program optimisation, type systems for static memory
management, transient fault tolerant computing, garbage collection
techniques, and instruction selection for virtual machines and
different microprocessors, including the x86 microprocessor. I have
also done work in the area of constraint-based program analyses.

From February 2006 until August 2006, I was on leave from ITU and
served as CTO at Zecure, a small company focussing on solutions for
Internet payment processing and e-commerce fraud detection.

During 2013, I was involved in establishing a european research
program on [Global Systems Science](http://hiperfit.dk/news/2013/06/24/global-systems-science).

I am a (co-)designer and (co-)developer of the following tools:

* [Futhark](https://futhark-lang.org/). A purely functional
data-parallel language targeting GPGPUs
[2014b, 2015, 2015a, 2016, 2016a, 2017, 2018a, 2018b, 2019, 2019a]. Futhark is a statically typed,
data-parallel, and purely functional array language in the ML
family. It comes with a heavily optimising ahead-of-time compiler that
generates efficient GPU code via OpenCL, using a number of fusion- and
special-purpose optimisation techniques.

* [The TAIL APL compiler](http://github.com/melsman/apltail). A
compiler for the APL programming language, which targets a typed
intermediate language [2014a, 2015b, 2016a]. The ultimate goal of this project is to
provide a way for APL programmers to target data-parallel
architectures, using a subset of well-known APL functions and
operators, many of which, by design, are naturally data-parallel.

* [SMLtoJs](http://smlserver.org/smltojs). A compiler from
Standard ML to JavaScript. SMLtoJs allows for building AJAX
applications using a statically typed language. It compiles all of
Standard ML and has support for calling JavaScript functions and for
executing JavaScript statements. It also allows for type safe
integration with SMLserver using, for instance, XML-RPC; see
below. SMLtoJs may compile itself - the result is [a Standard ML
compiler running in a browser](http://smlserver.org/ide) [2011, 2018c].

* [SMLserver](http://smlserver.org). An efficient multi-threaded
Web server platform for Standard ML programs
[2002, 2002b, 2003b, 2004, 2018c]. The aim of the SMLserver project has been to
push advanced programming concepts, such as higher-order functions and
polymorphic type systems, to the context of Web applications. The
development of SMLserver has been driven by practical needs. SMLserver
is used as the basic Web platform for a series of Web services at the
IT University of Copenhagen, including a course evaluation system, an
online course registration system, an alumni database, and the
employee and student database and search facility (more than 250.000
lines of Standard ML). SMLserver has been built as a Web server module
(for Apache or AOLserver) and has support for efficient pooling of
database connections for Oracle (based on OCI), Postgres, and MySQL
databases.

* [MLKit](http://elsman.com/mlkit/). An optimizing
compiler for the programming language Standard ML [2002c]. In the
context of the MLKit, I have been working on combining dynamic garbage
collection techniques and region-based memory management to gain a
higher degree of control over memory resources
[2021, 2020, 2004b, 2003a, 2002a]. Whereas the runtime system of the MLKit is
written in C and assembler, the MLKit compiler itself is written in
Standard ML.

* [Carillon](http://elsman.com/pdf/carillon-press-8.02.99.pdf). A tool to find Y2K problems in C programs [1999a].

In the context of the HIPERFIT research center, I have also worked on
techniques for specifying, managing, and pricing financial contracts
[2015c, 2016c, 2018, 2019c, 2019d], in particular, in the context of blockchain technology [2017a].

I have also participated in a research project on bigraphical
programming languages, which aims at modeling and controling
connectivity and locality for mobile and distributed systems
[2006]. Moreover, I have done work in the area of code generation for
transient fault tolerance [2007].

To ease administration of teaching, I have developed an advanced
generic Web-based system, called
[CourseGrader](https://sourceforge.net/projects/coursegrader/), for
managing course home work assignments and grades. The system is based
on a combination of TCL and Oracle and makes highly use of PL/SQL for
efficient online computing of grades based on a set of
course-configurable rules.

#### Research at Berkeley

From January 1999 until December 1999, I possessed a postdoctoral
research position at University of California, Berkeley, where I
worked with Associate Professor Alex Aiken. The work involved getting
automatic program analyses to scale to large programs. One example
application that we have developed is Carillon, a tool for finding Y2K
problems in C programs [1999a]. Carillon has been used to locate a Y2K
glitch in CVS version 1.9 (fixed in version 1.10), a version-control
system widely used in the open-source software community.

#### Ph.D in Computer Science

I obtained my Ph.D. degree from the Department of Computer Science,
University of Copenhagen (DIKU) in December 1998. My Ph.D. supervisor
was Associate Professor Mads Tofte. Members of the thesis committee
was Xavier Leroy, INRIA Rocquencourt; Greg Morrisett, Cornell
University; and Hanne Riis Nielson, Aahus University (Chair).

My Ph.D. thesis [1999b] is titled ''Program Modules, Separate
Compilation, and Intermodule Optimisation.'' The thesis is about a
series of techniques that allow for compiling program modules in such
a way that little overhead is incurred by dividing a program into
distinct modules. As a part of my Ph.D., I have worked with a group of
highly motivated professors and students in the development and use of
new compiler technology. The techniques developed in my Ph.D. thesis
are used in the MLKit [2002c].

As part of my Ph.D. program, I spent seven months (from January
to August 1997) at Cornell University, New York, USA. Here, I worked
with Assistant Professor Greg Morrisett and with people from Carnegie
Mellon University on the development of a system for separate
compilation in the TIL (Typed Intermediate Languages) Standard ML
compiler.

During my Ph.D. program, I gained experience in teaching courses
for Master's degree students in the areas of type theory, compilation
techniques for module languages, and techniques for type-based program
optimisation. My Ph.D. work resulted in a series of papers and reports
[1999, 1999b, 2002c, 1998].

#### Research Programmer

From September 1994 to May 1995, I was employed as a research
programmer to work on the MLKit. During this time, I worked on an
efficient implementation of the type system for the Standard ML
Modules language. Moreover, I implemented--with other people in the
MLKit group--a back-end for the MLKit that generates efficient machine
code for the HP PA-RISC microprocessor [1995]. Since then, I have
ported this back-end to the Intel X86 microprocessor and to an
embeddable virtual machine [2002] for use in a Web server
[2004, 2003b, 2002b].

#### M.Sc. in Engineering

I initiated the Master of Science program in engineering at the
Technical University of Denmark in September 1988. I spent the year
1991/92 at Whittier College, Los Angeles, USA, where I took classes in
physics, computer science, mathematics, and philosophy. In the second
part of the Master's program, I specialised in computer science. I
finished the Master's program in August 1994 with a Master's project,
on which Associate Professor Peter Sestoft was my advisor. The title
of my Master's thesis [1994] is ''A Portable Implementation of Standard
ML.'' This thesis is about the implementation of the static semantics
(parsing and elaboration) of Core Standard ML (Standard ML without
Modules) and about implementation of the dynamic semantics (runtime
system and compilation into byte code) of Core Standard ML.

In the last year of my M.Sc. program, I worked as a part-time
programmer in Siemens Nixdorf Information Systems A/S, where I worked
with database technologies (Oracle), for implementing work-flow
applications.

#### Teaching

I have taught the following courses:

* Advanced Topics in Programming Languages (MSc course, PL for Quantum Computing
  theme). University of Copenhagen, DIKU. One fourth of course. Fall 2024.

* Programming and Problem Solving in F# (BSc intro course). University of
  Copenhagen, DIKU. One third of course. Fall 2020.

* Programming and Problem Solving in F# (BSc intro course). University of
  Copenhagen, DIKU. One third of course. Fall 2019.

* Programming and Problem Solving in F# (BSc intro course). University of
  Copenhagen, DIKU. One third of course. Fall 2018.

* Parallel Functional Programming. University of Copenhagen, DIKU. Course Responsible. Fall 2018.

* Programming and Problem Solving in F# (BSc intro course). University of
  Copenhagen, DIKU. One third of course. Fall 2017.

* Parallel Functional Programming. University of Copenhagen, DIKU. Course Responsible. Fall 2017.

* Parallel Functional Programming. University of Copenhagen, DIKU. Course Responsible. Fall 2016.

* Introduction to Scripting, Databases, and System Architecture. The IT University of Copenhagen. One fourth of course. Course Responsible. Spring 2008.

* Introduction to Scripting, Databases, and System Architecture. The IT University of Copenhagen. One third of course. Course Responsible. Fall 2007.

* Introduction to Scripting, Databases, and System Architecture. The IT University of Copenhagen. Half course. Course Responsible. Spring 2007.

* Advanced Topics in Language-based Security. The IT University of Copenhagen. Full Ph.D. course. Course Responsible. Spring 2005.

* Web Publishing with Databases. The IT University of Copenhagen. Full course. Spring 2005.

* Web Publishing with Databases. The IT University of Copenhagen. One half of the course. Fall 2004.

* Web Publishing with Databases. The IT University of Copenhagen. One half of the course. Spring 2004.

* Advanced Language Implementation and Language Based Security. The IT University of Copenhagen. One third of the course. Fall 2003.

* Web Publishing with Databases. The IT University of Copenhagen. Fall 2003.

* Data Processing. Seven lectures on Web programming with PHP and MySQL. Royal Veterinary and Agricultural University of Denmark. Spring 2003.

* Data Processing. Seven lectures on Web programming with PHP and MySQL. Royal Veterinary and Agricultural University of Denmark. Spring 2002.

* Web Publishing with Databases. The IT University of Copenhagen. Spring 2002.

* Web Publishing with Databases. Royal Veterinary and Agricultural University of Denmark. Summer 2001.

* Web Publishing with Databases. The IT University of Copenhagen. Fall 2000.

* Web Publishing with Databases. The IT University of Copenhagen. Spring 2000.

* Type-based Optimisation Techniques. Department of Computer Science, University of Copenhagen. Spring 1998.

* Aspects of Modules languages. Department of Computer Science, University of Copenhagen. Fall 1996.

I have supervised a high number of M.Sc. thesis students, B.Sc. thesis
students, and smaller projects at DIKU and at ITU. The projects have
covered compiler technology, type systems, and the development,
documentation, and testing of Web-based and traditional GUI-style,
database-enabled, systems in Java, C#, PHP, TCL, Haskell, and Standard
ML. One of the Master's thesis projects has resulted in a startup
company Neducate, specializing on community Web sites for individual
public schools in Denmark. I am currently supervising two
Ph.D. students within areas coverered by HIPERFIT.

#### Organisational Work and Training

During my time at [SimCorp](http://www.simcorp.com), I participated in
a series of courses developed by FTP (Financial Training Partners)
covering a number of topics including theoretical pricing of financial
derivatives. From May 2009 to 2012, I worked as Team Leader in the
Instrument Modeling Language team at SimCorp.

From August 2007 to May 2008, I served as the head of the international
technical ITU program Software Development and Technology. From
November 2003 to January 2005 I served as Head of the ITU Internet and
Software Technology Study Program. During 2004, I have attended a
management course at SHL Denmark. During the educational year
2001-2002, I have attended a pedagogical education program for
assistant professors at KVL, in addition to a course on project
supervision. I have been a co-organiser of the DIKU International
Summer School on Region-Based Memory Management, August 18-22, 1997,
held at the University of Copenhagen, Denmark. I have reviewed papers
for a series of conferences, workshops, and journals, including
PLDI'96, PLILP'96, IFL'97, POPL'97, SAS'97, PLDI'99, ESOP'01, ESOP'03,
HOSC, JFP, and TOPLAS. I have served on the programme committees for
the 2008 International Conference on Compiler Construction (CC'08),
the 2007 Nordic Workshop on Secure IT Systems (NordSec'07), the 2005
ACM SIGPLAN Workshop on ML (ML'05), held in Tallinn, Estonia,
September 2005, ARRAY'17, and ICFP'18. I have also served as programme co-chair for the 2006
ACM Workshop on Semantics, Program Analysis, and Computing
Environments for Memory Management (SPACE'06), held in South Carolina,
January 2006 and for the 2016 ACM SIGPLAN 3rd International Workshop
on Libraries, Languages and Compilers for Array Programming (ARRAY'16).

#### Publications

* [2024c] Robert Schenck, Nikolaj Hey Hinnerskov, Troels Henriksen, Magnus Madsen, Martin Elsman. AUTOMAP: Inferring Rank-Polymorphic Function Applications with Integer Linear Programming. In Proceedings of the ACM on Programming Languages, Volume 8, Issue OOPSLA2. Article No.: 334, 27 pages. Pasadena, USA. October, 2024.

* [2024b] Martin Elsman. Double-Ended Bit-Stealing for Algebraic Data Types. In Proceedings of the 2024 ACM SIGPLAN International Conference on Functional Programming (ICFP '24). Milan, Italy. September 4-6, 2024.

* [2024] Martin Elsman. Explicit Effects and Effect Constraints in ReML. In Proceedings of the 51st ACM SIGPLAN Symposium on Principles of Programming Languages (POPL '24), London, United Kingdom. January 17-19, 2024.

* [2023c] Lubin Bailly, Troels Henriksen, and Martin Elsman. Shape-Constrained Array Programming with Size-Dependent Types. In Proceedings of the 2023 ACM SIGPLAN International Workshop on Functional High-Performance and Numerical Computing (FHPNC '23). Seattle, Washington, USA. September, 2023.

* [2023b] Martin Elsman and Troels Henriksen. Parallelism in a Region Inference Context. In Proceedings of the 44th ACM SIGPLAN International Conference on Programming Language Design and Implementation (PLDI ’23), Orlando, Florida, USA. June 17-21, 2023.

* [2023a] Martin Elsman. Garbage-Collection Safety for Region-Based Type-Polymorphic Programs. In Proceedings of the 44th ACM SIGPLAN International Conference on Programming Language Design and Implementation (PLDI ’23), Orlando, Florida, USA. June 17-21, 2023.

* [2022] Martin Elsman, Fritz Henglein, Robin Kaarsgaard, Mikkel K. Mathiesen, and Robert Schenck. Combinatory adjoints and differentiation. In Ninth Workshop on Mathematically Structured Functional Programming (MSFP 2022). Munich, Germany. April, 2022.

* [2021a Troels Henriksen and Martin Elsman. Towards Size-Dependent Types for Array Programming. In Proceedings of the 8th ACM SIGPLAN International Workshop on Libraries, Languages and Compilers for Array Programming (ARRAY ‘21). Virtual Event. June, 2021.

* [2021] Martin Elsman and Niels Hallenberg. Integrating region memory management and tag-free generational garbage collection. In Journal of Functional Programming (JFP). Volume 31, E4. Cambridge University Press. February 2021.

* [2020a] Martin Elsman and Ken Friis Larsen. Efficient Translation of Certain Irregular Data-Parallel Array Comprehensions (Extended Abstract). In Draft Proceedings of the 21st International Symposium on Trends in Functional Programming (TFP '20). Krakow, Poland. February 2020. PDF.

* [2020] Martin Elsman and Niels Hallenberg. On the Effects of Integrating Region-based Memory Management and Generational Garbage Collection in ML. In International Symposium on Practical Aspects of Declarative Languages (PADL '20). New Orleans, USA. January, 2020.

* [2019d] Wojciech Pawlak, Martin Elsman, and Cosmin Oancea. A Functional Approach to Accelerating Monte Carlo based American Option Pricing. In 31st symposium on Implementation and Application of Functional Languages (IFL '19). Singapore. September, 2019.

* [2019c] Wojciech Pawlak, Martin Elsman, and Cosmin Oancea. Extended Abstract: A Functional Approach to Accelerating Monte Carlo based American Option Pricing. Presented at the 8th ACM SIGPLAN International Workshop on Functional High-Performance and Numerical Computing (FHPNC ‘19). Berlin, Germany. August, 2019.

* [2019b] Duc Minh Tran, Troels Henriksen, and Martin Elsman. Compositional Deep Learning in Futhark. In Proceedings of the 8th ACM SIGPLAN International Workshop on Functional High-Performance and Numerical Computing (FHPNC '19). Berlin, Germany. August, 2019.

* [2019a] Martin Elsman, Troels Henriksen, and Niels G. W. Serup. Data-Parallel Flattening by Expansion. In Proceedings of the 6th ACM SIGPLAN International Workshop on Libraries, Languages and Compilers for Array Programming (ARRAY '19). Phoenix, AZ, USA. June, 2019.

* [2019] Troels Henriksen, Frederik Thorøe, Martin Elsman, and Cosmin Oancea. Incremental Flattening for Nested Data Parallelism. In Proceedings of the 24th Symposium on Principles and Practice of Parallel Programming (PPoPP '19). Washington, DC, USA. February 2019.

* [2018c] Martin Elsman, Philip Munksgaard, and Ken Friis Larsen. Experience Report: Type-Safe Multi-Tier Programming with Standard ML Modules. In ML Family Workshop (ML '18). St. Louis, Missouri, USA. September 2018.

* [2018b] Troels Henriksen, Martin Elsman, and Cosmin E. Oancea.  Modular Acceleration: Tricky Cases of Functional High-Performance Computing.  In Proceedings of the 6th ACM SIGPLAN workshop on Functional High-Performance Computing (FHPC '18). St. Louis, Missouri, USA. September 2018.

* [2018a] Martin Elsman, Troels Henriksen, Danil Annenkov, Cosmin E. Oancea. Static Interpretation of Higher-Order Modules in Futhark. In Proceedings of the 2018 ACM SIGPLAN International Conference on Functional Programming (ICFP'18). St. Louis, Missouri, USA. September 2018.

* [2018] Danil Annenkov and Martin Elsman. Certified Compilation of Financial Contracts. In Proceedings of the 20th International Symposium on Principles and Practice of Declarative Programming (PPDP'18). Frankfurt am Main, Germany. September 2018.

* [2017a] Benjamin Egelund-Müller, Martin Elsman, Fritz Henglein, Omri
Ross. Automated Execution of Financial Contracts on Blockchains. In
Journal of Business and Information Systems Engineering (BISE). Nov 2017.

* [2017] Troels Henriksen, Niels G. W. Serup, Martin Elsman, Fritz
Henglein, and Cosmin Oancea. Futhark: Purely Functional
GPU-programming with Nested Parallelism and In-place Array
Updates. In Proceedings of the 2017 ACM SIGPLAN International
Conference on Programming Language Design and Implementation
(PLDI'17). Barcelona, Spain. June 2017.

* [2016c] Danil Annenkov and Martin Elsman. Towards Certified
Compilation of Financial Contracts. In Proceedings of the 28th Nordic
Workshop on Programming Theory (NWPT'16). Aalborg, DK. November, 2016.

* [2016b] Martin Dybdal, Martin Elsman, Bo Joel Svensson, and Mary
Sheeran. Low-level Functional GPU Programming for Parallel
Algorithms. In Proceedings of the 5th ACM SIGPLAN workshop on
Functional High-Performance Computing (FHPC'16). Nara,
Japan. September, 2016.

* [2016a] Troels Henriksen, Martin Dybdal, Henrik Urms, Anna Sofie
Kiehn, Daniel Gavin, Hjalte Abelskov, Martin Elsman, and Cosmin
Oancea. APL on GPUs - A TAIL from the Past, Scribbled in Futhark. In
Proceedings of the 5th ACM SIGPLAN workshop on Functional
High-Performance Computing (FHPC'16). Nara, Japan. September, 2016.

* [2016] Christian Andreetta, Vivien B&#233;got, Jost Berthold, Martin
Elsman, Fritz Henglein, Troels Henriksen, Maj-Britt Nordfang, and
Cosmin E. Oancea. FinPar: A Parallel Financial Benchmark. In ACM
Transactions on Architecture and Code Optimization (TACO). Volume 13,
Issue 2, Article 18. 27 pages. June 2016.

* [2015c] Patrick Bahr, Jost Berthold, and Martin Elsman. Certified
Symbolic Management of Financial Multi-Party Contracts. In ACM
International Conference on Functional Programming
(ICFP'15). Vancouver, Canada. September 2015.

* [2015b] Michael Budde, Martin Dybdal, and Martin Elsman. Compiling
APL to Accelerate through a Typed Array Intermediate Language. In
Proceedings of the 2nd ACM SIGPLAN International Workshop on
Libraries, Languages and Compilers for Array Programming
(ARRAY'15). Portland, Oregon, USA. June, 2015.

* [2015a] Christian Andreetta, Vivien Begot, Jost Berthold, Martin Elsman,
Troels Henriksen, Maj-Britt Nordfang, and Cosmin Oancea. A Financial
Benchmark for GPGPU Compilation. DIKU Technical Report no 2015/02. ISSN 0107-8283.
Extended version of CPC'15 paper. January 2015.

* [2015] Cosmin Oancea, Jost Berthold, Martin Elsman, and Christian
Andreetta. A Financial Benchmark for GPGPU Compilation. In 18th
International Workshop on Compilers for Parallel Computing
(CPC'15). January 2015.

* [2014c] Patrick Bahr, Jost Berthold, and Martin Elsman. Towards
Certified Management of Financial Contracts. In Proceedings of the
26th Nordic Workshop on Programming Theory (NWPT'14). October, 2014.

* [2014b] Troels Henriksen, Martin Elsman, and Cosmin E. Oancea. Size
Slicing - A Hybrid Approach to Size Inference in Futhark. In
Proceedings of the 3rd ACM SIGPLAN workshop on Functional
High-Performance Computing (FHPC'14). Guthenburg, SE. September,
2014.

* [2014a] Martin Elsman and Martin Dybdal. Compiling a Subset of APL
Into a Typed Intermediate Language. In ACM SIGPLAN International
Workshop on Libraries, Languages and Compilers for Array Programming
(ARRAY'14). Edinburgh, UK. June, 2014.

* [2014] Martin Elsman and Anders Schack-Nielsen. Typelets - A
Rule-Based Evaluation Model for Dynamic, Statically Typed User
Interfaces. In International Symposium on Practical Aspects of
Declarative Languages (PADL'14). San Diego, USA. January, 2014.

* [2011] Martin Elsman. SMLtoJs: Hosting a Standard ML Compiler in a
Web Browser. In ACM SIGPLAN International Workshop on Programming
Language And Systems Technologies for Internet Clients
(PLASTIC'2011). Portland, Oregon, USA. October, 2011.

* [2007] Martin Elsman. Fault-Tolerant Voting in a Simply-Typed Lambda
Calculus. IT University Technical Report Series. TR-2007-99. June 2007.

* [2006] Arne J. Glenstrup, Troels C. Damgaard, Lars Birkedal, and
Martin Elsman. BDNF-based Matching of Bigraphs. IT University
Technical Report Series. TR-2006-93. October 2006.

* [2005] Martin Elsman. Type-Specialized Serialization with
Sharing. In Sixth Symposium on Trends in Functional Programming
(TFP'05). Tallinn, Estonia. September 2005.

* [2004] Martin Elsman and Ken Friis Larsen. Typing XHTML Web
Applications in ML. In International Symposium on Practical Aspects of
Declarative Languages (PADL'04). Dallas, USA. June 2004.

* [2004a] Martin Elsman. Type-Specialized Serialization with
Sharing. IT University Technical Report Series. TR-2004-43. February 2004.

* [2004b] Mads Tofte, Lars Birkedal, Martin Elsman, and Niels
Hallenberg. A Retrospective on Region-Based Memory Management. In
Higher-Order and Symbolic Computation (HOSC). 17(3): 245-265.
Copyright © 2004 Kluwer Academic Publishers. September 2004.

* [2003] Martin Elsman and Ken Friis Larsen. Typing XHTML Web
Applications in SMLserver. IT University Technical Report
Series. TR-2003-34. October 2003.

* [2003a] Martin Elsman. Garbage Collection Safety for Region-based
Memory Management. In ACM SIGPLAN Workshop on Types in Language Design
and Implementation (TLDI'03). New Orleans, Louisiana, USA. January 2003.

* [2003b] Martin Elsman and Niels Hallenberg. Web Programming with
SMLserver. In Fifth International Symposium on Practical Aspects of
Declarative Languages (PADL'03). New Orleans, Louisiana, USA. January 2003.

* [2002] Martin Elsman and Niels Hallenberg. A Region-Based Abstract
Machine for the MLKit. IT University Technical Report
Series. TR-2002-18. August 2002.

* [2002a] Niels Hallenberg, Martin Elsman and Mads Tofte. Combining
Region Inference and Garbage Collection. In ACM International
Conference on Programming Language Design and Implementation
(PLDI'02). Berlin, Germany. June 2002.

* [2002b] Martin Elsman and Niels Hallenberg. SMLserver - A Functional
Approach to Web Publishing. Technical Report. Royal Veterinary and
Agricultural University of Denmark and IT University of
Copenhagen. February 2002.

* [1999] Martin Elsman. Static Interpretation of Modules. In Fourth
International Conference on Functional Programming (ICFP'99). Paris,
France. September 1999.

* [1999a] Martin Elsman, Jeffrey S. Foster, and Alexander
Aiken. Carillon - A System to Find Y2K Problems in C Programs. User's
Manual. Computer Science Division, University of California,
Berkeley. July 1999.

* [1999b] Martin Elsman. Program Modules, Separate Compilation, and
Intermodule Optimisation. Ph.D. thesis, revised. Department of
Computer Science, University of Copenhagen. January 1999.

* [2002c] Mads Tofte, Lars Birkedal, Martin Elsman, Niels Hallenberg,
Tommy Højfeld Olesen, Peter Sestoft, and Peter Bertelsen. Programming
with Regions in the MLKit. DIKU Technical Report. Department of
Computer Science, University of Copenhagen. Revised for Version 4, 2002. April 1997.

* [1998] Martin Elsman. Polymorphic Equality - No Tags Required. In
Second International Workshop on Types in Compilation (TIL'98). Kyoto,
Japan. March 1998.

* [1995] Martin Elsman and Niels Hallenberg. An Optimising Back-End
for the MLKit Using a Stack of Regions. Student Project. Department of
Computer Science, University of Copenhagen. July 1995.

* [1994] Martin Elsman. A Portable Standard ML
Implementation. Master's thesis. Department of Computer Science,
Technical University of Denmark. August 1994.

Most publications (except Journal papers) are available [online](/papers.html).

#### PhD Students

* Martin Dybdal (finished August 2017)

* Danil Annenkov (finished October 2017)

* Wojciech Michal Pawlak (industrial PhD student in collaboration with SimCorp)

#### Project Supervision (selected projects)

- Kristian Laudrup Hansen. Combinatory AD for Python. BSc Project (ongoing).

- Mark Seemann. On the Relationship between Referential Transparency and Haskell
  Purity. BSc Project. January 2025.

- Daniel Enemark Riegels. Migration and Inequality in Mexico. BSc Project,
  Computer Science and Economics. September 2024.

- Frederik Julius Palmø. BSc Project. Optimising JavaScript Performance with
  Web-Assembly. BSc Project. July 2024.

- Mathias Kilde Overgaard Hansen, Jeppe Hoffmann Hansen. Implementation of
  Artificial Intelligence in Soccer. BSc Project, KomIT. In Danish. June 2024.

- Axel Prütz Kanne, Svante Geisshirt. Unikernels with Region Inference. BSc
  Project. June 2024.

- Ferdinand Bjerre Wahl, Gustav Frederik Byberg, Mathias Lausten
  Schandorph. Sustainable Portfolio Management. BSc Project, Computer Science
  and Economics. July 2023.

- Oscar Halvoring Augustinus, Jesper Klose Dahlfelt. ESG Investments and Modern
  Portfolio Theory. BSc Project, Computer Science and Economics. July 2023.

- Magnus Holm Jensen, Johannes Munkedal Tange. Sustainable Investing with
  ESG-Weighted Modern portfolio Optimization. BSc Project, Computer Science and
  Economics. July 2023.

- Julius Husted Volden, Mattias Nørgaard Matsushita, Rasmus Julius Høy
  Petersen. Portfolio Optimization with ESG. BSc Project, Computer Science and
  Economics. July 2023.

- Tor Rosenberg Osted, Nicolai Veiglin Arends, Olivia Sommer
  Nørgaard. Optimising Sustainable Financial Portfolios. BSc Project, Computer
  Science and Economics. July 2023.

- Kasper Nicolaj Schiller. A Domain-Specific Language for Financial
  Contracts. BSc Project, Computer Science and Economics. July 2023.

- Ajanthan Veeravagu. Optimising Sustainable Financial Portfolios. BSc Project,
  Computer Science and Economics. July 2023.

- Emil Kragh Toft, Jonathan Weinreich Hansen. Determining Feature Importance
  Using OLS Regression and Random Forest in the Context of Factor Models. BSc
  Project, Machine Learning and Data Science. July 2023.

- Kasper Unn Weihe. Convex Optimization and Parallel Computing for Portfolio
  Optimization. MSc Project. June 2023.

- Oscar Nelin. Parallel Bytecode Interpretation in Futhark. MSc 7.5 ECTS
  Project. January 2023.

- Kristian Knudsen Olesen. Extracting Certified Futhark Code from Coq. BSc
  Project. November 2021.

- Louis Krog Kaufmann. Acceleration of CVA Calculations using Futhark. BSc
  Project. December 2020.

- Robert Schenck. Sum Types in Futhark. MSc Thesis Project. January 2020.

- Anna Sofie Kiehn, Henriks Urms. Refinement types in Futhark. MSc Project.
  September 2019.

- Jens Egholm Pedersen. Modelling learning systems in artificial and spiking
  neural networks. MSc Thesis Project, IT and Cognition. March 2019.

- Anders Kiel Hovgaard. Higher-Order Functions for a High-Performance
  Programming Language for GPUs. MSc Thesis Project. May 2018.

- Nicholas Christian Langkjær Ipsen, Erik Ledertoug. Accelerated Image
  Recognition in Futhark. BSc Project. June 2018.

- Christian Kjær Larsen. Formalization of Array Combinators and their Fusion
  Rules in Coq. BSc Project. June 2017.

- Jonas Aslet. Visualising Portfolio Evolution. BSc Project. January 2016.

- Christian Grønnegaard Nielsen, Mathias Frederik Kærlev. Chow - An Interpreted
  C-like Language for Game Development. BSc Project. June 2017.

- Jakob Høiberg Rasmussen. A GUI fpr a Blockchain-based Financial Contract
  System. BSc Project. June 2017.

- Anders Lau Svendsen, Mads Jørgensen, Peter Emil Jensen. Freechain - A
  Universal Blockchain Framework. BSc Project. June 2017.

- Christopher Mulvad Groot. Blockchain Consensus Mechanisms. BSc Project. June
  2017.

- Martin Paarse. Historic Volatilities and Correlations for Underlyings in the
  HIPERFIT Portfolio Management Prototype. BSc Project. June 2016.

- Mikkel Storgaard Knudsen. Modules in Futhark. BSc Project. June, 2016.

- Frederik Bøgelund Larsen. Reactive Functional GUI Abstractions in Haskell. BSc
  Project. January 2016.

- Anna Sofie Kiehn, Henrik Urms. Compiling TAIL to Futhark. BSc Project. June 2015.

- Benjamin Brandt Ohrt. Implementing Data Validation in an External
  Environment. BSc Company Project. October 2015.

- Niels G. W. Serup. Kernel Fission for GPGPUs. BSc Project. June 2014.

- Rasmus Borgsmidt. Functional Array Programming Compiled to a Virtual
  Machine. BSc Project. June 2013.

- Philip Munksgaard. SmlCL - An ML Library for Utilizing Parallel Architectures
  using OpenCL. BSc Project. June 2013.
