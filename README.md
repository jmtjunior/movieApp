# Movie app. Web application for mobile. Version 1.0.0

Movie App powered by TMDB. Mobile App that shows upcoming movies and search movies by title.

Architecture based on https://docs.angularjs.org/guide/concepts#

 * index.html(template) => searchController.js(controller business UI logic) <=> movieService.js(service view reusable business logic) <=> Internet (https://api.themoviedb.org)

Dependencies
* Materialize (css)
* fonts.googleapis
* AngularJs
* jQuery (used by materialize components)

Website hosted at http://www.movieapp.dx.am/ for appreciation.

* Best seen on mobile.

Suggestions for further versions.
 * Apikey is hardcoded in this version. Best practice is to externalize it. 
 * Frontend improvements such as pagination buttons and results of upcoming movies to include poster and gender.
