# data-wrangling
This project is the 7th project of data analyst nanodegree program from udacity, it’s about wrangling data steps ( gathering , assessing , then cleaning ) . The data is archived data from WeRateDogs twitter account, and the data is not ready , that is gathered in three different ways as the first step of the project , this data includes :

1. Archive data: This data file is given in the classroom and downloaded manually. This file is the archive of WeRateDogs contains data about the account tweets with 2356 row (tweet).
2. image predictions data: The given file is in a link to download programmatically using python . This file contains predictions of images(dogs ) using neural network that can classify breeds of dogs.
3. json data from twitter api: This is the most challenging part of data gathering , this is the first time for me to get data from ready api. It takes about two hours of contacting with twitter to create my developer account then I got the credentials and start collecting data, it takes about 35 minutes of collecting data of tweet id’s. Then I saved the collected data in txt file before convert them to csv file to use it , the selected columns/features are the following : 'id','retweet_count','favorite_count','created_at'. After that , I assessed some problems in the data (Data Quality & Tidiness) then I cleaned them.

- data folder contains the mentioned data before cleaning, and twitter_archive_master.csv file contains the cleaned gathered data.
- wrangle_act.html and wrangle_act.ipynb contains the proposed steps.
- I used tableau software for data visualization, you can see it in act_report.pdf file.
- wrangle_report.pdf contains summary of the project.
