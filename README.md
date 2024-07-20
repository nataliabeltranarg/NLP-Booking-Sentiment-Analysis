# Natural Language Processing: Sentiment Analysis of Booking.com

## Project Overview 
This project explores how significant annual events in Barcelona, Spain, can influence rental prices. We focused on the the SONAR festival, held annually in June, which attracks an influx of visitors to the city. The data for this project was obtained through scraping the booking website, conducted solely for research purposes as part of an assignment for the Introduction to Text Mining and Natural Language Processing course at the Barcelona School of Economics. Our research compares rental prices in Barcelona during the week of June 12th to 16th, 2024, with a control week of June 5th to 9th, 2024. Additionally, we extended the analysis to include a comparison with the control city of Alicante, Spain.
  
## Section 1: Web Scraping 
This section focuses on the web scraping aspect of the project. We collected data on hotel names, dates, room prices, and hotel descriptions. For more detailed information on the event, cities, time periods, and the scraping process, please refer to our notebook titled '**scraping_booking.ipynb**'.

#### Notebook Contents
1. **Future Event Selection**
2. **Time Period & City Selection**
3. **Scraping Pipeline**
4. **Scrape Information**
  
## Section 2: Sentiment Analysis 
This section focuses on the analysis aspect of the project. We extracted and analyzed text features from hotel descriptions to understand their impact on rental prices. Alicante was chosen as the control city for comparison. For more detailed information on the sentiment analysis and its results, please refer to our notebook titled '**sentiment_analysis.ipynb**'.

#### Notebook Contents
5. **Difference in Difference Equations**
6. **Regression Models**
7. **Feature Extraction Control**
8. **Hotel Fixed Effect Regression**

#### Libraries Used
* BeautifulSoup
* NumPy
* Pandas
* Selenium
* NLTK
* Matplotlib
* Translator
* Statsmodels
* Scikit-learn

## Contact the Authors
For additional questions, feel free to reach out to the authors of this project:
* Natalia Beltrán (natalia.beltran@bse.eu)
* Harry Morley (harry.morley@bse.eu)
* Xi Cheng (xi.cheng@bse.eu)
  
## How to navigate the repository
```bash 
├── Booking Data 
│   ├── Control Data
│   │   ├── Alicante_before.csv
│   │   ├── Barcelona_before.csv 
│   └── Treatment Data
│   │   ├── Alicante_festival.csv
│   │   ├── Barcelona_festival.csv
├── scraping_booking.ipynb
├── sentiment_analysis.ipynb
└── README.md
```
