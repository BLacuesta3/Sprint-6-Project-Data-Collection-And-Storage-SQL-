Project Title: Sprint 6 Project/ Data Collection And Storage (SQL) 

Project Description: This project consists of exploratory data analyses and hypothesis testing of information from Zuber, a new ride sharing company in Chicago (hypothetical company). 
The main objective of this project is to understand passenger preferences and the impact of external factor on rides.  The parsing technique is used in order to read/upload the dataframe from a URL using the: requests and bs4 libraries This project includes various Exploratory Data Analysis (EDA) sections as well as a hypothesis testing task at the end of the project. 

Tasks Presented In The Project: 

1) Import the files.
 
2) Study the data they contain.
   
3) Make sure the data types are correct.
   
5) Identify the top 10 neighborhoods in terms of drop-offs.
 
6) Make graphs: taxi companies and number of rides, top 10 neighborhoods by number of dropoffs.

7) Draw conclusions based on each graph and explain the results.

8) Test the hypothesis:

"The average duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays."

Decide where to set the significance level (alpha) on your own.

Explain:

* How you formed the null and alternative hypotheses.

* What criterion you used to test the hypotheses and why.


Project Dataframes: 

* 'moved_project_sql_result_01 (2).csv'

* 'moved_project_sql_result_04 (2).csv'

* 'moved_project_sql_result_07 (3).csv'


Project Libraries And Tools Used: 

*requests

*pandas 

*bs4 (function: BeautifulSoup())

*numpy 

*scipy (module: stats)

Project Methodology: 

1) Importing The Necessary Libraries Via Parsing Using The Requests And bs4 Libraries

2) Data Cleaning/ Data Preprocessing

3) Bar Chart Displaying Number Of Rides Per Taxi Company (EDA Task)

   Bar Chart Results:
   The company with the most amount of rides per company was Flash Cab, which had 19,558 trips. The company with the least amount of rides per company was
   Blue Ribbon Taxi Association Inc., with 5,953 trips.

5) Bar Chart For Top 10 Neighborhoods In Terms Of Dropoffs (EDA Task)
   
   Top 10 Neighborhoods In Terms Of Dropoffs Bar Chart Results:

   1) Loop- with an average trips sum of approximately 10,727 trips.

   2) River North- with an average trips sum of approximately 9,523 trips.

   3) Streeterville- with an average trips sum of approximately 6,664 trips.

   4) West Loop- with an average trips sum of approximately 5,163 trips.

   5) O'Hare- with an average trips sum of approximately 2,549 trips.

   6) Lake View- with an average trips sum of approximately 2,420 trips.

   7) Grant Park- with an average trips sum of approximately 2,068.533 trips.

   8) Museum Campus- with an average trips sum of approximately 1,510 trips.

   9) Gold Coast- with an average trips sum of approximately 1,364.233 trips.

   10) Sheffield & DePaul- with an average trips sum of approximately 1,259 trips.

7) Hypothesis Testing Task:

   * Null Hypothesis: The average duration of rides from the Loop to O'Hare International Airport does not change on rainy Saturdays.

   * Alternate Hypothesis: The average duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays.
  
     ttest Used For Task: st.ttest_ind()

   Hypothesis Testing Task Result:

   "We reject null hypothesis."


