### Worksop Project Submission Template: Github Repository & Zip File

**[Naming Convention]** CourseCode-StartDate-BatchCode-Group_or_Individual-TeamName_or_PersonName-ProjectName.zip

* **[MTech Group Project Naming Example]** IRS-MR-2019-01-19-IS1PT-GRP-AwsomeSG-HDB_BTO_Recommender.zip

* **[MTech Individual Project Naming Example]** IRS-MR-2019-07-01-IS1FT-IND-SamGuZhan-HDB_BTO_Process.zip

* **[EEP Group Project Naming Example]** IRS-MR-2019-03-13-EEP-GRP-AwsomeSG-HDB_BTO_Recommender.zip

* **[EEP Individual Project Naming Example]** IRS-MR-2019-08-22-EEP-IND-SamGuZhan-HDB_BTO_Process.zip

[Online editor for this README.md markdown file](https://pandao.github.io/editor.md/en.html "pandao")

---

### <<<<<<<<<<<<<<<<<<<< Start of Template >>>>>>>>>>>>>>>>>>>>

---

## SECTION 1 : PROJECT TITLE
## PortfolioU Algorithmic Trading System

<img src="Miscellaneous/Results/graphfinalRun.png"
     style="float: left; margin-right: 0px;" />

---
## SECTION 2 : EXECUTIVE SUMMARY / PAPER ABSTRACT
The objective of this continuous assessment is to implement the technique proposed in one of the papers shortlisted by the lecture. Our team chose to implement the solution suggested on the paper titled “Quantified moving average strategy of crude oil futures market based on fuzzy logic rules and genetic algorithms” by Xiaojia Liu, Haizhong An, Lijun Wang and Qing Guan. As the title suggests, the authors intend to utilize a variety of moving averages functions using fuzzy logic optimized by genetic algorithm to achieve better returns in crude palm oil futures on the New York Mercantile Exchange (NYMEX). The paper talks about how different moving average can be combined to infer trading signals for buy/sell and use fuzzy logic to determine trading volume. The paper claims that fuzzy moving average strategy proposed gives stable returns when compared to moving average strategies. In our exercise, we learnt the techniques proposed and tried out the proposal to trade crude palm oil (FCPO) futures in the Bursa Malaysia Derivative Exchange. Our model managed to achieve 8,540,649.04 Malaysian Ringgits (MYR) at the end of the 6th year which is a loss of around -15% due to the overfitting of the training data. The rest of this write up discusses the approach, implementation methodology, results and learnings from this exercise. 

**Keywords**: Algorithmic trading, crude palm oil futures, fuzzy logic, genetic algorithm, moving average. 

---
## SECTION 3 : CREDITS / PROJECT CONTRIBUTION

| Official Full Name  | Student ID (MTech Applicable)  | Work Items (Who Did What) | Email (Optional) |
| :------------ |:---------------:| :-----| :-----|
| ISAAC VARUN KUMAR | A1234567A | xxxxxxxxxx yyyyyyyyyy zzzzzzzzzz| A1234567A@nus.edu.sg |
| LAXMAN SINGH | A1234567B | xxxxxxxxxx yyyyyyyyyy zzzzzzzzzz| A1234567B@gmail.com |
| RAMASAMY MUTHURAMAN | A1234567C | xxxxxxxxxx yyyyyyyyyy zzzzzzzzzz| A1234567C@outlook.com |
| TAN CHEE WEI | A1234567D | xxxxxxxxxx yyyyyyyyyy zzzzzzzzzz| A1234567D@yahoo.com |

---
## SECTION 4 : VIDEO OF SYSTEM MODELLING & USE CASE DEMO

Note: It is not mandatory for every project member to appear in video presentation; Presentation by one project member is acceptable.

[![Fuzzy Moving Average System with Genetic Algorithm Optimisation for Trading Crude Palm Oil Futures](http://img.youtube.com/vi/c-SQBHtVb8Y/0.jpg)](https://youtu.be/c-SQBHtVb8Y "Fuzzy Moving Average System with Genetic Algorithm Optimisation for Trading Crude Palm Oil Futures")

---
## SECTION 5 : USER GUIDE

`<Github File Link>` : <https://github.com/telescopeuser/Workshop-Project-Submission-Template-Trading/blob/master/UserGuide/README.md>

### Prerequisites
* Git
* Anaconda 1.9.2
* Jupyter Notebook 5.5.0
* Spyder 4.0
* Python 3.6

### Libraries
* matplotlib
* datetime  
* backtrader
* scikit-fuzzy
* ta-lib
* pandas
* numpy
* pytz

### Setup
> Copy Scripts/skfuzzy/controlsystem.py to <Anaconda Installation Folder>\Lib\site-packages\skfuzzy\control. This is required to use the get antecedent function custom implementation.

## Run system / solution
Please run the following commands on a terminal.
> git clone [ this repository ]
> cd **SystemCode/Scripts**
> jupyter notebook
> Open [bt2.ipynb](https://github.com/telescopeuser/Workshop-Project-Submission-Template-Trading/blob/master/SystemCode/Scripts/bt2.ipynb)
> run all the cells in order

---
## SECTION 6 : PROJECT REPORT / PAPER

`<Github File Link>` : <https://github.com/telescopeuser/Workshop-Project-Submission-Template-Trading/blob/master/ProjectReport/Fuzzy%20Moving%20Average%20System%20with%20Genetic%20Algorithm%20Optimisation%20for%20Trading%20Crude%20Palm%20Oil%20Futures.v1.pdf>

**Recommended Sections for Project Report / Paper:**
- Executive Summary / Paper Abstract
- Sponsor Company Introduction (if applicable)
- Business Problem Background
- Project Objectives & Success Measurements
- Project Solution (To detail domain modelling & system design.)
- Project Implementation (To detail system development & testing approach.)
- Project Performance & Validation (To prove project objectives are met.)
- Project Conclusions: Findings & Recommendation
- List of Abbreviations (if applicable)
- References (if applicable)

---
## SECTION 7 : MISCELLANEOUS

### BusinessProblem
* GA-Fuzzy ATS.pdf

### BusinessProblemData
* FCPO_6_years_NUS.xlsx

### Research
* Reference paper

### Results
* Figures used in report

### Function_class_list.txt

---

### <<<<<<<<<<<<<<<<<<<< End of Template >>>>>>>>>>>>>>>>>>>>

---

**This [Machine Reasoning (MR)](https://www.iss.nus.edu.sg/executive-education/course/detail/machine-reasoning "Machine Reasoning") course is part of the Analytics and Intelligent Systems and Graduate Certificate in [Intelligent Reasoning Systems (IRS)](https://www.iss.nus.edu.sg/stackable-certificate-programmes/intelligent-systems "Intelligent Reasoning Systems") series offered by [NUS-ISS](https://www.iss.nus.edu.sg "Institute of Systems Science, National University of Singapore").**

**Lecturer: [GU Zhan (Sam)](https://www.iss.nus.edu.sg/about-us/staff/detail/201/GU%20Zhan "GU Zhan (Sam)")**

[![alt text](https://www.iss.nus.edu.sg/images/default-source/About-Us/7.6.1-teaching-staff/sam-website.tmb-.png "Let's check Sam' profile page")](https://www.iss.nus.edu.sg/about-us/staff/detail/201/GU%20Zhan)

**zhan.gu@nus.edu.sg**
