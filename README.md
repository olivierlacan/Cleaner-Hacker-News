# Designed Hacker News

__Note: I modified the stylesheet and the screenshot below. – @olivierlacan__

Designed Hacker News is a loose collection of CSS rules that you can use to improve the style of Hacker News (http://hackerne.ws or http://news.ycombinator.com).

Here's a screenshot: ![](http://f.cl.ly/items/382O3L3v2y303x1h3t2Y/Screen%20Shot%202012-03-11%20at%2011.01.51%20PM.png)

The styles improve the legibility of the page by:

 * replacing Verdana with Lucida Grande on Mac OS X and with Segoe UI on Windows, and tweaking the font size; the new fonts are narrower than Verdana and easier to read
 * giving everything more room to breathe
 * removing the container color so there's no longer a border to the left of the list of submitted articles
 * reduces the contrast of each item's number and increases the contrast of links so the page becomes easier to scan

See screenshot.png for a preview of how it looks in Google Chrome.

Tested in Google Chrome 43 on Mac OS X and Safari 9.0

## Installation

### Chrome

To apply the styles in Google Chrome, install the Stylebot extension (https://chrome.google.com/webstore/detail/oiaejidbmkiecgbjeifoejpgmdaleoha), head to Hacker News, click the Stylebot button in the address bar (the one that says "css"), click Edit Css at the bottom, and then paste the contents of cleaner-hn.css.

To preview the styles you can paste this Javascript into your address bar:

    javascript:(function(){var st = document.createElement('link');st.type = "text/css";st.href = "https://raw.github.com/Primigenus/Cleaner-Hacker-News/master/cleaner-hn.css";st.rel = "stylesheet";document.body.appendChild(st)})()

(thanks to jQueryisAwesome on HN)

Also available via Stylebot.me: http://stylebot.me/styles/1107

### Safari

Install the [Stylish extension](http://sobolev.us/stylish/) and you can create a new style as follows
by copying the raw CSS from [cleaner-hn.css](cleaner-hn.css):

![](https://s3.amazonaws.com/f.cl.ly/items/2w1M0E423S1M2t3g1u27/Screen%20Shot%202015-08-11%20at%2010.12.10%20AM.png)
