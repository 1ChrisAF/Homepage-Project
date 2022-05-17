I'm using Firefox with the New Tab Override extension. I haven't set up a host 
for the page I'm writing to be my new tab and start page, so I'm using the 
local file at the moment. The extension builds the new tab page from the local
file selected and that file ONLY, so any local files referenced aren't
accessible after the build, as Firefox extensions can't reach local files. So,
I've loaded all of the styling into the page itself, and will look into a more
...elegant...solution later, like hosting all the files on a web server that
I can reach.

That's what this alt folder is for, it's just the home for the page I can use 
until the real site is ready to deploy. I don't really expect anyone else to
use it, it's just my personal project, but I figure treating it like I might
want others to use it, should be should practice.

Relevant links:
https://addons.mozilla.org/en-US/firefox/addon/new-tab-override/
https://github.com/cadeyrn/newtaboverride.git