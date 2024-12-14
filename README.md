# News-Article-Summarizer
A simple Python-based news summarizer using the `newspaper3k` and `textblob` libraries. This application allows users to input a URL of a news article and generate a summary along with sentiment analysis (positive, negative, or neutral). The user interface is built using Tkinter.

## Features

- Fetch and parse articles from URLs.
- Extract the title, author, publication date, and summary of the article.
- Perform sentiment analysis to determine the tone (positive, negative, or neutral).
- Simple and interactive GUI with Tkinter.

## Requirements

To run the project, you need Python 3.x installed on your system. You also need to install the following Python libraries:

- `newspaper3k` for parsing articles.
- `textblob` for sentiment analysis.
- `tkinter` for creating the GUI (it should be installed by default with Python).

### Install the necessary libraries:

```bash
pip install newspaper3k textblob


HOW TO USE:

1.Clone or download the repository to your local machine.
2.Install the required libraries (see above).
3.Run the main.py file.
4.Enter the URL of the news article in the provided text field and click the "Summarize" button.
5.The application will display the article's title, author, publication date, summary, and sentiment analysis.


CODE WALKTHROUGH:

1.summarize() function: This function is triggered when the user clicks the "Summarize" button. It retrieves the article URL, downloads and parses it using newspaper3k, and then generates the article's summary and sentiment using textblob.

2.Tkinter UI: The GUI is simple, consisting of text fields for displaying the title, author, publication date, summary, and sentiment. The user can enter the URL and press the "Summarize" button to get the information.

EXAMPLE:
After entering the URL of a news article, the application will show:

*Title of the article.
*Author(s) of the article.
*Publication date.
*A brief summary of the article.
*Sentiment analysis: polarity score and sentiment type.

License:
This project is open-source and available under the MIT License.
