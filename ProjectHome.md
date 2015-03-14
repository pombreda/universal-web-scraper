## Latest News ##
**October 29, 2012: No significant work has been done on the new version in the past month. I have limited free time and it's not enough to work on the scraper. However, I highly appreciate your emails, because they keep giving me ideas of new features I can add to the new version. Once I get this done, I'm sure you all will be pleasantly surprised by the great new interface, scraping flexibility and amount of new features. Thanks for your support!**

**September 25, 2012: A major update is underway! Thanks for supporting the scraper!**

**September 11, 2012: Universal Web Scraper v.1.14 has been released!**

## Overview ##
Universal Web Scraper is, as its name says, a universal web scraper and web crawler application written in PHP and meant to be used primarily for data extraction tasks. Universal Web Scraper is very easy to use and installs in less than 10 minutes. It has a very simplistic text-based interface with no fancy graphics (which will surely change with the release of future versions), but works very stable and reliable. All possible server timeouts are handled gracefully to allow seamless scraping sessions even on a large set of web pages. When your scraping sessions are complete, you can export all the extracted data into CSV files for further inspection and processing.

But the best thing about Universal Web Scraper is that, unlike other web scraping applications, **you don't need to know regular expressions** in order to complete your tasks - data extraction rules are provided by the user through the application interface in the form of simple and easy-to-understand English sentences. The sentences are then translated to regular expression patterns in the backend. In other words: all the hard work is handled by the application - not by the user.

## Requirements ##
In order to be able to use Universal Web Scraper on your web server you need to make sure:

- You have the cURL Extension installed/enabled in the PHP installation of your server environment.

- Your server environment has a database server that you can connect to and use to create new databases and database users, and grant various permissions to these users.

**Detailed installation and usage instructions, as well as screenshots, can be found at:** http://www.marinbezhanov.com/scraper/documentation/

**A working online demo can be tested at:** http://www.marinbezhanov.com/scraper/

## Future Development & Improvements ##
As in my other products, future development & improvements of Universal Web Scraper depend heavily on user feedback I receive. If you want certain features or have ideas how to make this product better, don't hesitate to contact me, Marin Bezhanov, via: http://www.marinbezhanov.com/contact.php

## Changelog ##
**version 1.14 (2012-09-11)**
  * Applied a patch that enables scraping of META tags based on their Open Graph properties
  * Added "Fallback Patterns" that allow the scraper to correctly match and extract the content of an attribute of a tag with an ID/class/property filter, regardless whether the attribute is defined before or after the ID/class/property of that tag
  * Fixed rule ID bug, which was preventing users from enabling certain data extraction rules that were previously stored in their installations, after removing old rules
  * Added a method for posting data to a target URL, which allows users to scrape dynamically generated content like search results pages for example
  * Added a "strip tags" option, which allows you to strip unwanted HTML tags from extracted data
  * Added SSL Support
  * Added a PayPal Donation button, in case you want to support development of this project with a small donation, which would be highly appreciated
  * Updated database structure (dbstruct.sql)

**version 1.12 (2012-07-31)**
  * Applied a patch that provides support to scraping void elements like META tags
  * Applied a patch that enables the scraper to recognize both single and double quotes as valid attribute delimiters

**version 1.1 (2012-05-19)**
  * Added ability to add and remove tags & attributes from the front end of the application.
  * Added ability to save and re-use scraping rules
  * Replaced all PHP short tags with long tags to increase compatibility on hosting accounts, where short tags are disabled by default.
  * Updated database structure (dbstruct.sql)

**version 1.0 (2012-03-26)**
  * Universal Web Scraper has been released to the public!