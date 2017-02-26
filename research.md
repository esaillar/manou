---
layout: page
title: Research
permalink: /research/
---

<div class="well" markdown="1">
# Research topics
</div>

I am interested in the development of tools that aim at **debugging** and **optimizing** HPC applications.

I began my thesis by focusing on a two-step detection of MPI collective errors in MPI applications. The first step statically identifies the reduced set of collective communications that may eventually lead to potential deadlock situations,
 and issues warnings. Using this analysis, a selective instrumentation of the code is then achieved, displaying an error, synchronously
 interrupting all processes, if the schedule leads to a deadlock situation. We observed a low compile-time and runtime overhead. This encourages us to 
 extend our method to multi-threaded contexts. The correctness of hybrid programs like MPI+OpenMP
 programs requires a special care regarding
 MPI calls location. The extension I proposed detect misuse of MPI collective operations inside and outside threaded regions.
 I adapted quite naturally this method to detect misuse of barriers and worksharing constructs in OpenMP applications.
 These features were regrouped in **PARCOACH**, a GCC plugin. Approach that we successfully applied to multiple benchmarks and applications.

Since December 2016, I am working on the European project HPC4E. My goal is to optimize kernels of some applications developed in the project with the metaprogramming language BOAST.

<div class="well" markdown="1">
# Publications

</div>
<div id="publications-hal">Loading publications from HAL...</div>
<script src="{{site.baseurl}}/js/hal.js"></script>
<script>load_from_hal("184161", "Emmanuelle Saillard" ,"{{site.baseurl}}");</script>

