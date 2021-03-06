---
title       : Biostats 753
subtitle    : 
author      : Jeffrey Leek
job         : Johns Hopkins Bloomberg School of Public Health
logo        : bloomberg_shield.png
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow   # 
url:
  lib: ../../libraries
  assets: ../../assets
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---






## Why do data science?

"It is not the critic who counts: not the man who points out how the strong man stumbles or where the doer of deeds could have done better. The credit belongs to the man who is actually in the arena, whose face is marred by dust and sweat and blood, who strives valiantly, who errs and comes up short again and again, because there is no effort without error or shortcoming, but who knows the great enthusiasms, the great devotions, who spends himself for a worthy cause; who, at the best, knows, in the end, the triumph of high achievement, and who, at the worst, if he fails, at least he fails while daring greatly, so that his place shall never be with those cold and timid souls who knew neither victory nor defeat."

<img src="../../assets/img/01_DataScientistToolbox/teddy.jpeg" height=100>  _Theodore Roosevelt, 26th President of the United States_

[Statistics and the science game](http://simplystatistics.org/2012/06/22/statistics-and-the-science-club/)

---

## The key challenge in data science

"Ask yourselves, what problem have you solved, ever, that was worth solving, where you knew knew all of the given information in advance? Where you didn’t have a surplus of information and have to filter it out, or you didn’t have insufficient information and have to go find some?"

<img src="../../assets/img/01_DataScientistToolbox/meyer.jpg" height=100 /> [Dan Myer, Mathematics Educator](http://www.ted.com/talks/dan_meyer_math_curriculum_makeover.html)

[The key word in data science is not data; it is science](http://simplystatistics.org/2013/12/12/the-key-word-in-data-science-is-not-data-it-is-science/)

---

## About me

<center> <font color="#CD3278">Data intensive</font> statistics in <font color="#008B45">molecular biology</font></center>

* Jeff Leek 
  * Website [http://biostat.jhsph.edu/~jleek/](http://biostat.jhsph.edu/~jleek/), [http://simplystatistics.org/](http://simplystatistics.org/)
  * Twitter [@jtleek](https://twitter.com/jtleek) 
  * Github [https://github.com/jtleek](https://github.com/jtleek)
  * Email [jtleek 'at' gmail 'punctuation' com](http://cdn.memegenerator.net/instances/400x/33457759.jpg)



---


## Why data science?

<img class=center src="../../assets/img/01_DataScientistToolbox/deluge.jpeg" height=400 />

[http://www.economist.com/node/15579717](http://www.economist.com/node/15579717)


---

## Why data science?

<img class=center src="../../assets/img/01_DataScientistToolbox/mckinsey.png" height=400 />

[http://www.mckinsey.com/insights/business_technology/big_data_the_next_frontier_for_innovation](http://www.mckinsey.com/insights/business_technology/big_data_the_next_frontier_for_innovation)

--- 

## Why statistical data science?

<img class=center src="../../assets/img/01_DataScientistToolbox/nytimes.png" height=400 />

[http://www.nytimes.com/2009/08/06/technology/06stats.html?_r=0](http://www.nytimes.com/2009/08/06/technology/06stats.html?_r=0)



---

## Why are you lucky?

<img class=center src="../../assets/img/01_DataScientistToolbox/bezos.jpg" height=400 />


---

## Why are you lucky?

<img class=center src=../../assets/img/01_DataScientistToolbox/heritage.png height=400 />

[Heritage Health Prize](http://www.heritagehealthprize.com/c/hhp)


---

## Who is a statistician?


<img class=center height=400 src=../../assets/img/01_DataScientistToolbox/morey.jpeg />
[Daryl Morey](http://en.wikipedia.org/wiki/Daryl_Morey)


---

## Who is a statistician?

<img class=center height=400 src=../../assets/img/01_DataScientistToolbox/mason.jpeg />
[Hilary Mason](http://www.hilarymason.com/)


---

## Who is a statistician?

<img class=center height=400 src=../../assets/img/01_DataScientistToolbox/koller.jpeg />

[Daphne Koller](http://ai.stanford.edu/~koller/)


---

## Who is a statistician? 

 <img class=center height=400 src=../../assets/img/01_DataScientistToolbox/silver.jpeg />

[Nate Silver](http://fivethirtyeight.blogs.nytimes.com/)


---

## What is the point of a Ph.D.


* Freedom
* Discover new knowledge
* Time to dive deep
* Opportunity for leadership
* Opportunity to make a name for yourself
  * R packages
  * Papers
  * Blogs
* A good presentation [http://pgbovine.net/phd.htm](http://pgbovine.net/phd.htm), he also has more good resources here [http://pgbovine.net/phd.htm](http://pgbovine.net/phd.htm)
* Get a job

---

## What is not the point of a Ph.D.

* Grades
* Classes
* Exams
* Proving you are smart
* Competition with other students locally

---

## What is 753?

* Historically just a methods course
* Now a combination of methods/data analysis. 
* Goals
  * Teach you to think about data
  * Teach you to organize an analysis
  * Help you understand current methods
  * Get you started creating your own methods
  * Teach you practical Ph.D. skills


---

## What does a Ph.D. statistician do?

* Research 
  * Collaborate with scientists
  * Discover new problems
  * Work on statistical methods/theory
* Teaching
  * Teach graduate students
  * Teach undergraduate students
* Service
  * Sit on committees
  * Review papers
  * Act as editor for papers


---

## What does a Ph.D. statistician do?

* Research 
  * <rt> Collaborate with scientists </rt>
  * <rt> Discover new problems </rt>
  * <rt>Work on statistical methods</rt>/theory
* Teaching
  * Teach graduate students
  * Teach undergraduate students
* Service
  * Sit on committees
  * <rt>Review papers</rt>
  * Act as editor for papers

---

## What does a Ph.D. statistician do - concretely. 


* Write papers
* Teach classes
* Advise students
* Review papers
* Go to meetings

---

## What are methods?

The term "methods" is somewhat open to interpretation - this is
one potential way to break journals down to give some insight


* __Theory__: Annals of Statistics, JRSSB, JASA TM
* __Data Analysis__: JRSSC, Nature, NEJM, JAMA, Genome Biology
* __Methods__: Biometrics, AOAS, Biostatistics, Neuroimage, Genome Biology, Bioinformatics

Many PhD theses "resemble" methods papers, and contain material
similar to that discussed in 573. 

---

## Goals of this course

Upon completion of this course students will be able to:

1. Obtain, clean, transform and process raw data into usable formats
2. Formulate quantitative models to address scientific questions
3. Organize and perform a complete data analysis, from exploration, to analysis, to synthesis, to communication. 
4. Understand and apply a range of statistical methods for inference and prediction.
5. __Develop ideas for new statistical methods, tools, and analyses__

Students will also be encouraged to independently read and apply statistical methods from texts and the scientific literature that are not covered in the course. They will also be encouraged to think of improvements or variations on existing methods to address specific scientific questions. 


---

## Textbooks

* Notes on the course webpage [https://github.com/jtleek/jhsph753and4](https://github.com/jtleek/jhsph753and4)
* [Elements of statistical learning](http://www-stat.stanford.edu/~tibs/ElemStatLearn/)
* [Advanced Data Analysis from An Elementary Point of View](http://www.stat.cmu.edu/~cshalizi/ADAfaEPoV/ADAfaEPoV.pdf)
* [Modern applied statistics with S](http://www.amazon.com/Modern-Applied-Statistics-Computing/dp/0387954570)
* [A course in large sample theory](http://www.amazon.com/Course-Sample-Chapman-Statistical-Science/dp/0412043718)
* [The elements of style](http://www.biostat.jhsph.edu/~jleek/teaching/2011/754/reading/StrunkandWhite.pdf)

---

## Grading policy 

_I believe the purpose of the Ph.D. is to train you to be able to think for yourself and initiate and complete your own projects. I am super excited to talk to you about ideas, work out solutions with you, and help you to figure out statistical methods and/or data analysis. I don't think that graduate school grades are important for this purpose. This means that I don't care very much about graduate student grades._

The only purpose for grades in my mind is to communicate whether you are on the path to passing the qual. Here are the grades I will give for that purpose.

* A = Do this well and you will pass
* B = Do this well and you will likely pass
* C = Do this well and you will have trouble
* D = Rarely given, means we need to have a talk

---

## Evaluation and feedback

* 35%  =  Data analysis (peer graded/instructor summarized)
* 20%  =  Bi-weekly problems (graded by TA)
* 10%  =  Data analysis review (completion)
* 25%  =  Final Project (graded by instructor)


* You will get receive
  * Grades on the methods problems
  * Feedback from your peers
  * Brief (< 1 paragraph + grade) feedback from me within a week of submitting your analyses.
  
_If you would like further feedback on your assignments please schedule time to meet with me. I will try to leave Fridays available from 10am-3pm in 20 minute slots available. You may book up to 3 slots at a time: http://jtleek.youcanbook.me/_



---

## Assignments

Assignments posted here: [https://github.com/jtleek/jhsph753and4/tree/master/assignments](https://github.com/jtleek/jhsph753and4/tree/master/assignments)

* Homework problems
  * Statistical methods focus
  * Submit to jtleek+methods14 gmail address cc Amanda
  * Title must be formatted: 753-Assignment-1-LastName
  * Due 10am on assignment due date
* Data analyses
  * Please submit data analysis assignments to [http://www.crowdgrader.org/](http://www.crowdgrader.org/)
  * All assignments and reviews are due by 10am on the due date.

---

## Data analysis projects

(For more on my project philosophy see: [http://bit.ly/wQT5uI](http://bit.ly/wQT5uI))

* You will do two
* All documents should be submitted electronically
* You must submit pdfs + rmds

__Grading criteria__

1. Did you answer the scientific question? (30%)
2. Did you use appropriate statistical methods? (40%)
3. Was your write-up simple, clear, and precise? (20%)
4. Was your code reproducible? (10%)


---

## Data Analysis Reviews

After each data analysis is turned in, they will be randomly assigned to another student for review. Your review will be due one week after it is assigned. Your comments should have the format of a typical peer review. You should include a summary of the analyses and conclusions in the project you are reviewing, any major revisions, and any minor revisions. I will also evaluate each data analysis independently to assign a grade. Synthesized comments will be made available for each project. 


---

## Crowdgrader

* [http://www.crowdgrader.org/](http://www.crowdgrader.org/)
* Please email me with the title "Crowdgrader email"
* I will add you to the assignment
* We are trying this out - if you can't get it to submit, we will do by email (ugh)

---

## Tentative syllabus (753 and 754)


* Obtaining data and data processing
* Exploratory data analysis
* Regression and generalizations
* Smoothing
* Prediction 
* High dimensional analysis
* Simulation studies

---

## Questions?



---

## Inference

<img class=center src=../../assets/img/01_DataScientistToolbox/infcentraldogma.png height=450>

[http://www.gs.washington.edu/academics/courses/akey/56008/lecture/lecture2.pdf](http://www.gs.washington.edu/academics/courses/akey/56008/lecture/lecture2.pdf)

---

## Prediction

<img class=center src=../../assets/img/08_PredictionAndMachineLearning/centraldogma.png height=450>


---

## Structure of a data analysis

* Define the question
* Define the ideal data set
* Determine what data you can access
* Obtain the data
* Clean the data
* Exploratory data analysis
* Statistical prediction/modeling
* Interpret results
* Challenge results
* Synthesize/write up results
* Create reproducible code

---

## Defining a question

<img class=center src=../../assets/img/stat-projects.jpg height=400 />

1. Statistical methods development
2. [Danger zone!!!](http://www.drewconway.com/zia/?p=2378)
3. Proper data analysis 


---

## An example

__Start with a general question__

Can I automatically detect emails that are SPAM that are not?

__Make it concrete__

Can I use quantitative characteristics of the emails to classify them as SPAM/HAM?

---

## Define the ideal data set

* The data set may depend on your goal
  * Descriptive - a whole population
  * Exploratory - a random sample with many variables measured
  * Inferential - the right population, randomly sampled
  * Predictive - a training and test data set from the same population
  * Causal - data from a randomized study
  * Mechanistic - data about all components of the system
  

---

## Our example

<img class=center src=../../assets/img/datacenter.png height='400' />
[http://www.google.com/about/datacenters/inside/](http://www.google.com/about/datacenters/inside/)


---

## Determine what data you can access

* Sometimes you can find data free on the web
* Other times you may need to buy the data
* Be sure to respect the terms of use
* If the data don't exist, you may need to generate it yourself


---

## Back to our example

<img class=center src=../../assets/img/security.png height='400' />


---

## A possible solution


<img class=center src=../../assets/img/uci.png height='400' />

[http://archive.ics.uci.edu/ml/datasets/Spambase](http://archive.ics.uci.edu/ml/datasets/Spambase)


---

## Obtain the data

* Try to obtain the raw data
* Be sure to reference the source
* Polite emails go a long way
* If you will load the data from an internet source, record the url and time accessed

---

## Our data set

<img class=center src=../../assets/img/spamR.png height='400' />

[http://search.r-project.org/library/kernlab/html/spam.html](http://search.r-project.org/library/kernlab/html/spam.html)



---

## Clean the data

* Raw data often needs to be processed
* If it is pre-processed, make sure you understand how
* Understand the source of the data (census, sample, convenience sample, etc.)
* May need reformating, subsampling - record these steps
* __Determine if the data are good enough__ - if not, quit or change data

---

## Our cleaned data set


```r
# If it isn't installed, install the kernlab package with install.packages()
library(kernlab)
data(spam)
str(spam[, 1:5])
```

```
'data.frame':	4601 obs. of  5 variables:
 $ make   : num  0 0.21 0.06 0 0 0 0 0 0.15 0.06 ...
 $ address: num  0.64 0.28 0 0 0 0 0 0 0 0.12 ...
 $ all    : num  0.64 0.5 0.71 0 0 0 0 0 0.46 0.77 ...
 $ num3d  : num  0 0 0 0 0 0 0 0 0 0 ...
 $ our    : num  0.32 0.14 1.23 0.63 0.63 1.85 1.92 1.88 0.61 0.19 ...
```


[http://search.r-project.org/library/kernlab/html/spam.html](http://search.r-project.org/library/kernlab/html/spam.html)


--- 

## Subsampling our data set
We need to generate a test and training set (prediction)

```r
# If it isn't installed, install the kernlab package
library(kernlab)
data(spam)
# Perform the subsampling
set.seed(3435)
trainIndicator = rbinom(4601,size=1,prob=0.5)
table(trainIndicator)
```

```
trainIndicator
   0    1 
2314 2287 
```

```r
trainSpam = spam[trainIndicator==1,]
testSpam = spam[trainIndicator==0,]
```


---

## Exploratory data analysis

* Look at summaries of the data
* Check for missing data
* Create exploratory plots
* Perform exploratory analyses (e.g. clustering)

---

## Names

```r
names(trainSpam)
```

```
 [1] "make"              "address"           "all"               "num3d"            
 [5] "our"               "over"              "remove"            "internet"         
 [9] "order"             "mail"              "receive"           "will"             
[13] "people"            "report"            "addresses"         "free"             
[17] "business"          "email"             "you"               "credit"           
[21] "your"              "font"              "num000"            "money"            
[25] "hp"                "hpl"               "george"            "num650"           
[29] "lab"               "labs"              "telnet"            "num857"           
[33] "data"              "num415"            "num85"             "technology"       
[37] "num1999"           "parts"             "pm"                "direct"           
[41] "cs"                "meeting"           "original"          "project"          
[45] "re"                "edu"               "table"             "conference"       
[49] "charSemicolon"     "charRoundbracket"  "charSquarebracket" "charExclamation"  
[53] "charDollar"        "charHash"          "capitalAve"        "capitalLong"      
[57] "capitalTotal"      "type"             
```



---

## Head

```r
head(trainSpam)
```

```
   make address  all num3d  our over remove internet order mail receive will people report
1  0.00    0.64 0.64     0 0.32 0.00   0.00        0  0.00 0.00    0.00 0.64   0.00      0
7  0.00    0.00 0.00     0 1.92 0.00   0.00        0  0.00 0.64    0.96 1.28   0.00      0
9  0.15    0.00 0.46     0 0.61 0.00   0.30        0  0.92 0.76    0.76 0.92   0.00      0
12 0.00    0.00 0.25     0 0.38 0.25   0.25        0  0.00 0.00    0.12 0.12   0.12      0
14 0.00    0.00 0.00     0 0.90 0.00   0.90        0  0.00 0.90    0.90 0.00   0.90      0
16 0.00    0.42 0.42     0 1.27 0.00   0.42        0  0.00 1.27    0.00 0.00   0.00      0
   addresses free business email  you credit your font num000 money hp hpl george num650 lab labs
1          0 0.32        0  1.29 1.93   0.00 0.96    0      0  0.00  0   0      0      0   0    0
7          0 0.96        0  0.32 3.85   0.00 0.64    0      0  0.00  0   0      0      0   0    0
9          0 0.00        0  0.15 1.23   3.53 2.00    0      0  0.15  0   0      0      0   0    0
12         0 0.00        0  0.00 1.16   0.00 0.77    0      0  0.00  0   0      0      0   0    0
14         0 0.00        0  0.00 2.72   0.00 0.90    0      0  0.00  0   0      0      0   0    0
16         0 1.27        0  0.00 1.70   0.42 1.27    0      0  0.42  0   0      0      0   0    0
   telnet num857 data num415 num85 technology num1999 parts pm direct cs meeting original project
1       0      0 0.00      0     0          0    0.00     0  0   0.00  0       0      0.0       0
7       0      0 0.00      0     0          0    0.00     0  0   0.00  0       0      0.0       0
9       0      0 0.15      0     0          0    0.00     0  0   0.00  0       0      0.3       0
12      0      0 0.00      0     0          0    0.00     0  0   0.00  0       0      0.0       0
14      0      0 0.00      0     0          0    0.00     0  0   0.00  0       0      0.0       0
16      0      0 0.00      0     0          0    1.27     0  0   0.42  0       0      0.0       0
   re edu table conference charSemicolon charRoundbracket charSquarebracket charExclamation
1   0   0     0          0         0.000            0.000                 0           0.778
7   0   0     0          0         0.000            0.054                 0           0.164
9   0   0     0          0         0.000            0.271                 0           0.181
12  0   0     0          0         0.022            0.044                 0           0.663
14  0   0     0          0         0.000            0.000                 0           0.000
16  0   0     0          0         0.000            0.063                 0           0.572
   charDollar charHash capitalAve capitalLong capitalTotal type
1       0.000    0.000      3.756          61          278 spam
7       0.054    0.000      1.671           4          112 spam
9       0.203    0.022      9.744         445         1257 spam
12      0.000    0.000      1.243          11          184 spam
14      0.000    0.000      2.083           7           25 spam
16      0.063    0.000      5.659          55          249 spam
```


---

## Summaries

```r
table(trainSpam$type)
```

```

nonspam    spam 
   1381     906 
```


---

## Plots

```r
plot(trainSpam$capitalAve ~ trainSpam$type)
```

<div class="rimage center"><img src="fig/unnamed-chunk-6.png" title="plot of chunk unnamed-chunk-6" alt="plot of chunk unnamed-chunk-6" class="plot" /></div>


---

## Plots 

```r
plot(log10(trainSpam$capitalAve + 1) ~ trainSpam$type)
```

<div class="rimage center"><img src="fig/unnamed-chunk-7.png" title="plot of chunk unnamed-chunk-7" alt="plot of chunk unnamed-chunk-7" class="plot" /></div>


---

## Relationships between predictors

```r
plot(log10(trainSpam[,1:4]+1))
```

<div class="rimage center"><img src="fig/unnamed-chunk-8.png" title="plot of chunk unnamed-chunk-8" alt="plot of chunk unnamed-chunk-8" class="plot" /></div>


---

## Clustering




```r
hCluster = hclust(dist(t(trainSpam[,1:57])))
plot(hCluster)
```

<div class="rimage center"><img src="fig/unnamed-chunk-10.png" title="plot of chunk unnamed-chunk-10" alt="plot of chunk unnamed-chunk-10" class="plot" /></div>


---
## New clustering

```r
hClusterUpdated = hclust(dist(t(log10(trainSpam[,1:55]+1))))
plot(hClusterUpdated)
```

<div class="rimage center"><img src="fig/unnamed-chunk-11.png" title="plot of chunk unnamed-chunk-11" alt="plot of chunk unnamed-chunk-11" class="plot" /></div>


---
## Statistical prediction/modeling

* Should be informed by the results of your exploratory analysis
* Exact methods depend on the question of interest
* Transformations/processing should be accounted for when necessary
* Measures of uncertainty should be reported

---
## Statistical prediction/modeling

```r
trainSpam$numType = as.numeric(trainSpam$type)-1
costFunction = function(x,y) sum(x!=(y > 0.5)) 
cvError = rep(NA,55)
library(boot)
for(i in 1:55){
  lmFormula = reformulate(names(trainSpam)[i], response = "numType")
  glmFit = glm(lmFormula,family="binomial",data=trainSpam)
  cvError[i] = cv.glm(trainSpam,glmFit,costFunction,2)$delta[2]
}

## Which predictor has minimum cross-validated error?
names(trainSpam)[which.min(cvError)]
```

```
[1] "charDollar"
```


---

## Get a measure of uncertainty

```r
## Use the best model from the group
predictionModel = glm(numType ~ charDollar,family="binomial",data=trainSpam)

## Get predictions on the test set
predictionTest = predict(predictionModel,testSpam)
predictedSpam = rep("nonspam",dim(testSpam)[1])

## Classify as `spam' for those with prob > 0.5
predictedSpam[predictionModel$fitted > 0.5] = "spam"
```


---

## Get a measure of uncertainty


```r
## Classification table
table(predictedSpam,testSpam$type)
```

```
             
predictedSpam nonspam spam
      nonspam    1346  458
      spam         61  449
```

```r

## Error rate
(61+458)/(1346+458 + 61 + 449)
```

```
[1] 0.2243
```


---

## Interpret results

* Use the appropriate language
  * describes 
  * correlates with/associated with
  * leads to/causes
  * predicts
* Give an explanation
* Interpret coefficients
* Interpret measures of uncertainty

---

## Our example

* The fraction of charcters that are dollar signs can be used to predict if an email is Spam
* Anything with more than 6.6% dollar signs is classified as Spam
* More dollar signs always means more Spam under our prediction
* Our test set error rate was 22.4% 

---

## Challenge results

* Challenge all steps:
  * Question
  * Data source
  * Processing 
  * Analysis 
  * Conclusions
* Challenge measures of uncertainty
* Challenge choices of terms to include in models
* Think of potential alternative analyses 

---

## Synthesize/write-up results

* Lead with the question
* Summarize the analyses into the story 
* Don't include every analysis, include it
  * If it is needed for the story
  * If it is needed to address a challenge
* Order analyses according to the story, rather than chronologically
* Include "pretty" figures that contribute to the story 

---

## In our example

* Lead with the question
  * Can I use quantitative characteristics of the emails to classify them as SPAM/HAM?
* Describe the approach
  * Collected data from UCI -> created training/test sets
  * Explored relationships
  * Choose logistic model on training set by cross validation
  * Applied to test, 78% test set accuracy
* Interpret results
  * Number of dollar signs seems reasonable, e.g. "Make money with Viagra \\$ \\$ \\$ \\$!"
* Challenge results
  * 78% isn't that great
  * I could use more variables
  * Why logistic regression?


---

## Create reproducible code

<img class=center src=../../assets/img/rmarkdown.png height='400' />

---


## Data analysis files

* Data
  * Raw data
  * Processed data
* Figures
  * Exploratory figures
  * Final figures
* R code
  * Raw / unused scripts
  * Final scripts
  * R Markdown files
* Text
  * README files
  * Text of analysis / report


---

## Raw Data

<img class=center src=../../assets/img/medicalrecord.png height='400'/>

* Should be stored in your analysis folder
* If accessed from the web, include url, description, and date accessed in README

---

## Processed data

<img class=center src=../../assets/img/excel.png height='400'/>
* Processed data should be named so it is easy to see which script generated the data. 
* The processing script - processed data mapping should occur in the README
* Processed data should be [tidy](http://vita.had.co.nz/papers/tidy-data.pdf)

---

## Exploratory figures

<img class=center src=../../assets/img/example10.png height='400'/>

* Figures made during the course of your analysis, not necessarily part of your final report.
* They do not need to be "pretty"

---

## Final Figures

<img class=center src=../../assets/img/figure1final.png height='400'/>

* Usually a small subset of the original figures
* Axes/colors set to make the figure clear
* Possibly multiple panels

---

## Raw scripts

<img class=center src=../../assets/img/rawcode.png height='350'/>

* May be less commented (but comments help you!)
* May be multiple versions
* May include analyses that are later discarded

---

## Final scripts

<img class=center src=../../assets/img/finalscript2.png height='300'/>

* Clearly commented
  * Small comments liberally - what, when, why, how
  * Bigger commented blocks for whole sections
* Include processing details
* Only analyses that appear in the final write-up

---

## R markdown files

<img class=center src=../../assets/img/rmd.png height='400'/>

* [R markdown](http://www.rstudio.com/ide/docs/authoring/using_markdown) files can be used to generate reproducible reports
* Text and R code are integrated
* Very easy to create in [Rstudio](http://www.rstudio.com/)

---

## Readme files

<img class=center src=../../assets/img/readme.png height='400'/>

* Not necessary if you use R markdown
* Should contain step-by-step instructions for analysis
* Here is an example [https://github.com/jtleek/swfdr/blob/master/README](https://github.com/jtleek/swfdr/blob/master/README)

---

## Text of the document

<img class=center src=../../assets/img/swfdr.png height='350'/>

* It should include a title, introduction (motivation), methods (statistics you used), results (including measures of uncertainty), and conclusions (including potential problems)
* It should tell a story
* _It should not include every analysis you performed_
* References should be included for statistical methods


---

## Questions?

[https://github.com/jtleek/jhsph753and4/lectures](https://github.com/jtleek/jhsph753and4/lectures)

