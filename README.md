#PubMed Scraper

GitHub
Python

A Python script to scrape data from PubMed, a database of biomedical literature, using the Entrez API provided by the NCBI (National Center for Biotechnology Information).
Installation

    Clone the repository:

    shell

git clone https://github.com/your-username/pubmed-scraper.git

Navigate to the project directory:

shell

cd pubmed-scraper

Install the required dependencies:

shell

    pip install -r requirements.txt

Usage

    Open the scraper.py file in a text editor.

    Set your email address:

    python

EMAIL = 'your_email@example.com'

Customize the search query and the maximum number of results:

python

search_query = 'cancer treatment'
max_results = 10

Run the script:

shell

python scraper.py

The script will fetch the specified number of PubMed articles based on the search query and save the results in a file named results.txt in the same directory.
