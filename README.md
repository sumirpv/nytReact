## nyt-react-search

This is a React-based rendition of the NYT article application created earlier in the program.

Create a new React-based rendition of the New York Times Article Search application from a previous assignment.

## This requires:

* creating React components
* working with helper functions
* utilizing the React mounting lifecycle to query and display * * articles based on user searches.
* using Node, Express and MongoDB so that users can save articles to read later.

## Instructions

* Create a MongoDB database called nytreact.
* Using mongoose, then create an Article schema and model
## Articles should have each of the following fields:

* title (Title of the stored article from nytimes.com)
* date (publish date and time of the article)
* url (URL of the article on nytimes.com)

## Create a Node/Express/MongoDB/ReactJS app called nytreact. Running this application will:

Create a Bootstrap layout similar.
This should be a SPA (Single Page Application) that uses react-router to navigate, hide and show React components without changing the route within Express.
## Express routes that are required for the app:

/api/saved (get) - components will use this to query MongoDB for all saved articles

/api/saved (post) - components will use this to save an article to the database

/api/saved (delete) - components will use this to delete a saved article in the database

* (get) - to load single HTML page (with ReactJS) in public/index.html. This route goes after ALL OTHER routes

