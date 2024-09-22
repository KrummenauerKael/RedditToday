# RedditToday

RedditToday is a Python script designed to analyze Reddit posts and identify trending words, helping to gauge user interests on the platform.

## Features

- Searches for top words in Reddit posts or can be used to search specific desireable words.
- Provides insights into user interests based on post content.

![example_img](https://github.com/user-attachments/assets/00cbb7ab-7699-4200-88e1-0be03e88bc7c)

![example_img_v2](https://github.com/user-attachments/assets/7ef48fd5-8766-4d8a-bb97-0a25ee550ee6)

## Requirements

- Python 3.x
- Required libraries listed in `requirements.txt` (Note: Some libraries may be outdated and will require changes to work with the latest versions.)

## Usage

- Ensure you have a `credentials.json` file with your Reddit API credentials in the project directory.
- stopWords.txt provides a list of words that the script will ignore and not count, removing words from the text file will make them countable.
