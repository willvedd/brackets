Brackets
========

This is a small project I developed to keep track of my annual (and low stakes) march madness bracket pool. The point was to make the experience for everyone better by preventing the usual hassle that comes with typical bracket pools. Specficically, signing-up for an account, navigating a foreign UI, joining a group properly. These aren't such huge roadblocks for some savvy sports fans but I still didn't want to subject my entire poolbase to poor UX. 

I also wanted the entire operation to be as transparent as possible. With the brackets and scoring live on the webpage live on the web along with the repo on github, there is no room for debate or foul play. By either the admin or the participants.

Instead, I ask users to fill out their bracket however they wish, whether on paper or digitally. I just require them to send me a digital file such as a photo, screengrab or generated PDF. They then can be linked easily to the page for viewers to see each other's brackets. Granted, scoring is done by manually counting correct picks, but it is part of the enjoyment for me, and for the participants I find. It gives a more old-school feel that ESPN, CBS and Y!Sports don't seem to offer.

The page is pretty bare bones with a little bit of styling. It is generally responsive and viewable on most devices. The primary feature is the scoring table which is has some custom styling and some styling take from Twitter's Bootstrap. Column sorting functionality is integrated using a jQuery plug-in called Tablesorter (http://tablesorter.com/). The main advantage to this system is Github's hosted pages via the "gh-pages" branch. This makes updating and pushing such a simple process.
