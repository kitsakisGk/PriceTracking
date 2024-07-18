# PriceTracking

## The code is writen on Jupyter Notebooks. 

Open Anaconda prompt
Install the latest pip updates : <br>
pip install --upgrade pip --trusted-host pypi.org --trusted-host files.pythonhosted.org 

---------------------------------

Install undetected-chromedriver(For the web-links to play) : <br>
pip install undetected-chromedriver --trusted-host pypi.org --trusted-host files.pythonhosted.org

---------------------------------

Create a Python script named install_packages.py <br>
```python
import ssl
import os

ssl._create_default_https_context = ssl._create_unverified_context

os.system('pip install undetected-chromedriver')
os.system('pip install pandas sqlalchemy openpyxl')
```
---------------------------------

Run the script: <br>
```bash
python install_packages.py
```
---------------------------------

### Connect to database

I used Microsoft SQL Server for the server and the database. <br>
All SQL Dbs can be used. Connect with your DB server and the program will start write on the tables. 

---------------------------------

Run the Jupyter Notebook LivePriceTracking. <br> <br>
You need to have also downloaded the PowerBI so you can see the results. <br>
You can see how my prompt in PowerBI is and you can either use it as it is or you can change it based on your likes.

---------------------------------

![image](https://github.com/user-attachments/assets/b7223875-57a1-4923-ae6e-143c90566c1c)



