# Libraries used

## Extjs ecosystem
| Name | Category | Description | More informations |
|:-----------|:------------|:------------|:------------|
| ExtJS      | Framework| JavaScript framework for building data-intensive, cross-platform web and mobile applications for any modern device.   | https://docs.sencha.com/extjs/7.0.0/index.html  |
| ColorPicker | Extjs Extensions  | Picking and select color   | https://github.com/Simonwep/pickr  |
| ActivityMonitor   | Extjs Extensions   | Watching the browser's BODY element for mouse movement and keystrokes   | https://github.com/Arhia/ExtJS-ActivityMonitor   |
| Printer   | Extjs Extensions   | Printing Ext Grid Component   | https://github.com/Arhia/Ext.ux.grid.Printer   |
| Multisearch  | Extjs Extensions   | Adding a row of configurable form fields below the grid header where the filter values can be typed or selected.   | https://learnfromsaki.com/software/ext-grid-multisearch-plugin/   |

## Others 

| Name   | Category   | Description  | More informations  | Version installed  |
|:-----------|:------------|:------------|:------------|:------------|
| ace editor    | Production  | Standalone code editor written in JavaScript   | https://github.com/ajaxorg/ace   |
| async   | Production  | Async is a utility module which provides functions for working with asynchronous JavaScript    | https://github.com/caolan/async   | 2.6.0   |
| font awesome   | Production   | Get vector icons and social logos  | https://fontawesome.com/how-to-use/on-the-web/referencing-icons/basic-use   | 4.7.0   |
| filesaver   | Production   | Solution to saving files on the client-side   | https://github.com/eligrey/FileSaver.js/   |  1.3.3   |
| highcharts   | Production   | Charting library based on SVG, with fallbacks to VML and canvas for old browsers   | https://github.com/highcharts/highcharts   | 2.6.0   |
| iban   | Production   | IBAN and BBAN validation, formatting and conversion in Javascript   | https://github.com/arhs/iban.js/   | 0.0.10   |
| jquery   | Production   | JavaScript library created to facilitate writing client-side scripts in web page HTML   | https://api.jquery.com/  | 3.1.1   |
| jszip   | Production   | Javascript library for creating, reading and editing .zip files   | https://stuk.github.io/jszip/   | 3.1.3   |
| lodash   | Production   |JavaScript utility library delivering modularity   | https://lodash.com/docs/4.17.15   | 4.17.5   |
| momentjs   | Production   | Parse, validate, manipulate, and display dates and times in JavaScript.   | https://momentjs.com/docs/   | 2.22.1   |
| platform   | Production   | Platform detection library   | https://github.com/bestiejs/platform.js/   | 1.3.5
| sentry  | Production   | Javascript Error Tracking   | https://docs.sentry.io/   | 4.3.4   |
| showdown   | Production   | Javascript Markdown to HTML converter   | https://github.com/showdownjs/showdown   | 1.9.1   |
| toastr   | Production   | Javascript library for non-blocking notifications   | https://github.com/CodeSeven/toastr   | 2.1.3   |
| uuid   | Production   | Generate RFC-compliant UUIDs in JavaScript    | https://github.com/uuidjs/uuid   | 3.1.0   |
| core-js  | Production(Polyfills)   | JS Library including polyfills for ECMAScript up to 2020  | https://github.com/zloirock/core-js   | 2.5.3  |
| promise-polyfill   | Production(Polyfills)   | ES6 Promise polyfill for the browser and node   | https://github.com/taylorhakes/promise-polyfill   | 7.1.2   |
| url-search-params-polyfill   | Production(Polyfills)   | Polyfill for URLSearchParams   | https://github.com/WebReflection/url-search-params   | 3.0.0   |
| chai   | Development  | Chai is a BDD / TDD assertion library   | https://github.com/chaijs/chai   | 4.1.2  |   

# Update libraries

1. Go to the editor site and download the version you would like to upgrade
2. Put the file on the corresponding folder in the /client/libs/*nameofmylibrary*
3. Replace the name of the previous file by the new one on corresponding lines (250 to 276) of concat.js