# week-1-assignment-fixed

New repo for my week 1 assignment after the previous one was broken because of large audio file issue

Reflection

I'm happy with the outcome of the website, and think I achieved all of the required goals. I achieved a few of the stretch goals by making a "return to top" button, a footer with social media links, and a hover effect on my buttons (even the ones that were just anchors disguised as buttons). I tried to add the background music but this was a bit of a disaster as I've detailed below so I gave up on it. I also looked around for how to get smooth scrolling on my buttons but couldn't figure it out.

Audio Issues

My biggest problem so far is with the audio file that I tried to use. I couldn't get the HTML audio tag working so I gave up on that and deleted the file from this folder (using delete in VS Code, not a git rm in the console, which might've been what caused the problem), but it still showed up saying that it was too large so couldn't be committed to github properly. The file was 109 MB when the github limit is 100 MB so I tried an Indiana Jones-esque solution of swapping it for a much smaller audio file that I renamed to have the same name. As I'm typing this I'm about to commit again to see if that works.

It didn't work. Now I'm trying to fix the problem with a stack overflow thread that I've found (https://stackoverflow.com/questions/19573031/cant-push-to-github-because-of-large-file-which-i-already-deleted). This didn't work for me either, possibly because I'm not confident enough with github or the terminal to know which of the proposed solutions would've been right for me. Instead I've made a new github repo and copied the files across. The "JungleAmbience.mp3" that is now in the repo is a remnant of me swapping in another audio file with the same name because I didn't want to delete it and cause the problem all over again. It's actually a song by The Vaselines that was the first thing I found in my music folder, but I'm choosing to consider it cut content to be discovered by the millions of Gorilla Central fans in the future.

Sources

Footer not sticking to bottom - https://www.reddit.com/r/css/comments/xm6yll/any_idea_why_is_my_footer_not_staying_at_the/
Internal links - https://way2tutorial.com/html/html_internal_links.php (this forced me to break Manny's suggestion of keeping ids only for JS which I was planning to stick to)
Return to top button - https://www.w3schools.com/howto/howto_js_scroll_to_top.asp
I wasn't keeping track of links but anytime I used an HTML abbreviation I was also googling that.
How to make an HTML button that functions as a link - https://stackoverflow.com/questions/2906582/how-do-i-create-an-html-button-that-acts-like-a-link (I opted for the solution to just make an anchor and style it to look like a button)
