# Project 6: Feed Reader
For Udacity Front-End Developer Nanodegree

# About

Tests were added in `jasmine/spec/feedreader.js` to test for functionality of the website.  The following tests are included:

- RSS feeds are defined in `allFeeds` and are not empty.
- Each feed in `allFeeds` has a defined and valid (simple RegExp) URL.
- Each feed has a defined and non-blank name.
- The navigation menu is hidden by default (on page load).
- The nav. menu toggles visibility after clicking the menu icon.
- The first feed has at least one entry.
- The feed changes content after selecting a new feed.

# How to Run

-Download or clone the repository and open it in your browser locally. 
-All needed Jasmine libraries are included, and you will see a section below the page showing the test results.

<Note> To add or edit the feed sources, open `js/app.js` and change the `allFeeds` object.
