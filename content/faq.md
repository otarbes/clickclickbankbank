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

***

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

**LINK REPORT**

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

### How often my links are checked?

There is no automatic scan and check of your links, as we don’t want to use your link quota unnecessarily. For every scan, you will just have to click on “New Scan” your dashboard.

***

## Amazon Product Advertising API

### Creating Credentials for Amazon Product Advertising API

**Create Credentials**

![](/images/amazon-associates-api-tools.png)

Your credentials can be created directly in your Amazon Associates account.

In case you’re using another local Associates program, your url might be different.

![](/images/amazon-associates-credentials-1.png)

In case you don’t have credentials yet, please click on the button “Add Credentials”.

If you can not create credentials here, your Associates account does not yet meet all requirements. Recently, new affiliates must have generated at least 3 sales before gaining access to the API.

**Download Credentials**

![](/images/amazon-associates-credentials-download.png)

After your credentials were generated, you can view and download them.

Please be aware that you can not view your credentials later again. That’s why you should download and save them to a secure place on your **computer.**

**Manage Credentials**

![](/images/amazon-associates-credentials-manage-1.png)

All previously credentials will be shown in your Amazon Associates account.

Existing credentials may be deleted, but your secrets cannot be seen again.

In case you don’t know your credentials anymore, please create new one (note that there’s a maximum limit of 2 active pairs of credentials).

### Amazon API “not connected” – Frequent causes

In case the app was not able to establish a connection to the Amazon API, here are some of the most frequent causes:

* You haven’t been signed up for the Amazon Product Advertising API yet
* API access and/or secret key are invalid
* The email you’re using to login to the AWS area and Amazon Associates are not the same

### Signup for Amazon API

If you don’t have signed up for the Amazon Product Advertising API until now, let’s do it together.

Brazil	[http://associados.amazon.com.br/gp/associates/apply/main.html](http://associados.amazon.com.br/gp/associates/apply/main.html "http://associados.amazon.com.br/gp/associates/apply/main.html")

Canada	[https://associates.amazon.ca/gp/flex/advertising/api/sign-in.html](https://associates.amazon.ca/gp/flex/advertising/api/sign-in.html "https://associates.amazon.ca/gp/flex/advertising/api/sign-in.html")

China	[https://associates.amazon.cn/gp/advertising/api/detail/main.html](https://associates.amazon.cn/gp/advertising/api/detail/main.html "https://associates.amazon.cn/gp/advertising/api/detail/main.html")

France	[https://partenaires.amazon.fr/gp/flex/advertising/api/sign-in.html](https://partenaires.amazon.fr/gp/flex/advertising/api/sign-in.html "https://partenaires.amazon.fr/gp/flex/advertising/api/sign-in.html")

Germany	[https://partnernet.amazon.de/gp/flex/advertising/api/sign-in.html](https://partnernet.amazon.de/gp/flex/advertising/api/sign-in.html "https://partnernet.amazon.de/gp/flex/advertising/api/sign-in.html")

India	[http://affiliate-program.amazon.in/gp/associates/apply/main.html](http://affiliate-program.amazon.in/gp/associates/apply/main.html "http://affiliate-program.amazon.in/gp/associates/apply/main.html")

Italy	[https://programma-affiliazione.amazon.it/gp/advertising/api/detail/main.html](https://programma-affiliazione.amazon.it/gp/advertising/api/detail/main.html "https://programma-affiliazione.amazon.it/gp/advertising/api/detail/main.html")

Japan	[https://affiliate-program.amazon.com/gp/flex/advertising/api/sign-in-jp.html](https://affiliate-program.amazon.com/gp/flex/advertising/api/sign-in-jp.html "https://affiliate-program.amazon.com/gp/flex/advertising/api/sign-in-jp.html")

Mexico	[https://afiliados.amazon.com.mx/gp/advertising/api/detail/main.html](https://afiliados.amazon.com.mx/gp/advertising/api/detail/main.html "https://afiliados.amazon.com.mx/gp/advertising/api/detail/main.html")

Spain	[https://afiliados.amazon.es/gp/flex/advertising/api/sign-in.html](https://afiliados.amazon.es/gp/flex/advertising/api/sign-in.html "https://afiliados.amazon.es/gp/flex/advertising/api/sign-in.html")

United Kingdom	[https://affiliate-program.amazon.co.uk/gp/flex/advertising/api/sign-in.html](https://affiliate-program.amazon.co.uk/gp/flex/advertising/api/sign-in.html "https://affiliate-program.amazon.co.uk/gp/flex/advertising/api/sign-in.html")

United States	[https://affiliate-program.amazon.com/gp/flex/advertising/api/sign-in.html](https://affiliate-program.amazon.com/gp/flex/advertising/api/sign-in.html "https://affiliate-program.amazon.com/gp/flex/advertising/api/sign-in.html")

![](/images/amazon-affiliate-wordpress-plugin-docs-signup-amazon-api.png)

On this page click on “Sign up” on the right and fill in registration. It’s possible to use your existing Amazon account if you don’t mind.

***

## Affiliate Program

### What is the ClicklickBankBank affiliate program and how does it work?

ClickClickBankBank affiliate program is a partnership based on revenue sharing, where the affiliate (you) drives traffic to clickclickbankbank.com website (us, we or our) in exchange for commissions. When your website visitor clicks on the reference link (as defined in our ClickClickBankBank Affiliate Program Terms) to our website and completes a purchase, you get a commission for any and every ClickClickBrankBank subscription they buy.  
To help you reach this goal, we provide a variety of promo materials in 2 languages, tracking, reporting, prompt monthly payments and excellent customer support.

### **What do I get as an affiliate?**

As our affiliate, you will gain access to your own personal account. You can log in at any time andget access to our banners and links, see how your reference links are performing: how many visits, signups sales and rebills came to us through your reference link and of course you will also be able to see your balance and how much money you earned both in the past and in the present.

### Who can join your affiliate program?

Anyone who has an active website at the time of sign up can join ClickClickBankBank affiliate program, with an exception of websites that contain pornography, explicit language or content, violence, hate speech, promote illegal activities, gambling, coupons, bargains or discounts, violate intellectual property rights or laws, contain materials that are defamatory, libelous, or disparaging or links to any content listed here. Please note, that you have to be at least 18 years old to join. We also reserve the right to refuse or revoke membership of parked domains; websites with little or no original content, or those that are inactive.

If you don't have a website, you can still share your reference link via e-mail, post videos or promote ClickClickBankBank through social networks, such as Facebook, Twitter, etc. We have affiliates from all over the world and most our affiliates sell our services across the globe. The signup process is completely free and only takes several minutes of your time.

### What is the reference link?

A reference link is the link, which leads to www.clickclickbankbank.com and contains your ClickClickBankBank reference identification number (REF ID) in it.

### Where can I use the reference link?

You can use it on your website, blog, in non-spam emails, social profiles and in your messages, sent via messengers (SPAMMING is forbidden and is severely punishable).

### How much will I earn for bringing referrals?

By participating in our affiliate program you will earn 30% commission for all newly acquired ClickClickBankBank subscription purchases that came through your reference link. Commissions are recurring,so you will get 30% of what your referral pays us every month until they stop paying for our subscription.  
Please note that this applies only to brand new, first time users you refer. Old, existing or returning ClickClickBankBank subscribers are not eligible referrals.

### Can I earn commissions with my own purchases?

Nice try, but no. You will not receive the commission for purchasing ClickClickBankBank subscription through your own reference link. Moreover, if you signed up just to get the 30% discount for yourself, your account will be blocked and you will not receive commission for this or any future purchases.

### How do you attribute a commissions if there are multiple affiliates involved?

We use first cookie attribution model, so if a user originally landed on our website from your reference link, then you will receive commission on all their purchases from www.clickclickbankbank.com, provided that the cookie life period didn’t expire. So if the referral is originally yours, you will receive commission from their account renewals, after gaps in payments, as well as for their upgrades.

### How and when do I get paid?

Commission payments are made upon reaching a minimum threshold of $50. If you haven’t reached it yet, the amount will be transferred to the next payout period. Payments are made on the 10th and 25th days of each month, when your account balance reaches $50 or more for the previous months’ transactions. There might be slight deviations from these dates, if the 10th or 25th days fall on weekends or public holidays. In cases like these, please expect the commission payment to reach you on Monday (after the weekend) or on the first workday following a public holiday. Payments are processed through PayPal.

### How do I track my earnings?

You can login to your ClickClickBankBank affiliate profile at any time to access your statistics and get updated information about any commission that you’ve earned. In your statistics you will be able to see the date, visits, unique visits, sign ups, sales, sales amount, rebills (repeat payments), rebills amount and your profit. Additionally, you can see your current Balance and all payments that we already made to you.

### What if I had a question not covered here?

If you have a specific question or a collaboration proposal, please feel free to mail us directly at affiliates@clickclickbankbank.com.