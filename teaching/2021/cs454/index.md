---
layout: page
title: CS454 AI Based Software Engineering (Autumn 2021)
---

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'Syllabus')" id="defaultOpen">Syllabus</button>
  <button class="tablinks" onclick="openTab(event, 'Schedule')">Schedule</button>
  <button class="tablinks" onclick="openTab(event, 'Assignments')">Assignments</button>
  <button class="tablinks" onclick="openTab(event, 'Projects')">Projects</button>
  <button class="tablinks" onclick="openTab(event, 'Reading List')">Reading List</button>
</div>

<!-- Tab content -->
<div id="Syllabus" class="tabcontent" markdown="1">

### Syllabus

This class covers metaheuristic optimisation algorithms and their application to software engineering problems. The goal of the class is twofold: the first objective is to understand major classes of metaheuristic algorithms, including local search algorithms and population based optimisation (such as genetic algorithm and particle swarm optimisation). The second objective is to study the application of these algorithms to software engineering problems. For this, the class will introduce the fundamental concepts in so called Search Based Software Engineering, and then study various application cases across the software development lifecycle (requirements, design, planning, testing, maintenance, etc). The desired learning outcome is to be able to use metaheuristic optimisation to automate, and/or gain insights into, software engineering tasks.

The first half of the course will be a series of lectures on metaheuristic algoithms. The second half will be a series of case studies based on paper presentations, given by students, about important and/or recent papers in the field of Search Based Software Engineering.

### Lectures
Time: 14:30-15:45, Mondays and Wednesdays
Location: Online/Zoom (link to be distributed later)

### Communication

To be announced.

### Lecturer

Shin Yoo [shin.yoo@kaist.ac.kr](mailto:shin.yoo@kaist.ac.kr)
Office: E3-1 Room 2405

### Required Skills

The course assumes that students have the following skills. **Unless you satisfy the following, you may encounter significant difficulties during courseworks and projects**:

- **Strong programming skills**: you are required to develop an **individual** course project. There will be also a number of hands-on sessions where we will program together during the class.
- Unix/Linux-savvy: you should be familiar with the usual build tools and Unix/Linux command line environments.
- Git-aware: you will be required to submit a github repository as part of your project deliverables.
- (Optional but strongly recommended) LaTeX

Out of these, I would understand if you have to learn how to use git during this course. But programming proficiency and *nix literacy are essential from the beginning.

### Evaluation

This may change.

* Coursework: 30%
* Project: 40%
* Midterm Exam: 30%

### Teaching Assistant

- Jinhan Kim [jinhankim@kaist.ac.kr](mailto:jinhankim@kaist.ac.kr)
- Saeyoon Oh: [saeyoon17@kaist.ac.kr](mailto:saeyoon17@kaist.ac.kr)
- Office: E3-1 Room 2417

</div>

<div id="Schedule" class="tabcontent" markdown="1">

### Lectures

The schedule below is from 2020: the outline is still **tentative** for now and may change, given that we do not know the exact class size yet.

- 08/30: [Introduction 1/2][slide01]
- 09/01: [Introduction 2/2][slide02]
- 09/06: [Fitness Landscape][slide03], [Random Search][slide04] and [Local Search Algorithms][slide05]
- 09/08: [Evolutionary Computation 1/2][slide06]
- 09/13: [Evolutionary Computation 2/2][slide07]
- 09/15: [Genetic Programming][slide09]
- 09/20: Chuseok Holiday
- 09/22: Chuseok Holiday
- 09/27: [Multi-objective Optimisation][slide10]
- 09/29: [MOEA Evaluation Metrics][slide11], [Normalisation][slide12]
- 10/04: Day off for National Foundation Day
- 10/06: [Bio-inspired Algorithms][slide13], [SBSE Overview][slide14]
- 10/11: Day off for Hangeul Proclamation Day  ([Advanced Algorithms and Optimisation Tips][slide15] w/ Pre-recorded lecture + Q&A Session)
- 10/13: [Theory - Elementary Landscape Analysis][slide16], [No Free Lunch Theorem][slide17]
- 10/18: No Lecture
- 10/20: **Midterm Exam**
- 10/25: Project Proposal (10 teams, five minutes each)
- 10/27: [General Machine Learning for SE][slide18]
- 11/01: Paper Presentation - Team 10, 4
- 11/03: Workshop on assignment 2
- 11/08: Paper Presentation - Team 3, 5
- 11/10: Paper Presentation - Team 1, 6
- 11/15: Paper Presentation - Team 2, 8
- 11/17: Paper Presentation - Team 7, 9
- 11/22: Project Health Check (team 1, 3, 5, 7, 9)
- 11/24: Project Health Check (team 2, 4, 6, 8, 10)
- 11/29: Workshop on assignment 3
- 12/01: No Lecture (Undergraduate Admission Interview)
- 12/06: Project Final Presentation 
- 12/08: Project Final Presentation
- 12/13: No Lecture (Final Exam Week)
- 12/15: No Lecture (Final Exam Week)
- 12/19: Project Final Report Submission Deadline
</div>

<div id="Assignments" class="tabcontent" markdown="1">

Details of each assignment and submission dates will be updated as we go along.

### **Assignment #1: Getting to know the subject**

Choose a paper from the reading list. Write a critical review of the paper, containing the following points:

- What is the software engineering problem authors are trying to solve?
- What are the technical contributions of the paper?
- What do you like about this work, and what did you hate about this work?
- How would you extend this work, if you are to do a follow-up research? (This would be a good preparation for project brainstorming)

It is due on 23:59, Monday 6th September 2021. There is a submission site at KLMS. **Late submission is not allowed for this coursework**.


### **Assignment #2: Stochastic Optimisation**

Your goal is to formulate an existing, real life problem as a search, and implement a solver. The problem should be sufficiently big to justify the use of metaheuristic algorithm. Please see the [coursework documentation]({{site.baseurl}}/assets/files/teaching/cs454/assignment2.pdf) for more details.

It is due on 23:59 on 4th October. There is a submission site at KLMS. Late submission is allowed within a week from the deadline, and will receive 0.7 multiplier penalty for the final score.

### **Assignment #3: Travelling Salesman Problem**

Your goal is to implement a solver for the [Travelling Salesman Problem](https://en.wikipedia.org/wiki/Travelling_salesman_problem). This is a well known NP-complete problem with lots of practical applications. Please refer to the [coursework document]({{site.baseurl}}/assets/files/teaching/cs454/assignment-tsp.pdf) for more details. It is **due by the end of Monday 8th November 2021**. 

There is a live competition leaderboard too. Solve the [rl11849.tsp](http://elib.zib.de/pub/mp-testdata/tsp/tsplib/tsp/rl11849.tsp) problem instance and upload your solution to the [leaderboard](https://coinse.kaist.ac.kr/leaderboard/) (you need to sign up and create an account - use your KAIST email address). Leaderboard participation is not mandatory for this course, and your coursework grade is independent from your ranking. However, just for fun, there will be a prize for the winner.

<!-- ### **Assignment #3: Critical Essay**

During the paper seminar weeks, everyone should submit an essay about the paper he or she is reading as the discussion leader team member. The *minimum* expected length is a single A4 page: write what you think is a coherent and convincing critique.

The deadline for each team will be exactly seven days after the presentation of the paper they are writing about. There will be a submission site at KLMS, whose deadline will be set to the very last one: we will check the initial submission time for those who have early deadlines. The usualy late submission penalty applies. -->
</div>

<div id="Projects" class="tabcontent" markdown="1">

## Group Project Outline

The course project requires you to identify and formulate an SBSE problem and solve it using a metaheuristic approach. 

### Project Ideas

There are a few ways to find ideas to work on:

* Consider your own experience as a developer: if there is some aspect of software development that you think you can improve by automatically searching for a solution, you can deploy algorithms that we have learnt.

* Replicating and/or Improving Literature: there are very good surveys [4, 2, 5, 3] and position papers [1] on SBSE, as well as individual research work. You can find a research topic/idea that looks attractive to you, and replicate the work in a small scale. Of course, if you can find a way to improve techniques in the literature, it is even more desirable! There are a few possible places to look:

    ??? International Symposium on Search Based Software Engineering (SSBSE): [http://dblp.uni-trier.de/db/conf/ssbse/index.html](http://dblp.uni-trier.de/db/conf/ssbse/index.html)
    
    ??? SBSE Track at ACM Genetic Algorithm and Evolutionary Computation Conference (GECCO): [https://dblp.uni-trier.de/db/conf/gecco/](https://dblp.uni-trier.de/db/conf/gecco/) (Look for Search-based Software Engineering section under each year???s proceedings)

    ??? International Workshop on Search Based Software Testing (SBST): [https://dblp.org/db/conf/icse/](https://dblp.org/db/conf/icse/). URL is for all workshops collocated with International Conference on Software Engineering - look for SBST, which has been running since 2014.

    Many major software engineering conferences have also accepted many SBSE papers over the years. Our reading list is a great starting place. If you are unsure about the scope of a paper, please consult me.

* Practical Challenges: The SSBSE conference, which I mentioned above, has also been running a Challenge Track since 2013. Each year, the organisers choose a few software systems in different languages, and participants are encouraged to do something related to those systems using SBSE. Applications that have been submitted so far include: fault prediction, energy consumption improvement, searching for GUI crash events, test case prioritisation, test data generation, deep parameter optimisation, etc.


I understand that the scope is very wide and initially choosing a subject can be a bit confusing. You are welcome to consult any of the T/As and/or me, either by email or face to face. If you want to see me, it is best to make an explicit appointment by email(shin.yoo@kaist.ac.kr).


### Deliverables & Timeline

#### 25 October: Project Sales Pitch

#### Paper presentation: although it is not mandatorily coupled, you can choose to present a paper that your project is based on.

#### 22nd November: Health Check
- Each team will do 5 minute presentation to report the current progress.

#### Final Project Presentation: 6th and 8th December
- Each team will do 10 minute presentation to report the final outcome.

#### Final Report

Submit the following via KLMS: **the dealine is the end of 19 December 2021**. The person who is submitting the team report can zip it with his/her individual report; others can simply upload their individual report.

- **Each team** should submit at least one group report. There is no page limit, or required font size, but please make sure you submit a PDF file to KLMS. The group report should describe the problem, your approach, and the evaluation results. It should also include a link to your **code repository**.

- **Each person** should submit an individual report. Individual reports should include the following two parts:
    + Detailed description of what you have contributed to the project
    + A 10-point scale evaluation of all your teammates, wich short descriptive evaluation of their contribution and teamwork

### Previous Projects

These are made available only as a reference. You cannot propose identical projects. Two of them are in Korean, because the policy was different then: apologies for those who do not read/speak Korean.

- [Search-based Javascript Modelling for Static Analysis (from 2016, Korean)]({{site.baseurl}}/assets/files/teaching/2018/cs454/cs454-previous-project-2016-group3.pdf)
- [GUI Test Suite Generation using Ant Colony Optimization with EFG Traversal Criterion (from 2017, Korean)]({{site.baseurl}}/assets/files/teaching/2018/cs454/cs454-previous-project-2017-group2.pdf)
- [Improving Test Data Generation for Java Programs using Search-based Approach and d-criterion (from 2016)]({{site.baseurl}}/assets/files/teaching/2018/cs454/cs454-previous-project-2016-group6.pdf)
- [Sample Efficient Hyperparameter Optimization (from 2017)]({{site.baseurl}}/assets/files/teaching/2018/cs454/cs454-previous-project-2017-group1.pdf)

### References

1. Mark Harman. The current state and future of search based software engineering. In FOSE ???07: 2007 Future of Software Engineering, pages 342???357, Washington, DC, USA, 2007. IEEE Computer Society.

2. Mark Harman, S. Afshin Mansouri, and Yuanyuan Zhang. Search based software engineer- ing: A comprehensive analysis and review of trends techniques and applications. Technical Report TR-09-03, Department of Computer Science, King???s College London, April 2009.

3. Mark Harman, S. Afshin Mansouri, and Yuanyuan Zhang. Search-based software engi- neering: Trends, techniques and applications. ACM Computing Surveys, 45(1):11:1???11:61, December 2012.

4. Philip McMinn. Search-based software test data generation: A survey. Software Testing, Verification and Reliability, 14(2):105???156, June 2004.

5. Outi R??ih??. A survey on search-based software design. Technical Report D-2009-1, Department of Computer Science, University of Tampere, 2009.

</div>

<div id="Reading List" class="tabcontent" markdown="1">

### Reading List

Here are some papers on various SBSE topics to pick from in order to prepare for the paper presentation of your group. You can also consult the [SBSE Repository](http://crestweb.cs.ucl.ac.uk/resources/sbse_repository/repository.html).

<!-- #### Requirements

* Y. Zhang, M. Harman, and S. A. Mansouri. The Multi-Objective Next Release Problem. In GECCO ???07: Proceedings of the 2007 Genetic and Evolutionary Computation Conference, pages 1129???1136. ACM Press, 2007.

* Y.Xue and Y.-F. Li. Multi-objective Integer Programming Approaches for Solving Optimal Feature Selection Problem: A new perspective on Multi-objective Optimization Problems in SBSE. In Proceedings of the 40th International Conference on Software Engineering, ICSE ???18, pages 1231???1242, New York, NY, USA, 2018. ACM. -->

#### Project Management

* F. Ferrucci, M. Harman, J. Ren, and F. Sarro. Not going to take this anymore: Multi-objective overtime planning for software engineering projects. In Proceedings of the 2013 International Conference on Software Engineering, ICSE ???13, pages 462???471, Piscataway, NJ, USA, 2013. IEEE Press.

* R. Degiovanni, F. Molina, G. Regis, N. Aguirre. A genetic algorithm for goal-conflict identification. In Proceedings of the 33rd International Conference on Automated Software Engineering, ASE '18.

#### Modularisation

* B. S. Mitchell and S. Mancoridis. On the automatic modularization of software systems using the bunch tool. IEEE Transactions on Software Engineering, 32(3):193???208, 2006.

* K. Praditwong, M. Harman, and X. Yao. Software module clustering as a multi-objective search problem. IEEE Transactions on Software Engineering, 37(2):264???282, March-April 2010.

#### Test Data Generation

* G. Fraser and A. Arcuri. Whole test suite generation. Software Engineering, IEEE Transactions on, 39(2):276???291, Feb 2013.

* J. M. Rojas, G. Fraser, and A. Arcuri. Seeding strategies in search-based unit test generation. Journal of Software Testing, Verification, and Reliability, 2016. Wiley.

* R. B. Abdessalem, S. Nejati, L. C. Briand, and T. Stifter. Testing vision-based control systems using learnable evolutionary algorithms. In Proceedings of the 40th International Conference on Software Engineering, ICSE ???18, pages 1016???1026, New York, NY, USA, 2018. ACM.

* A. Panichella, F. Kifetew, and P. Tonella. Automated Test Case Generation as a Many-Objective Optimisation Problem with Dynamic Selection of the Targets. IEEE Transactions on Software Engineering, 2018. IEEE. 

* J. Castelein, M. Aniche, M. Soltani, A. Panichella, and A. van Deursen. Search-based test data generation for SQL queries. In Proceedings of the 40th International Conference on Software Engineering, ICSE ???18, pages 1230???1230, New York, NY, USA, 2018. ACM.

* R. B. Abdessalem, A. Panichella, S. Nejati, L. C. Briand, and T. Stifer. Testing Autonomous Cars for Feature Interaction Failures using Many-Objective Search. In Proceedings of the 33rd International Conference on Automated Software Engineering, ASE '18.

* A. Gambi, M. Mueller, and G. Fraser. Automatically testing self-driving cars with search-based procedural content generation. Proceedings of the 28th ACM SIGSOFT International Symposium on Software Testing and Analysis, pages 318-328, 2019. ACM.

* R. Jabbarvand, J. Lin, and S. Malek. Search-based energy testing of Android. In Proceedings of the 41st International Conference on Software Engineering, ICSE ???19.

* F. Zhang, S. P. Chowdhury, and M. Christakis. DeepSearch: A Simple and Effective Blackbox Attack for Deep Neural Networks. In Proceedings of the 28th ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering, ESEC/FSE '20.

* X. Gao, R. K. Saha, M. R. Prasad, and A. Roychoudhury. Fuzz Testing based Data Augmentation to Improve Robustness of Deep Neural Networks. In Proceedings of the 42nd International Conference on Software Engineering, ICSE '20.

* S. Reddy, C. Lemieux, R. Padhye, K. Sen. Quickly Generating Diverse Valid Test Inputs with Reinforcement Learning. In Proceedings of the 42nd International Conference on Software Engineering, ICSE '20.

#### Automated Program Repair

* W. Weimer, T. Nguyen, C. L. Goues, and S. Forrest. Automatically finding patches using genetic programming. In Proceedings of the 31st IEEE International Conference on Software Engineering (ICSE ???09), pages 364???374, Vancouver, Canada, 16-24 May 2009. IEEE.

* S. H. Tan, H. Yoshida, M. R. Prasad, and A. Roychoudhury. Anti-patterns in search-based program repair, Proceedings of the 24th ACM SIGSOFT International Symposium on Fundations of Software Engineering, pages 727-737, 2016. ACM.

* S. Mahajan, A. Alameer, P. McMinn, and W. Halfond. Automated repair of layout cross browser issues using search-based techniques. Proceedings of the 26th ACM SIGSOFT International Symposium on Software Testing and Analysis, pages 249???260, 2017. ACM.

* Y. Yuan, and W. Banzhaf. ARJA: Automated Repair of Java Programs via Multi-Objective Genetic Programming. IEEE Transactions on Software Engineering, 2018.

* M. Wen, J. Chen, R. Wu, D. Hao, and S.-C. Cheung. Context-aware patch generation for better au- tomated program repair. In Proceedings of the 40th International Conference on Software Engineering, ICSE ???18, pages 1???11, New York, NY, USA, 2018. ACM.

* S. Saha, R. K. Saha, and M. R. Prasad. Harnessing evolution for multi-hunk program repair. In Proceedings of the 41st International Conference on Software Engineering, ICSE ???19.

#### Regression Testing

* S. Yoo and M. Harman. Pareto efficient multi-objective test case selection. In Proceedings of International Symposium on Software Testing and Analysis, pages 140???150. ACM Press, July 2007.

* M. G. Epitropakis, S. Yoo, M. Harman, and E. K. Burke. Empirical evaluation of pareto efficient multi- objective regression test case prioritisation. In Proceedings of the 2015 International Symposium on Software Testing and Analysis, ISSTA 2015, pages 234???245, New York, NY, USA, 2015. ACM.

#### Refactoring

* M. O'Cinn??ide, L. Tratt, M. Harman, S. Counsell, and I. Hemati Moghadam. Experimental assessment of software metrics using automated refactoring. In Proceedings of the ACM-IEEE international symposium on Empirical software engineering and measurement, ESEM ???12, pages 49???58, New York, NY, USA, 2012. ACM.

* V. Alizadeh and M. Kessentini. Reducing Interactive Refactoring Effort via Clustering-Based Multi-objective Search. In Proceedings of the 33rd International Conference on Automated Software Engineering, ASE '18.

#### Genetic Improvement

* D. White, A. Arcuri, and J. Clark. Evolutionary improvement of programs. IEEE Transactions on Evolutionary Computation, 15(4):515 ???538, August 2011.

* E. T. Barr, M. Harman, Y. Jia, A. Marginean, and J. Petke. Automated Software Transplantation. Proceedings of the 2015 International Symposium on Software Testing and Analysis, pages 257???269, 2015.

* W. Langdon and M. Harman. Optimizing existing software with genetic programming. Transactions on Evolutionary Computation, 19(1):118???135, 2015.

* B. R. Bruce, J. Petke, and M. Harman. Reducing Energy Consumption using Genetic Improvement. In Proceedings of the 2015 Annual Conference on Genetic and Evolutionary Computation, pages 1327-1334, 2015. ACM.

#### Deep Parameter Optimisation

* F. Wu, W. Weimer, M. Harman, Y. Jia, and J. Krinke. Deep parameter optimisation. In Proceedings of the 2015 Annual Conference on Genetic and Evolutionary Computation, GECCO 2015, pages 1375???1382, 2015.

#### Fault Localisation

* S. Yoo. Evolving human competitive spectra-based fault localisation techniques. In G. Fraser and J. Teixeira de Souza, editors, Search Based Software Engineering, volume 7515 of Lecture Notes in Computer Science, pages 244???258. Springer Berlin Heidelberg, 2012.

* J. Sohn and S. Yoo. FLUCCS: Using code and change metrics to improve fault localisation. In Proceedings of the International Symposium on Software Testing and Analysis, ISSTA 2017, pages 273???283, 2017.

#### Miscellaneous

* M. Almasi, H. Hemmati, G. Fraser, P. McMinn, J. Benefelds. Search-based detection of deviation failures in the migration of legacy spreadsheet applications. Proceedings of the 27th ACM SIGSOFT International Symposium on Software Testing and Analysis. pages 266-275. 2018, ACM.

* Y. Shen, Y. Jiang, C. Xu, P. Yu, X. Ma, and J. Lu. ReScue: Crafting Regular Expression DoS Attacks. In Proceedings of the 33rd International Conference on Automated Software Engineering, ASE '18.

* J. Chen, V. Nair, R. Krishna, and T. Menzies. ???Sampling??? as a Baseline Optimizer for Search-Based Software Engineering. IEEE Transactions on Softare Engineering, 2018.

* M. Pradel, G. Gousios, J. Liu, S. Chandra. TypeWriter: Neural Type Prediction with Search-based Validation. In Proceedings of the 28th ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering, ESEC/FSE '20.

</div>

<script>

if (window.location.href == sessionStorage.getItem('lastVisitedUrl')) {
    // When this page is lastly visited: Reopen the lastly visted tab
    try {
        i = sessionStorage.getItem('currentButtonIndex')
        document.getElementsByClassName("tablinks")[i].click()
    } catch (e) { 
        document.getElementById("defaultOpen").click();
    }
} else {
    // Get the element with id="defaultOpen" and click on it
    document.getElementById("defaultOpen").click();
}
    
</script>

[slide01]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide01.pdf
[slide02]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide02.pdf
[slide03]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide03.pdf
[slide04]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide04.pdf
[slide05]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide05.pdf
[slide06]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide06.pdf
[slide07]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide07.pdf
[slide08]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide08.pdf
[slide09]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide09.pdf
[slide10]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide10.pdf
[slide11]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide11.pdf
[slide12]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide12.pdf
[slide13]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide13.pdf
[slide14]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide14.pdf
[slide15]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide15.pdf
[slide16]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide16.pdf
[slide17]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide17.pdf
[slide18]: {{site.baseurl}}/assets/files/teaching/cs454/cs454-slide18.pdf

[ucl_random_testing]: {{site.baseurl}}/assets/files/teaching/2016/cs492b/ucl_random_testing.pdf
[Chen2004]:{{site.baseurl}}/assets/files/teaching/2016/cs492b/Chen2004.pdf
