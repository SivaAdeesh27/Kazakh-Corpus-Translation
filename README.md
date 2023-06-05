# Kazakh-Corpus-Translation

This Python automation script scrapes content from multiple Kazakh news websites, translates the sentences, and creates a parallel corpus of Kazakh and translated sentences.

## Features

- Scrapes content from multiple Kazakh news websites
- Extracts unique links from each page
- Tokenizes the Kazakh text into sentences
- Translates the Kazakh sentences into a target language using Google Translate API
- Creates a parallel corpus of Kazakh and translated sentences
- Schedules the script to run periodically (every 24-28 hours)

## Dependencies

- requests
- BeautifulSoup
- html2text
- urllib.parse.urljoin
- os, re, schedule, time, datetime, random
- deep_translator
- pandas

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SivaAdeesh27/Kazakh-Corpus-Translation.git
     
2. Install the required dependencies:
    ```bash
   pip install -r requirements.txt


## Usage

1. Modify the `main_urls` and `output_files` lists as needed.
2. Change the target language for translation in the `translate_parallel_corpus` function call (currently set to `'en'` for English).
3. Run the script once, and it will keep updating the parallel corpus on the specified schedule.

