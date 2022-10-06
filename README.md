# Google_Form_Selenium
Autofill multiple google form at once using Python Selenium

In this project, I use my friend google survey form as my experiment.
https://docs.google.com/forms/d/e/1FAIpQLScuZvMbA5PLSZxWhHEny7Bw67sQhPJFPQcw8kGydohKH4XSDA/formResponse

Step 1: You need to install the Webdriver. Before installing, you need to check your Chrome version. ("Customize and Control Google Chrome" -> "Help" -> "About Google Chrome")
Then, go to  https://chromedriver.chromium.org/downloads and choose the download corresponding to your version number and operating system.

Step 2: You need to install Selenium in your environment. For me, I use Jupyter Notebook. 
For install Selenium: 'pip install selenium'

Step 3: You need to find the elements in the webpage. Go to google form page and right-click open the 'inspect'. (COPY -> COPYXPATH)

Step 4: Interacting with the elements.

**Reminder: Old version of Selenium API (find_element_by_id()) has changed.
Webpage for you to reference: https://pythoninoffice.com/fixing-attributeerror-webdriver-object-has-no-attribute-find_element_by_xpath/
