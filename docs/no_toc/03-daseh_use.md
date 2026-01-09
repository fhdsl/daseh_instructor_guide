


# Use of DaSEH

## Learning Objectives


This chapter will provide guidance on how to use DaSEH resources for instruction. 

- We will give a information on what material is appropriate for beginner, intermediate, or advanced learners.
- We will describe ways that instructors can use the full set of DaSEH resources, some of the modules, or just the data.
- We will present some examples of extensions that can accompany the materials and can serve as a template for homework assignments or independent student exploration. 

The examples presented in this chapter are merely suggestions - modifications to the material to fit student needs are expected and encouraged! If you come up with a different way to use our resources, please [let us know]https://daseh.org/contact.html) what you come up with so that other educators may be inspired by your creativity. 

### Prerequisites


#### Environmental Health Subject Matter
 
The materials in DaSEH use data related to environmental health. There is no requirement for any prior knowledge on environmental health. The resources are also applicable for those interested in data science for other uses. 

#### Statistics

The DaSEH materials do expect some familiarity with statistics and focuses mostly on the application of R for analysis, rather than the theory of statistics. We recommend additional resources for statistics if you are teaching a statistics course.

#### Coding/Data Science

All materials for DaSEH use the R statistical programming language for data analysis. No familiarity with R basics is expected for learners.  

#### Software 

All case studies use the R statistical programming language for data analysis. While there is no specific R version requirement for the case studies, the `OCSdata` package, which can be used to get and load the data, does require R 3.5. Furthermore, R packages used to run specific analyses in each case study may have their own R version requirements. R version requirements may be checked in the `sessionInfo()` section in each case study.  


### Experience Level Descriptions

The table below explains how we define the beginner, intermediate, and advanced experience levels. 

| Experience Level | Description |
| ------- | ---------------- |
| Beginner | Little to no previous experience with coding and/or statistical analysis. |
| Intermediate | Familiar with at least one programming language and has experience working with data and statistics. |
| Advanced | Fluent in at least one programming language and likely familiar with more. Has a depth of experience working with data science projects. |

Typically, most middle/high school and first year undergraduate students will fit in the beginner category. Upperclassmen undergraduates and some graduate students are often at the intermediate level. Most advanced level students will be at the graduate level. However, this is a generalization, and a student may be considered beginner, intermediate, or advanced at any academic level depending on their independent studies and experiences. 

## DaSEH in the Classroom

The DaSEH materials are structured in a modular manner to support both partial and full use of our materials. Educators are also free to use the DaSEH data by itself.  

### Teaching the full set of materials

The DaSEH materials are written to provide a comprehensive introduction to enviornmental health data science. Our materials provide students with experience in all the  standard aspects of a data science workflow as well as best practices regarding reproducibility. The following list provides a few examples of how educators could use the mateirals: 

- Use our full set of slides as lecture and materials as we have used them
- Do a flipped classroom approach and assigned students to read the slides as homework and do labs in the class together
- Assign students to extend analysis beyond what is shown in our lecture or lab materials to dive deeper or provide more homework 


#### Duration

DaSEH was designed to fit the duration of an intensive two week short course for 3.5 hours a day for roughly 32 hours of instruction time. However, the materials could also be spread out to fit a semester 16 week long course.


### Teaching Part of the DaSEH Materials

Some educators may find that only certain modules are relevant to their course learning objectives. Each provides information about how to access the appropriate data. Note that you may have to add some introduction to explain any functions that were explained in a previous module. 


* For a data visualization course, the following modules could be helpful:

   - Basic R (only if students don't have familiarity with R)
   - RStudio  (only if students don't have familiarity with R)
   - Manipulating Data in R (to convert data from wide to long format to facilitate data visualization)
   - Intro to Data Visualization
   - Data Visualization
   - Factors

* For a data wrangling course, the following modules could be helpful:

    - Basic R
    - RStudio  (only if students don't have familiarity with R)
    - Subsetting Data in R
    - Data Classes
    - Data Cleaning
    - Manipulating Data in R
    - Factors

* For a reproducibility course the following modules could be 
  
<br>





### Teaching With Case Study Data Only

Educators can use the data available with the case studies without using the case study as a whole. The data is available on GitHub and can be accessed using the `OCSdata` R package. 


## Case Study Recommendations

Each case study demonstrates an entire data analysis starting from data import and wrangling and continuing to statistical analysis and data visualization. This means that individual case studies can often incorporate different skill levels for different stages of the analyses. For example, a case study can use advanced data wrangling approaches but only need beginner level statistical analysis methods. Below we provide broad categorizations of each of the case studies in terms of the skill levels required (beginner, intermediate, or advanced) for each of the general stages of the case studies (data wrangling, data visualization, and statistics). More details on the specific skills taught in each case study can be found in the [Case Study Search Tool](https://www.opencasestudies.org/#searchtab) or in the Learning Objectives section in each case study. 

Here, we are using the following interpretations of "beginner", "intermediate", and "advanced":  

<br>

| Skill Level | Data Import | Data Wrangling | Data Visualization | Statistics | 
| ------- | --------- | --------- | ------- | --------- |
| Beginner | No experience with importing data into any programming language | No experience wrangling and cleaning raw data in any programming language | No experience visualizing data in any programming language | No experience with statistical concepts |
| Intermediate | Some experience with importing common data formats (e.g. CSVs) into R or significant experience in another programming language | Some experience wrangling or cleaning raw data in common formats (e.g. numerical data) in R or significant experience in another programming language | Some experience with common visualization packages in R (e.g. ggplot) or significant experience in another programming language | Some familiarity with common statistical concepts (e.g. summary statistics, hypothesis testing) and techniques (e.g. t-test) |
| Advanced | Experience with importing uncommon data types (e.g. PDFs or web-scraping) and comfort with troubleshooting import challenges | Experience cleaning and wrangling raw data in uncommon formats (e.g. regular expressions) in R and comfort with troubleshooting wrangling challenges | Experience with creating complex data visualizations in R and comfort with visualization challenges | Good understanding of foundational statistical concepts and comfort with applying foundational statistical techniques |



The following table lists a few example case studies that would be suitable for each experience level. 


| Case Study | Data Import | Data Wrangling | Data Visualization | Statistics | 
| ------- | --------- | --------- | ------- | --------- |
| School Shootings in the United States | Intermediate | Beginner | Advanced | Beginner | 
| Disparities in Youth Disconnection | Intermediate | Beginner | Beginner | Beginner | 
| Opioids in United States | Intermediate | Beginner | Beginner | Intermediate | 
| Vaping Behaviors in American Youth | Beginner | Beginner | Beginner | Intermediate | 
| Mental Health of American Youth | Advanced | Beginner | Beginner | Beginner | 
| Exploring global patterns of obesity across rural and urban regions | Intermediate | Beginner | Beginner | Beginner | 
| Influence of Multicollinearity on Measured Impact of Right-to-Carry Gun Laws - Part 1 | Beginner | Advanced | NA | NA | 
| Influence of Multicollinearity on Measured Impact of Right-to-Carry Gun Laws - Part 2 | NA | NA | Intermediate | Advanced | 
| Exploring CO2 emissions across time | Beginner | Beginner | Beginner | Beginner | 
| Exploring global patterns of dietary behaviors associated with health risk | Intermediate | Intermediate | Intermediate | Intermediate | 
| Predicting Annual Air Pollution | Beginner | Beginner | Intermediate | Advanced | 
| Exploring health expenditure using state-level data in the United States | Beginner | Beginner | Beginner | Beginner | 

## Troubleshooting

You may encounter errors trying to render our case studies. 

In which case, we suggest that you check the "Session Info" section under the "Additional Information "section of the case study to see what versions of packages we used. 

R packages versions can have updates to arguments and function names that can cause code to work differently or can break the code.

If you encounter an error, this is likely the reason. We try to update our case studies when we can, but we can't always update the information in a timely manner as this is currently a passion project. You can either use the error message from trying to knit the case study to determine what function may have been updated or deprecated (we recommend this option to help you or your students learn the most up-to-date information), or you can use the versions of the packages that are shown in our Session Info section and load the versions that we used, following the directions [here](https://search.r-project.org/CRAN/refmans/remotes/html/install_version.html). 

## Example Use Cases

Because the case studies were developed to be modular and stand-alone, they can be used in a variety of ways that cater to the learner's goals, experience, and interests. Below, we provide a few examples of how case studies have been used previously. If you use Open Case Studies in a new way, we would love to [hear](https://www.opencasestudies.org/#contact) about it! 

### Using Case Studies as Lecture Content

[Practical Data Science in R](https://cogs137.github.io/website/) is a 10-week intermediate undergraduate course taught by [Dr. Shannon Ellis](https://www.shanellis.com/) at University of California Santa Barbara. In 2021, Dr. Ellis taught the course using three Open Case Studies and used them to illustrate how foundational data science skills and statistical concepts taught throughout the course can be applied to real data. 

Here you can see how the course used the `OCSdata` package:



[Dr. Ellis](https://www.shanellis.com/) incorporated labs and homework assignments into the course, which had guided coding and analysis exercises related to the concepts discussed in lecture which used content from the case studies in a slide format. She also assigned written reports where students presented the analysis they conducted related to the case study in the format of a scientific article (see example assignment below). 

### Using Case Studies for Assignments

[Advanced Data Science](http://jtleek.com/ads2020/) was a semester-long graduate data science course taught by [Dr. Jeff Leek](https://jtleek.com/) and [Dr. Roger Peng](https://rdpeng.org/) in 2020 at Johns Hopkins Bloomberg School of Public Health, primarily for PhD students. This course is designed for students to gain experience in designing and communicating data analyses effectively and critically analyzing analyses. Assignments included [writing scientific journal sections](https://github.com/advdatasci/homework9) (e.g. Introduction, Methods, Results, Discussion) based on the case studies and [extending analyses](https://github.com/advdatasci/homework11) based on results presented in the case study. 

### Independent Study

Case studies can be used for learners to gain experience in statistics and data science independently. We strongly recommend that independent learners aim to actively engage with the case study by running the analyses independently, exploring the data beyond what is presented in the case study, and extending the analyses by to investigate their own hypotheses. Furthermore, creating a finished product, such as a blog post or a presentation, can be an excellent demonstration of the skills learned. 

### Interactive Case Studies

Some of the case studies also have interactive versions. These versions allow students to write and run code in the browser interactively, with hints and answers available for students to check their progress as they go through the case study. Interactive case studies could be appropriate for independent learning or for in class labs, as they provide real time feedback and can reduce demands on the educator to provide intensive personalized feedback. Please see the following video for a demonstration on how to use the interactive case studies:   



## Examples of assignments 

Educators are not limited to having the students go through the case study in their current format. Case studies can be a spring board for further exploration and additional assignments. For example, in addition to helping students develop data analysis skills, we hope that the case studies can also help students develop their curiosity, technical writing and communication skills. Additional assignments can include but is not limited to data visualization and presentation, written reports, and oral presentations. Below we provide a few examples of potential assignments that educators can use to tailor instruction to the desired learning objectives. See [here](http://jtleek.com/ads2020/week-5.html) guidelines about considerations for effective and ethical data visualizations from the [Advanced Data Science Course](http://jtleek.com/ads2020/) taught by [Jeff leek](https://jtleek.com/) and [Roger Peng](https://rdpeng.org/) at [Johns Hopkins Bloomberg School of Public Health](https://publichealth.jhu.edu/).

### Written Report 

Below is an example of a scientific-style paper written based on the [Opioid Use Case Study](https://www.opencasestudies.org/ocs-bp-opioid-rural-urban/#Main_Question). We also include an example rubric by which this paper can be evaluated adapted from [here](https://ocw.mit.edu/courses/biological-engineering/20-109-laboratory-fundamentals-in-biological-engineering-spring-2010/assignments/guidelines-for-writing-up-your-research/#Evaluation). 

- [OCS Opioid Use in the US Example Report](https://raw.githubusercontent.com/opencasestudies/OCS_Guide/main/assets/OCS_Opioids_Example_Report.pdf)

- [OCS Opioid Use in the US Example Report Rubric](https://raw.githubusercontent.com/opencasestudies/OCS_Guide/main/assets/OCS_Opioids_Example_Report_Rubric.pdf)

### Oral Presentation 

Below is an example of a presentation based on the [Vaping Behaviors in American Youth Case Study](https://www.opencasestudies.org/ocs-bp-vaping-case-study/). This presentation focuses on the context of the study and the methods used in the analysis. Assignments for presentations can be modified to emphasize presenting results and conclusions or to emphasize communication to different audiences (e.g. policy makers, other researchers, the public, etc. ).  

- [OCS Vaping Case Study Oral Presentation Assignment Example](https://github.com/advdatasci/homework12)
- [OCS Vaping Case Study Oral Presentation Example](https://www.youtube.com/watch?v=noWLCSipKEU)


### Data Visualization

The data visualizations included in the case studies are not the only way to present the data used within the analyses. While the principles of effective data visualization are a focus of the case studies, the data included as well as the study questions can be used to guide students through the design choices that are commonly considered when determining how to best present data. Students can be assigned to create a new visualization beyond what is included in the case studies that emphasizes different aspects in the data.

### Further Exploration

Several case studies have additional data that is not discussed. This can be used for further exploration of the subject area that was discussed in the case study. This can be guided by the questions included in the Homework section of the case studies. Case studies that have additional data include the [Opioid Use Case Study](https://www.opencasestudies.org/ocs-bp-opioid-rural-urban/#Main_Question), the [Right to Carry Case Study](https://www.opencasestudies.org/ocs-bp-RTC-analysis/), and the [CO2 Emissions Case Study](https://www.opencasestudies.org/ocs-bp-co2-emissions/).

Below is an example of an assignment assigned to students in the [Advanced Data Science Course at Johns Hopkins](http://jtleek.com/ads2020/). In this assignment students were asked to create a simpler machine learning analysis based on the case study. They were also asked to share their analysis with another student and write a summary and critique of the other student's analysis. This provides an opportunity for the student to try out analysis skills with their own analysis work, and also work on their comprehension skills of reading other people's work. It also shows how we can get different results with minor changes in our analyses.:

 - [OCS Air Pollution Extension Assignment Example](https://github.com/advdatasci/homework12)


*Acknowledgments*

We would like to thank the following people for generously sharing the ways in which they used Open Case Studies materials in their teaching:  

- [Dr. Shannon Ellis](https://www.shanellis.com/)
- [Dr. Jeff Leek](https://jtleek.com/)
- [Dr. Roger Peng](https://rdpeng.org/)



## Session info


```
## R version 4.3.2 (2023-10-31)
## Platform: x86_64-pc-linux-gnu (64-bit)
## Running under: Ubuntu 22.04.4 LTS
## 
## Matrix products: default
## BLAS:   /usr/lib/x86_64-linux-gnu/openblas-pthread/libblas.so.3 
## LAPACK: /usr/lib/x86_64-linux-gnu/openblas-pthread/libopenblasp-r0.3.20.so;  LAPACK version 3.10.0
## 
## locale:
##  [1] LC_CTYPE=en_US.UTF-8       LC_NUMERIC=C              
##  [3] LC_TIME=en_US.UTF-8        LC_COLLATE=en_US.UTF-8    
##  [5] LC_MONETARY=en_US.UTF-8    LC_MESSAGES=en_US.UTF-8   
##  [7] LC_PAPER=en_US.UTF-8       LC_NAME=C                 
##  [9] LC_ADDRESS=C               LC_TELEPHONE=C            
## [11] LC_MEASUREMENT=en_US.UTF-8 LC_IDENTIFICATION=C       
## 
## time zone: Etc/UTC
## tzcode source: system (glibc)
## 
## attached base packages:
## [1] stats     graphics  grDevices utils     datasets  methods   base     
## 
## loaded via a namespace (and not attached):
##  [1] jsonlite_2.0.0   dplyr_1.1.4      compiler_4.3.2   gitcreds_0.1.2  
##  [5] promises_1.2.1   tidyselect_1.2.0 Rcpp_1.0.12      xml2_1.5.1      
##  [9] webshot2_0.1.2   stringr_1.5.1    jquerylib_0.1.4  later_1.3.2     
## [13] tidyr_1.3.1      yaml_2.3.12      fastmap_1.1.1    readr_2.1.5     
## [17] R6_2.6.1         generics_0.1.3   knitr_1.50       tibble_3.3.0    
## [21] bookdown_0.46    rprojroot_2.1.1  bslib_0.6.1      pillar_1.9.0    
## [25] tzdb_0.4.0       rlang_1.1.6      utf8_1.2.4       websocket_1.4.4 
## [29] cachem_1.0.8     stringi_1.8.3    xfun_0.55        sass_0.4.8      
## [33] cli_3.6.5        magrittr_2.0.3   ps_1.9.1         digest_0.6.34   
## [37] rvest_1.0.5      processx_3.8.6   hms_1.1.3        lifecycle_1.0.4 
## [41] chromote_0.5.1   vctrs_0.6.5      ottrpal_2.0.0    evaluate_1.0.5  
## [45] glue_1.7.0       spelling_2.3.2   fansi_1.0.6      rmarkdown_2.25  
## [49] purrr_1.0.2      httr_1.4.7       htmltools_0.5.7  tools_4.3.2     
## [53] pkgconfig_2.0.3
```

