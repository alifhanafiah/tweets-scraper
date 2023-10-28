# Tweets Scraper

Tweets Scraper is a Python script that enables users to scrape tweets from Twitter based on specific topics using the Selenium library.

## Features

- **Twitter Authentication**: Log in to your Twitter account using your credentials.
- **Topic-Based Scraping**: Search for tweets related to your specified topic.
- **Data Extraction**: Extract tweet data, including username, handle, timestamp, text, comments, likes, and retweets.
- **Data Export**: Save the scraped tweet data to a CSV file for further analysis.

## Prerequisites

Before getting started, make sure you have the following installed:

- Python 3.x
- WebDriver for your web browser (e.g., Microsoft Edge WebDriver)
- Anaconda or Miniconda

## Installation

1. **Miniconda**: If you haven't already, install Miniconda by downloading it from the official website: [Miniconda](https://docs.conda.io/en/latest/miniconda.html).

1. **WebDriver**: Download the appropriate WebDriver for your web browser. For Microsoft Edge, you can find the WebDriver [here](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/).

1. **Clone the Repository**: Open your terminal and clone this repository:

   ```bash
   git clone https://github.com/yourusername/twitter-scraper.git
   ```

1. **Create a Virtual Environment**: Open your Anaconda or Miniconda terminal and create a virtual environment:

   ```bash
   conda create -n my-twitter-scraper python=3.10
   ```

   Replace `my-twitter-scraper` with your preferred environment name.

1. **Activate the Environment**:

   ```bash
   conda activate my-twitter-scraper
   ```

1. **Install Dependencies**: In your project directory, install the required Python packages listed in the requirements.txt file:

   ```bash
   pip install -r requirements.txt
   ```

1. **Open Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

1. **Configuration**: Update the script with your Twitter account credentials and the desired topic to scrape.

## Usage

- Replace the following placeholders in the script with your actual Twitter account credentials:

  - `your_email@example.com`
  - `your_twitter_username`
  - `your_twitter_password`

- Change the `Tweets_Query` variable to your desired topic.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project was created for educational purposes and should be used responsibly and in accordance with Twitter's terms of service.
