# SBST-report-generator

## SET UP: 

### Initial downloads
- Download all the files in this repository and drop them in a directory 

- Install Anaconda w/ Python here: https://anaconda.org/anaconda/python/files?version=3.7.4
  -  Select the installation file for your operating system 



### Install dependencies: 
run highlighted commands in conda prompt 
- requests (`pip install requests`) 
- pandas (`pip install pandas`)
- lxml (`pip install lxml`)
- bs4/BeautifulSoup (`pip install bs4`)
- selenium (chrome) (`pip install selenium`) 
- docx (`pip install docx`) 

### Login credentials
- Enter username and password in `config.py` 
- make sure to put them inside the quotes, eg: `username = "xxxx_xxxxxxx"`

## RUNNING SCRIPT:

- Launch conda prompt 
- change directory to folder containing `scrape.py` file
- run `python scrape.py` 
- let it run for 10 - 15 minutes 
- file generated is named `test.doc` 


## TROUBLESHOOTING  

### Chromedriver-related issues: 
-  Download a newer version of chrome driver here if it's giving you an error: https://chromedriver.chromium.org/downloads


### dependency-related issues: 
- Make sure dependencies are installed properly on conda prompt 

### Python version issues: 
- If you have installed a different version of python and Anaconda, revert back to the one listed above (Python 3.7.4) 
