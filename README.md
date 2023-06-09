# Statistical Analysis and Statistical Test in SAS

In this project, we're looking at the data science job opportunity connected to their salary, location, firm, sector, industry type, and skills to determine whether there's a link between these factors. This dataset contains data science job roles and descriptions in different companies and approximate salaries offered for various positions in other companies. This data set contains all the information on data science job posting on Glassdoor, like company name, industry type, sector, minimum and aximum salary offered, location of the company, skills required, and job description of the role. This analysis will help us find the key factors driving the demand for ata science jobs. We will be able to understand the inclination of organizations toward data science business strategies and the rising adoption of an advanced career in creating opportunities for the data science job through lassdoor data analysis. 

## The dataset for this project has been taken from the URL link:
[Data Science Job Posting Data Analysis](https://www.kaggle.com/datasets/deepcontractor/unicorn-companies-dataset)

## Statistical Analysis
**Statistical analysis for the variable Base Salary (USD)**<br>
![test 1](https://user-images.githubusercontent.com/122247029/229635696-00647f69-7347-49b3-a56c-61afa86e5e25.PNG)

![test 2](https://user-images.githubusercontent.com/122247029/229635708-74db5e19-a84d-4589-837f-5d62a8fb3ef2.PNG)<br>

**Mean**
The mean of the base salary is 159796.75 UDS. The minimum salary is 12500, and the maximum salary is 685000 USD. The data indicated that a candidate’s average salary is around 159796.75 UDS. This mean value indicated an average salary offered to a candidatecompared to different companies. This mean value can be compared against an individual base salary to judge if they have comparably provided a good salary compared to another candidate. Similarly, their respective means can be used to compare the base salary of a smaller group against a more comprehensive group. An example would be comparing the mean base salary offered by a small company and a big company. <br>

**Standard Deviation**
The standard deviation of the variable base salary is 61995. 20. That means that each company’s base salary is at an average difference of 61995.20 from the mean salary of all the companies. This value shows how the data is spread out from the mean. The standard deviation is less than the mean value, indicating that the data points were below the mean. Since the standard deviation is lower than the mean value, the data are more clustered around the mean. <br>

**Median**
The median of the variable base salary is 150000, and the mean value is 159796.75. The median provides a helpful measure of the center of a dataset. We can see that the median value is very close to the mean value. Since the median value is almost very close to the mean, we can conclude that the dataset distribution is symmetrical. We are comparing the median to the mean; we can say that the data set is evenly distributed from the lowest to highest values.<br>

**Minimum**
We see the minimum base salary offered to a job. When we compare the base salary provided by different companies for different job roles and different years of experience, we see that the minimum salary offered is $12500<br>

**Maximum** We see the maximum base salary offered to a job. When we compare the base salary provided by different companies for different job roles and different years of experience, we see that the maximum salary offered is $685000<br>

**Variance**
The variance of the variable base salary is 3843404792, which is very high. This indicates that some companies offer very high salaries, and some offer very low salaries. This also suggests that salary values are more spread out. <br>

## Statistical Test
**1. One-way Frequency**<br>

![SAS One-way frequency chart](https://user-images.githubusercontent.com/122247029/229633765-914b35ba-a064-4132-b352-f74bbc3422ff.PNG) 
![One-way frequency chart](https://user-images.githubusercontent.com/122247029/229633651-838302ee-0522-4636-82ae-2fa31e054164.PNG) <BR>
One-way frequency tables help us understand which data values are common and rare. A frequency distribution provides a visual representation of the distribution of observations within a particular test. We often use a frequency distribution table to visualize the data. These tables organize our data and are an effective way to present the results to others. Frequency tables are also known as frequency distributions because they allow you to understand the distribution of values in your dataset. The most frequently occurring values are easily identified, as are valueranges, lower and upper limits, cases that are not common, outliers, and the total number of observations between any given values. A frequency table shows the distribution of observations based on the base salary offered by different companies. This frequency table can be used to understand which value occurs more and which value occurs less in the dataset. This table helps us know the frequency distribution and describes how frequently a value is repeated in the data set. This table shows that the base salary of 150000 USD and 160000 USD is repeated 35 times. Many values are not repeated. This table shows the variation in salary from 12500 USD to 685000 USD. We can see the distribution of the salary. In this case, if a candidate is looking for a particular salary range, they can divide the salary category into lower, average, and high salary ranges according to their expectation and compare the salaries offered by different companies. They can see how many companies offer low, medium, and high salaries. With the help of the table, the candidate will get an idea of their salary expectation.<BR>

**2. Correlation Analysis**<br>

![SAS corelation analysis](https://user-images.githubusercontent.com/122247029/229633803-b361fa37-3c23-4dc7-a5f5-f643b1309d54.PNG) 
![corelation analysis scatter plot](https://user-images.githubusercontent.com/122247029/229633848-3e56a9c2-7d75-41c3-8083-e36dc185b440.PNG)<BR>
In this example, the analysis variable is Base salary (USD), and the correlated variable is years of experience. Here we are checking the correlation between these two variables. We are checking if years of experience have any effect on base salary. Correlation analysis measures the strength of the linear relationship between two variables and computes their association. With the help of correlation analysis, we can calculate the level of changes in one variable due to the difference in the other. The Pearson correlation coefficient tests whether the relationship between two variables is significant. Pearson's correlation is used when you want to see if there is a linear relationship between two variables. The values range of the correlation coefficient is between -1.0 and 1.0. A calculated number greater than 1.0 or less than -1.0 means that there is an error in the correlation measurement. A correlation of -1.0 shows a perfect negative correlation, while a correlation of 1.0 shows a perfect positive correlation. A positive correlation means the two variables move in the same direction. A negative correlation means they move in opposite directions.The table shows the Pearson correlation coefficient as – 0.03, which shows a negative correlation. For Negative correlation, the two variables move in opposite directions, i.e., one variable increases as the other decreases, and vice versa. From this analysis, we can conclude that there is no relation between the variables, base salary, and years of experience. <br>

**3. Linear Regression**<br>

![linear regression output](https://user-images.githubusercontent.com/122247029/229633895-6b740674-a6c2-4e1e-bb50-0bd9ad0da570.PNG)
![linear regression chart](https://user-images.githubusercontent.com/122247029/229633934-51adb678-72d3-4377-a102-150eb71e4842.PNG)<br>
Linear regression analysis predicts a variable's value based on another variable's value. The variable you want to predict is called the dependent variable. The variable you are using to predict the other variable's value is called the independent variable. In our example, the dependent variable is base salary, and the independent variable is the year of experience.<br>
Linear Regression Equation<br>
𝑌 = 𝑚𝑥 + 𝑐<br>
In the above equation, m is the slope, c is the constant, and y is the y-intercept From the linear regression table, we can write the liner regression equation as <br>
𝑌 = 1 ∗ (𝑦𝑒𝑎𝑟 𝑜𝑓 𝑒𝑥𝑝𝑒𝑟𝑖𝑒𝑛𝑐𝑒) + 250000<br>
R square value is approximately 0.0464, which is 4.64%. This shows a correlation between base salary and years of experience. This indicates very low correlations. There were 570 observations. No missing values are reported. The r-squared value is 4.64%, which is the correlation between base salary and years of experience in this example. <br>
For p=0.5, it is statistically significant because it is greater than 0.0001, shown in the table. This means that any variation in the base salary can be explained by the change in the year of experience. For p=0.05, the results are statistically significant because it is greater than 0.0001; the model value is given in the table. We can conclude that years of experience explain the variation in base salary has significantly less impact on this variation.
