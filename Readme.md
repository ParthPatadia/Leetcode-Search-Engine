Run LC.py 
This code is a Python script that uses the Selenium and BeautifulSoup libraries to scrape links from the LeetCode website. The script opens a Chrome browser using the ChromeDriver, navigates to different pages of the LeetCode problem set, and extracts all the links to individual problem pages. The extracted links are then saved to a file named "LeetCode.txt".

Run cleaner.py
This code reads the links from the "LeetCode.txt" file, removes elements from the array that contains a specified pattern ("/solution"), and saves the remaining links to a new file named "lc_problems.txt".

Run problems_explore.py
This code extends the previous code by adding functionality to scrape the content of individual problem pages on the LeetCode website. It uses Selenium and BeautifulSoup libraries to navigate to each problem page, extract the heading and body text, and save the data to files.

Run prepare.py
This code reads an index.txt file, preprocesses the document text, and performs some operations to prepare the documents, vocabulary, IDF (inverse document frequency) values, and inverted index. 

Run app.py
This code is a Flask web application that implements a search engine using the loaded vocabulary, documents, and inverted index.
