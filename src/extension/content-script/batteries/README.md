#

## Battery

Battery refers to a directory in the code that collects JavaScript files for integrating Alby with different services or social media platforms. Each battery represents a specific integration point.

### E.g. 

The Reddit battery contains code that checks whether the current browser tab is on Reddit (by matching the URL) and if there is a lightning address in the Reddit profile description. 
The link provided  https://github.com/getAlby/lightning-browser-extension/blob/d2e6e2d6d145d5904519f6ca479a7cfc499422c9/src/extension/content-script/batteries/Reddit.ts
(loading order, and the fallback "Monetization" battery that checks for custom tags)

https://github.com/getAlby/lightning-browser-extension/blob/master/src/extension/content-script/batteries/index.ts

