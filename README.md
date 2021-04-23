### NOTE: This theme works best on the "old" design of Joplin. It has not been integrated with the new design launched Fall 2020.

---
## joplin theme
# dark mode

based off of https://github.com/amandamcg/joplin-theme

a dark mode theme for Joplin.

Joplin is an open source note taking app. Learn more about [Joplin](http://joplinapp.org).

It has been tested on Mac version Joplin Joplin 1.0.232 (prod, darwin)


## 1. Install Font

This theme assumes you have IBM Plex Sans and IBM Plex Mono installed on your computer.

Install those from [https://github.com/IBM/plex](https://github.com/IBM/plex) or change the following lines in the `:root` section of  `userstyle.css` and `userchrome.css` to your favorite font:
```
--font-sans: "IBM Plex Sans";
--font-mono: "IBM Plex Mono";
```

## 2. Install Theme
- Open the Joplin app
- Navigate to  `Joplin > Preferences > Appearances`
- Click `Advanced Settings`
- Click `Custom stylesheet for rendered Markdown` and paste the content from `userstyle.css`
- Edit `Custom stylesheet for Joplin-wide app styles` and paste the content from `userchrome.css`


### Apply Changes
The css changes won't apply until you close and reopen the app.

HINT: If you are using Dev Tools to mess with CSS `Help > Toggle Developer tools`, you can hit `Command-R` (Mac) to Force Reload the app to apply the CSS without having to quit.

## 3. Check to see how it looks.
You can paste `css-sample.md` into a new Joplin note to see it in action.

- Make sure to select the "Dark" Theme in `Joplin > Preferences > Appearances`
- Editor font size is set to 14

![joplin-appearance-settings.png](/img/joplin-appearance-settings.png)

- HINT: I often have to force quit and restart the app after applying CSS changes and switching notes, not sure why.

## 4. Tweak the variables
Lots of this theme is defined in the `:root` section of  `userstyle.css` and `userchrome.css`. You can update colors and sizing there. Make sure to update the variables in both files!

```
:root {
    --white: #e3e3e3;
    --dark-white: #EEF0EA;
    --light-grey: #A3A79F;
    --grey: #575856;
    --dark-grey: #272728;
    --darker-grey: #1D2024;
    --black: #131517;
    --base-size-1: 1px;
    --base-size-4: 4px;
    --base-size-8: 8px;
    --base-size-10: 10px;
    --base-size-13: 13px;
    --base-size-18: 18px;
    --base-size-24: 24px;
    --base-size-32: 32px;
    --base-size-40: 40px;
    --base-size-272: 272px;
    --z-toc: 99;
    --font-weight-light: 200;
    --font-weight-base: 400;
    --font-weight-bold: 500;
    --font-sans: "IBM Plex Sans";
    --font-mono: "IBM Plex Mono";
    --primary: #0097DB;
    --secondary: #005378;
    --font-line-height: 1.4em;
    --font-size: var(--base-size-13);
    --icon-size: var(--font-size);
}
```



## Delete Theme
- Open the Joplin app
- Navigate to  `Joplin > Preferences > Appearances`
- Click `Advanced Settings`
- Click `Custom stylesheet for rendered Markdown` and delete all the CSS
- Edit `Custom stylesheet for Joplin-wide app styles` and delete all the CSS

## Want to see more themes and talk about Joplin CSS?
Visit https://discourse.joplinapp.org/t/share-your-css/1730/56

