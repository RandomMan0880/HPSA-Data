# HPSA-Data

<b> Important Note: </b> Because data used in this project is not able to be shared, this notebook cannot be downloaded and run. Instead, feel free to peruse the code by opening the ipython notebook on Github. Click this link if you are having trouble opening the notebook: <a href='https://github.com/RandomMan0880/HPSA-Data/blob/main/HPSA_Predictor.ipynb'> LINK </a>

HPSA, short for "Health Professional Shortage Area", is a federal government term for a specific region, facility, or location that is experiencing a shortage of healthcare professionals. HPSA Scores are regularly reviewed and updated by the National Health Service Corps in determining priority of assignment of clinicians to certain areas. The scores range from 0 to 26 where the higher the score, the greater the priority. In this project, I will train a Random Forest model using the new Tensorflow Decision Forests package to predict Primary Care HPSA scores based on various location metrics (county income, unemployment rate, etc) using features taken from other government websites such as the US Bureau of Labor Statistics and wrangling them together with SQL.

Skills Used:

Languages: Python, SQL

Packages: Keras, Tensorflow Decision Forests, Psycopg2, SQLAlchemy, Pandas, Regex, Statsmodels, 

Visualizations: Tableau, Plotly, Matplotlib

Environment: Linux (Ubuntu)



My visualizations of existing and predicted healthcare shortage areas in the US. Higher numbers indicate greater severity of staffing deficits. 


![image](https://user-images.githubusercontent.com/71114407/195734535-967a1b6d-5814-4d04-ab73-760ab9c19681.png)

![image](https://user-images.githubusercontent.com/71114407/195734555-9715ad27-fb9c-4dad-b752-7448a331c86b.png)


