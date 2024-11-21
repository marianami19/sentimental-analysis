Sentiment analysis
(also known as opinion mining or
emotion AI ) refers to the use of natural language
processing, text analysis, computational linguistics, and
biometrics to systematically identify, extract, quantify, and
study affective states and subjective information.
Sentiment analysis is widely applied to voice of the
customer materials such as reviews and survey responses,
online and social media, and healthcare materials for
applications that range from marketing to customer service
to clinical medicine.
![image](https://github.com/user-attachments/assets/2ac65830-c2ac-47a9-8506-fe469ceec9c0)


This project demonstrates sentiment analysis on textual data, focusing on web-scraped news headlines. It preprocesses the data, applies sentiment analysis using Azure AI Text Analytics, and evaluates the results.

Features
Web Scraping: Collects news headlines using the requests library and BeautifulSoup.
Text Preprocessing: Includes cleaning and formatting of text data for analysis.
Sentiment Analysis: Utilizes Azure AI Text Analytics for sentiment scoring and classification.
Results Evaluation: Outputs sentiment predictions for analysis.

Requirements
The following Python libraries are used in the project:

bs4 for web scraping.
requests for handling HTTP requests.
pandas for data manipulation and analysis.
azure-ai-textanalytics for sentiment analysis using Azure Cognitive Services.

Install the required packages using:


pip install bs4 requests pandas azure-ai-textanalytics
File Structure
The notebook contains the following sections:

Package Installation: Ensures the necessary dependencies are installed.
Data Collection: Demonstrates web scraping to extract news headlines.
Text Preprocessing: Functions to clean and prepare text data for analysis.
Sentiment Analysis: Example usage of Azure AI Text Analytics on cleaned data.
Usage
Ensure all required libraries are installed.
Replace the url in the web scraping code with your desired news source.
Set up your Azure subscription key and endpoint for the Text Analytics API in the designated code section.
Run the notebook cells sequentially to:
Scrape data.
Preprocess text.
Analyze sentiments.

Output
Sentiment scores and labels for each headline.
A DataFrame containing the processed and analyzed data.
