# Description

Firefox clean tweaks for userChrome configuration based on [minimal-functional-fox](https://github.com/turing753/minimal-functional-fox)

# Preview

![userChrome.css preview 1](https://github.com/turing753/myuserchrome/blob/master/preview_1.png)

![userChrome.css preview 2](https://github.com/turing753/myuserchrome/blob/master/preview_2.png)


# Usage
1. Go to `about:support` in Firefox.
2. Application Basics > Profile Directory > Open Directory.
3. Unzip `chrome` config folder into the folder that appears.
4. Go to `about:config` in Firefox.
5. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to true.

Make sure that you have the `Dark` theme enabled.
1. Go to the address `about:addons`
2. Select `Themes`
3. Enable the `Dark` theme.

# Tips
* Install Recommended new tab [extension](https://addons.mozilla.org/en-US/firefox/addon/nighttab).

# Development
If you wanna mess around the styles and change something, you might find these
things useful.

To use the Inspector to debug the UI, open the developer tools (F12) on any
page, go to options, check both of those:

- Enable browser chrome and add-on debugging toolboxes
- Enable remote debugging

Now you can close those tools and press Ctrl+Alt+Shift+I to Inspect the browser
UI.

# Credits
- turing753
- gvoze32
- jscher2000
