# clubV

Notable Features

**Custom web fonts with Font Squirrel**

• This tool generated the necessary files to use custom fonts in CSS. I chose to use it because I wasn’t satisfied with the typical font selection found on Google Fonts.


• I used these fonts on the site’s home page to give a personality to the artists before a
user experienced their music.

• Including these fun and experimental title fonts added to the look and editorial feel of
the site.

**Shining Text Animation Effect**

• I chose to use this animation because it added motion to an otherwise static button.


• I attached this animation to the “click to enter” prompt. I changed the gradient from
black and white to a zero opacity white and white, then to a yellow and white gradient
when interacted with.


• I’ve seen similar animations at the beginning of classic arcade games when users are
prompted to enter coins, so I thought that would be a fun way to enter a website.


**Google Cloud**

• I chose to host the background videos on Google Cloud in an effort to speed up the
site’s loading time and reduce the overall processing load.


• The background video changes when a user hovers over the artist’s name. This was
achieved by triggering a javascript function to make an API call to a Google Storage
Bucket containing each video, then changing the background video’s source.


• The background videos give users a preview of the artist’s work.'


**Bob on Hover**

• I chose to use this animation because it’s a subtle yet fun way to show the user that
they can click on the artist’s names.


• This animation is triggered when a user hovers over an artist’s name.


• This animation is very subtle and doesn’t add much to the overall site, but it looks
cool when moving against a textured background (like when hovering over Moiré).


**Nav +/- and Fade Opacity**

• I chose to use this animation to reveal and hide the navigation links. I modified it to
fit the look and feel of my site, and to translate across the screen while transforming
from a plus symbol to a minus symbol.


• When a user clicks on the plus symbol, a CSS animation is triggered while a
javascript function simultaneously toggles the div that contains it from open to
closed.


• There is a lot going on on each page of the site. I hid the navigation bar because it’s
not necessary on the homepage or project pages until a user needs to return a muted
home screen.


**Vanilla JS Image Particles**

• I chose to use this as a background for the Ghettoville page because it sets the tone of
the article, and compliments its music.


• This javascript function draws 20,000 particles moving downward at a constant speed
while calculating the brightness of each pixel on a local image. The particle speed is
adjusted to slow at brighter, whiter pixels, creating a rain-like ghosting effect.


• The slow reveal forces users to engage with the image, and hopefully the text that is
revealed soon after.
