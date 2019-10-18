# hs19-biocswirl

# BiocSwirl: Terminal based Bioconductor Courses 

Keywords: 
Tutorials, Communication, scRNA-seq, Workflow Design, Command Line

There have been many resources available to interdisciplinary researchers for years now in the form of Rbookdown tutorials, in person workshops, and Youtube videos but each method of learning has its pros and cons- for blogpost and video type tutorials we have the inability to troubleshoot and raise our hands, for in person workshops we have time limitations. All of which suffer from not being regularly updated. Bioinformatics has grown in adoption in many traditional non-computer science fields that lack the time and energy to go truly in depth past copying and pasting code found online. Swirlstats and terminal based Python courses such as browser-based Codeacademy, have shown to be efficient course structures to teach data science and statistics to complete beginners. BiocSwirl, inspired by such courses, aims to make learning bioinformatics concepts hands on through the development of course material that takes you through the common bioinformatics workflows (in this hackathon we will focus on scRNA-seq).

Our goal is to develop swirlify() style console/terminal based courses for the purposes of teaching bioinformatics workflow steps and good coding practices. The philosophy is to keep the GUI use and application switching as minimal as possible but the content itself very rich and informative. Bioconductor, Radian, bioSyntax (shoutout to hackseq 2016!), are examples of some packages we plan to use to teach workflow steps, file types, and concepts in R.

#HACKSEQ 2019 PLAN
        a. Day 1: 
            i. MORNING  MEETING: 
                1. Team formation, introductions, overview of Hackathon workflow and Lesson Plan/Analysis Pipeline, Adding everyone to Github, Git overview and push/pull protocols 
                2. Assignment of individuals to either Docs or Interface, Git issue Overview
                3. Installation of:
                        i. Devtools, usethis, knitr, roxygen2, git
                        ii. Radian, BioSyntax, beRi, Bioconductor 
                        iii. scRNA datasets 
                        iv. R packages: scRNAseq, Rsamtools, fastqc, rsubread, scater, scran, scpipe, Seurat, heatmapr
                        v. IF NEEDED: Rpytools, htmltools, 
                4. Specific Task Assignment 
            ii. DAILY| WORK: 
                1. Docs Team: 
                    a. assign lesson plan documentation to individuals based on expertise (Basic Concepts, workflow, low level, high level, or coding practices) 
                    b. encode the YAML files
                    c. gaining a general idea of good hands on lessons, desired input/outputs in terminal  
                2. Interface Team: 
                    a. MAIN GOAL: Integration of all resources and file structure aka “Harmony”, interactivity component
                    b. Building the file structure needed and create necessary pointer variables in R, writing install files (including install options), initialization of R package (+ licensing), based on swirlstats structure 
                    c. Building the skeleton lesson plan, prepping gene files for testing and ensuring annotation displays correctly, making sure correct lessons launch with user input  
        b. Day 2: 
            i. MORNING MEETING: 
                1. Team get together, overview of where everyone’s at, carry over tasks left over from day before, and assign new tasks
                2. Documentation refinement, moving from background and theory to hand on coding sections
            ii. DAILY WORK:
                1. Docs Team: working on lesson plans from day before, or moving onto next 
                2. Interface Team: 
                    a. Development of Lesson plan structure, importing in YAML files from docs team and organizing structure of lesson plan. Importing of dummy and test gene files to test for annotation and compatibility, 
                    b. “Failteacher” - > git diffs (or equiv) data outputs and gives feedback based on differences (unlikely!!) 
                    c. Begin CRAN documentation 
                    d. Creating launch icon, user settings, allow of radian/terminal option OR Rstudio option, Progress tracking, save/load metadata files for quickstart
                    e. [IF THERES TIME] Lesson tester to overview input functionality, purposeful breaking  
        c. DAY 3
            i. MORNING MEETING: 
                1. PRIORITIZATION OF ISSUES
                2. Reassignment to critical areas
                3. Team vote on what to abandon/Keep 
            ii. DAILY WORK: 
                1. Proofreading 
                2. Debug/Finishing touches 
                3. Present work 
