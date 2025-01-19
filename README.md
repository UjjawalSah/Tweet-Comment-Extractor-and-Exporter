# Tweet Comment Extractor and Exporter

This Python script allows users to extract comments from a tweet by providing its URL and export the data into an Excel file for easy analysis.

---

## Requirements:

- **Python 3.x**
- **Tweepy**: Install via `pip install tweepy`
- **Pandas**: Install via `pip install pandas`
- **Google Colab** (for downloading the Excel file)
- **Twitter API Bearer Token** (required for authentication)

---

## Features:

- Extract comments from a tweet using its URL.
- Export extracted comments into an Excel file for easy access and analysis.
- Handles rate limits imposed by Twitter API automatically with retry functionality.

---

## Installation:

1. Clone the repository or download the script files.
2. Install the required Python libraries:
    ```bash
    pip install tweepy pandas
    ```
3. Replace `YOUR_BEARER_TOKEN` with your Twitter API bearer token in the script.

---

## Usage:

1. Input the URL of the tweet for which you want to extract comments.
2. The script will fetch the comments and save them into an Excel file.
3. Download the Excel file directly from Google Colab.

---

## Note:

- If the rate limit is exceeded, the script will wait for 15 minutes before retrying.
- Be mindful of Twitter's API rate limits when using this script.
- The Excel file will be downloaded with the name `tweet_comments.xlsx`.

---

## License:

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

