# JS/PHP Active911 Map

## What is it?
~~A burning trash heap~~
It's a map that plots alerts from an active911 alert feed, with an implemented radar.
Coded in JS and PHP.

## What you need to do
In `rssfeed.php` you'll have to set the variable `rssFeedURL` to your department's rss feed URL. You can find your rss URL under the agency tab on the active911 site.

Set the defaultPosition variable in `index.html` `line 57` to a suitable geo coordinate. This is what's displayed when no alerts are active, and map is first loaded. Idealy, display your covered area.

You'll need to get a google maps API code and update the URL in `index.html` on `line 353`.
NOTE: Google maps does have an address to geo coord limitation. Last time I checked it was 1000 per day. Be careful if you're testing this with an active alert. You'll reach your limit pretty quick.

I think that's it... I hope...


## Why?
I put up monitors and got active911 going for my department, and a few members asked if I could get a radar showing over the map. I got it done, in probably the ugliest and most unefficient way possible, but I got it done.


## Why'd you do x-thing this way?
I don't know. It works -- or it did at one time.


## Other idea/implementations
I thought about implementing a slide show. Just so the TVs aren't displaying the same picture for hours on end. Would cycle through pictures of our trucks, the radar, a plain map.


## It doesn't work
¯\\_(ツ)_/¯

If nothing else, use it for insperation.
