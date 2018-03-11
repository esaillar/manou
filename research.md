---
layout: page
title: Research
permalink: /research/
---

<div class="panel panel-info" markdown="1">
  <div class="panel-heading">
    <h3 class="panel-title">Research topics</h3>
  </div>
  <div class="panel-body" markdown="1">
I am interested in the development of tools that aim at **debugging** and **optimizing** HPC applications.

I began my thesis by focusing on a two-step detection of MPI collective errors in MPI applications. The first step statically identifies the reduced set of collective communications that may eventually lead to potential deadlock situations,
 and issues warnings. Using this analysis, a selective instrumentation of the code is then achieved, displaying an error, synchronously
 interrupting all processes, if the schedule leads to a deadlock situation. We observed a low compile-time and runtime overhead. This encourages us to 
 extend our method to multi-threaded contexts. The correctness of hybrid programs like MPI+OpenMP
 programs requires a special care regarding
 MPI calls location. The extension I proposed detect misuse of MPI collective operations inside and outside threaded regions.
 I adapted quite naturally this method to detect misuse of barriers and worksharing constructs in OpenMP applications.
 These features were regrouped in **PARCOACH**, a GCC plugin. Approach that we successfully applied to multiple benchmarks and applications.

During this time, I developed dynamic program analyses for communication and synchronization optimizations in large scientific codes.

From December 2016 to September 2017, I worked on the European project HPC4E. My goal was to optimize kernels of some applications developed in the project with the metaprogramming language BOAST.

In October 2017, I joined the STORM team at Inria Bordeaux as a tenured reserach scientist (CR). 

  </div>
</div>


<div class="panel panel-info" markdown="1">
  <div class="panel-heading">
    <h3 class="panel-title">PARallel COntrol flow Anomaly CHecker (PARCOACH)</h3>
  </div>
  <div class="panel-body">

PARCOACH aims at helping developers in their debugging phase of parallel and distributed applications.

<a href="https://team.inria.fr/storm/software/parcoach/" target="_blank">Read more about PARCOACH</a>

  </div>
</div>
