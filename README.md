# News-Analysis-Project-Uncover-What-Matters

## Overview
This project processes news articles to provide mood ratings, short summaries, and identify 
common themes. Additionally, it offers an optional aspect-based sentiment analysis for deeper 
insights into specific elements of the news. 

## Prerequisites
Ensure you have Python3 version 3.10 or above installed on your system. The following Python libraries are required for this project:
-**Pandas:** For handling Excel files and data manipulation. 
- **nltk:** For text preprocessing and tokenization. 
- **re:** For regular expressions and text cleaning. 
- **textblob:** For sentiment analysis. 
- **gensim:** For topic modeling. 
- **scikit-learn:** For additional text processing tasks. 
- **Install these libraries using pip**
- ```pip install pandas nltk textblob gensim scikit-learn```


### Before running the program
Change location of input and output file as per the location where you have stored the file
- **Read file:** ```df = pd.read_excel(r'File_location\Assignment.xlsx')```
- **output:** ```df.to_excel(r'FileLocarion\news_analysis_output.xlsx', index=False)```
## Steps to run the Program
Download Necessary NLTK Data: Before running the script, ensure that you download the necessary NLTK data. This can be done within the script. 
Prepare Your Excel File: Place your Excel file containing the news articles in the same directory as the script. Ensure the file has a column named paragraph which contains the news articles. 
- **Run the Script:** Save the following script as news_analysis.py and run it using Python. 
- **View the Output:** The output will be saved in a new Excel file named news_analysis_output.xlsx in the same directory. This file will contain the cleaned text, mood ratings, topics, aspect sentiment (for 'cost'), and short summaries of the articles.
