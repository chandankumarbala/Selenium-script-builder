# Selenium-script-builder
This JS based code takes an original selenium script and generates test-cases in bulk each with different JSON input file.
data.json,jata2.json -> The json files are sample files that mimics the input JSON data.
google.html -> is the original recorded test case from Selenium IDE.
writer.html -> Is the file that containes entire logic. Download the project and open this file in browser.
FileSaver.min.js -> is a js library used to download the newly generated test script.
jquery-1.12.4.min.js -> Used for all parsing and DOM related jobs.

The code is rough and not properly segregated .It is developed for senarios where there are plenty of  JSON data files that has to be run onto a test case using Selenium IDE.

The user has to provide the work space location where all the JSON and recorded test cases are located , then attach the files using file selectors in the webpage click to generate and download the bulk test cases.

