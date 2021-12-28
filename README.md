# Vulpes 🦊

``` text
> Minimal Firefox user.js tweaked for privacy
```

Firefox is a [mess](https://polarhive.ml/blog/firefox/). This repository contains many tips & tweaks you can use on Firefox based browsers. I think Mozilla should ship with these tweaks pre-configured, out of the box.

## What's with the name?

``` text
vulpes - family of foxes; this user.js can be used with any Firefox based browser
```

## Like LibreWolf?

In general, vanilla Firefox can be tweaked to do everything that [LibreWolf](https://librewolf.net/) does. Most [GNU/Linux](https://polarhive.ml/linux) distros ship with better, up-to-date versions of Firefox, browser addons receive critical auto-updates, some distros specifically add patches to improve performance / [integrate](https://gitlab.com/librewolf-community/browser/linux/-/issues/232) better with the [desktop like KDE](https://community.kde.org/Plasma/Browser_Integration). Most importantly you get official support from Mozilla, should you be facing bugs. LibreWolf might feel too harsh for some people, some sites stop working. In this case you should be using the [Tor Browser](https://www.torproject.org/) instead - for better privacy & compartmentalize your browsers.

So it's not really necessary to use LibreWolf if you can follow the simple instructions given here & you don't have a problem with software updates being hosted on Mozilla's servers.

## Tweaks 🛠

- Better Dark Theme
- Telemetry disabled
- Firefox accounts disabled
- Google Safe browsing & Geolocation disabled
- Reduced pinging 3rd party sites like pocket

---

# Instructions

### 0. Copy The ``user.js``

1. Click [here](https://codeberg.org/polarhive/vulpes/archive/main.zip) to download the latest user.js file
2. Extract the ZIP
3. Copy the ``user.js`` file to the clipboard
4. Launch Firefox
5. Type ``about:profiles`` in the addressbar & hit enter
6. Navigate to the Firefox current profile folder by clicking on ``Open Directory``
7. Paste the ``user.js`` file into that Firefox profile directory
8. Close Firefox & launch it again

### 9. Search Engine

Google, Bing, Yahoo are not good choices. Pick another search engine like [DuckDuckGo](https://duckduckgo.com/), [Whoogle](https://github.com/benbusby/whoogle-search), [Brave Search](https://search.brave.com/), [Wikipedia](https://wikipedia.org/), a [Searx](https://searx.me/) instance, or simply just bookmark sites.

TIP -> Right click on the addressbar to add search engines

### 10. Extensions

- [Ublock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
- [Privacy Redirect](https://addons.mozilla.org/en-US/firefox/addon/privacy-redirect/)
- [Material Ocean Dark Theme](https://addons.mozilla.org/en-US/firefox/addon/material-ocean-theme/)

TIP -> HTTPS is always on. Don't need to install any extensions.

### Done

Check this page for updates. Bookmark it. [CTRL+D]

---
It's a shame Mozilla bloats Firefox with every new update. Well at least it's better than anything on the market as of now. That being said, please tell Mozilla to not indulge in politics & divide users. I want them to actually fight for the 'Open Web' than act as a pawn for [Google](https://www.pcmag.com/news/mozilla-signs-lucrative-3-year-google-search-deal-for-firefox), slowly losing marketshare.

---
This repo is hosted on [Codeberg](https://codeberg.org/polarhive/vulpes) & on GitHub as a READ-ONLY mirror.

[![license: GPLv3 or Later](https://polarhive.ml/assets/badges/gpl-3.svg)](https://www.gnu.org/licenses/gpl-3.0.txt)
