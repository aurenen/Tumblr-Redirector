# Tumblr-Redirector
A simple bit of code that redirects posts when you change your url. So when people try to visit posts on your old url, they don't have to search for the correct post at your new url. 

There's no fancy redirect page, it just automatically redirects to the new url. You can modify and incorporate this into your redirect page theme if you'd like. Just stick the <script> ... </script> stuff in your theme.

## Instructions
Edit your theme code, copy/paste everything from code.html, and replace your current theme code with it.

Find the following line:
> OLDURL is now at NEWURL

And replace it with the correct urls

Find this line:
> window.location.replace("http://NEWURL.tumblr.com" + window.location.pathname);

And replace NEWURL with your actual new url, do not remove the quotes.
