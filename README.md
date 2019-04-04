
# An Introduction to Web Scraping


## Introduction
While APIs are an ideal way to retrieve data from third parties, not all organizations provide access to all of their data using APIs. Some companies just provide access to their data via web pages. If you want to access that information in an automated way, you're going to have to write a script to "scrape" their website. In this course, we'll provide a brief introduction to web scraping, run you through the basics of HTML and CSS so you are at least familiar with what they look like, and then we'll give you some practice scraping a website using a Python library called Beautiful Soup.

## Objectives
You will be able to:
* Explain what web scraping is and why you might want to do it
* Explain some of the potential issues/problems with web scraping

## The Benefits of Web Scraping

One of the great things about web scraping is that it allows you to potentially download any information that's available via a website, giving you access to a huge quantity of data. And by automating the process, you can access the data much more efficiently than you could by manually going to all of the pages and copying down the information.

Automated web scraping is particularly useful where you want to download large quantities of data or automate the process of checking for and downloading updates to a page on a regular basis - both tedious and time consuming tasks if you do them manually.

## The Challenges of Web Scraping

Unlike APIs where companies expect you to access them using a script and design them accordingly, most companies sharing information on a website expect a human to manually browse to those pages. One of the nice things (from a website owners perspective) about a human manually browsing their website is that you can only make so many requests per unit of time. As such, you're unlikely to place too much of a load on their servers (the more pages that the more people request, the more expensive it is to host and maintain a website). You are also unlikely to use their data in a way they didn't intend. For example, clicking through to 1000 web pages manually to download the title, SKU and price of all of their products to compare prices across vendors is just so tedious and time consuming that there is at least some barrier to you doing it.

Because of both the costs/load and the potential for misuse, some websites actively take measures to make it harder for you to scrape their website. Some websites are easy to scrape, some are unintentionally difficult (they're not trying to stop you, but the load of your script breaks their web server) and others are intentionally difficult. Depending on the site, you can potentially find yourself in an arms race with the organization providing the website where you are trying to automate the process of downloading the information and they are trying to stop you from accessing the website using an automated tool. Some companies (such as LinkedIn) go to great lengths to detect and to try to block automated tools and users who employ them.



## Summary

Web scraping is a great way of automating the downloading of information from websites, but bear in mind that there are going to be some sites where it is harder (or even practically impossible) to automatically scrape content, so don't assume you'll be able to scrape data from a site until you have the data safely downloaded on your computer!
