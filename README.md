# Dark Docs
A dark theme for Google Docs web, based on the colors used in dark modes in other Google products. Subtle animations added. 

![](Screenshot_20220723_183923.png)

## Installation

### Automatic

Install the theme at [Dark Docs on UserStyles.world](https://userstyles.world/style/2597/dark-docs). Doing this will make it easy to receive updates. 

If [Stylus](https://github.com/openstyles/stylus/) is installed on your browser,\
[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-238b8b.svg)](https://userstyles.world/api/style/2597.user.css)

<details>
<summary>
<h3>Manual</h3>
<p>Manual installation is not recommended, since you receive updates slower and you’ll need to run the Less preprocessor every time you update. 
</summary>

1. Use a browser extension that applies user CSS themes to webpages, such as [Stylus](https://github.com/openstyles/stylus/).
2. Use the [Less](https://lesscss.org/) preprocessor on all the stylesheets, or enable it in UserCSS. 
3. Apply the stylesheets: 
    - [Colors and animations](colors-animations.css) to URLs starting with `https://docs.google.com/document/d/`, `https://docs.google.com/document/u/`, `https://docs.google.com/sharing/driveshare`, `https://docs.google.com/sharing/boq/driveshare`, `https://docs.google.com/picker/v2/home?req=%5B%22ireq%22%2C%5Bnull%2C%5B%5B1%5D%2C%5B%5D%2C%5B%5D%2C%5B%5D%2C%5B2048%2C2048%5D%5D%2C%5B1%5D%2Cnull%2Cnull%2C%5`, and `https://docs.google.com/picker/v2/home?req=%5B%22ireq%22%2C%5Bnull%2C%5B%5B1%2C6%5D%2C%5B%5D%2C%5B%5D%2C%5B%5D%2C%5B2048%2C2048%5D%5D%2C%5B1%5D%2Cnull%2Cnull%2C%5B`
    - [Basic elements](basic-elements.css) to `https://docs.google.com/document/d/`, `https://docs.google.com/sharing/driveshare`, and `https://docs.google.com/document/u/`
    - [Homepage](homepage.css) to `https://docs.google.com/document/u/`
    - [Main editor](main-editor.css), [side panels](side-panels.css), and [other screens](other-screens.css) to `https://docs.google.com/document/d/`
    - [Share sheet](share-sheet.css) to `https://docs.google.com/sharing/boq/driveshare`. 
    - [Google Images picker](google-images-picker.css) to `https://docs.google.com/picker/v2/home?req=%5B%22ireq%22%2C%5Bnull%2C%5B%5B1%5D%2C%5B%5D%2C%5B%5D%2C%5B%5D%2C%5B2048%2C2048%5D%5D%2C%5B1%5D%2Cnull%2Cnull%2C%5`. If this doesn’t work for you, then you will need to look in dev tools and see where the iframe comes from. 
    - [Google Drive sidebar](google-drive-sidebar.css) to `https://docs.google.com/picker/v2/home?req=%5B%22ireq%22%2C%5Bnull%2C%5B%5B1%2C6%5D%2C%5B%5D%2C%5B%5D%2C%5B%5D%2C%5B2048%2C2048%5D%5D%2C%5B1%5D%2Cnull%2Cnull%2C%5B`. Like the Google Images picker, this side panel is an iframe so your link might be different. 
4. Assign values to these Less variables:
    - `@document-filter` should be a CSS filter that changes the appearance of the document. By default it is `var(--darkfilter)` which is equal to `invert(100%) hue-rotate(180deg) contrast(@document-contrast)`. 
    - `@document-contrast` should be a percentage value. By default it is `80%` which slightly reduces the contrast of the document. Reducing the value reduces contrast. 
    
</details>

Dark Docs only works with Google Docs. There are plans to make themes for Google Sheets and Slides in the far, far future. If you create such a project (with a similar intent to this project), you may submit a pull request to include a link to it here.

## Contributing
The intent is simple - to make a dark mode for Google Docs web that shares the same colors and overall look to the Google Docs mobile app in dark mode. 
