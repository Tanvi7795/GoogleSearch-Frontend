# GoogleSearch-Frontend
## Front-end for Google Search, Google Image Search, and Google Advanced Search.

When you open this page in a browser, you should see a (very simple) HTML form. Type in a search query like “Harvard” and click “Google Search”, and you should be taken to Google’s search results page!

How did that work? In this case, the action attribute on the form told the browser that when the form is submitted, the data should be sent to https://www.google.com/search. And by adding an input field to the form whose name attribute was q, whatever the user types into that input field is included as a GET parameter in the URL.

## Specification

The website includes three pages: one for regular Google Search (which must be called index.html), one for Google Image Search, and one for Google Advanced Search.
- On the Google Search page, there are links in the upper-right of the page to go to Image Search or Advanced Search. On the Google Search page, the user should be able to type in a query, click “Google Search”, and be taken to the Google search results for that page. 
- On the Google Image Search page, the user should be able to type in a query, click a search button, and be taken to the Google Image search results for that page.
- On the Google Advanced Search page, the user should be able to provide input for the following four fields (taken from Google’s own advanced search options) <br/>
  * Find pages with… “all these words:” <br/>
  - Find pages with… “this exact word or phrase:” <br/>
  - Find pages with… “any of these words:” <br/>
  - Find pages with… “none of these words:” <br/>

## Sneak Peeks
### Google Search Page
![](sneakpeeks/index.gif)


### Google Image Search
![](sneakpeeks/images.gif)


### Google Advanced Search
![](sneakpeeks/advancedsearch.gif)




