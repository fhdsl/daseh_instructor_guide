


# Running a program like DaSEH  <img src="https://raw.githubusercontent.com/fhdsl/daseh_instructor_guide/1afbe6783430718ae6a63c607da6e457a73a90ff/assets/leaf.png" alt="Leaf" loading="lazy" style="width:10%; height:auto; vertical-align: middle; display: inline;">

## Learning Objectives

In this chapter we will discuss how to:
- Plan a short course like daseh 
- List tips for running a codeathon


## Planning a DaSEH course 

We have created a [checklist of tasks](https://docs.google.com/spreadsheets/d/1FGPiE5y4qUXLWMOrpa18xmeFTr_8UL6ja_vzWwTwjbg/edit?usp=drive_link) for those who wish to use our materials for an academic course or short course program. 

<iframe src="https://docs.google.com/spreadsheets/d/1FGPiE5y4qUXLWMOrpa18xmeFTr_8UL6ja_vzWwTwjbg/edit?usp=drive_link" width="672" height="400px"></iframe>


## Tips for Logistics

The following are more extensive details and tips about the logistical aspects of planning courses, codeathons and learning programs that we learned from our experience teaching DaSEH and other educational activities. 

### Scheduling Considerations

Our materials could be used as we have for a [9 day online course](https://daseh.org/materials_schedule.html) and [3 day codeathon](https://docs.google.com/document/d/1ZD-w0vc3Vtv1vf95h6323zaaxORg9vC7Hp4I_IUeW0I/edit?usp=drive_link)), or they could be used for an academic 8 or 16 week course, or some other configuration to suite your needs. 


### Considerations for Event Spaces

There are 3 major things to consider for a DaSEH event space, if it is for an in person course or codeathon:

1. Make sure the space that has adequate WIFI that you can make accessible to the participants. 

2. Make sure there are tabletops available for participants to place their laptops - or perhaps use a computer lab that has designated computers.

3. Make sure there are enough outlets in the room or a plan for extension cords that will allow for learners to plug in their laptops.


### Virtual Set Up Considerations

We personally like Zoom for teaching, but other virtual options could also work.

If using Zoom or another platform, consider the following:

1. Set up and send out your link in advance so you can ensure learners know where to go. See this [documentation on scheduling Zoom meetings](https://support.zoom.com/hc/en/article?id=zm_kb&sysparm_article=KB0060700) for guidance. 

  Pro tip: Share the link in an email and on Slack or other platforms to connect with learners right before and the day of as well to help them know where to go. Also share it in the calendar invite.

2. Use adequate security measures so that uninvited guests do not join your virtual space. 

  Not sharing your link publicly can be especially effective, but you may also want to use a password, if you do so, ensure that learners know where to find the password.
  
3. Set up settings ahead of time if possible

  Zoom allows you to set up settings like automatic recordings ahead of time. 
  
4. Have a plan for breakout rooms ahead of time.

  If you plan to have breakout rooms for labs or other purposes, you can set these up in advance.
  We highly suggest that you set them up with the option for people to change rooms. See Zoom's [documentation on breakout rooms](https://support.zoom.com/hc/en/article?id=zm_kb&sysparm_article=KB0061353) or this [video on breakout rooms](https://share.google/BHESeIKN8GWuAfbXm).
  
  Be sure to provide guidance to learners about [changing rooms](https://teamdynamix.umich.edu/TDClient/30/Portal/KB/ArticleDet?ID=3838) if you make this an option. 
  
5. Set up polls ahead of time if possible

We often poll our learners on the first day to learn about their experience with topics and to learn about their interests. These can be set up in advance to save time. See this [video about setting up polls ahead of time.](https://share.google/KSqtsRtHTadUrYCiI)

Pro tip: We suggest that you share your recordings on a Google Drive, so that you only have to share one link where people can find recordings, as you upload them to the drive. 
  








### Making certificates

Certificates are generated in R using the [`certificate` package](https://forwards.github.io/certificate/) and the [`googlesheets4` package](https://googlesheets4.tidyverse.org/) to programmatically generate certificates for each participant reading in a google sheet with all of their names. 

These are then manually signed. 

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
