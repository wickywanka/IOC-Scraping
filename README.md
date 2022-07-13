# IOC-Scraping


[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)

This is a Flask-based Threat Hunting tool. This application uses the Pastebin Scraping API to harvest IOCs such as IP addresses, domains, hashes, and emails from the most recent Pastebin pastes. Elasticsearch is utilised as the database to store the pastes, and Kibana is used to visualise the data from Elasticsearch.



## Prerequisites

- Python 2.7
- Flask
- Requests
- Elasticsearch 5.6
- BeautifulSoup
- Kibana


## Usage

- Enter your Pastebing Scraping API key and Flask secret key in the code
- Run the `PastebinScrapy.py` file
- Open `127.0.0.1:5000` in any browser
- Open `127.0.0.1:5601` in any browser to see the Kibana dashboard



## Contributors

- [Bhavesh Dhake](https://linkedin.com/in/bdhake)
