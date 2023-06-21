## In this project I used BeautifulSoup and Request Library for web scraping and FlipCart was the website where I got all the data.

# Libraries/Dependencies:

1. Beautiful Soup
2. Request
3. csv
4. numpy
5. pandas
6. re
7. datetime


# How to extract data:

1. Open the flipcart.com website.
2. Search for specific company names like Apple or Samsung.
3. Apply filter if needed.
4. Get the link to the current page
5. Open AWS Jupyter Notebook or Anaconda Jupyter
6. Request permission to extract the data
7. If you got 200 in response then you can extract otherwise check the code for what kind of error you are facing.
8. Right Click on the specific part you want to extract and click inspect
9. Get the class of id from div and try my code for extraction
10. Once get all the information for one object now start the loop for all the page
11. Use a loop for all the data
12. Use a loop to go to the next page
13. After all the data is received convert it into a .csv file
14. Now use this data for further analysis and make predictions.
