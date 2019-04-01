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
I am interested in developing tools and methods that aim at **debugging** and **optimizing** HPC applications.

I have developed **PARCOACH**,a static/dynamic tool to detect collective errors in parallel applications. The static part identifies the reduced set of collective communications that may eventually lead to potential deadlock situations,
 and issues warnings. Using this analysis, a selective instrumentation of the code is then achieved, displaying an error, synchronously
 interrupting all processes, if the schedule leads to a deadlock situation. 

PARCOACH is implemented as a **LLVM pass** and is still under development.
  </div>
</div>


<div class="panel panel-info" markdown="1">
  <div class="panel-heading">
    <h3 class="panel-title">Projects</h3>
  </div>
  <div class="panel-body">
<td markdown="1">
- <p> <a href="http://hacspecis.gforge.inria.fr" target="_blank">HAC SPECIS</a>, project funded by Inria. </p>
- <p> ANR Exacard </p> 
- <p> COHPC, Inria associate team. <a href="https://team.inria.fr/cohpc/" target="_blank">Visit the website</a></p> 
</td>
  </div>
</div>


<div class="panel panel-info" markdown="1">
  <div class="panel-heading">
    <h3 class="panel-title">Software</h3>
  </div>
  <div class="panel-body">

- <p> PARallel COntrol flow Anomaly CHecker (PARCOACH) </p>
PARCOACH aims at helping developers in their debugging phase of parallel and distributed applications. The tool is still under development.

<a href="https://team.inria.fr/storm/software/parcoach/" target="_blank">Read more about PARCOACH</a>

  </div>
</div>



<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/css/bootstrap.min.css">
<link href="//netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap-glyphicons.css" rel="stylesheet">


<div class="panel-group" id="accordion" markdown="1">
 <div class="panel panel-info">
  <div class="panel-heading">
    <h3 class="panel-title"> <a class="accordion-toggle collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapse2"> Talks</a></h3>
  </div>
  <div id="collapse2" class="panel-collapse collapse">
  <div class="panel-body">
<td markdown="1">
- <a href="http://gpl2018.imag.fr/index.html" target="_blank">Journées nationales du GDR GPL, Grenoble June 12-15, 2018</a>
   Vérification des applications MPI par une anayse statique/dynamique  -  Verification of MPI applications using a static/dynamic analysis (Talk in french)
- <a href="http://tesson.julien.free.fr/LaMHA/2018/" target="_blank">Journée LaHMA, Paris December 13, 2018</a>
   Analyse statique/dynamique pour la vérification des applications parallèles  -  Static/Dynamic Analysis for the verification of parallel applications (Talk in french)

</td>
  </div>
  </div>
  </div>
</div>


<div class="panel panel-danger" markdown="1">
  <div class="panel-heading">
    <h3 class="panel-title">Open Internship Positions</h3>
  </div>
  <div class="panel-body">
<a href="{{site.baseurl}}/resources/M2_Intru.pdf" target="_blank">Static Selective Instrumentation for Parallel Programs Verification (M2)</a> 
  </div>
</div>
