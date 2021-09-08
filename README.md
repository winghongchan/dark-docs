# Dark Docs
A dark theme for Google Docs web, based on the colors used in its mobile app. 

Some subtle animations added. 

## Usage
1. Use a browser extension that applies user CSS themes to webpages, such as [Stylus](https://github.com/openstyles/stylus/).
2. Apply the stylesheet to URLs starting with `https://docs.google.com/document/`. For now, I have only made the CSS to work with Google Docs, and not the other Workspace products. 

## Plans
These are in approximately the order that I want to work on them.
- **Scrollbars.** In Firefox, the Table of Contents scrollbar is white and I do need to change that (thankfully it auto-hides). In Chromium browsers, the scrollbar thumbs stand out too much on a dark background. 
- **Automatic theme changing.** This CSS will remain dark regardless of browser or computer settings, so it must be disabled manually in the browser extension settings. It may be handy for the theme to turn itself off when the device is in light mode.
- **Formatting.** The code is not very well laid out, and I want to improve this as the stylesheet expands.
- **Sheets and Slides.** I want to support them eventually, using their respective accent colors. 
