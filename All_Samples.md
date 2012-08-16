---
layout: basic

title: All Samples in GitHub.com/BlackBerry
tags: samples
jsfile: All_Samples.js
---
{% include common-defs.md %}

<div id='right'>
<div class='caption'>Samples Catalog</div>
<ul>
<li><a href="#samplesHtml5">HTML5 Samples</a></li>
<li><a href="#extensionsHtml5">HTML5 Extensions</a></li>
<li><a href="#samplesNative">Native Samples</a></li>
<li><a href="#samplesAir">AIR Samples</a></li>
<li><a href="#extensionsAir">AIR Extensions</a></li>
<li><a href="#samplesJava">Java Samples</a></li>
<!-- REMOVE start
<li><a href="#samplesOtherClient">Other Client Samples</a></li>
REMOVE end -->
<li><a href="#samplesServer">Other Samples</a></li>
</ul>
</div>

This page catalogs all the samples in RIM's
[GitHub Organization](http://github.com/blackberry)
through several tables generated from a [JSON file](All_Samples.json).
Also see the list of [All Repos].

<p style="margin-left: 20px;"><em>Currently Displaying
<span style='font-size:140%;' id='narrow-samplecount'><!-- dynamic content --></span> samples
containing
<span style='font-size:140%;' id='narrow-currenttag'><!-- dynamic content --></span></em>
</p>

If you like the samples [star them](https://github.com/blog/1204-notifications-stars).

<div style="margin-top:10px;" class="collapsable" label="Table, Tooltips and Sorting">
</div>
<div style="margin-top: 2px; margin-left:30px;">
There are <span id="stats-samplecount"><!-- dynamic content --></span> samples
optionally annotated with
<span class="question" tip="A list of 'tags' characterizing this sample">T</span>, 
<span class="question" tip="Extra details on the sample">?</span>
<span class="question" tip="This entry stands for a collection of samples">C</span>
and
<span class="warning" tip="Issues to resolve">!</span> tooltips
and organized into 4 tables.
The tables can be sorted on one or more columns: to select multiple
columns select the next column while pressing the 'SHIFT' (on mac) key.
</div>

<div label='Find using Tags' class='collapsable' style='margin-top:10px;'>
</div>
<div style='margin-top: 2px; margin-left:30px;'>
The set of samples displayed can be narrowed via tags; try clicking on these:
<span class='tagfilter'><em>native</em></span>,
<span class='tagfilter'><em>cascades</em></span>,
<span class='tagfilter'><em>html5</em></span>,
<span class='tagfilter'><em>air</em></span>,
<span class='tagfilter'><em>java</em></span>
<span class='tagfilter'><em>playbook</em></span>,
<span class='tagfilter'><em>bb10</em></span>,
and
<span class='tagfilter'><em>extension</em></span>.
To go back to showing all the samples click on on <span id='showAllSamples'><em>Show All</em></span>.

<!-- displaying was here -->

<div label="Using Additional Tags" class="collapsable" style="margin-top:10px;">
</div>
<div style="margin-left:+10px;">
<p>
The samples use
<span id='stats-tagcount'><!-- dynamic content --></span> other tags you can use to further refine your search:<div id='tagList'>
</div>
</p>
</div>
</div>

<div style="margin-top:10px;" class='collapsable' label="Repositories">
</div>
<div style="margin-top: 2px; margin-left:30px;">
<p style="margin-top: 2px;">The tables list the repository hosting each sample, in some cases
shortening the name for presentation purposes.
Samples come from <span id='stats-repocount'><!-- dynamic content --></span> repos:
</p>
<p><div id='repoList'><!-- dynamic content --></div></p>
</div>

<div style="margin-top:10px;" class='collapsable' label="Feedback and Todo">
<!-- dynamic content -->
</div>
<div style="margin-top:2px; margin-left:30px;">
<ul>
<li>Need different tags for "playbook, may run on bb10 but have not yet tested" from "playbook only"</li>
<li>Should consolidate the number of tags</li>
<li>Decide whether to split Native into Cascades vs the rest</li>
<li>Improve visual presentation of collapse/expand; maybe use down/right icons</li>
<li>Make Zebra striping work after narrowing</li>
<li>Decide how to hande Wiki links</li>
<li>The code that decides on "other" samples is fragile</li>
<li>The JavaScript code needs cleanup</li>
</ul>

<p>
We always welcome your feedback on how to best present information in this and related pages.
</p>
</div>


<div class="dynContent">
<div id="samplesHtml5">
<a name="samplesHtml5"><h2>HTML5 Samples</h2></a>
</div>

<a href="#top">Back to top</a>
</div>

<div class="dynContent">
<div id="extensionsHtml5">
<a name="extensionsHtml5"><h2>HTML5 Extensions</h2></a>
</div>

<a href="#top">Back to top</a>
</div>

<div class="dynContent">
<div id="samplesNative">
<a href="samplesNative"><h2>Native Samples</h2></a>
</div>

<a href="#top">Back to top</a>
</div>

<div class="dynContent">
<div id="samplesAir">
<a href="samplesAir"><h2>AIR Samples</h2></a>
</div>

<a href="#top">Back to top</a>
</div>

<div class="dynContent">
<div id="extensionsAir">
<a href="extensionsAir"><h2>AIR Extensions</h2></a>
</div>

<a href="#top">Back to top</a>
</div>

<div class="dynContent">
<div id="samplesJava">
<a href="samplesJava"><h2>Java Samples</h2></a>
</div>

<a href="#top">Back to top</a>
</div>

<!-- REMOVE for now, no entries

<div class="dynContent">
<div id="samplesOtherClient">
<a href="samplesOtherClient"><h2>Other Client Samples</h2></a>
</div>

<a href="#top">Back to top</a>
</div>

REMOVE until here -->


<div class="dynContent">
<div id="samplesOther">
<a href="samplesOther"><h2>Other Samples</h2></a>
</div>

<a href="#top">Back to top</a>
</div>