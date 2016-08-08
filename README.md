## Firefox Autocomplete Prioritize URL

There's a trend in browser interfaces where URLs are becoming less prominent. Safari iOS is one of the worst offenders, only showing the domain in the URL bar. Firefox 48 took a step in that direction, by rearranging the autocomplete dropdown to show page titles and URLs inline (instead of stacked), with the URLs displayed in a smaller font after the title. Since titles are uneven, the URLs are hard to scan at a glance:

![](http://i.imgur.com/b9uICBX.png)

This can be fixed by moving the URL to the first position with [a bit of CSS](https://cdn.rawgit.com/nathancahill/prioritize-url/master/autocomplete.css):

![](http://i.imgur.com/1fRhAzU.png)

As a bonus, I also tightened up the design a little to use the default 12px font instead of the new, large 14px titles.

### Installation

After installing [Stylish](https://userstyles.org/), install [the stylesheet here](https://cdn.rawgit.com/nathancahill/prioritize-url/master/autocomplete.css).

### Issues

This has only been tested on Firefox 48 for Mac. Feel free to try it out on other platforms and open issues for any bugs that you find.
