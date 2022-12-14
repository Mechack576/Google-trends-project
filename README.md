This project is built in golang
It is a command line interface project that gets google's daily trend list using rss
It prints them by giving you the rank, title,link to the google trend, and a list
of the news items around this trend and links to them as well.

The 3 main functions are:
getGoogleTrends() 
    This is where I make the http request to the RSS URL
readGoogleTrends()
    reads the response body
Main()
    unmarshals the data and prints the results

