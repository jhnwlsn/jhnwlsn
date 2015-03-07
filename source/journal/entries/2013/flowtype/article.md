---
title: FlowType.JS
date: 2013/08/20
published: false
---
Ideally, the most legible typography contains [between 45 and 75 characters per line](http://webtypography.net/Rhythm_and_Proportion/Horizontal_Motion/2.1.2/). This is difficult to accomplish for ***all*** screen widths with only CSS media-queries. FlowType.JS eases this difficulty by changing the font-size&mdash;and subsequently the line-height&mdash;based on a specific element's width. This allows for a perfect character count per line at ***any*** screen width.

## How It Came to Be
One morning, [Casey Zumwalt](http://zumwa.lt/) and I were critiquing a design that he had put together. In presentation, the website was pieced together, in-browser, with simple images. When we were discussing how the site will break down when the window was resized and something caught our eyes: the content inside the images scaled with the size of the browser. In other words, everything remained the same no matter what screen size.

We felt this would be beneficial to accomplish due to the dramatically various desktop screen sizes (E.g. 11" MacBook Air, 40" Television) so that websites would look the same no matter what screen size. It was also important that the responsive qualities remained intact.

The idea set in our minds for a few weeks, and then I thought of a way to do it with some simple jQuery. Within an hour, I wrote a minimally viable jQuery plugin that accomplished one important function: changing the font-size based on the window's width. This was important because everything could change with responsiveness except for the font-size.

One problem with the minimally viable plugin was that it only responded to the window width instead of the element width that the text resided in. Within the next few days, I finally got it to work but the plugin had slowly become too bloated. Thanks to several other people, including the wonderful [Giovanni Difeterici](http://www.gdifeterici.com/), we got the plugin to be incredibly small.

#### Still Interested? Check out these links:
[Full Featured Demo](http://simplefocus.com/flowtype)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Repo on GitHub](http://github.com/simplefocus/flowtype.js)
