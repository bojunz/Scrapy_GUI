# Scrapy_GUI
![Shanshui GIF](https://github.com/bojunz/Scrapy_GUI/blob/main/Shanshui%20(2).gif)


# Abstract
This project integrates web scraping, data cleaning, analysis, visualization, and UI/UX design into a cohesive software solution. The process begins with the ethical collection of Amazon product prices and rankings through authorized channels. The data is then meticulously cleaned and analyzed. Following this, the results are visualized and encapsulated in a user-friendly software application. Users benefit from a one-click crawling feature and intuitive visualization tools, designed to facilitate data analysis and decision-making for non-technical users.

## Key process
Keywords: web crawling, HTML parsing, threading management, UI/UX design, data analysis
| Iteration | Description                                                                                 |
|-----------|---------------------------------------------------------------------------------------------|
| 1         | The target product page was parsed, the crawl location was identified, and request headers were configured to simulate real user interactions.  |
| 2         | Selenium technology was added, which enabled successful access. However, after testing, it was found that changing the appropriate request header information could also enable direct successful access. |
| 3         | The project architecture was established, including the crawl interval, number of loop, and data storage locations. |
| 4         | Designed the graphical user interface for the data capture component, including UI/UX elements such as a log area, start and stop buttons, and an aesthetically pleasing interface.               |
| 5         | Addressed a synchronization issue where the back-end did not stop data capture upon pressing the stop button due to threading conflicts. This issue was resolved through multi-threading and event handling techniques              |
| 6         | Developed the back-end for data visualization, including data cleaning and time-series analysis to monitor competitor behavior. |
| 7         | Designed the UI/UX for the data visualization front-end, integrating visualization results into the display page and adding features for chart and product switching.                  |
