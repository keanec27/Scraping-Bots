# Scraping-Bots
This Repo contains scraping bots for various websites using selenium.

#### Run the following code if using Colab
```python
!pip install selenium
!apt-get update
!apt-get install -y chromium-browser
!apt install chromium-chromedriver
options = webdriver.ChromeOptions()
options.add_argument('--no-sandbox')
options.add_argument('--headless')
options.add_argument('--disable-gpu')
options.add_argument('--disable-dve-shm-uage')

driver = webdriver.Chrome(options=options)
```
###### Now the scripts can be run directly.

#### If using Jupyter Notebook make sure Selenium is installed if not run 

```python
pip install selenium
```
