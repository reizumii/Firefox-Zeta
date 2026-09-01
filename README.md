## [Firefox-Zeta](#features) 🪨 - Super clear browser theme

![Preview of Firefox-Zeta](assets/preview.png)

Fast and minimal Firefox theme with zero buttons and intuitive controls.

> **ℹ️ Firefox-Zeta is a reimplementation of [Firefox-Alpha](https://github.com/Tagggar/Firefox-Alpha)**

---

### [`⬇️ Install`](#install)
### [`⚡ Shortcuts`](#shortcuts)
### [️`📝 Notes`](#notes)

## Features

See **Firefox-Alpha's** [features section](https://github.com/Tagggar/Firefox-Alpha#features) for more details.

* [x] **Combined URL bar and Selected Tab**
* [x] **Multi-row Tabs**
* [x] **Multi-row Bookmarks**
* [x] **New Clean Menu**
* [x] **New Downloads Bar**
* [x] **Simple Find Bar**
* [x] **[New Extensions Bar](#new-extensions-bar)**
* [x] **[Adaptive Color](#adaptive-color)**

---

### New Extensions Bar

The extensions button now lives as a bar in the top-left corner of the window just before the first tab, reducing cognitive load and enhancing usability.

🌟 All your favorite extensions still accessible;

👍 Nice and clean hover animation.

### Adaptive Color

Install the [Adaptive Tab Bar Colour](https://addons.mozilla.org/firefox/addon/adaptive-tab-bar-colour/) extension to make the browser UI adjust to the website's color.

👌 Dynamic and seamless color switching;

⚠️ Leave the configuration on defaults.

## Shortcuts

Putting emphasis on shortcuts ensure an efficient and productive workflow:

- <kbd>MMB</kbd> on an empty tab area to create a new tab;
- <kbd>RMB</kbd> on an empty tab area to access containers;
- <kbd>Ctrl</kbd>+<kbd>L</kbd> to focus on the URL bar;
- <kbd>Ctrl</kbd>+<kbd>F</kbd> to find text in a page;
- <kbd>Ctrl</kbd>+<kbd>I</kbd> to manage site permissions;
- <kbd>Ctrl</kbd>+<kbd>Tab</kbd> to switch between recently opened tabs;
- <kbd>Alt</kbd>+<kbd>←</kbd> / <kbd>→</kbd> to go backward or forward one page;
- <kbd>Alt</kbd> to access the menu.

I'm not gonna list all of them, check out the [Firefox cheat sheet](https://duckduckgo.com/?q=firefox%20cheat%20sheet&ia=cheatsheet&iax=1) for more 😛

> 👾 Moving tabs with a mouse will always remain buggy due to CSS limits. Thus, it is highly recommended to use tab management extensions that utilize keyboard shortcuts.

## Install

1. Type and enter `about:support` in the address bar;
2. Find the `Profile Folder` row and open the profile folder;
3. Create a new folder named `chrome`, and move `userChrome.css` inside it;
    - 📂 `/` `Firefox` `/` `Profiles` `/` `###.default-release` `/` `chrome` `/` `userChrome.css`
4. Type and enter `about:config` in the address bar, and change the following:
    - `toolkit.legacyUserProfileCustomizations.stylesheets` › `true`
    - 🚫 Toggle these off for cleaner search suggetions:
      - `browser.urlbar.suggest.trending` › `false`
      - `browser.urlbar.suggest.quickactions` › `false`
      - `browser.urlbar.suggest.recentsearches` › `false`
    - Or disable search results completely: `browser.urlbar.maxRichResults` › `0`
    - ⚠️ If you have pinned extensions in the toolbar, unpin them now.
5. Restart Firefox and enjoy.

## Notes

> **ℹ️ Only tested on Firefox 153 ESR**

Also, **no vertical tabs support**, don't make an issue about this 😛
