# YouTube Video Analytics Automation

## Project Description

This project automates the process of scraping data from Krish Naik's YouTube channel using Selenium and BeautifulSoup. I admire Krish Naik's videos and the content he creates, and I often follow his tutorials. As a result, I chose to apply my learning by working on this project. The scraped data is stored in an Excel file for further analysis. The project demonstrates web scraping techniques, data preprocessing, and data visualization using Python.

## Features

- Scrapes video details from Krish Naik's YouTube channel.
- Extracts information such as video titles, views, upload dates, and links.
- Preprocesses text data using NLP techniques with NLTK.
- Uses PorterStemmer and Tokenizer for text preprocessing.
- Implements progress tracking using `tqdm` for loop visualization.
- Performs data visualization, including word clouds and count plots using Seaborn.
- Parses HTML content for better data extraction.
- Saves the extracted data into an Excel file using `xlsxwriter`.

## Technologies Used

- **Python**: Core programming language.
- **Selenium**: For automating web scraping.
- **BeautifulSoup**: For parsing HTML data.
- **Pandas**: For data manipulation.
- **XlsxWriter**: For exporting data to Excel.
- **NLTK**: For text preprocessing and NLP tasks.
- **PorterStemmer & Tokenizer**: For text normalization.
- **tqdm**: For visualizing progress in loops.
- **Seaborn**: For data visualization.
- **WordCloud**: For generating word clouds from text data.
- **NumPy**: For numerical computations.
- **HTML Parsing**: For extracting structured data from web pages.

## Installation

### Prerequisites

Ensure that you have Python installed. You can install the required dependencies using:

```sh
pip install -r requirements.txt
```

### WebDriver Setup

Since Selenium is used, you need to download and set up the appropriate WebDriver (e.g., ChromeDriver for Chrome):

1. Download ChromeDriver from [here](https://chromedriver.chromium.org/downloads).
2. Place it in a known directory and provide the path in your script.

## Usage

1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/youtube_scraper.git
   cd youtube_scraper
   ```
2. Run the script:
   ```sh
   python youtube_scraper.py
   ```
3. The output file will be generated as an Excel sheet.

## Learning Outcomes

By completing this project, you will:

- Gain experience in web scraping using Selenium and BeautifulSoup.
- Understand automation for data extraction from dynamic web pages.
- Learn how to preprocess text data using NLP techniques with NLTK.
- Implement PorterStemmer and Tokenizer for text normalization.
- Utilize NumPy for efficient numerical operations.
- Implement data visualization techniques, such as word clouds and count plots.
- Understand how to store scraped data in structured formats like Excel.
- Learn how to work with query string URL parameters for data extraction.
- Perform Exploratory Data Analysis (EDA) to gain insights from scraped data.

## Future Improvements

- Support for multiple channels.
- Store data in a database instead of Excel.
- Implement error handling for better robustness.
- Extend NLP analysis to include sentiment analysis.
- Improve HTML parsing for more detailed data extraction.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License

This project is licensed under the MIT License.

