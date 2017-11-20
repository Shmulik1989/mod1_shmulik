## General

Your code is well readable and structured. Your files are structures as well, only (when it comes to hosting online) you wouldn't put the html in a seperate folder but in the root. 

Good use of technical markup like the utf-8 meta tag and the lang attribute on the html. 

The navigation should always be on top of the html. If you got no css applied it should still be on top of the page (i.e. for screen readers or crawl spiders)

## Design

With multiple background images it seems a bit much. But that's no concern.

The body background scales with the entire page. So it "jumps" when the length of the page differs. You might want to look into "background-attachment: fixed". That way it will also not scale too much on long sites.

## Code

See comments

