# gamepadviewer
Adds new assets for https://gamepadviewer.com/ (PS4)

Preview using default controller assets
1. Attach a PS4 controller (other controllers will provide partial functionality)
1. Go to https://gamepadviewer.com/
1. From the main header bar, select Player1 or appropriate input device from list
1. From the main header bar, select PlayStation 4 from the controller dropdown
1. User hamburger menu


Use repository's assets on stream
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

Branch Repo and edit
- This repo demonstrates the usage of the PS4 assets
- To create your own
  - update the assets to your liking. I have provided converted and cleaned up PSD's and the output PNG's as well as the original white PS4 SVGZ's
  - update the css background url's
  - host your files in a new location
  - update your Edit CSS URL on gamepadviewer to the location of your hosted custom.css file
  - refresh browser and/ or browser source if necessary
  
  Have Fun!
