![head.png](https://github.com/cafawo/FinancialDataAnalytics/blob/master/figures/head.jpg?raw=1)

# Applied Econometrics (SoSe 2024)

**Prof. Dr. Fabian Woebbeking**</br>
Assistant Professor of Financial Economics

IWH - Leibniz Institute for Economic Research</br>
MLU - Martin Luther University Halle-Wittenberg

fabian.woebbeking@iwh-halle.de


**Birte Winter**</br>
PhD Candidate, Teaching Assistant (TA)

IWH - Leibniz Institute for Economic Research</br>

birte.winter@iwh-halle.de


## Schedule

**The deadline for submitting the seminar paper is the first day of presentations!**

Dates and rooms can be found on Stud.IP: https://studip.uni-halle.de/dispatch.php/course/details?sem_id=5a9defd4ce9b514471199574c12ee710&again=yes


## Grading Policy

The grading policy is discussed in detail during the first meeting.

* Seminar project and paper: 70%
* Presentation and discussion: 30%
	* Own presentation: 20%
	* Questions and discussion: 10%

## Topics

1. Linear regression, least squares and statistical significance
	* Research Question: Explain square meter prices with the property age 
2. Multivariate regression, goodness of fit and information criteria	
	* Research Question: Explain square meter prices with property age, acquisition date, distance to the nearest metro station, number of supermarkets in the neighborhood, and accessibility amenities factor (which is the number of supermarkets divided by the distance to the next metro) 
3. Principal component analysis (PCA)
	* Research Question: Use spot rates to model the yield curve and its slope 
4. Non-linear regression
	* Research Question: Explain square meter prices with property age, acquisition date, distance to the nearest metro, number of supermarkets in the neighborhood, and property age squared 
6. Linear probability, Logit-/ and Probit models
	* Research Question: Predict the likelihood of a prospective client's contentment with the provided service and discern the key elements articulated by clients that predominantly impact airline satisfaction.
5. Tobit regression
	* Consider a scenario where we aim to analyze academic aptitude scores (ranging from 200 to 800) by incorporating reading and math test results, alongside the type of program the student is enrolled in (academic, general, or vocational). Students who answer every question correctly on the academic aptitude test are awarded a perfect score of 800, regardless of potential differences in their actual aptitude levels. Similarly, those who answer all questions incorrectly receive the minimum score of 200, despite potential variations in their true aptitude levels.
	* Research Question: Investigate the relationship between academic aptitude and reading proficiency, math proficiency, and program type, while considering the potential truncation at both upper and lower limits of the aptitude scale
7. Panel data, H-Test, random and fixed effect models*
	* Research Question: How does the total cost of airline operations vary with factors such as revenue passenger miles, fuel price, and load factor?
8. Regression discontinuity*
	* Research Question: Investigate the relationship between the outcome variable and the running variable. Specifically, does the outcome variable change significantly as the running variable crosses a certain threshold while considering other relevant factors such as age, income, education level, health status, and work experience?
9. Difference in difference*
	* Research Question: explain the effect of the treatment (did) on GPD per Capital (gdppc). Account for group-specific and time-specific effects. Check the parallel trend assumption. 
10. Instrumental variable regression*
	* Research Question: Wage should be explained by ability. However, this is unobservable. Use an individual’s mother’s education as an instrumental variable.

(*) Advanced topics


## Task description

Please find general writing guidelines as well as a template at: https://github.com/cafawo/WritingGuidelines

Each seminar paper and presentation should cover:

* **Overview and literature**: a brief description of the method and potential applications. Include a small number of high quality references that use this method and explain the research objectives and findings therein. The goal is to showcase the method, not to give an extensive literature review.
* **Methodology**: Explain the methodology, when and why to use it and potential limitations.
* **Data structure and visualization**: You have been given a test dataset. Show the data (e.g. a tabular snapshot) and why it lends itself to your methodology.
* **Summary statistics**: Show a table with summary statistics of your data.
* **Model specifications**: Specify the corresponding empirical model (mathematical notation) and explain.
* **Results and interpretation**: Fit the model and show your results. Provide a brief interpretation (Which coefficient(s) are significant? What does that mean?).
* **Conclusion**: A very brief summary of your findings.


## Software

You will need a software toolbox that is capable of statistical analysis. Use what you are most familiar with, for example:
* https://www.r-project.org/ (open source)
* https://www.python.org/ (open source)
* https://www.stata.com/
* https://www.ibm.com/spss
* https://gretl.sourceforge.net/ (open source)


## Literature




Despite the vast amount of high-quality online and open-source resources available, if you are looking for a textbook, I recommend _"Mastering metrics : the path from cause to effect"_ or the more comprehensive (Master/PhD level) _"Mostly Harmless Econometrics: An Empiricist's Companion"_ both by Joshua D. Angrist and Jörn-Steffen Pischke. Both books are available at the Library.
