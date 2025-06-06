# disable-autosuggest
This is a browser extension to disable autosuggest and autocomplete features on various sites and search engines. You know what you want to search for, so don't get distracted by suggestions. This extension also disables trending topics when they are displayed in search input boxes.

**Search Engines Supported:**  
Bing, Brave Search, DuckDuckGo, Google, Startpage, Yahoo

## How to Install
- Firefox and Firefox for Android: link coming soon
- Chrome Web Store: link coming soon  

## How it Works

### Bing
We disable the autocomplete/autosuggest feature by blocking the autocomplete endpoint.

### Brave Search
We disable the autocomplete/autosuggest feature by blocking the autocomplete endpoint.

### DuckDuckGo
We disable the autocomplete/autosuggest feature by blocking the autocomplete endpoint.

### Google
We disable the autocomplete/autosuggest feature on Google search pages by blocking the search autocomplete endpoint. We also modify the CSS of the search box to round out the input box without the suggestions.

### Startpage
We disable the autocomplete/autosuggest feature by blocking the autocomplete endpoint.

### Yahoo
We disable the autocomplete/autosuggest feature by blocking the autocomplete endpoint.

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

## Development Env
Requires web-ext  
`npm install --global web-ext`