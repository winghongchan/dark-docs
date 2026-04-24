# Dark Docs
Googley dark mode for the Google Docs web app, based on the dark modes in other Google web apps. 

If [Stylus](https://add0n.com/stylus.html) is installed on your browser, <br>[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-238b8b.svg)](https://userstyles.world/api/style/2597.user.css)
![](https://raw.githubusercontent.com/winghongchan/dark-docs/main/Screenshot%202023-04-28%20at%2016-40-22%20Dark%20Docs.png)
Install, rate and view ratings: <br>[Dark Docs on UserStyles.world](https://userstyles.world/style/2597/dark-docs)

<details>
  <summary>
    What happened to Shades & Slides?
  </summary>
  Unfortunately, Shades & Slides fell into a state of disrepair and I decided that maintaining three separate userstyles for similar web apps (Docs, Sheets, and Slides) would be too much work. 

  So, while I keep Dark Docs in a usable state, I’m working on **Dynamic Docs**. It’s a single userstyle that applies to Docs, Sheets, and Slides, and it’ll enable Material You–like theming. 

  That said, the Shades & Slides is still available on this repository. [Get the Shades & Slides code here](https://github.com/winghongchan/dark-docs/blob/main/shades-and-slides.user.css). If the presenter view opens with a white sidebar and top bar, close presenter view and re-open it from the slideshow view’s mini toolbar in the bottom left.	
</details>

## Browser-specific notes

### Chromium-based (including Chrome, Edge, Vivaldi, &c.) users
- By default, Dark Docs uses the Invert document filter so your document appears with an inverted colour scheme (approximately white on black). If you must view images un-inverted, you may change the document filter to “Dim” or “None” in the [configuration dialog](https://github.com/openstyles/stylus/wiki/UserCSS#how-do-i-customize-usercss). 
For more info and another workaround to the photo bug, see [issue #8](https://github.com/winghongchan/dark-docs/issues/8).

## Contributing

Dark Docs is written as a [UserCSS](https://github.com/openstyles/stylus/wiki/Writing-UserCSS) file and uses the [{less}](https://lesscss.org/) preprocessor. I try to keep it as vanilla as possible though.  

> Extra help is needed to make a dark mode for Google’s Gemini AI features, since I don’t have a Google AI plan. 

The intent is simple—to make a dark mode that is consistent with Google’s latest design, referencing [Material 3 specs](https://m3.material.io). Dark Docs also aims to update the full interface to Material 3; this was done for a more consistent appearance and so we only need to reference M3 standards, not M2 or Holo. 

The previous plan was to make an “M3 Themer for Google Sheets” and rebase Dark Docs and Shades & Slides on to that, but the new plan is to just make Dynamic Docs (which will work on Docs, Sheets, and Slides). 

### AI

AI has not been used to develop Dark Docs and Shades & Slides. Some AI tools may have been trained on code not compatible with the GNU GPLv3 license or would otherwise put Dark Docs and Shades & Slides into legal trouble. Don’t use AI-written code on this project. 
