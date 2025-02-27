## Data Science Experimental Design Project (Work In Progress)

## Python 随机对照试验的实证研究

该项目评估了自适应学习技术与传统静态学习方法对学生成绩和参与度的影响，并采用严格的实验设计进行研究。为了确保结果的稳健性，研究采用了多种随机对照试验（RCT）设计，包括平行RCT、配对RCT、交叉RCT、撤回RCT和因子RCT。

参与者根据基线特征（如GPA、过往表现）进行分层，并分配到自适应学习（实验组）或静态学习（对照组）。主要绩效指标包括测试后测验分数、学习进度、学习时间、知识保留率和辍学率。

数据分析采用Shapiro-Wilk和Levene检验来验证正态性和方差齐性，并使用单因素方差分析（ANOVA）和卡方检验进行评估。研究结果表明，自适应学习组在测试成绩、学习时间和知识保留率方面显著优于静态学习组，同时辍学率更低。这些发现为优化教育策略提供了数据驱动的见解。

### 主要贡献总结
####  1.	研究设计与数据收集：
- 根据基线特征对参与者进行分层和配对，确保治疗组和对照组的可比性。
- 设计并实施了多种 RCT 实验，确保结果的稳健性。
- 收集了多项关键绩效指标，包括测验分数、进步分数、学习时间、保留率和辍学率。
####   2.	数据分析：
- 使用 Shapiro-Wilk 和 Levene 检验验证数据的正态性和方差齐性。
- 对连续变量进行单向方差分析，对分类变量进行卡方检验，评估组间差异。
- 通过比较各项指标的平均值，评估小组表现。
####   3.	研究结果和影响：
- 发现自适应学习组在测验分数、学习时间和保留率方面显著优于静态学习组。
- 自适应学习组的辍学率显著低于静态学习组。
- 提供了数据驱动的见解，支持教育策略的优化。
#### 4.	技术技能：
- 使用 Python（Pandas、NumPy、SciPy、Statsmodels、Matplotlib）进行数据分析和可视化。
- 应用统计分析和实验设计方法，确保研究的科学性和严谨性。
- 通过数据可视化展示研究结果，增强结果的可解释性和影响力。

该项目展示了我在实验设计、统计分析和数据驱动决策方面的专业能力。

---

### Project Title: Evaluating the Effectiveness of Adaptive Learning vs. Static Learning

This project assessed the impact of adaptive learning techniques versus traditional static learning methods on student achievement and engagement through a rigorous experimental design. A variety of randomized controlled trial (RCT) designs were employed, including parallel, paired, crossover, withdrawal, and factorial RCTs, to ensure robust results.

Participants were stratified based on baseline characteristics (e.g., GPA, past performance) and assigned to either the adaptive learning (treatment) or static learning (control) group. Key performance indicators included post-test quiz scores, progress scores, learning time, retention rates, and dropout rates.

Data analysis involved verifying normality and homogeneity using Shapiro-Wilk and Levene tests, followed by one-way ANOVA and chi-square tests. Results showed that students in the adaptive learning group significantly outperformed those in the static learning group in terms of test scores, learning time, and retention, while also exhibiting lower dropout rates. These findings provide data-driven insights for optimizing educational strategies.


### Objective:
* To assess the impact of adaptive learning technologies on student performance and engagement compared to traditional static learning methods.

### Methodology:

* Study Design: Implemented both Parallel RCT, Matched-Pairs RCT, Crossover RCT, Withdrawal RCT, Factorial RCT to ensure robust comparisons between groups.

* Participants: Stratified and matched students based on baseline characteristics (GPA, prior performance, etc.) to form treatment (Adaptive Learning) and control (Static Learning) groups.

* Data Collection: Collected metrics including Post-Test Quiz Score, Improvement Score, Study Time, Retention Rate, and Dropout Rate.

### Analysis:
* Conducted Shapiro-Wilk and Levene’s tests for normality and equal variances.

* Utilized One-Way ANOVA for continuous variables and Chi-Square Test for categorical variables to analyze results.

* Compared means of each metric to evaluate group performance.

### Results:
* Found significant improvements in quiz scores, study time, and retention rates in the adaptive learning group.

* Noted a lower dropout rate in the adaptive learning group compared to the static learning group.

### Conclusion:
The project demonstrated that adaptive learning technologies significantly enhance student engagement and performance, providing valuable insights for educational strategies.

