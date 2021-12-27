# Scrapping flooranddecor site

    The website is devided into 7 department, each one is devided into multiple sub-departments which display all its products.

## So, this is the methodology we followed to scrape this website:

1. Scraping all the sub_departments' urls. 
2. Itrateing over all the sub_departments' urls and scrape all the products' urls.
3. Building a class that can use product's url to extract all its information.
4. finally, I build a manager class to comine all this together, to get all products' urls, and then itrate over them with using the benefits
       we can get with the composition relation with the previous class to extract all the products' information through the website 
