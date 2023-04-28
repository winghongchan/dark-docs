# Dark Docs
A dark theme for the Google Docs web app, based on the appearance of dark modes in other Google products. Subtle animations added and major [Material Design](https://m3.material.io/) consistency fixes added. 

If [Stylus](https://github.com/openstyles/stylus/) is installed on your browser,\
[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-238b8b.svg)](https://userstyles.world/api/style/2597.user.css)

![](https://raw.githubusercontent.com/winghongchan/dark-docs/main/Screenshot%202023-04-28%20at%2016-40-22%20Dark%20Docs.png)

## Installation

Install the theme at [Dark Docs on UserStyles.world](https://userstyles.world/style/2597/dark-docs). Doing this will make it easy to receive updates. 

You may choose to give Dark Docs a rating on UserStyles.world. 

### Firefox (and LibreWolf, Pale Moon, &c.) users
Dark Docs uses the newer `:has()` selector for hard-to-fix things. Support for it in Firefox is currently in development, but you can enable support for it by setting the layout.css.has-selector.enabled preference to true. Follow along with Mozilla’s work on this at [Bugzilla](https://bugzilla.mozilla.org/show_bug.cgi?id=418039). 

Chromium-based browsers have full support of the `:has()` selector. 

### Chrome (and Edge, Vivaldi, Ungoogled Chromium, &c.) users
By default, Dark Docs uses the Invert document filter so your document appears with an inverted colour scheme (approximately white on black). Since Google Docs renders each page as a single <canvas> element, there doesn’t seem to be a way to un-invert images so that they look normal. If you must view images un-inverted, you may change the document filter to “Dim” or “None” in the [configuration dialog](https://github.com/openstyles/stylus/wiki/UserCSS#how-do-i-customize-usercss). 

## Contributing

Dark Docs is written as a [UserCSS](https://github.com/openstyles/stylus/wiki/Writing-UserCSS) file and uses the [{less}](https://lesscss.org/) preprocessor. 

The intent is simple—to make a dark mode for Google Docs web that shares the same colors and overall look to the Google Docs mobile app in dark mode. 

Dark Docs only works with Google Docs. There are plans to make themes for Google Sheets and Slides in the future. If you create such a project (with a similar intent to this project), you may submit a pull request to include a link to it here.
