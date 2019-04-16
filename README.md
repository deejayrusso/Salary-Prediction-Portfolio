# Salary Prediction Portfolio
Salary Prediction Project (Python)

### <u>Methods Used</u>
<ul>
  <li>Data Analysis and Visualization</li>
  <li>Linear Regression</li>
  <li>Polynomial Transformation</li>
  <li>Ridge Regression</li>
  <li>Random Forest</li>
  </ul>

### <u>Technologies/Libraries Used</u>
<ul>
  <li>Python 3</li>
  <li>Pandas</li>
  <li>NumPy</li>
  <li>Seaborn</li>
  <li>Scikit-learn</li>
  <li>Matplotlib</li>
  <li>SciPy</li>
  <li>Jupyter</li>
  </ul>
  
## <u>Description</u>
The purpose of this project is to use data transformation and machine learning to create a model that will predict a salary when given years of experience, job type, college degree, college major, industry, and miles from a metropolis. 

## <u>Data</u>
The data for this model is fairly simplified as it has very few missing pieces. The raw data consists of a training dataset with the features listed above and their corresponding salaries. Twenty percent of this training dataset was split into a test dataset with corresponding salaries.

There is also a testing dataset that does not have any salary information available and was used as a substitute for real-world data. 

### <u>Information Used To Predict Salaries</u>
<ul>
  <li><b>Years Experience:</b> How many years of experience</li>
  <li><b>Job Type:</b> The position held (CEO, CFO, CTO, Vice President, Manager, Janitor, and senior or junior position)</li>
  <li><b>College Degree:</b> Doctoral, Masters, Bachelors, High School, or None</li>
  <li><b>College Major:</b> Biology, Business, Chemistry, Computer Science, Engineering, Literature, Math, Physics, or None</li>
  <li><b>Industry:</b> Auto, Education, Finance, Health, Oil, Service, or Web</li>
  <li><b>Miles From Metropolis:</b> How many miles away from a major city</li>
  </ul>  
 
## <u>Summary</u>
Applying second order polynomial transformation to the features used gave the most accurate predictions with the least error when using a linear regression model. The result was a mean squared error of 354 with a 76% accuracy rate. 

This model can be used as a guide when determining salaries since it shows reasonable predictions when given information on years of experience, miles from metropolis, job type, industry, and college degree and major.
