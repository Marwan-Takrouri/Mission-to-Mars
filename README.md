***The  Mission to Mars Project***: 


Overview 

First things first, though—preparation. Robin needs to download a few libraries and tools that she'll need when she's ready to start scraping data so I helped her by suggesting using the below :
 1-Splinter to automate a web browser.
2-BeautifulSoup to parse and extract the data ..
3-MongoDB to hold the data that has been gathered.
Robin, who loves astronomy and wants to work for NASA one day, has decided to use a specific method of gathering the latest data: web scraping. Using this technique, she has the ability to pull data from multiple websites, store it in a database, then present the collected data in a central location: a webpage

Robin has gotten all of her tools installed and we  tested Mongo to make sure it's ready for data, but before she can really start pulling it off of the web, she needs to be able to identify where the data is stored within the HTML code with a saved image .

Every webpage is built using hypertext markup language, more commonly known as HTML. Some sites are more sophisticated than others, but they all have the same basic structure. Each element of a page, such as a title or a paragraph, is wrapped in a tag. Each tag is specific to the element it's holding, and there are many different types of tags.
Me and Robin installed all of the tools and researched different HTML tags in preparation for her web-scraping project. We really ready to jump in and start gathering data, but even with her initial research, she realized she wasn't quite ready to start scraping. The HTML components on the first site she visited quickly became more complex than she expected.

Instead, Robin has decided to practice identifying specific data using Chrome Developer Tools (also known as DevTools). Which I have found to be very useful on our project .
This tool allows us as developers to look at the structure of any webpage. Not only that, but there's a search function as well. This should help make more sense of the tags and components that hold the data she's looking for.


Robin is a bit more familiar with HTML tags and how they fit together to create a webpage, which is a great first step. She also has the necessary tools installed to get started with the scraping, so she's eager to dive in.

We decided as well to use  Splinter to automate a browser—this is pretty fun because we'll actually be able to watch a browser work without us clicking anywhere or typing in fields, such as using a search bar or next button.

After we help Robin get Splinter rolling, we'll actually scrape data using BeautifulSoup. This is where our practice with HTML tags comes in. To scrape the data we want, we'll have to tell BeautifulSoup which HTML tag is being used and if it has an attribute such as a specific class or id.

Let's take a closer look at HTML tags.
With those precautions out of the way, Robin's ready to start scraping Mars news

Terms of Service and Terms of Use bring up an ethical issue when gathering data. Many websites don't allow automated browsing and scraping—some of the scraping scripts out there are designed to gather data quickly, and the constant traffic can overload web servers and disable a website.

Many websites don't allow automated browsing and scraping—some of the scraping scripts out there are designed to gather data quickly, and the constant traffic can overload web servers and disable a website.
That is why we have to be very careful when using the scrapping data tools to gather our project deliverables.


Results :

We used the web browser to visit the mars hemisphere and view a high resolution Images about mars as below  


Then we Use the for loop to complete the following actions 
1-Click on each hemisphere link 
2-Navigate to the full-resolution image page
3-Retrieve the full-resolution image URL string and title for the hemisphere image.
 4-use browser.back() to navigate back to the beginning to get the next hemisphere image

The out put was as below images :


    
 ![image](https://user-images.githubusercontent.com/89116297/160252601-405e92a8-aae6-4470-82a3-918d7a9ece12.png)
 




Then we changed our coding the Scraping.py and the app.py to print out the same high resolution images as below in the code.


Then after scraped the data, confirm that our webpage has the full-resolution images and the titles of the four hemisphere images, like the earlier images , 


BOOTSTRAP GRID :
We changed our Index and devtool to show the pictures in column design instead of the original one as below :


![deliverable 3 devtool changed to columns view ](https://user-images.githubusercontent.com/89116297/160252643-5fec2fea-2549-4d41-ac8d-42e33c698a5d.png)



 
