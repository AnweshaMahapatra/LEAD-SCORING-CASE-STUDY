
# PROJECT TITLE

LEAD SCORING CASE STUDY

## PROBLEM STATEMENT

An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses. 

 

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%. 

 

Now, although X Education gets a lot of leads, its lead conversion rate is very poor. For example, if, say, they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone.
## OUR TASK :

Our task was to help X Education identify the most potential leads, also known as ‘Hot Leads’. The company wanted to build a model to assign a lead score to each of the leads such that the customers with higher lead score have a higher conversion chance and the customers with lower lead score have a lower conversion chance. The CEO, in particular, had given a ballpark of the target lead conversion rate to be around 80%.
## INFORMATION OF DATA :

We were provided with a leads dataset from the past with around 9000 data points. This dataset consists of various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. which may or may not be useful in ultimately deciding whether a lead will be converted or not. The target variable, in this case, is the column ‘Converted’ which tells whether a past lead was converted or not wherein 1 means it was converted and 0 means it wasn’t converted. You can learn more about the dataset from the data dictionary provided in the zip folder at the end of the page. Another thing that you also need to check out are the levels present in the categorical variables. Many of the categorical variables have a level called 'Select' which needs to be handled because it is as good as a null value.
## GOALS OF THE CASE STUDY:

There are quite a few goals for this case study:

1. Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.
2. There are some more problems presented by the company which your model should be able to adjust to if the company's requirement changes in the future so you will need to handle these as well. These problems are provided in a separate doc file. Please fill it based on the logistic regression model you got in the first step. Also, make sure you include this in your final PPT where you'll make recommendations.
 
## SOLUTION DIVIDED INTO FOLLOWING STEPS: 

1. Data Understanding
2. Data Cleaning and Visualisation
3. Data Preparation
4. Model Building and Evaluation
## CONCLUSION:

In conclusion, lead scoring is a crucial process for companies like X Education, as it can help identify the most potential leads, resulting in higher lead conversion rates. With the help of data analytics and machine learning techniques, we were able to build a predictive model that can accurately assign a lead score to each lead. Our model's performance has helped X Education achieve its target lead conversion rate of 80%.
## DETAILS OF FILES GIVEN:

1. LEAD SCORE CASE STUDY.ipynb : The python file showing coding and data analysis

2. Assignment Subjective Questions.pdf : Some subjective questions answered

3. Lead Score Case Study.pdf : Final Presentation
4. Leads.csv : Data worked on
5. Summary.pdf : Summary on what's done in the entire py file