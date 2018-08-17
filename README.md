# uBlock filters for Strava cleanup

This is a list of filters that I've put together to clean up my Strava feed as it's gotten more and more filled with their own advertising, and loads of fake rides, such as Zwift, Peloton, and Trainer Road.

## Using the filters

First decide which filters you want to use. For most folks you'll just want "ublock.txt" which is a pretty heavy-handed approach to killing almost all of their non-ride related junk in the feed. At some point I might split it out so you can pick and choose what you want to block - such as if you aren't in any clubs and want that removed. For now, ublock.txt is a single list of rules which agressively removes a bunch of stuff from my feed.

To use a filter, find the .txt file you're interested in, and then click on the file, and choose "Raw". The raw text file will open, and you can use that URL to add to your uBlock custom filters.

For instance, ublock.txt should give you a link such as:

https://raw.githubusercontent.com/ChrisHeerschap/ublock/master/ublock.txt

1. Copy the link for the filter you want.
1. Open your uBlock settings
1. Switch to the "Filter lists" tab
1. At the bottom of the list, you'll see Custom with a checkbox next to Import. 
1. Click the checkbox next to Import and it'll open up a text entry pane.
1. Paste in the URL you've copied
1. "Apply changes" becomes active in the top right, click that.
1. Reload Strava and enjoy the greatly uncluttered dashboard.

