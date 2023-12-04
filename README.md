# Project Name: Amazon_analysis

## Overview
This project aims to analyze user behavior data from an SQLite database related to Amazon products. The analysis includes data reading, preparation, and exploration to derive insights into user preferences, popular products, and user engagement.

## Project Structure
The project is structured as follows:

1. **Data Reading from SQLite Database**
   - Utilizes Python to connect to an SQLite database and fetch relevant data.

2. **Data Preparation**
   - Basic cleaning and data wrangling:
     - Removing invalid rows.
     - Eliminating duplicate rows.
     - Converting the "time" feature data type to datetime.

3. **User Product Recommendations**
   - Analyzing data to understand what products Amazon can recommend to users.

4. **Popular Products**
   - Identifying products with a good number of reviews.

5. **User Behavior Analysis**
   - Investigating differences between frequent viewers and non-frequent viewers.

6. **User Verbose Analysis**
   - Examining whether frequent users are more verbose in terms of posts or comments.

7. **Sentiment Analysis**
   - Conducting sentiment analysis on user interactions to understand overall sentiments.

## How to Run
1. Ensure you have Python and Jupyter Notebook installed.
2. Clone this repository to your local machine.
3. Open the Jupyter Notebook file `Amazon_analysis_iwazaki.ipynb`.
4. Run each cell sequentially to execute the code and generate insights.

## Dependencies
- Python 3.x
- Jupyter Notebook
- SQLite Database

## Data Source
The project uses data stored in an SQLite database. Ensure the database connection details are correctly configured.
here's the link to file :https://drive.google.com/file/d/1H7-pPFI2BjxHTdWSCb7e2ROWSjV03adx/view?usp=drive_link

## Conclusion
This project provides valuable insights into Amazon user behavior, helping to identify trends, popular products, and user sentiments.

Feel free to reach out if you have any questions or suggestions!
