Write a Google Chrome extension that adds a modal dialog to any web page whenever the query parameter `?fanrock=true` is present in the address bar. The contents of the modal should show the OpenGraph metadata (if present) of the page.

For example, if I were to visit the [Rotten Tomatoes page](https://www.rottentomatoes.com/m/avatar?fanrock=true) for the movie Avatar, it would look like this:

![Avatar](https://raw.githubusercontent.com/fanrock/homework/master/avatar.jpg)

Where To Start:
---------------
 - the [Chrome Extension Developer's Guide](https://developer.chrome.com/extensions/devguide)
 - Facebook [OpenGraph Markup Documentation](https://developers.facebook.com/docs/sharing/webmasters#markup)
 - Facebook [OpenGraph Debugger](https://developers.facebook.com/tools/debug/)
 - the [Facebook Pixel Helper](https://chrome.google.com/webstore/detail/facebook-pixel-helper/fdgfkebogiimcoedlicjlajpkdmockpc?hl=en) Chrome Extension - this is a good example of a Chrome extension that does reads data from the page but doesn't do exactly what this task is.

Bonus:
---
 - publish your extension (if you're already a registered Google Developer)

Deliverables
------------
Fork this repository and write your code in your own private branch. Edit this `README.md` file with instructions on how to execute whatever code you write. It should work as an unpacked extension. Send a [pull request](https://help.github.com/articles/using-pull-requests/) when your code is complete.
