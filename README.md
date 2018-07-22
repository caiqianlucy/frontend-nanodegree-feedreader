# Feed Reader Testing

Feed Reader is a web-based application that reads RSS feeds. Here I wrote a jasmine based testing to test the basic function of Feed Reader.

## How to run?
1. You can clone or download files from https://github.com/caiqianlucy/frontend-nanodegree-feedreader.

2. Find index.html and open it in your browser.

3. Check the test result at the bottom of the page, you will find all the tests pass.

4. If you want to add additional tests, open jasmine/spec/feedreader.js and you can modify the file.

## What functions are tested?
1. allFeeds are defined and not empty.
2. Each feed are defined with correct URL and name.
3. The menu is hidden by default.
4. The menu is shown upon click and hidden upon another click.
5. When the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
6. A new feed is loaded by the loadFeed function that the content actually changes.

## Skills
1. Jasmine
2. HTML5
3. CSS3
4. Javascript
5. jQuery 

