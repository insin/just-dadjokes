# Just /r/dadjokes

A little [React](http://facebook.github.io/react/) app which uses
[Reddit](https://www.reddit.com/)'s [API](https://www.reddit.com/dev/api) via
JSONP to display self-posts from the
[/r/dadjokes](https://www.reddit.com/r/dadjokes/) subreddit.

Might be useful/adaptable for other subreddits where self-posts are the main
draw.

## Features

* Configurable minimum score threshold (default: `0`)
* Linked media can be inlined or embedded as appropriate (defaults to on):
  * Imgur links
  * Imgur galleries
  * Imgur GIFV videos
  * YouTube videos
  * Any link ending in .gif/.jpg/.png
* The Reddit `/s` convention for spoiler links is converted to display spoilers
  inline on hover/focus.

## MIT Licensed