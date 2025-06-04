# disable-autosuggest
This is a browser extension to disable autosuggest and autocomplete features on various sites and search engines. You know what you want to search for, so don't get distracted by suggestions. This extension also disables trending topics when they are displayed in search input boxes.

**Search Engines Supported:**  
DuckDuckGo, Google

## How to Install
- Firefox and Firefox for Android: link coming soon
- Chrome Web Store: link coming soon  

## How it Works

### DuckDuckGo
We disable DuckDuckGo's autocomplete/autosuggest feature by adding the `kac=-1` url parameter to all DuckDuckGo search URLs.

### Google
We disable Google's autocomplete/autosuggest feature on Google search pages.

## Firefox Installation instructions
1. Download a release xpi file from this github repo
2. Go to `about:addons`
3. Click the gear icon next to the "Manage Your Extensions" heading
4. Select "Install Add-on From File..." and select the release file you downloaded
5. Pin the extension to the Toolbar

## Chrome Installation instructions
1. Download the `src` folder from this github repo
2. Go to `chrome://extensions/`
3. Activate "Developer mode"
4. Click the "Load unpacked" button
5. Select the `src` folder you saved locally
6. Pin the extension to the Toolbar

## Coming Soon
1. Support for the Chrome browser.
2. Add International support
3. Disable AI results in more search engines.
4. Ability to run the extension in mobile browsers.
5. Allow optionally disabling auto-suggest dropdowns to reduce resource utilization.
6. Make disabling non-AI instant answers optional where possible.