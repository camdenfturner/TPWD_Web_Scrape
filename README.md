# TPWD_Web_Scrape
Python scripts for scraping draw hunt data from the TPWD site.

Each year, members of my hunting group apply for public hunting tags on the Texas Parks and Wildlife Department's website.
It is always a challenge to sift through web-pages, organize information on hunt opportunities, analyze the data, and decide on which ones to apply for.
This year, I used BeautifulSoup in Python to scrape the data into a csv so I can share it on a google sheet, where my group can orchestrate our efforts.

Draw probability per application is one of the most important metrics, and is actually missing from the site, though it can be calculated with available data.
I calculated this field in python and added it to the dataset, so we can easily calculate our collective probability of drawing tags, or even probability of harvesting an animal using 'Success Rate' which is publically available.

Here is an example of a page:
https://tpwd.texas.gov/huntwild/hunt/public/public_hunt_drawing/hunt-category-details.phtml?OCat=GDA
