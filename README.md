# Google Play Reviews Scraper

This repository contains a Python script that uses the [google_play_scraper](https://pypi.org/project/google-play-scraper/) library to scrape reviews from the Google Play Store for any specified app. The script retrieves reviews, converts the data into a pandas DataFrame, saves the results as a CSV file, and prints basic performance metrics.

## Features

- Scrape reviews from the Google Play Store by specifying the app's package name.
- Configure parameters such as language, country, and sort order.
- Save scraped reviews to a CSV file for further analysis.
- Display a preview of the data.

## Prerequisites

- Python 3.7+
- [google_play_scraper](https://pypi.org/project/google-play-scraper/)
- [pandas](https://pandas.pydata.org/)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/google-play-reviews-scraper.git
   cd google-play-reviews-scraper

2. **Install the required packages:**
   google-play-scraper
   pandas

## Usage
You can run the script directly after configuring the parameters.

## Customization
To scrape reviews for a different app, simply change the package name in the reviews() function. You can also adjust the language, country, review count, and sort order as needed.
