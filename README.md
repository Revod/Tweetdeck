# Tweetdeck
Minimal and Custom CSS for Tweetdeck
-------------
## Installation

These instructions are for Stylish on [Chromium-based browsers (like Chrome)](https://chrome.google.com/webstore/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe) and [Mozilla-based browsers (like Firefox)](https://addons.mozilla.org/en-US/firefox/addon/stylish/?src=external-userstyleshome). Steps will vary based on browser and plugin.

### How to add a new style

* Click on the Stylish icon.
* Click on "Manage installed styles" (Chrome) or "Manage styles" (Firefox).
* Click on "Write New Style"
* Name it "Snowflake whatever"

### How to install this style

* Name the Style anything you want, but something easy to recognise like *Snowflake* would be good.
* Paste the text from `snowflake whatever.css` for the theme you use into the textbox.

#### Chrome

* Create a rule pointing to `URLs starting with` `https://tweetdeck.twitter.com`.
* Click on **Save** and look at TweetDeck!

#### Chrome Web App (Extension)

This is a bit more work and does **NOT** require Stylish

* Download your stylesheet
* Open your file manager/explorer and navigate to `%UserProfile%\AppData\Local\Google\Chrome\User Data\Default\Extensions\hbdpomandigafcibbmofojjchbcdagbl\`
* Next, click on the folder resembling a version number, and afterwards navigate to `web` and `css`
* Now, open `snowflake whatever.css`
* **IMPORTANT STEP:** Don't replace the styles with the one from Snowflake, go down 1-2 lines and paste the Snowflake style after the original one.
* Refresh the tab/standalone window with the Chrome Extension, and you now have your style installed!

#### Firefox

* Add the following into the textbox on a single line, before the contents of Snowflake.css: 
* `@-moz-document url-prefix("https://tweetdeck.twitter.com") {`
* Scroll to the bottom of the textbox and add an extra line with a single `}` on it.
* Click on **Save** and look at TweetDeck!

Known issues
-------------

Known issues on color schemes variations:
- ~~Some things are still blue. Gotta change it.~~