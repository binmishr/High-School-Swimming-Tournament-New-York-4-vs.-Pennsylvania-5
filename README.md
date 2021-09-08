# High-School-Swimming-Tournament-New-York-4-vs.-Pennsylvania-5

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

So it begins – the first match-up of the first round of the first ever Swimming + Data Science High School Swimming State-Off. If you missed the introductory post and are wondering what all this is about you can catch up here. Today’s match-up is between number 4 seeded New York and number 5 seeded Pennsylvania.
Setup

To begin let’s load some packages. Swimmer will be our workhorse for getting hold of the results. Then we’ll use the various tidyverse packages dplyr, stringr and purrr to facilitate our analysis and flextable for nice tables of the results.
******

library(SwimmeR)
library(dplyr)
library(stringr)
library(purrr)
library(flextable)

Raw Results

New York State has two seasons in a given school year. A girls’ season in the fall, followed by a boys season in the winter.  We’re just interested in the most recent state meets, Girls 2019 and Boys 2020, so let’s put links to those results into a list.
