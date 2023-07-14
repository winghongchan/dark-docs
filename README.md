# Dark Docs
A dark theme for the Google Docs web app, based on the appearance of dark modes in other Google products. 

If [Stylus](https://add0n.com/stylus.html) is installed on your browser,\
[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-238b8b.svg)](https://userstyles.world/api/style/2597.user.css)

![](https://raw.githubusercontent.com/winghongchan/dark-docs/main/Screenshot%202023-04-28%20at%2016-40-22%20Dark%20Docs.png)

## Installation

Install the theme at [Dark Docs on UserStyles.world](https://userstyles.world/style/2597/dark-docs). Doing this will make it easy to receive updates. 

You may choose to rate Dark Docs via the hyperlink above. 

### Firefox (and LibreWolf, &c.) users
Dark Docs uses the newer `:has()` selector for hard-to-fix things. Support for it in Firefox is currently in development, but you can enable support for it by setting the layout.css.has-selector.enabled preference to true. Follow along with Mozilla’s work on this at [Bugzilla](https://bugzilla.mozilla.org/show_bug.cgi?id=418039). 

Chromium-based browsers have full support of the `:has()` selector. 

### Chrome (and Edge, Vivaldi, Ungoogled Chromium, &c.) users
By default, Dark Docs uses the Invert document filter so your document appears with an inverted colour scheme (approximately white on black). If you must view images un-inverted, you may change the document filter to “Dim” or “None” in the [configuration dialog](https://github.com/openstyles/stylus/wiki/UserCSS#how-do-i-customize-usercss). 

For more info and another workaround to the photo bug, see [issue #8](https://github.com/winghongchan/dark-docs/issues/8). 

## Contributing

Dark Docs is written as a [UserCSS](https://github.com/openstyles/stylus/wiki/Writing-UserCSS) file and uses the [{less}](https://lesscss.org/) preprocessor. 

The intent is simple—to make a dark mode for Google Docs web that shares the same colors and overall look to the Google Docs mobile app in dark mode, while following [Material 3 specs](https://m3.material.io). Dark Docs includes noticeable changes that update the full interface to Material 3; this was done for a more consistent appearance and so we don’t need to reference quite as much documentation with regards to colouring. 

Dark Docs only works with Google Docs for now. Expansion to Google Slides is [underway](https://github.com/winghongchan/dark-docs/blob/main/shades-and-slides.user.css). There are plans to expand to Google Sheets in the future. If you create such a project (with a similar intent to this project), you may submit a pull request to include a link to it here. 
