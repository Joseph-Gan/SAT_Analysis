# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Test Analysis



### Overview


The SAT are standardized tests that many colleges and universities in the United States require for their admissions process. This score is used along with other materials such as grade point average (GPA) and essay responses to determine whether or not a potential student will be accepted to the university.

The SAT has two sections of the test: Evidence-Based Reading and Writing and Math ([*source*](https://www.princetonreview.com/college/sat-sections)).

**New 2016 SAT**
There have been recent major revisions to the SAT test, which, the College Board claims, have been driven by the need to assess more closely the subjects that students learn in high school and the ones they will learn at college, rather than the previously isolated concepts created for an individual set of assessments. The new test came into effect in March 2016.



### Problem Statement

SAT has undergone major changes in its examination format in 2016 to improve the examination system. This paper will investigate the impact of the changes to the SAT participate rate.

---

### Datasets

* [`act_2019.csv`](./data/act_2019.csv): 2019 ACT Scores by State
* [`sat_2015.csv`](./data/sat_2015.csv): 2015 SAT Scores by State
* [`sat_2017.csv`](./data/sat_2017.csv): 2017 SAT Scores by State
* [`sat_2018.csv`](./data/sat_2018.csv): 2018 SAT Scores by State
* [`sat_2019.csv`](./data/sat_2019.csv): 2019 SAT Scores by State

### Data Dictionary

|Feature|Type|Description|
|:---:|:---:|:---|
|**State**|*string*| The states of United State| 
|**Participation Rate**|*float*|Mean Participation Rate of SAT for the mentioned Year|
|**EBRW**|*float*|Evidence-Based Reading and Writing mean score|
|**Math**|*float*|Math mean score|
|**Total**|*float*|Total (EBRW & Math) mean score|
|**Year**|*string*|Year for the SAT|
|**Test**|*float*|SAT|

### Methodology
In this project, we will explore the followings:-

* changes in participation rate on entire united state from 2015 - 2019
* changes in state-wise participation rate
* correlations between participation rate and examination score
* Dominance of SAT compare to ACT across United State in 2019

### Conclusions and Recommendations
#### Conclusion

- SAT Participation Rate has shown as overall increased from 2017 to 2019 after the major examination format changes.
- There are a few of states where the participation rate has decreases instead, Mainly **Nevada** and the US east coast (**Georgia, North Carolina, South Carolina, Virginia etc..**).<br>
- The SAT Participation rate is negatively correlated with the SAT score. Followings describe the possible explanation on the observation:

    1. Mandatory SAT Participation has diluted the quality of high achiever. Thereby reducing the overall SAT score. This can be seen in  **Colorado**.
    2. Possible Selection Bias from the Examination Score might be contributing on the drop in SAT score as stated in:- https://www.nber.org/system/files/working_papers/w14265/w14265.pdf

#### Recommendations
- There are strong regional affliation in ACT, SAT preference. Coastal progressive states shows preference in SAT, while Midwestern and Mountain conservative states tend to favor the ACT.

- SAT College Board should further investigate on the low participation rate in Mountain convervatives state and the negative swing in Nevada State on following factors:
    1. Political Affliation
    2. Income Distribution
    3. University admission rate
