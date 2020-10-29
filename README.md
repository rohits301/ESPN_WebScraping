# ESPN Cricinfo WebScraper
* A web scraper that scrapes details of batsmen of each team that played in ICC Cricket World Cup for a given world cup year and puts them into an excel file
* It uses Request package to make parallel requests to the server and **cheerio** to extract data out of it
* It uses **Node.js** fs module to create a team directory and **xlsx** module to make excel file of each player