# Web browser

![security: high](https://img.shields.io/badge/security-high-blue) ![usability: medium/high](https://img.shields.io/badge/usability-medium%2Fhigh-yellow)

Modern web browsers are generally quite secure _on account of_ being a major attack vector. They are effectively like operating systems in and of themselves, and attempt to isolate from the host OS as best they can.

I personally use [Firefox](https://www.mozilla.org/en-GB/firefox/new/) for most things—particularly because of its support for [containers](#browser-containers)—or else [Google Chrome](https://www.google.com/intl/en_uk/chrome/) on rare occasions.

## Browser profiles

Both [Chrome](https://support.google.com/chrome/answer/2364824) and [Firefox](https://support.mozilla.org/en-US/kb/profile-manager-create-remove-switch-firefox-profiles) support the concept of "profiles," which are meant to isolate completely different browsing sessions from one another.

I like profiles as a way to sandbox specific extensions (e.g., [crypto wallets](/use-cases/cryptocurrency.md)), but otherwise prefer [containers](#browser-containers) to sandbox web applications.

## Browser containers

Firefox uniquely supports a feature called [Multi-Account Containers](https://support.mozilla.org/en-US/kb/containers) that allows a single browser window to contain tabs from different "containers" side-by-side, without sharing data between them. It's really quite similar to something like [Docker containers](containers.md), but for web browsing.

For separating, e.g., work and personal activity, I find this user experience _far superior_ to [browser profiles](#browser-profiles), which can't share a window.