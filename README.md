Automotive Data Scraping Pipeline (Mini Project)
This project focuses on the "Data" in Data Science. I built a robust web scraping pipeline to extract and structure real-world automotive data.

📊 Project Highlights
Objective: Extracted comprehensive car details (Price, Fuel Type, Transmission, Model) from AckoDrive.com.

Target Location: Mumbai (dynamically adjusted based on availability).

Tools Used: BeautifulSoup, Requests, Pandas.

Data Structure: Structured raw web data into a clean, analysis-ready CSV format.

챌 Challenges & Solutions
Dynamic Class Names: Overcame the challenge of scraping a modern React-based site with complex, non-static HTML classes.

Data Gaps: Successfully adapted the pipeline to handle "New Car" listings when used car data was unavailable, ensuring a complete dataset for the assigned brands.

📂 Repository Structure
Plaintext

├── Web_scrapping/
│   ├── Hyundai_AckoDrive_Raw_Data_Mumbai.csv  # Raw Scraped Data
│   ├── ackodrive_mumbai_sample.pdf            # Project Presentation
│   └── scraping_notebook.ipynb                # Documented Python Code
├── Karmatix_AI/                               # Flagship Project Files
└── README.md                                  # You are here!
👨‍💻 Get Started
To run the web scraper or explorer the notebooks locally:

Clone the Repo:

Bash

git clone https://github.com/Karma-tic/Web-Scraping.git
Install Dependencies:

Bash

pip install beautifulsoup4 pandas requests streamlit
🌟 Acknowledgments
A huge thank you to my mentors at Evoastra Ventures for their constant guidance and to my teammates for their collaboration. This experience has been pivotal in sharpening my skills in building scalable, real-world AI solutions.
