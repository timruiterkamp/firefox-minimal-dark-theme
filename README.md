# Firefox

Minimal dark theme for firefox

![The theme](https://github.com/timruiterkamp/firefox-minimal-dark-theme/blob/master/firefox-browser.png)
_On hover the icons of navigation and options appear_

## Setup

The first steps are going into the firefox browser and typing: `about:profiles` in the url bar. This will take you to an overview of your profiles.
Here you select the root directory and open it in your filesystem (open in finder for example).

### Next steps

- Create a folder named `chrome`.
- Drop the file named `userChrome.css` from this repository inside the chrome map.
- Restart your browser and enjoy

### Customization

- To customize the file from the browser, you have to turn on the live editing mode. To do this you press `cmd + shift + i` or `ctrl + shift + i` to open the element inspector and then click on the three dots on the right(in the top bar) and choose settings.
- Scroll down in the settings till you reach `advanced settings` and turn on the last two options (debugging toolboxes and remote debugging)
- Now you can customize the file live from the browser when hitting `cmd + alt + shit + i` or on windows: `ctrl + alt + shift + i`.
- Go to the style editor and search for the userChrome.css file and start editing.
- The inspector works like normal and you can just lookup every element on the page.
- For inspiration visit: [The reddit page](https://www.reddit.com/r/FirefoxCSS/)
