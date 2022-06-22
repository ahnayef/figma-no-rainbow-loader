# Figma Anti-LGBT

Chrome extension that removes cringe pride-themed loading bar from Figma.com.

[Download from Chrome Web Store](https://chrome.google.com/webstore/detail/figma-anti-lgbt/lnecjeoakphagjeoceoapondpmabphgl/) • [Download soruce from GitHub](https://github.com/VityaSchel/figma-anti-lgbt/archive/refs/heads/master.zip)

![image](https://user-images.githubusercontent.com/59040542/175054360-9ecad24e-27b6-4703-b3a0-ef9a2eae9f5c.png)

## Why?

I made this extension in 41 minutes to remove pride loading bar because there is no extensions like this in the internet. Bleach my eyes!!

I intentionally made it in vanilla js (or css?) without React, Webpack and SCSS to minimize size of packed extension. Currently it's just 28 KB overall and **only 546 bytes without icons**.

## How?

This extension is basically replacing `background` property of loading bars to `#0d99ff`. In order to prevent it from stop working with site updates, classes are selected by prefix, not whole substring.

Confirmed to work on Recent files page, editor and prototype presentation.

## How to use?

- Download it in Chrome Web Store, and that's it! No setup needed.

OR

1. Download this repository using "Download as ZIP" button (or clone if you cool enough)
2. Go to Chrome &rarr; Extensions &rarr; Load packed extension
3. Locate figma-anti-lgbt/src directory inside downloaded repository

## Can I do something with this like report you or write hateful «u homophobic» comment??

[go ahead](https://twitter.com/hlothdev)