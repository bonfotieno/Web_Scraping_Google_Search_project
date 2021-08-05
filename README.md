# Web_Scraping_Google_Search_project
### This repo consist of a web scraping tutorial notebook and Web Scraping Google search project

The project file is Web_Scraping_Google_Search_project.py

This is what the program does:<br>
• Gets search keywords from the command line arguments.<br>
• Retrieves the search results page.<br>
• Opens a browser tab for each result.<br>

This means the code will need to do the following:<br>
• Read the command line arguments from sys.argv.<br>
• Fetch the search result page with the requests module.<br>
• Find the links to each search result.<br>
• Call the webbrowser.open() function to open the web browser.<br>

##### This code works so long as google search results link attributes has never been changed by google. You can as well do the changes in the code if it was changed.
