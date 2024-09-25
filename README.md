# webscraper
Selenium initial web-scrape with ubuntu/debian

# Steps:
### requirements:
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt


1. update all packages
apt update
apt upgrade

2. download google-chrome stable package
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb

3. install google-chrome
apt install ./google-chrome-stable_current_amd64.deb

4. download chromedriver
wget https://chromedriver.storage.googleapis.com/107.0.5304.62/chromedriver_linux64.zip

5. unzip chromedriver
unzip chromedriver_linux64.zip

6. move chromedriver to /usr/bin/chromedriver
mv chromedriver /usr/bin/chromedriver

7. give chromedriver executable permissions
chmod +x /usr/bin/chromedriver

8. check chromedriver version
chromedriver --version

9. check google-chrome version
google-chrome --version

10. run python script
python3 main.py or python3 test.py

since it's pointed to python.org, you should get a "Welcome to Python.org" from the browser title.

