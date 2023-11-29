# Data Science Certification Capstone Project 

For this capstone project, the scenario is set in the context of the commercial space industry. The focus is on SpaceX, a prominet player in this field known for its reusable Falcon9 rockets. The main challenge is to determine the cost of each launch by predicting whether the first stage of the Falcon9 rocket will land successfully and be reusable. 

In this project, I take on the role of a data scientist working for a new rocket company called SpaceY. My task is to gather information about SpaceX, create dashboards for my team, and leverage machine learning to predict whether SpaceX will reuse the first stage in each launch. The cost of a launch is closely tied to the success of the first stage landing, as reusability significantly reduces expenses. 

The ultimate goal is to provide SpaceY with insights into the pricing dynamics of rocket launches, taking into account the success or failure of the first stage landings. Throughout the course of the project, I will be displaying some key leanrings from the course, such as data analysis, dashboard creation, and machine learning techniques. 

The course this project is from is the IBM Data Science Professional Certificate.

# Step 1 - Data Collection 
In this step, I use 2 different methods to collect SpaceX data relevant to this project. 
### Lab 1  - [Collect Data from SpaceX API](https://github.com/AndCWen/Data_Science_Capstone/blob/main/DataCollectionAndCleaning.ipynb)
In this lab, I gather data from SpaceX API.
### Lab 2 - [Collect Data Using Web Scraping](https://github.com/AndCWen/Data_Science_Capstone/blob/main/Data_Collection_WebScraping.ipynb)
In this lab, I gather data about Falcon 9 and Falcon Heavy launches from Wikipedia using web scraping techniques, create a dataframe from the data, and then export it to a csv for use later. 

# Step 1 - Data Wrangling
### Lab 3 [Data Wrangling](https://github.com/AndCWen/Data_Science_Capstone/blob/main/Data_Wrangling.ipynb)
In this step, I do some Exploratory Data Analysis to observe any patterns in the data. I also create a landing outcome label based on the Outcome column which makes it easier to identify a successful landing or a unsuccessful landing by assinging a 1 to success or a 0 to a faiure. This will come in handy later. 

