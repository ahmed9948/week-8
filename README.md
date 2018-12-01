# week-8
Vulnerabilities in websites.

The three sites all looked the same in terms of format, the only difference is that they were different colors, blue, green, and red.
The blue wesbite vulnerabilities was session hijacking. I had two different browsers open one was firefox and the other was chrome. I inspected the element in both browsers and looked at the token and it was the same.
I went to hack tools and changed the token in firefox, then I went to chrome and pasted the new token that I have changed, I refreshed the page and I was able ti stay logged in.

The green website vulnerabilities was cross site scripting. I went to feedback and put in the information, I entered a java script in the comments and submitted it.
I went to the main page and logged in, I then went to the feedback section, once the page loaded, the cross site scipt attacked and it showed the custom alert that I typed.

The red website vulnerabilities was IDOR.
Once I clicked on "Find a sales person" I found a list of a lot of empolyees, I clicked on a few and noticed that in the URL "php?id=(#)".
I started messing around with the id numbers until I found the one that is not supposed to be showed to public. 
