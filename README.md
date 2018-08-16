# nomovdo+ - A working video blocking extension for Chrome

[![License](https://img.shields.io/badge/license-BSD-blue.svg)](LICENSE)

[Download](https://chrome.google.com/webstore/detail/nomovdo%2B-video-blocker/iphdnlmkhpokogoiilglemoglfoocagf)

nomovdo+ is an extension for blocking videos on websites.

Note: this is a modified version of [this extension](https://github.com/bullno1/nomovdo) but
handles more cases. I'm happy to give this up if the original author want's to take the
changes but basically the original is not blocking videos on lots of places so I started
hacking to make try to make it work in more cases.

# original readme

It was created because I could not find anything that works consistently on all websites.

## Features

- Block **all videos** by default.
- Whitelist a domain with a single click.

## FAQ

### Why can't I start a video manually?

Because this is a video blocker, not an autoplay blocker.

A proper explanation: some websites seem to employ trickery to get around even Chrome's internal autoplay setting.
The only way to ensure no autoplay is no working videos.

### Why not uBlock?

It only hides instead of removing/disabling elements.
Videos are still downloaded and sound can still be heard.
Large media element blocking feature relies on a magic number that is annoying to tweak.

### Why not `chrome://flags/#autoplay-policy`?

It does not have a whitelist and for some sites like Youtube, I prefer autoplay.

### Would Chrome have this built-in in the future?

Unlikely: https://developers.google.com/web/updates/2017/09/autoplay-policy-changes.
They came up with a convoluted system instead of just allowing users to completely block autoplay.

### Why disabling instead of removing video elements?

Thumbnails look nice and I don't want to mess with the site's layout.

## Credits

[Video icon](https://thenounproject.com/search/?q=video&creator=1275668&i=387694) by AlfredoCreates.com, from the Noun Project
