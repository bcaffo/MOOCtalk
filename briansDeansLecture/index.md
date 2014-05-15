---
title       : Teaching statistics for the future
subtitle    : The MOOC revolution and beyond
author      : Brian Caffo
job         : Department of Biostatistics, Johns Hopkins Bloomberg School of Public Health
logo        : bloomberg_shield.png
framework   : io2012
highlighter : highlight.js  
hitheme     : tomorrow       
url:
    lib: ../libraries
    assets: ../assets
widgets     : [mathjax, quiz, bootstrap]
mode        : selfcontained # {standalone, draft}
ext_widgets : {rCharts: [libraries/nvd3]}
---

## Teaching statistics for the future
### Outline of the talk
1. What I supposedly do during the day
2. A brief taxonomy and history of online educational models
3. Massive Open Online Courses (MOOCs) 
4. JHU Biostat involvement in Coursera
5. Novel moving target directions of the field statistics
6. **Data Science series** 
7. swirl

---
<a href="https://github.com/bcaffo/MOOCtalk"><img style="position: absolute; top: 0; right: 0; border: 0;" src="https://camo.githubusercontent.com/a6677b08c955af8400f44c6298f40e7d19cc5b2d/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f6769746875622f726962626f6e732f666f726b6d655f72696768745f677261795f3664366436642e706e67" alt="Fork me on GitHub" data-canonical-src="https://s3.amazonaws.com/github/ribbons/forkme_right_gray_6d6d6d.png"></a>

## About these slides
* HTML5 using (customized) [Google io2012 style](https://code.google.com/p/io-2012-slides/)
* Created using [slidify](http://slidify.org)
* Appear on github at (https://github.com/bcaffo/MOOCtalk) fork if you'd like
* Jointly written with my collaborators Jeff, Roger, Nick and Sean
* CC licensed by-nc-sa

---
## Thanks to the dean
<div align = "center">
<img src="../fig/Animal-House-21.jpg">
</div>
>- For taking time out of his busy schedule of cracking down on Delta Tau Chi for
this talk

---
## You know you've made it when
<div align = "center">
<img src="../fig/tbc.PNG">
</div>

---
## Core team

<div align="center">
<img src="../fig/brianCaffo.jpeg" alt="Drawing" style="height: 200px;"/>
<img src="../fig/jeffLeek.jpeg" alt="Drawing" style="height: 200px;"/>
<img src="../fig/rogerPeng.jpeg" alt="Drawing" style="height: 200px;"/>
</div>

<div align="center">
<img src="../fig/nickyC.jpg" alt="Drawing" style="height: 200px;"/>
<img src="../fig/seanKross.png" alt="Drawing" style="height: 200px;"/>
<img src="../fig/iraGooding.jpeg" alt="Drawing" style="height: 200px;"/>
</div>

--- &twocol w1:50% w2:50%
## Plus generous contributions from the

*** =left
- [Department of Biostatistics](http://www.biostat.jhsph.edu)
- [Center for Teaching and Learning](http://www.jhsph.edu/offices-and-services/center-for-teaching-and-learning/)
- [Bloomberg School of Public Health](http://www.jhsph.edu)
- [Johns Hopkins University](http://www.jhu.edu)
- [Coursera](http://coursera.org)
- Steve, Mike, Karen, Sukon

*** =right
- Everyone at CTL
- Everone at Multimedia 
- Team SWIRL
- Lauren and Ethan (Brian's 2013 interns)
- Contributions from github pull requests
- Tolerant families!
- 800 thousand intrepid self learners

---
## My day job(s)
### SMART (www.smart-stats.org)
<div align="center">
<img src="../fig/smart.png" alt="Drawing" style="width: 700px;"/>
</div>

---
## Connectomics
### resting state fMRI
<div align="center"><img src="../fig/defaultMode1.png" alt="Drawing" style="width: 600px;"/></div>
<br>
<div align="center">
<img src="../fig/defaultMode2.png" alt="Drawing" style="width: 600px;"/></div>

--- &twocol w1:50% w2:50%
## (Incomplete) characteristics of educational systems

*** =left
- Online / in person / blended
- Active/participatory/interactive learning
- Scalable / non-scalable
- Low cost / high cost / freemium
- Student paced / teacher paced
- Open / restricted access

*** =right
- Flipped / lecture style / blended 
- Open / closed source content
- Instructor interaction
- Credentialing 
- Funding model

---
## Examples
- Traditional in person teaching generally has characterists of: in person, lecture style, non-scalable, high cost, restricted access with a large amount of instructor interaction valued credentialing
- "Tranditional" online courses are online or blended online and in person and otherwise try to approximate traditional in person classes. 
- Online interactive learning (OIL Code School, Code academy) primary characteristics are student-paced interactive learning
- Intelligent tutoring systems (swirl), like OILs just not necessarily online
- Khan Academy is online, interactive, scalable and low cost
- Other modalities : iTunes U, OpenCourseware, Udemy

---
## MOOCs 

Primary characteristics are open access, low cost, scalable, online 

### (every letter is negotiable, from Wikipedia citing Mathieu Plorde)
<div align="center">
<a href=http://www.flickr.com/photos/23311795@N04/8620174342>
<img src="../fig/MOOC_poster_mathplourde.jpg" alt="Drawing" style="width: 600px;"/>
</a>
</div>

---
## Most visible MOOC instruction sites
<a href=https://www.edx.org/>
<img src="../fig/edX.png" alt="Drawing" style="height: 100px;"/>
</a>
<a href=https://www.udacity.com/>
<img src="../fig/udacity.png" alt="Drawing" style="height: 100px;"/>
</a>
<a href=https://www.udemy.com/>
<img src="../fig/udemy.jpeg" alt="Drawing" style="height: 100px;"/>
</a>
<a href=https://corsera.rog/>
<img src="../fig/coursera.png" alt="Drawing" style="height: 300;"/>
</a>

---
## Also
### Several university/organization-specific sites, platforms and content delivery systems
- Stanford, CMU, Duke, Harvard, MIT, google ...
- Varying degrees of content/delivery
- EdX platform has been open sourced
- Google course builder (now contributing to EdX)
- Massive amount of development going into platforms and instruction sites/portals

---
## Coursera platform, videos
<div align=center>
<img src="../fig/platformVideos.png" alt="Drawing" style="height: 200;"/>
</div>

--- &twocol w1:50% w2:50%

*** =left
## Example videos 
### (on YouTube)

- [Example from data science inference](https://www.youtube.com/watch?v=ZD7kR4QLFnE#t=269)
- [Ad hoc phone recording](https://www.youtube.com/watch?v=ZeS-ELmY7Fk)

*** =right
## Equipment

- [Cintiq 22inch display](http://www.wacom.com/en/us/creative/cintiq-22-hd)
- [Yeti usb microphone](http://bluemic.com/yeti/) 
- [Camtasia](http://www.techsmith.com/camtasia.html)
- [Note 2](http://www.samsung.com/global/microsite/galaxynote/note2/index.html?type=find)
- [Lecture notes](https://play.google.com/store/apps/details?id=com.acadoid.lecturenotes)
- [ffmpeg](http://www.ffmpeg.org/)

<img border="0" src="http://cdn.bluemic.com/images/yeti/main-right.jpg" alt="Pulpit rock" width="100" >

---
## Coursera platform, quizzes
<div align=center>
<img src="../fig/platformQuizzes.png" alt="Drawing" style="height: 300;"/>
</div>

---
## Coursera platform, peer grading
<div align=center>
<img src="../fig/platformPeerGrading.png" alt="Drawing" style="height: 250;"/>
</div>

---
## Coursera platform, forums
### You're on the internets
(Forums can be brutal)
<div align=center>
<img src="../fig/platformForums.png" alt="Drawing" style="height: 400px;"/>
</div>

--- 
## Johns Hopkins Biostat Coursera classes
### Original three
* Brian Caffo, Roger Peng, Jeff Leek
* Run 09/2012, 09/2012, 01/2013
<div align=center>
<img src="../fig/bootcamp_B-02.jpg" alt="Drawing"/>
<img src="../fig/computing_B-02.jpg" alt="Drawing"/>
<img src="../fig/data_B-02.jpg" alt="Drawing"/>
</div>

---
## Enrollments by class and offering
<iframe src="../fig/classPlot2.html" width=100%, height=600></iframe>


---
## Statements of accomplishment by offering
<iframe src="../fig/classPlot3.html" width=100%, height=600 ></iframe>



---
## Over time
<!-- MotionChart generated in R 3.0.3 by googleVis 0.5.2 package -->
<!-- Thu May 08 21:37:41 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataMotionChartIDf046e7189f () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "MBBC1",
new Date(2012,8,24),
16398,
749,
1,
0 
],
[
 "MBBC2",
new Date(2013,8,30),
10965,
508,
1,
0 
],
[
 "CDA",
new Date(2012,8,24),
50883,
3938,
1,
0 
],
[
 "DA",
new Date(2013,0,22),
101747,
4254,
1,
0 
],
[
 "Case",
new Date(2013,6,22),
19631,
2712,
1,
0 
],
[
 "StatReas",
new Date(2014,0,21),
26063,
1068,
1,
0 
],
[
 "fMRI",
new Date(2014,1,24),
23947,
1682,
1,
0 
],
[
 "Tools",
new Date(2014,3,7),
64515,
6467,
1,
1 
],
[
 "Rprog",
new Date(2014,3,7),
62433,
2965,
1,
1 
],
[
 "Clean",
new Date(2014,3,7),
33737,
781,
1,
1 
],
[
 "MBBC1",
new Date(2013,3,16),
22153,
1427,
2,
0 
],
[
 "MBBC2",
new Date(2014,0,6),
6742,
291,
2,
0 
],
[
 "CDA",
new Date(2013,0,2),
44661,
6271,
2,
0 
],
[
 "DA",
new Date(2013,9,28),
91379,
2246,
2,
0 
],
[
 "MBBC1",
new Date(2013,6,29),
18270,
1109,
3,
0 
],
[
 "CDA",
new Date(2013,8,23),
83441,
6768,
3,
0 
],
[
 "MBBC1",
new Date(2013,10,18),
18270,
408,
4,
0 
],
[
 "CDA",
new Date(2014,0,6),
65002,
4092,
4,
0 
],
[
 "MBBC1",
new Date(2014,2,3),
16454,
196,
5,
0 
] 
];
data.addColumn('string','class');
data.addColumn('date','date');
data.addColumn('number','enrollment');
data.addColumn('number','soa');
data.addColumn('number','offering');
data.addColumn('number','ds');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartMotionChartIDf046e7189f() {
var data = gvisDataMotionChartIDf046e7189f();
var options = {};
options["width"] =    600;
options["height"] =    400;

    var chart = new google.visualization.MotionChart(
    document.getElementById('MotionChartIDf046e7189f')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "motionchart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartMotionChartIDf046e7189f);
})();
function displayChartMotionChartIDf046e7189f() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartMotionChartIDf046e7189f"></script>
 
<!-- divChart -->
  
<div id="MotionChartIDf046e7189f"
  style="width: 600px; height: 400px;">
</div>


---
## Over time, MBBC 1
<iframe src="../fig/classPlot5.html" width=100%, height=600></iframe>



----
## Cumulative enrollment over all classes over time
<img src="assets/fig/unnamed-chunk-2.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" style="display: block; margin: auto;" />


---
## Completion rates
* Students participate in MOOCs for a variety of reasons
* Numerous students sign up for a course, but do not 
actively participate
* Recent MBBC 1
  * 17K students
  * 10K accessed the course site ever
  * 7K watched any video ever
  * 2K submitted any quiz
  * 196 earned a SOA
  * 129 signature track
  * 128 posted to the forums

--- 
## Some summary statistics
* Classes considered are MBBC1, MBBC2, CDA, DA, Case, StatReas, fMRI, Tools, Rprog, Clean
* A total of 776,691 students enrolled  
* 19 class offerings


* Average of 40,878 students per class
* Minimum class size of 6,742 for class
MBBC2 offering 2
* Maximum class size of 101,747 for class
DA offering 1

---
## Signature track

<div align="center">
<img src="../fig/sigTrack.jpeg" alt="Drawing" style="height: 100px;"/>
<img src="../fig/verified.png" alt="Drawing" style="height: 100px;"/>
</div>

- Verification based on typing patterns (highly unique according to Coursera)
  - Secondary verification via webcams
- Coursera gives student aid
- Revenue distribution via agreement between Coursera and partner institution
- 155 signature track for 20k students in MBBC1 V4
- Much higher retention and completion rates for signature track
- Between 1% and 12% Signature track rate for classes (depending on a variety of factors)
- All of our classes are $49 for sig track

--- &twocol w1:50% w2:50%
## Interesting fallout from doing this

*** =left
- Jeff's class was listed as one of the top 10 most enrolled Coursera classes
  - Roger's class has since eclipsed it in cumulative enrollment
- Brian, Roger, Martin, John have run signature track ($49 per student)
- Brian's class featured on the front page of the Washington Post 
- Roger interviewed on Anderson Cooper and NPR

*** =right
- Scott Zeger introduced class *Cased Based Introduction to Statistics*
- Brian introducted *MBBC2*
- Martin Lindquist introduced *Statistical Analysis of fMRI Data*
- John McGready introduced *Statistical Reasoning for Public Health*

---
## MOOCs by university
<iframe src="../fig/classPlot6.html" width=100%, height=600 ></iframe>


  
---
## Case studies

<div align="center">
<img src="../fig/email1.png" alt="Drawing" style="height: 300px;"/>
</div>

---
## Case studies

<div align="center">
<img src="../fig/email2.png" alt="Drawing" style="height: 300px;"/>
</div>

---
## Case studies

<div align="center">
<a href = "http://www.fastcompany.com/3029295/bottom-line/why-the-worlds-largest-mooc-says-it-can-help-you-get-ahead-in-the-new-economy">
<img src="../fig/JL.PNG" alt="Drawing" style="height: 200px;"/>
</a>
<a href = "https://twitter.com/ahalterman/status/425805189380308992">
    <img src="../fig/jl2.png" alt="Drawing" style="height: 300px;"/>
</a>
</div>

---
## Statistics, big data, data science

<div align=center>
<img src="../fig/shortage.png" alt="Drawing" style="height: 300px;"/>
</div>

---
## Complimentary problems
<div align=center>
<img src="../fig/incomesTuition.png" alt="Drawing" style="height: 300px;"/>
</div>

---
## Johhs Hopkins Data Science Specialization
### Codirected and taught by Roger Peng, Jeff Leek and Brian Caffo

<div align=center>
<img src="../fig/dataScience.png" alt="Drawing" style="height: 500px;"/>
</div>

---
## Courses

<div align=center>
<img src="../fig/courses.png" alt="Drawing" style="height: 500px;"/>
</div>

---
## Specialization certificate

<div align=center>
<img src="../fig/specilizationCertificate.png" alt="Drawing" style="height: 500px;"/>
</div>

--- &twocol w1:50% w2:50%
## Unique aspects of the program
*** =left
- Completely redesigned stat curriculum
- 9 signature track courses
- 1 capstone project course
- Total cost (modular) $490
  - $49 per sig track for 10 classes

*** =right
- Each class is four weeks
- Quizzes, in video quizzes, programming assignments and peer assessment projects
- Run monthly after initial rollout
- All content open source
- Toolbox, R Programming and Getting and Cleaning Data have all run
(enrollments of 64k, 62k, 34k resp)

--- 
## Platform choices
- Everything done on Coursera
- All programming in R
- All lecture notes done in Slidify (common theme)
- All content open source
- Version control through git and github
- (Students will learn and use git)
- RStudio as an IDE
- knitr for reproducible documents and report writing

---  &twocol w1:50% w2:50%
## Standard and non-standard stat content 
*** =left
- Basic probability and math stat
- Statistical inference
  - Hypothesis tests, confidence intervals, likelihood
  - Brief intro to Bayesian analysis
- Regression and generalized linear models
- Statistical machine learning
- EDA
- Data analysis

*** =right
- Reproducible research, report generation
- Presentations
- Interactive graphics (rCharts, shiny, manipulate, googleVis)
- Data munging, obtaining data
- Programming
- Plotting (ggplot2, rCharts, R base graphics)
- Capstone project


---
## Shiny is pretty neat

<div align=center>
<img src="../fig/shiny01.png" alt="Drawing" style="height: 300px;"/>
</div>
* [Shiny example John Muschelli's app](https://muschellij2.shinyapps.io/ENAR_2014/)
* [Rawan Allozi's algorithm](http://spark.rstudio.com/bcaffo/pta/)
* Rstudio is giving free hosted shiny apps for students in the concentration!

---
## Capstone industry partnerships
* Current negotiations are ongoing for exciting capstone projects
* Company donates the data to the Specialization that the students analyze for their project
    * Prepare video or documentation outlining the problem
* University MOUs being finalized with some of the most exciting tech companies

---
## Cost comparison with other programs
<div align="center">
<img src = "../fig/dscompare.png">
</div>


---
<br>
<br>
<br>
<div align="center">
<img src = "../fig/swirl/swirl.png" style="height: 300px;"/>
</div>

---
## A friendlier way to learn R...

<div align="center">
<img src = "../fig/swirl/Screenshot 2014-05-08 11.58.39.png" style="height: 500px;"/>
</div>

---
## Self-paced and interactive

<div align="center">
<img src = "../fig/swirl/Screenshot 2014-05-08 12.02.43.png" style="height: 500px;"/>
</div>

---
## Learn R and stats, together

<div align="center">
<img src = "../fig/swirl/Screenshot 2014-05-08 12.06.28.png" style="height: 500px;"/>
</div>

---
## swirl + Coursera

<div align="center">
<img src = "../fig/swirl/Screenshot 2014-05-08 12.16.23.png" style="height: 500px;"/>
</div>

---
## Get Coursera credit, automatically

<div align="center">
<img src = "../fig/swirl/Screenshot 2014-05-08 12.17.26.png" style="height: 500px;"/>
</div>

---
## Make your own interactive content

<div align="center">
<img src = "../fig/swirl/Screenshot 2014-05-01 23.52.07.png" style="height: 500px;"/>
</div>

---
## swirlstats.com

<div align="center">
<img src = "../fig/swirl/Screenshot 2014-05-08 13.05.12.png" style="height: 500px;"/>
</div>

---

<br>
<br>
<br>
<br>
<br>
<br>
<div align="center">
<img src = "../fig/swirl/Screenshot 2014-05-08 12.03.35.png" style="height: 200px;"/>
</div>


---
Thanks!
=========
* Jeff, Roger, Nick, Sean, Ira
* Johns Hopkins
* Bloomberg School of Public Health
* Department of Biostatistics
* SMART group
    * Ciprian, Martin, Ani, Vadim
* Students

---
## My peeps
<div align=center>
<img src="../fig/theGirls.jpg" style="height: 400px;"/>
</div>

--- 
## Version test2 

