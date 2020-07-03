# Startpage.com Search — Themed

Themed [startpage.com](https://www.startpage.com/) search engine definitions to Firefox.

Needed because in Private Mode, cookies can't be remembered, so the search engine will always use the default theme, unless the theme is set via URL query parameters.

Uses the [chrome_settings_overrides](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/chrome_settings_overrides) manifest key). Submits the query via GET request for compatibility with [Multi-Account Containers](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/). Compared with the [official extension](https://addons.mozilla.org/en/firefox/addon/startpage-private-search/), these ones activates the the "dark mode" themes.

Comes in multiple flavors ...

- Black
- Dark
- Night

## Develop Locally

* Clone the repo
* Install tools:
	* [Node.js](https://nodejs.org)
	* [nvm](https://github.com/nvm-sh/nvm)
* Use specified Node version:
	* `nvm use`
* Install dependencies:
	* `npm i`
* Package for distribution:
	* `npm run bundle`
