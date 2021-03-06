# TV Browser

Use the [TV Maze API docs](http://www.tvmaze.com/api) to build a single-page app that allows a user to search TV shows. The documentation lists the various **endpoints** that the TV Maze development team has made available. Identify which endpoint(s) would most useful for your TV show searching app. Try clicking on the URL examples for each endpoint to see the structure of the JSON data at that endpoint. Each of the API's endpoints may have differently structured JSON responses.

When testing out the API's endpoint URLs, you will want to install [JSON Formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?hl=en) to make the JSON responses more readable.

## MVP
Use the input to get the search term from the user. Display the results in the dom.

## Further
When you get the results, fill in the select element with an option element for each result

## Further
Attach an event listener to the select. When the user selects an option make another AJAX call. Use the response of that AJAX call to render the individual show they requested


## Full App

 1. Make the selector field (CSS selector `"#show-select"`) hidden by default.

 2. After the user submits a search for a TV show...
  - un-hide the `"#show-select"` field.
  - populate the `"#show-select"` field with the list of search results. (create option tags in the select for each result you get)
  - make the first / default select option read "Shows matching `keyword`…".

 3. Whenever the user selects a title from the `#show-select` field (HINT: listen for a `"change"` event), display that show's name and image in the `"#show-detail"` div.

## Take a look:

http://ga-wdi-exercises.github.io/tv-browser/
