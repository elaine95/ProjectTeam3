# Canadian Median Employment Income For New Graduates Analysis (2010-2015)

### Project Description

> Have you ever wondered Canadian’s employment income for new graduates? And what kind of characteristics driven to those different levels of income? In this project, we aim to analyze a dataset which contains Canadian’s median employment income of postsecondary graduates two years after graduation by degree, field of study, gender, age group and status from 2010-2015, the goal is to answer to following questions:

* What are the top 3 fields of study that yielded the highest median employment income 2 years after graduation
* Does age and gender affect the median income in the same field of study?
* Which type of accreditation yields the highest new graduate income?
* Which province has the highest median income and which has the lowest? What field of study has the highest median income in each Province?
* Is there a relationship between the number of graduates and income?

### Dataset
[Dataset URL](https://open.canada.ca/data/en/dataset/47bf6ec6-079c-413a-a6eb-7de43401280b)
[Supporting Document URL](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3710012201)
> We have selected a trusted dataset [Open Government Licence - Canada](https://open.canada.ca/en/open-government-licence-canada) and sourced from Statistics Canada (You can access the dataset in the above links). The dataset contains characteristics and median employment income of postsecondary graduates two years after graduation, by educational qualification (Classification of programs and credentials - professional degree variant), field of study (Classification of Instructional Programs (CIP) Canada 2016 - Alternative primary groupings), gender, age group and status of student in Canada. The raw dataset has 218,9307 entries with total of 21 column.
We have cleaned and analysed the dataset for each topic. Please find the detailed analysis for each topic in the Jupyter Notebooks folder.

### Project Conclusions
1. "Health and related fields", "Dental, Medical and veterinary residency programs", and "Business, management, marketing and related support services" were consistently the top 3 fields of study that yielded the highest median employment income in all years of study.
2. Gender has a significant impact on the employment median income for new graduate no matter in which age group or provinces. Specifically, female has lower median income for all age group across Canada. ![Plot of Employment Median Income by gender in different age group](https://github.com/elaine95/ProjectTeam3/blob/master/Plots/Income_by_gender_for_different_age.png)
3. New graduates median income also affected by the type of accreditation. In general, graduates with higher accreditation type tends to have higher median income. Doctoral and Master degree have significant higher median income than Degree, Diploma and Certificate accreditation. ![Median Income by Different Accreditation](https://github.com/elaine95/ProjectTeam3/blob/master/Plots/Median_income_by_different_Accreditation.png)
4. Considering median income geographically, Alberta has the highest income whereas Prince Edward Island has the lowest median income for all field of study from 2010 to 2015. However, it is interesting to know that there are four provinces including AB, NL, BC and NB's top median income are graduates who gained education of Engineering as their field of study. ![Plot of Employment Median Income in Different Provinces](https://github.com/elaine95/ProjectTeam3/blob/master/Plots/Top_median_income_among_provinces.png)
5. There is no notable relationship between number of graduates and employment median income. ![Scatter Matrix Median Income in relation with Number of Graduates](https://github.com/elaine95/ProjectTeam3/blob/master/Plots/graduate_number_and_income_relationship.png)
