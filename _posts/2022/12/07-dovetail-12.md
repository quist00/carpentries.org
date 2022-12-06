---
layout: page
authors: ["Zhian N. Kamvar"]
teaser: "More coordination needed"
title: "The Dovetail #11: Updates from The Carpentries Workbench"
date: 2022-12-07
time: "09:00:00"
tags: ["Lesson Infrastructure", "Community", "Carpentries Workbench", "Beta", "Dovetail"]
---

This is the twelfth post in [a series that we are calling "The Dovetail",
about the transition to The Carpentries Workbench](https://carpentries.org/posts-by-tags/#blog-tag-dovetail).
In this series, we aim to keep members of The Carpentries community abreast of
the current news about [the Workbench](https://carpentries.github.io/workbench). 

If you are interested in participating in discussions around The Carpentries
Workbench, head over to our GitHub Discussions forum: <https://github.com/carpentries/workbench/discussions>

<span style='font-size: large;'>If you have used the workbench and would like to provide feedback, please
<b><a href='https://carpentries.typeform.com/to/KRBl4IZM'>tell us about your experience</a>.</b></span> 

---

## IT'S GONNA BE MAY

In our [previous blog post]({{ site.url }}/blog/2022/11/dovetail-11/), we
outlined the goals of the beta phase, acknowledged the very real situation of
limited volunteer time, and announced that we will convert all of our lessons in
mid-April 2023. Since it was published, I have had some struggles with my own
health, did some thinking about the process, and decided to push back the
deadline. Thus, **we will convert all of our lessons to use The Carpentries
Workbench in May 2023.** Moreover, all of the [lessons in the Beta Phase](https://carpentries.github.io/workbench/beta-phase.html#beta) 
will undergo their transitions at the same time in Februrary and then April 2023. 


## Communication Breakdown

When we [annouced the Beta Phase]({{ site.url }}/blog/2022/05/workbench-beta/),
we had intended for the Beta Phase to start in the middle of July and run
through until the end of October, giving us time to transition the all of the
lessons by December. Of course, while we had taken into account [Hofstadter's law](https://en.wikipedia.org/wiki/Hofstadter%27s_law)
in planning the Beta Phase, situations beyond our control popped up and I had to
delay the Beta Phase until October. 

Before the beta phase went live, I checked in with the maintainers to see if
they were okay proceeding, but I had negelcted to give our volunteers any space
to let me know if they _could not_ continue with the beta testing of The
Workbench. Moreover, I was not adequately prepared for such an organisational or
communication task of this magnitude. Thus, communications were often sent out
on Fridays (from the US Pacific Coast), which often meant that they would get
buried in Monday communications. 

Thus

 - [Data Analysis and Visualization in R for Ecologists](https://github.com/datacarpentry/R-ecology-lesson/) (pre-beta; on hold)
 - [R for Social Scientists](https://github.com/datacarpentry/r-socialsci/) (pre-beta; delayed 2 weeks)
 - [Introduction to Geospatial Raster and Vector Data with R](https://github.com/datacarpentry/r-raster-vector-geospatial/) (pre-beta; on track)
 - [Data Cleaning with OpenRefine for Ecologists](https://github.com/datacarpentry/OpenRefine-ecology-lesson/) (cancelled)
 - [Library Carpentry: The UNIX Shell](https://github.com/LibraryCarpentry/lc-shell/) (on hold)
 - [Instructor Training](https://github.com/carpentries/instructor-training/) (on track)
 - [Análisis y visualización de datos usando Python](https://github.com/datacarpentry/pthon-ecology-lesson-es/) (on track)


### Lessons Currently In the Beta Phase

[R for Social Scientists](https://datacarpentry.org/r-socialsci) and 
[Introduction to Geospatial Raster and Vector Data with R](https://datacarpentry.org/r-raster-vector-geospatial) 
have both entered into the Workbench Beta Phase. The table below shows the
status of lessons that are currently in the beta phase:

| Lesson                                                   | Stage[^1] |  Workbench URL                                               | Next Transition Date |
| -------------------------------------------------------- | --------- | ------------------------------------------------------------ | -------------------- |
| Data Analysis and Visualisation in R for Ecologists      | pre-beta  | <https://preview.carpentries.org/R-ecology-lesson>           | 2023-02-06           |
| R for Social Scientists                                  | pre-beta  | <https://preview.carpentries.org/r-socialsci>                | 2023-02-06           |
| Introduction to Geospatial Raster and Vector Data with R | pre-beta  | <https://preview.carpentries.org/r-raster-vector-geospatial> | 2023-02-06           |
| Instructor Training                                      | pre-beta  | <https://preview.carpentries.org/instructor-training>        | 2023-02-06           |

[^1]: The Workbench Beta Phase is divided into three distinct stages, read more at <https://carpentries.github.io/workbench/beta-phase.html>.

## Updates to The Carpentries Workbench

Since 2022-11-16, 

 - [{sandpaper} version 0.10.6 -> 0.10.7](https://carpentries.github.io/sandpaper/news/index.html#sandpaper-0107)
   - Workflows have been updated to no longer throw warnings of deprecated GitHub commands
   - Automated pull requests will now go to a single branch for each type of pull request, updating as needed.
     This prevents the situation where there are multiple pull requests open from [@carpentries-bot](https://github.com/carpentries-bot), 
     with the last one superseding the previous ones. 
 - [{pegboard} 0.3.2](https://carpentries.github.io/pegboard/news/index.html#pegboard-032)
   - no updates :)
 - [{varnish} 0.2.8 -> 0.2.9](https://carpentries.github.io/varnish/news/index.html#varnish-028)
   - matomo analytics have been temporarily disabled.

To update your local Workbench installation, open R and use the following code:

```r
# Enable repository from carpentries
options(repos = c(
  ropensci = 'https://carpentries.r-universe.dev',
  CRAN = 'https://cloud.r-project.org'))
# Download and install sandpaper in R
install.packages(c('tinkr', 'pegboard', 'sandpaper', 'varnish'))
```

## Tips and Tricks for Using The Workbench

Make sure you stay hydrated and take time for self-reflection. 
