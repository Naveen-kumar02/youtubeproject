# Project Title
    YouTube Data Harvesting and Warehousing 
# Tools required:
    1. youtube api key
    2. python
    3. MongoDb
    4. MySql
    5. streamlit
# Problem Statement:
   The problem statement is to create a Streamlit application that allows users to access and analyze data from multiple YouTube channels. The application should        have the following features:
        1.   Ability to input a YouTube channel ID and retrieve all the relevant data (Channel name, subscribers, total video count, playlist ID, video ID, likes,                 comments of each video) using Google API.
        2.   Option to store the data in a MongoDB database as a data lake.
        3.   Ability to collect data for up to 10 different YouTube channels and store them in the data lake by clicking a button.
        4.   Option to select a channel name and migrate its data from the data lake to a SQL database as tables.
        5.   Ability to search and retrieve data from the SQL database using different search options.

# Project Overflow:
    Step 1: create streamlit dashbord as per the requirement, go through the documnetation https://docs.streamlit.io/library/api-reference/performance/st.cache_data

    Step 2: create google youtube api key , to create youtube api key refer the documentation          
            https://docs.google.com/document/d/1c2cjHu1uaRacIeOBMgIfT3YXwbaKIIfm4_rxDAcczos/edit?usp=sharing

    Step3: Scrape the channel details, playlist details, video details, comment details by using youtube api key and store into the mongodb by using mongodb 
           connectivity in python

    Step4: After store into the mongodb get the data from the mongodb and convert the data into table format the insert into the MySql 

    Step5: once this process is finished you will get the answer by choosing the question and display in the streamlit dashboard.


