# Jonathan Hansen Portfolio

# [Project 6: Wisconsin Land Use](https://github.com/Jonnyboyy808/Wisconsin_land_use) 

# [Project 5: SEC's EDGAR Data Pipeline and Visualizations](https://github.com/Jonnyboyy808/Edgar_Data)
- This project focuses on compressing EDGAR web logs. EDGAR is the SEC's database for public companies to file incomes statements and other reports. These logs contain anonymized IP addresses of the visitors.
- Given the size of the .zip files, I first sampled a percentage of it as a .csv file, then added a country column that linked each IP address to its corresponding country. 
- I visualized with GeoPandas, showing the world's EDGAR traffic per hour, as well as each specific continent's EDGAR per hour. 
- Lastly, I made an animation showing how the world's EDGAR traffic changes throughout every hour of the day, with darker shading corresponding to more EDGAR traffic. 
- All instructions on how to run this project can be found on the readme found by clicking the project's hyperlink.

![](/images/8pm.png)
![](/images/Europe.png)

# [Project 4: Building a Data Website with Flask](https://github.com/Jonnyboyy808/Flask_data_website)
- The data hosted is on The Rolling Stone's Top 100 songs of all time. 
- The Browse page brings you to a dataframe hosting all the information including data such as the song name, artist(s), producer(s) and writer(s). 
- The API page allows you to customize the data you're looking for to query your own data.
- Additionally, the page has a donate link and an email subscription option that allows you to sign up for a mailing list. 

![](/images/Datasite_Homepage.png)
![](/images/Browse_DF.png)
![](/images/API.png)

# [Project 3: Web Scraping with Selenium From a Flask-implemented Website](https://github.com/Jonnyboyy808/hunting_for_treasure)
- The instructions on how to run scrape on Flask application are included in the project's hyperlink.
- Scrape.py's easter_egg method scrapes the website to find hidden text between <span> tags that concatenate to a secret message.
- Scrape.py's dfs_pass and bfs_pass methods uses depth-first search and binary-first search on the website's homepage to collect hidden letters and concatenate them to seperate passwords.
- These passwords can be entered using Scrape.py's protected_df method, which will then return a dataframe of all the information hidden on the page shown when the password is entered. 
  
![](/images/Homepage.png)
![](/images/Protected_df.png)
  
# [Project 2: Analyzing the Evolution of a Git Repository](https://github.com/Jonnyboyy808/.py_Program_Complexity)
- The repository I analyzed contained a python program that counted words. 
- The first step of the project was tracking how the .py file has grown and changed over time and who has made those changes to the repo. 
- Next, given the .py program counted words, I passed three test strings into my own function "run_wc" that ran every commit of the word counter to see which commits matched what's expected and which don't. 
- To test performance of the different commits, four were chosen to run the .py program on X randomly generated words and Y chosen unique words from X and the times were recorded. 
-Lastly, since version one and two were the fastest, I wanted to visualize the difference in complexity as the words got more and more unique. 

![](/images/Complexity_DF.png)
![](/images/Complexity.png)


# [Project 1: Analyzing the Geography of Countries and Their Capitals](https://github.com/Jonnyboyy808/Country_and_Capital_Geography-)
- Data scraped from http://techslides.com/list-of-countries-and-capitals.
- The first part of the project included putting the data into Pandas dataframes and was analyzed on various things including a capitals distance to a coast, which countries are most landlocked, the countries with the highest/lowest birth/death rates, and capital population density. 
- In the second half of the project, the dataframes were dumped into a SQLite database to be queried and visualized on several things, including the number of countries per continent, population per continent, highest/lowest GDP per country, and interesting scatterplots, such as phone usage on GDP per capita or GDP per capita on literacy rates. 

![](/images/Death:Birth%20rate%20DF.png)
![](/images/Death-birth-rates.png)

Project 3: 
