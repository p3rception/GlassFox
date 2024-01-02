![](/media/glassfox.png)
<hr>

## What is FirefoxCSS
Mozilla Firefox provides the ability to fully customise your browser using custom CSS. You can find more here [r/FirefoxCSS](https://www.reddit.com/r/FirefoxCSS/).

## Installation
1. Go to about:config and update toolkit.legacyUserProfileCustomizations.stylesheets to true.
2. Go to about:support and click "Show in Finder" in the Profile Folder field.
3. Click on folder containing all core Firefox files
4. Paste the entire "chrome" folder from this repository and restart Firefox.

## Acknowledgements
- https://github.com/zvuc/firefox-macos-native-tabbar
- https://github.com/datguypiko/Firefox-Mod-Blur
- https://github.com/dannycandle/FluidFox
- https://github.com/Hann8n/Atom-for-Firefox
- https://github.com/Soft-Bred/Brave-Fox

## GlassFox
- Tested only in MacOS.
- Fully transparent and transluscent.
- White pixel-sized border for the url-bar and the active tab.
- Centered url-bar.
- Brave Browser (and some Safari) Icons (all [available](/firefoxcss/chrome/brave-icons/), not all used). 

![](/media/firefox.png)

### (Optional) Custom Bookmarks Bar
- Safari-like text-only bookmarks with an icon animation twist.
- Place the contents of `bookmark-animation.css` to `userChrome.css`.

![](/media/bookmark-animation.gif)

### (Optional) Stretched tabs
- That's a second version of the skin that has Safari-like stretched tabs.
- I removed URL-bar's border as I think it complicates the minimal aspect of the theme.
- To achieve this you need change/add the following in `userChrome.css`:
```
#urlbar-background {
    border: none !important;
}
```
```
/* Stretch Tabs */
.tabbrowser-tab[fadein]:not([pinned]) {
    max-width: none !important;
}
```

![](/media/stretch-tabs.gif)
