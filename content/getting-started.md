+++
img_path = ""
layout = "page"
subtitle = ""
title = "Getting Started"
[menu.secondary]
weight = 1

+++
## Account creation

### **STEP 1: REGISTER**

Go to [ClickClickBankBank.com](https://app.clickclickbankbank.com/sign-up), select your pricing and confirm your personal information.

![](/images/step1b.png)

![](/images/step1.png)

Once done, you will receive a confirmation email.

### **STEP 2: AMAZON PRODUCT ADVERTISING API**

* Sign-up for using Amazon Product Advertising API
* Create your API Credentials
* Save them on your computer

### **STEP 3: CREATE A NEW SCAN**

Click on the “New Scan” button at the top right of your Dashboard.

![](/images/newscan.png)

Fill-in the form:

* Domain: URL you want to scan
* Amazon Access Key
* Amazon Secret Key
* Amazon Store: the country needs to be linked to your credentials
* Amazon Affiliate ID: the Affiliate ID is linked to your credentials
* Cloaking: If you use a link cloaking plugin (EasyAzon for example), please integrate your link structure here. If you use for instance [https://mysite.com/go/amazing-amazon-product,](https://mysite.com/go/amazing-amazon-product, "https://mysite.com/go/amazing-amazon-product,") enter in the field [https://mysite.com/go/](https://mysite.com/go/ "https://mysite.com/go/") so that we know that these are Amazon affiliate links. Please leave blank if you are not using any cloaking.

And that’s it!

You will be redirected to the Dashboard and a couple of minutes later you will get the results.

## Report details & information

Once your scan will be done, you will have access to a detailed report.

### **SUMMARY**

![](/images/report.png)

* URLs count: This is the number of URLs that we scanned. It could be similar to the number of pages on your website depending on your site structure.
* Products count: Total of Amazon products that we found.
* Links count: Total of Amazon affiliate links that we found.
* Unique links count: Total of Amazon affiliate links deduplicated. This will be the amount of link deducted from your balance.

On the diagram you will find the following information:

* Available: Percentage of Amazon products in stock
* Deleted: Percentage of Amazon products removed from Amazon website (404 error)
* Out of Stock: Percentage of Amazon products that are out stock but still displayed on Amazon
* Error: Percentage of Amazon products with an error status. Sometimes the Amazon Product Advertising API generates errors while trying to fetch product data, if you have a high % of Error please [contact us](mailto:support@clickclickbankbank.com).

### **SCAN REPORT**

![](/images/scan report.png)

* Filter by ASIN: Enter any ASIN and check its status immediately
* Sort by: You can filter by the following product status : Available, Deleted, Out of Stock, Error.
* Name: Product name as stated on Amazon
* ASIN: Product code from Amazon
* Link: Direct link to the Amazon product page
* Status: Product status as stated in the Amazon Product Advertising API
* Stock: Inventory available as stated in the Amazon Product Advertising API
* Amazon link: Link displayed on your website

### **LINK REPORT**

When you click on a link from the scan report, you will access to more detailed information for this link :

* product name associated to this link
* ASIN
* inventory status
* available stock.

![](/images/link report 1.png)

Then you will have some additional info regarding your website and the pages that are hosting this link :

* Crawl date
* Domain crawled
* Pages where we found this link

![](/images/link report 2.png)

If we found other links for the same products, they also be listed here so you know all the pages and links that need to be updated.

![](/images/link report 3.png)