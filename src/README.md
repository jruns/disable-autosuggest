# disable-autosuggest
This is a browser extension to disable autosuggest and autocomplete features on various sites and search engines. You know what you want to search for, so don't get distracted by suggestions. This extension also disables trending topics when they are displayed in search input boxes.

## Search Engine Support

### DuckDuckGo
We disable DuckDuckGo's autocomplete/autosuggest feature by adding the `kac=-1` url parameter to all DuckDuckGo search URLs. We also block the DuckDUckGo autocomplete endpoint.

### Google
We disable Google's autocomplete/autosuggest feature on Google search pages. We also block the Google search autocomplete endpoint.