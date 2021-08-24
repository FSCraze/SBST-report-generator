# SBST-report-generator

## SET UP: 

### Download all the files in this repository and drop them in a directory 

### Install Anaconda w/ Python here: https://www.anaconda.com/products/individual 


### Install dependencies: (run highlighted commands in conda prompt ) 
- requests (`pip install requests`) 
- pandas (`pip install pandas`)
- lxml (`pip install lxml`)
- bs4/BeautifulSoup (`pip install bs4`)
- selenium (chrome) (`pip install selenium`) 
- docx (`pip install docx`) 

### Enter username and password in `config.py` 
(make sure to put them inside the quotes, eg: `username = "xxxx_xxxxxxx"`)

## RUNNING SCRIPT:

- Launch conda prompt 
- change directory to folder containing `scrape.py` file
-  run `python scrape.py` 



## Troubleshooting 

### Download a newer version of chrome driver here if it's giving you an error: https://chromedriver.chromium.org/downloads
