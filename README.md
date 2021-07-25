# gamepadviewer
Adds new assets for https://gamepadviewer.com/ (PS4)

Preview using default controller assets
1. Attach a PS4 controller (other controllers will provide partial functionality)
1. Go to https://gamepadviewer.com/
1. From the main header bar, select Player1 or appropriate input device from list. This may default to "None"
1. From the main header bar, select PlayStation 4 from the controller dropdown. This may default to "Xbox One"
1. Use your controller, entering different inputs to see actions appear on screen

Use repository's assets
1. From the main header bar, select the menu icon
1. Select the "Generate Url" link
1. Choose Player1 or appropriate input device from list
1. Choose PlayStation 4 for the Skin list
1. Enable Strength Meter (technically optional, but assets are designed for this mode)
1. Enter a hosted url for the Edit CSS URL. Point it to the custom.css file. This repo uses github pages [custom.css](https://cjh15hub.github.io/gamepadviewer/custom.css)
1. Adjust other settings if desired
1. Copy generated URL

With the copied URL
- You can preview the configured controller in any browser window
- Create a browser source in OBS, or other streaming platform. Use the copied URL as the source. [OBS Broswer Source](https://obsproject.com/wiki/Sources-Guide#browsersource)

Branch repo and edit
- This repo demonstrates the usage of the PS4 assets
- To create your own
  - update the assets to your liking. I have provided converted and cleaned up PSD's and the output PNG's as well as the original white PS4 SVGZ's
  - update the css background url's
  - host your files in a new location
  - update your Edit CSS URL on gamepadviewer to the location of your hosted custom.css file
  - refresh browser and/ or browser source if necessary
- Other Assets can be added for the other controller types!
  - Add new assets and update the custom.css file to include overrides for the backgrounds
  - Existing assets can be used as starting point, these can be found the in [sources tab](https://developer.chrome.com/docs/devtools/javascript/sources/) under a folder named the controller type / skin
  - Also in the sources you can find the style.css which contains rules to refrence the assets.
  - The rules are prefixed by the controller type / skin and are denoted in labeled sections of the css
  - Copy the selectors for the rules for the body and parts of the controller, then update the background: url(...) rule to point to your new assets.
  

Have Fun!
