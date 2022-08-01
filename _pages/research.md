---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

**Doing More with Less: School Management and Education Production**. 2022. *Job Market Paper*
<br/> <small>[ Draft Coming Soon! ]</small>

**School Segregation, Student Achievement, and Parental Preferences**. 2022. <br/> <small>[ <a href="#/" onclick="visib('school_boundaries')">Abstract</a> | [Draft][school_boundaries] ]</small>

<div id="school_boundaries" style="display: none; text-align: justify; line-height: 1.2" ><small>
For most American K-12 students, where you live determines where you go to school. At the local level, school assignment is dictated by school attendance zones: boundaries that assign households to schools. I use geospatial data on the boundaries used to assign over 10 million public school students across 1,401 districts to identify changes in school assignment and estimate how these changes affect school segregation, student achievement, and neighborhood house prices. Comparing districts that impose integrative versus segregationary rezoning schemes shows that rezoning decisions can change segregation substantially, and that reductions in segregation narrow test score gaps between White and Black students. I find evidence that house prices fall in neighborhoods that are newly-assigned to schools with higher shares of Black and Hispanic students.
</small><br><br/></div>

[school_boundaries]:{{ site.baseurl }}{% link files/school_boundaries.pdf %}

**Budget Hawks on the Board: School Boards, Education Finance, and Student Achievement**. 2022. <br/> <small>[ <a href="#/" onclick="visib('school_boards')">Abstract</a> | Draft Coming Soon! ]</small>

<div id="school_boards" style="display: none; text-align: justify; line-height: 1.2" ><small>
Funding for education in America is spread across multiple levels of government, but financial decision-making is handled by locally elected school boards. During elections, many candidates for board seats run on promises of reforming district finances. I identify such "budget hawks" using natural language processing methods and campaign statements from school board candidates in California. I use a regression discontinuity design to test how district outcomes evolve in the years following the narrow victory of a hawk over a non-hawk. The election of a budget hawk leads to large cuts in district capital spending in the short-run and long-run reductions in operational spending. I find suggestive evidence that students in these districts exhibit lower rates of test-based proficiency in subsequent years. Heterogeneity analyses suggest that districts that exhibit higher reductions in spending experience larger test score declines. 
</small><br><br/></div>

[school_boards]:{{ site.baseurl }}{% link files/school_boundaries.pdf %}

**Economic Shocks and Skill Acquisition: Evidence from a National Online Learning Platform at the Onset of COVID-19** (with [Ina Ganguili](https://blogs.umass.edu/iganguli/), [Jamal I. Haidar](https://scholar.harvard.edu/haidar/home), [Asim Ijaz Khwaja](https://khwaja.scholar.harvard.edu/), and [Basit Zafar](https://sites.google.com/site/basitakzafar/)). 2022. <br/>
<small>[ <a href="#/" onclick="visib('saudi_skills')">Abstract</a> | [Draft][saudi_skills] | [NBER WP 29921][saudi_skills_nber] ]</small>

<div id="saudi_skills" style="display: none; text-align: justify; line-height: 1.2" ><small>
We study how large shocks impact individuals’ skilling decisions using data from the largest online learning platform in Saudi Arabia. The onset of the COVID-19 pandemic brought about a massive increase in online skilling, and demand shifted towards courses that offered skills, such as telework, likely to be immediately valuable during the pandemic. Consistent with a model where individuals trade off reskilling costs with their expectations of future labor market conditions and their duration of work, we find that shifts into telework courses were largest for older workers. In contrast, younger workers increased enrollments in courses related to new skills, such as general, occupation-specific, and computer-related skills. Using national administrative employment data, we provide suggestive evidence that these investments in skills in early 2020 helped users maintain employment over the course of the pandemic.
</small><br><br/></div>

[saudi_skills]:{{ site.baseurl }}{% link files/saudi_skills.pdf %}

[saudi_skills_nber]: https://www.nber.org/papers/w29921


[//]: This java script is the button to show abstract
<script>
 function visib(id) {
  var x = document.getElementById(id);
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>

[//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Abstract</button>