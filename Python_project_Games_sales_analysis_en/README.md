# Project Games_sales_analysis: Analysis of sales and ratings of games

In this project, we work with dataset, which contains information on sales of games of different genres and platforms, as well as user and critic ratings of games. My task is to get acquainted with the data, check its correctness and conduct pre-processing, having received the necessary data slice. Then categorize the games by user and critic ratings. And highlight the top-7 platforms by the number of games released over the entire required period.

I used Python and Jupyter Notebook (Python_project_Games_sales_analysis_en.ipynb file is next to this one) and pandas library. 

General conclusion:

As a result of data preprocessing, the data frame was cleared of gaps and duplicates, and data types were converted. In total, the number of rows in the data frame was reduced by 512 rows, or 3.02% of the original number. We were interested in data for 2000-2013, so we sliced the data using a Boolean mask with .between() method and saved it to a new dataset, which we continued working with. Next, we added new columns user_score_group and critic_score_group, and assigned each game to the High rating, Average rating and Low rating groups - depending on user and critic ratings. Using grouping and sorting, we found the top-7 platforms by the number of games. 
The largest platforms from 2000-2013 are PS2 and DS.