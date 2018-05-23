# Data-based Plant Breeding


A data science toy project using regression analysis to predict prices and characteristics of cannabis strain combinations 


`high_times_price_index_scraper.ipynb` Is a scraper designed to collect price data from [Hightimes magazine's trans high market quotations (THMQ)](https://hightimes.com/tag/thmq/). As the prices are all stored in image files on the THMQ pages, the scraper was designed to grab the images, crop them with PIL and feed them to an [OCR API](http://www.bitocr.com/). Ultimately, though, I decided to take the project in another direction, and did not make use of the data generated using this scraper. 


`Cannabis_genetics_scrape_and_analysis.ipynb` Is a Jupyter notebook showing a scraper designed to harvest genealogy and THC content data from [Wikileaf](https://www.wikileaf.com/), as well as the analysis of that data using a linear regression model. A more thorough write-up is [available here](https://pedronavaja.github.io/Post-2/)

