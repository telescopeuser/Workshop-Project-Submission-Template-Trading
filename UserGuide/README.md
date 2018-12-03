# PortfolioU
An automatic trading system implementing the fuzzy logic, genetic algorithm trading system as written in this paper “Quantified moving average strategy of crude oil futures market based on fuzzy logic rules and genetic algorithms” by Xiaojia Liu, Haizhong An, Lijun Wang and Qing Guan


## Prerequisites
* Git
* Anaconda 1.9.2
* Jupyter Notebook 5.5.0
* Spyder 4.0
* Python 3.6


## Libraries
* matplotlib
* datetime  
* backtrader
* scikit-fuzzy
* ta-lib
* pandas
* numpy
* pytz


## Setup
Copy Scripts/skfuzzy/controlsystem.py to <Anaconda Installation Folder>\Lib\site-packages\skfuzzy\control. This is required to use the get antecedent function custom implementation.

## Running the solution
Please run the following commands on a terminal.
* git clone https://github.com/steve7an/PortfolioU.git
* cd PortfolioU/Scripts
* jupyter notebook
* Open bt2.ipynb on notebook
* run all the cells in order



/Scripts
1. bt2.ipynb - the Jupyter notebook for the script


/Scripts/Data/Test
1. Training.csv


/Scripts/Data/Prod
1. Testing.csv 


/Scripts/skfuzzy
Replace the file in the your path to use the get_antecedent function:
\anaconda3\Lib\site-packages\skfuzzy\control
1. controlsystem.py - modified this file on the skfuzzy library to include the get antecedents function


/Scripts/Data/Model - all the cached fuzzy models
1. ama_10_100.csv
2. ama_10_150.csv
3. ama_10_20.csv
4. ama_10_200.csv
5. ama_10_50.csv
6. ama_15_100.csv
7. ama_15_150.csv
8. ama_15_20.csv
9. ama_15_200.csv
10. ama_15_50.csv
11. ama_20_100.csv
12. ama_20_150.csv
13. ama_20_200.csv
14. ama_20_50.csv
15. ama_3_10.csv
16. ama_3_100.csv
17. ama_3_150.csv
18. ama_3_20.csv
19. ama_3_200.csv
20. ama_3_50.csv
21. ama_5_10.csv
22. ama_5_100.csv
23. ama_5_150.csv
24. ama_5_20.csv
25. ama_5_200.csv
26. ama_5_50.csv
27. desktop.ini
28. sma_1_10.csv
29. sma_1_100.csv
30. sma_1_150.csv
31. sma_1_20.csv
32. sma_1_200.csv
33. sma_1_50.csv
34. sma_10_10.csv
35. sma_10_100.csv
36. sma_10_150.csv
37. sma_10_20.csv
38. sma_10_200.csv
39. sma_10_50.csv
40. sma_15_100.csv
41. sma_15_150.csv
42. sma_15_20.csv
43. sma_15_200.csv
44. sma_15_50.csv
45. sma_20_100.csv
46. sma_20_150.csv
47. sma_20_200.csv
48. sma_20_50.csv
49. sma_3_10.csv
50. sma_3_100.csv
51. sma_3_150.csv
52. sma_3_20.csv
53. sma_3_200.csv
54. sma_3_50.csv
55. sma_5_10.csv
56. sma_5_100.csv
57. sma_5_150.csv
58. sma_5_20.csv
59. sma_5_200.csv
60. sma_5_50.csv
61. tma_10_100.csv
62. tma_10_150.csv
63. tma_10_20.csv
64. tma_10_200.csv
65. tma_10_50.csv
66. tma_15_100.csv
67. tma_15_150.csv
68. tma_15_20.csv
69. tma_15_200.csv
70. tma_15_50.csv
71. tma_20_100.csv
72. tma_20_150.csv
73. tma_20_200.csv
74. tma_20_50.csv
75. tma_3_10.csv
76. tma_3_100.csv
77. tma_3_150.csv
78. tma_3_20.csv
79. tma_3_200.csv
80. tma_3_50.csv
81. tma_5_10.csv
82. tma_5_100.csv
83. tma_5_150.csv
84. tma_5_20.csv
85. tma_5_200.csv
86. tma_5_50.csv
87. tpma_1_10.csv
88. tpma_1_100.csv
89. tpma_1_150.csv
90. tpma_1_20.csv
91. tpma_1_200.csv
92. tpma_1_50.csv
93. tpma_10_100.csv
94. tpma_10_150.csv
95. tpma_10_20.csv
96. tpma_10_200.csv
97. tpma_10_50.csv
98. tpma_15_100.csv
99. tpma_15_150.csv
100. tpma_15_20.csv
101. tpma_15_200.csv
102. tpma_15_50.csv
103. tpma_20_100.csv
104. tpma_20_150.csv
105. tpma_20_200.csv
106. tpma_20_50.csv
107. tpma_3_10.csv
108. tpma_3_100.csv
109. tpma_3_150.csv
110. tpma_3_20.csv
111. tpma_3_200.csv
112. tpma_3_50.csv
113. tpma_5_10.csv
114. tpma_5_100.csv
115. tpma_5_150.csv
116. tpma_5_20.csv
117. tpma_5_200.csv
118. tpma_5_50.csv