---
layout: page
title: DroidCov
description: Android Test Automation Tool
img: /assets/img/2.jpg
importance: 2 
category: Development
---

<h3> (2020) DroidCov: Android Test Automation Tool</h3>

<p>In this project we developed an automated way to test a set of Android apps using all the state-of-the-art Android testing tools
which are <a href="https://dl.acm.org/doi/pdf/10.1145/2931037.2931054">Sapienz</a> proposed in 2016,
<a href="https://dl.acm.org/doi/pdf/10.1109/ICSE.2019.00042">Ape</a> proposed in 2019, 
and <a href="https://developer.android.com/studio/test/monkey">Monkey</a> which is the most popular Android testing tool proposed by Google.
</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/2.jpg' | relative_url }}" alt="" title="Coverage results"/>
    </div>
</div>
<div class="caption">
   The statement coverage comparison of the three subject testing tools.
</div>

<ul>
<li>Used for <b>replication</b> of previous papers' experiments and testing a benchmark of around 30 Android apps automatically using all testing tools. Benchmark apps are selected from <a href="https://ieeexplore.ieee.org/abstract/document/7372031">Choudhary et al paper</a>, and <a href="https://dl.acm.org/doi/pdf/10.1109/ICSE.2019.00042">Ape paper</a>.</li>
<li>This tool can be used in a practical Android development context too, as it automatically can <b>test multiple versions of apps</b> using different testing tools simultaneously and collect <b>app failures and coverage results</b> for Android developers.</li>
<li> Studied the role of <b>randmocitiy</b> and <b>number of iterations</b> on the coverage achieved by proposed testing approaches. </li>
<ul>
