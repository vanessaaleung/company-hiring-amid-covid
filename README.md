# COVID 2019 Challenge - Who's Hiring

**Team Member:  Vanessa Liang/ Minke Wang/ Stella Zhang/ Yuping Qi**

![COVID 2019 Challenge - Who's Hiring](https://github.com/vanessaaleung/hiring-amid-covid/blob/master/COVID%2019%20Challenge.jpg)

During the special time period of Corona Virus pandemic, it has been especially tough for graduating students and professionals to successfuly land a job. We want to take the initiative to offer help by providing strategic recommendations in job search and accepting offers. Through examining the company's demographic information and funding stauts, we build machine learning models with H2O framework targeting at predicting the future hiring status of companies in the job market in hope to mitigate risks of receiving offer revokes and maximize job search opportunity efficiency during such a hard time.  

Here is our presentation slides outlining our key findings and techniques: 
[**Presentation Deck**](https://docs.google.com/presentation/d/1rA-9K6CHSCv-9bS60clzPGuw63TwUBhOI55NjV4sseo/edit?usp=sharing)

### **Business Case**

Covid-19 pandemic has caused layoff industry-wide, and even the most high-flying startups are feeling the effects of the virus. Layoffs have happened at companies like Bird, ZipRecruiter and ClassPass. As MSBA students are actively looking for jobs currently, we hope our project can provide students with some insightful ideas as which are currently the hardest-hit industries also give recommendation in terms of which companies are likely to freeze hirings  in the future based on our model so that we can optimize our job hunting strategy. 

=============

### **Data Source**

Data Source are mainly pulled from the below sources: 
1. Company Hiring Status:[Candor](https://candor.co/hiring-freezes/)
2. Company demographics information and funding status: [Crunchbase](https://www.crunchbase.com/)

=============


### **Prediction Model**

H2O AutoML frame work is utilized to predict the hiring status of companies with their investment, funding information and demographics information including industry, age etc. 

Best Performace model: Gradient Boosting Machine (GBM)<br>
False Positive Rate: 3.22% <br>
F1 Score: 94.57%<br>
Gini Index: 97%

=============


### **Recommendations**

Based on the modeling results, we reccommend that job seekers keep in mind the follow suggestions: 
For job seekers: 
1. Seek companies already reached round B of funding
2. Consider companies with longer operating history  
3. Business-Facing Companies, Finance and Security Industry are promising 

For policy makers and state governors:
1. Keep an eye on vulnerable industries, consider subsidizing Customer-facing education, retail, and social media industries
2. Encourage states to diversify industries

=============
