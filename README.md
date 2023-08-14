# Dark Docs | Shades & Slides
Matching dark themes for the Google Docs and Slides web apps, based on the appearance of dark modes in other Google products. 

| Dark Docs | Shades & Slides |
|:-:|:-:|
| If [Stylus](https://add0n.com/stylus.html) is installed on your browser, <br>[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-238b8b.svg)](https://userstyles.world/api/style/2597.user.css) | If [Stylus](https://add0n.com/stylus.html) is installed on your browser, <br>[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-238b8b.svg)](https://userstyles.world/api/style/11559.user.css) |
| ![](https://raw.githubusercontent.com/winghongchan/dark-docs/main/Screenshot%202023-04-28%20at%2016-40-22%20Dark%20Docs.png) | ![](https://github.com/winghongchan/dark-docs/blob/e0968ec55cfa89e2c00b52f01d905a5c2dde065e/2023-08-14%2018.26.43%20docs.google.com%20b08defbb432b.png) |
| Install, rate and view ratings: <br>[Dark Docs on UserStyles.world](https://userstyles.world/style/2597/dark-docs) | Install, rate and view ratings: <br>[Shades & Slides on UserStyles.world](https://userstyles.world/style/11559) |

## Browser-specific notes
### Firefox and derivatives
Dark Docs uses the newer `:has()` selector for hard-to-fix things. Support for it in Firefox is currently in development, but you can enable support for it by setting the layout.css.has-selector.enabled preference to true. Follow along with Mozilla’s work on this at [Bugzilla](https://bugzilla.mozilla.org/show_bug.cgi?id=418039). 

Chromium-based browsers have full support of the `:has()` selector. 

### Chromium-based (including Chrome, Edge, Vivaldi, &c.) users
- By default, Dark Docs uses the Invert document filter so your document appears with an inverted colour scheme (approximately white on black). If you must view images un-inverted, you may change the document filter to “Dim” or “None” in the [configuration dialog](https://github.com/openstyles/stylus/wiki/UserCSS#how-do-i-customize-usercss). 
For more info and another workaround to the photo bug, see [issue #8](https://github.com/winghongchan/dark-docs/issues/8).

- If the presenter view opens with a white sidebar and top bar, close presenter view and re-open it from the slideshow view’s mini toolbar in the bottom left.	

## Contributing

Dark Docs and Shades & Slides are written as [UserCSS](https://github.com/openstyles/stylus/wiki/Writing-UserCSS) files and both use the [{less}](https://lesscss.org/) preprocessor. However, they are developed separately so code that works in one might not immediately work in the other. After I complete M3 Themes for Google Sheets (that’s right, I’m being even more ambitious with Google Sheets and plan to make it themable), I will re-base all three and make them all themable. 

The intent is simple—to make a dark mode that is consistent with Google’s latest design, referencing [Material 3 specs](https://m3.material.io). Dark Docs and Shades & Slides include noticeable changes that update the full interface to Material 3; this was done for a more consistent appearance and so we don’t need to reference quite as much documentation with regards to colouring. 

If you created a Googley dark mode for Google Sheets, you may submit a pull request to include a link to it here. 

### AI

AI has not been used to develop Dark Docs and Shades & Slides. Some AI tools may have been trained on code not compatible with the GNU GPLv3 license or would otherwise put Dark Docs and Shades & Slides into legal trouble. If you use an AI tool to write a contribution, please provide primary and secondary sources to prove to the other contributors that your AI tool is safe to use for a project licensed under the GNU GPLv3. Or just play it safe and don’t use AI here. 
