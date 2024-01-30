# Class 17 Notes Web Scraping

## Why is this important?

- Web scraping makes data collection easier with automation, allows easier access to information from the web and businesses use web scraping to gather info on competitors

## Reading Questions 

- The key differences between scraping static and dynamic websites are static websites are easier to scrape than dynamic and libraries used are different for both.

- Three techniques you can employ to avoid getting blocked while scraping websites are "Do not follow the same crawling pattern": incorporate random movements in order to make your spider look more human-like.  "Use a headless browser like Puppeteer, Selenium or Playwright": These libraries automatically control browsers to render a block of JS, making it look like a real browser.  "Use Captcha Solving Services":  These will complete captcha checks. [source](https://www.scrapehero.com/how-to-prevent-getting-blacklisted-while-scraping/)

- Playwright is a headless browser that enables web automation, which makes a script that web scrapes look like a real browser preventing it from being blocked.  Playwright would be useful for making a script that automatically logs into a website for a user.  

- XPATH allows for accurate and precise selction of elements in the HTML of a website and makes getting data from the page more efficient.  An example of this would be selecting all inputs with an id of username `//input[@id='username']`

## What do I want to know more about

- N/A
