
# Capstone Project 1 Proposal - Comparing and Contrasting Charter Schools with Public Schools in Massachusetts

## Introduction

For a long time, the issue of school choice has been an important and highly debated subject. More recently, the debate has been renewed by proposals in the Department of Education to extend public funding in the form of waivers for students to attend alternatives to public schools. The DoE has also placed a greater importance on the role that charter schools, which have been coming under greater scrutiny within the last decade. One of the main reasons charter schools have become as controversial as they are is the lack or regulatory oversight that charter schools generally have. Without the same level of regulation as public schools, there are concerns of inequity and efficacy in the preparing of children for further education or careers.

## The project

In this project, I will investigate a few of these questions around the issue of charter schools and whether or not they provide equitable and effective alternatives to public schools. This project is for public knowledge as well as for those that are responsible for making decisions related to education policy. This sort of analysis could be used to determine the need/role for charter schools as well as any need for additional regulation.

To narrow my analysis, I will be analyzing data obtained from the state of Massachusetts, which details various demographic, enrollment, performance, disability, and fundamental statistics for all public and charter schools in Massachusetts. The data for my project can be found as part of this Github repository.

## Questions

The questions/concerns that I'm choosing to focus on are:

1. A common criticism of charter schools is that they are in effect accelarating re-segregation of schools. In previous national studies, it was found that three-quarters of charter schools were segregative to one particular minority, while the other quarter had similar demographics as their neighboring public schools. Is this the case in Massachusetts? In particular, in how many areas of the state are the charter school populations significantly different from the public school population?

2. There are also concerns that charter schools do not provide opportunities or services to students who are English language learners or have disabilities. Again, is there a significant difference between these populations for charter schools than those for public schools?

3. How do charter schools perform relative to public schools when it comes to preparing their students for higher education? Is there a significant difference in acceptance at either the 2- or 4-year college levels?

4. For elementary schools, are the state MCAS results for charter schools significantly different from their neighboring public schools?

5. Can we predict the success of a school from any of the above features? Also, if we were to collect similar data from previous years, would there be a trend in changing populations that we could use to predict the demographics of charter and public schools in the future?

## Method

To answer the above questions, I will attempt the following:

1. Clean and group the data obtained from the state of Massachusetts Department of Education by whether schools are public or charter. I will also separate the data into various data frames based on relevant features.

2. I will further group the data by zip code to make comparisons between neighboring schools so that the effect of region and/or income per capita on population demographics or school resources is reduced. I might also try grouping by other regional identifiers such as school district code or town.

3. Once the public and charter schools have been grouped by zip code, I will perform a two-sample goodness of fit test to see if there are statistically significant differences in the charter and public school populations for each of the questions I asked above.

## Deliverables

At the conclusion of this project, I will be able to deliver:

1. The code generating the statistics by zip code comparing charter schools with their neighboring public schools.

2. A paper outlining the results of this analysis as well as a slide-deck providing a narrative for any differences found.

3. Maps to highlight any regional factor that might be used for further data analysis.
