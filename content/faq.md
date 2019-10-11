+++
img_path = ""
layout = "page"
subtitle = ""
title = "FAQ"

+++
## General Questions

### Technical requirements

Due to the fact that our app is not connected in any way with your website, our app works with all kind of websites and CMS platforms. The only pre-requisite is that your hosting provider has not implemented aggressive rate limiting rules. Rate limiting is a frequently used tool to defend against network and application-level DDoS attacks against websites. If this is the case, ask your hosting provider to whitelist the following user-agent : AffiliateLink. If you encountered an unexpected issue, don’t worry. Most of the time this can be fixed quickly by contacting us at support@clickclickbankbank.com. Feel free to get in touch with us and we would be happy to assist you. In order to use our tool, it is also imperative that you already have access to the official Amazon Product Advertising API. Please check in your Amazon Affiliate Account to ensure that you are able to create API keys before you buy.

### Do you have a demo or trial?

We don’t have any demo but we do have several live demonstrations, screenshots of the app settings, a list of features and our support team is available to answer any questions you may have.

We also offer a 7 day money back guarantee which allows you to dig into the tool, try it out on your site and see how it works for you.

### What is your refund/cancellation policy?

Refund are for available for 7 days after signup, or anytime if you did not start any scan in your account. Note that you can change or cancel your plan at any moment within your Plan & Billing section.

## Getting Started

### Quickstart

Here you can find a short tutorial for starting with ClickClickBankBank. Please be aware that this is not a complete documentation.

**STEP 1: REGISTER**

Go to [ClickClickBankBank.com](https://app.clickclickbankbank.com/sign-up), select your pricing and confirm your personal information.

![](/images/step1b.png)

![](/images/step1.png)

Once done, you will receive a confirmation email.

**STEP 2: AMAZON PRODUCT ADVERTISING API**

* Sign-up for using Amazon Product Advertising API
* Create your API Credentials
* Save them on your computer

**STEP 3: CREATE A NEW SCAN**

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

### Report details & information

Once your scan will be done, you will have access to a detailed report.

**SUMMARY**

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

**SCAN REPORT**

![](/images/scan report.png)

* Filter by ASIN: Enter any ASIN and check its status immediately
* Sort by: You can filter by the following product status : Available, Deleted, Out of Stock, Error.
* Name: Product name as stated on Amazon
* ASIN: Product code from Amazon
* Link: Direct link to the Amazon product page
* Status: Product status as stated in the Amazon Product Advertising API
* Stock: Inventory available as stated in the Amazon Product Advertising API
* Amazon link: Link displayed on your website

### How often my links are checked?

There is no automatic scan and check of your links, as we don’t want to use your link quota unnecessarily. For every scan, you will just have to click on “New Scan” your dashboard.