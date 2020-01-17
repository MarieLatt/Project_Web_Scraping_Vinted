
# Sorting through products on Vinted: a Web Scraping Project 

The goal of this project is to web scrape the Vinted.fr website to be able to filter products with more categories than the ones provided by the Vinted website.


## Data

For this project, I focused on 1 product in particular: [White Stan Smith Woman's Shoes, size 38](https://www.vinted.fr/femmes/baskets?size_id[]=58&page=1&search_text=stan%20smith&color_id[]=12&status[]=2&status[]=1&status[]=6&brand_id[]=14).

For this particular product, there are more than 500 results on Vinted.fr.
* Filtering by date of last visit of the seller on Vinted reduces the probability of cancellation of the sell because the seller did not send the product.
* Filtering by number of pictures provided, evaluations of the seller, and price according to the condition could reduce the probability of counterfeit product.

Here is the list of features scraped for each product:
* Url: url of the product on Vinted
* Brand: Brand of the product
* Size: Size of the product
* Condition: Condition of the product ('satisfaisant'= satisfactory, 'bon état'= good, 'très bon état'= very good, 'neuf'= new, 'neuf avec étiquette'=new with tags)
* Colors: list of colors for the product (2 colors max)
* Views: number of views of the product 
* Interested: number of members interested by the product
* Uploaded: date the product was uploaded on Vinted
* Last_seen: date the seller was last connected on Vinted
* Price: selling price (euros)
* Nb_evals: number of evaluations the seller received
* Stars: average evaluation for the seller
* Title: title given by the seller for the product
* Description: description of the product given by the seller
* Nb_pictures: number of pictures of the product uploaded


## Tools

* Python
* Pandas
* requests
* BeautifulSoup
* Matplotlib

