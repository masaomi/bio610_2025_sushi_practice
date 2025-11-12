# Exercise 3 - Feature Counts
- Author: FGCZ
- Date: 26/04/2024

Steps
1. [Head to the STAR dataset](#1-head-to-the-star-dataset-in-sushi)
2. [Run CountQC](#2-run-countqc-on-the-resulting-featurecounts-dataset)
3. [Explore the CountQC Static Report](#3-explore-the-countqc-static-report)

----

### 1. Head to the STAR dataset in SUSHI

From the `Count` application list, select `FeatureCountsApp`. Check the settings, the defaults should be fine. 

Options
* Here, you can exclude certain samples by holding the `Command` or `Control` key (Mac/Windows respectively) and clicking samples to include. 
* We can also exclude multi-mapped reads here if you desire *exact* mapped reads (unnecessary in nearly all bulk RNA seq runs). You can also selet multiple transcript types here, *e.g.*, if you have total RNA seq data (like ribo-depleted as opposed to poly-A selected). 

<img src="screenshots/screenshot18.png" width="50%">

<img src="screenshots/screenshot19.png" width="70%">

### 2. Run CountQC on the resulting FeatureCounts dataset 

<img src="screenshots/screenshot20.png" width="70%">

<img src="screenshots/screenshot21.png" width="70%">

### 3. Explore the CountQC Static Report

* [Questions RNAseq exercise3](https://fgcz-shiny.uzh.ch/SUSHI_course_2023/RNAseq/exercise3/)

Next: [Exercise4 Differential Expression](Exercise_4.md)
