# Dark Docs
Material 3 dark mode for the Google Docs web app, based on the dark modes in other Google web apps. 

If [Stylus](https://add0n.com/stylus.html) is installed on your browser, <br>[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-238b8b.svg)](https://userstyles.world/api/style/2597.user.css)

![](https://raw.githubusercontent.com/winghongchan/dark-docs/main/Screenshot%202023-04-28%20at%2016-40-22%20Dark%20Docs.png)
Install, rate and view ratings: [Dark Docs on UserStyles.world](https://userstyles.world/style/2597/dark-docs)

<details>
  <summary>
    What happened to Shades & Slides?
  </summary>
  Unfortunately, Shades & Slides fell into a state of disrepair and I decided that maintaining three separate userstyles for similar web apps (Docs, Sheets, and Slides) would be too much work. 

  So, while I keep Dark Docs in a usable state, I’m working on [Dynamic Docs](https://github.com/winghongchan/dark-docs/blob/main/dynamic-docs.user.css). It’s a single userstyle that applies to Docs, Sheets, and Slides, and it’ll enable Material You–like theming. 

  That said, Shades & Slides is still available on this repository. [Get the Shades & Slides code here](https://github.com/winghongchan/dark-docs/blob/main/shades-and-slides.user.css). If the presenter view opens with a white sidebar and top bar, close presenter view and re-open it from the slideshow view’s mini toolbar in the bottom left.	
</details>

## Help & Support

If you face issues with Dark Docs, please report them on the [Issues](https://github.com/winghongchan/dark-docs/issues) page. 

### Note to users of Chromium-based browsers (such as Chrome, Edge, Vivaldi, &c.)
- By default, Dark Docs uses the Invert document filter so your document appears with an inverted colour scheme (light text on a dark background). If you must view images un-inverted, you may change the document filter to “Dim” or “None” in the [configuration dialog](https://github.com/openstyles/stylus/wiki/UserCSS#how-do-i-customize-usercss). 
For more info and another workaround to the photo bug, see [issue #8](https://github.com/winghongchan/dark-docs/issues/8).

## Contributing

There’s [Dark Docs](https://github.com/winghongchan/dark-docs/blob/main/dark-docs-m3.user.css) (a dark mode for Google Docs) and [Dynamic Docs](https://github.com/winghongchan/dark-docs/blob/main/dynamic-docs.user.css) (which enables Material You–like theming for Docs, Sheets, and Slides). I am working on both in parallel. 

The intent of Dark Docs is simple—to make a dark mode that is consistent with Google’s latest design, referencing [Material 3 specs](https://m3.material.io). Dark Docs also aims to update the full interface to Material 3; this is done for a more consistent appearance and so we only need to reference M3 standards, not M2 or Holo. 

Dynamic Docs aims to enable Material You–like colour theming on Docs, Sheets, and Slides. It is not currently ready to use. Once Dynamic Docs is tested and ready, I will move all Dark Docs users who installed from USw onto Dynamic Docs, where they’ll have the choice to keep the default Googley blues or use a new colour theme. 

Dark Docs and Dynamic Docs are both [UserCSS](https://github.com/openstyles/stylus/wiki/Writing-UserCSS) files and use the [{less}](https://lesscss.org/) preprocessor. I try to keep it as vanilla as possible though. 

> I don’t have a Google AI plan. If you do and are interested in contributing, you can help give the Gemini AI features a dark mode.

### AI

AI has not been used to write any code in this repository. Some AI tools may have been trained on code not compatible with the GNU GPLv3 license or would otherwise put Dynamic Docs, Dark Docs, and Shades & Slides into legal trouble. Don’t put AI-written code in this repository. 
