# Restaurant Roulette App
This app helps you pick a restaurant to eat when you are having trouble making a choice. It uses the Yelp Rest API to get choices based on your preferences and randomly selects one.

**Link to project:** https://restaurantroulette.onrender.com//


## How It's Made:

**Tech used:** HTML, CSS, EJS, Node.js, and Express

It runs on Node.js and Express in the backend and EJS to render the page. A user will enter a location either by zip code or city, state and then select preferences for a restaurant. After the user enters makes all their selections, it will randomly select a restaurant with information. It will give them the rating, picture, address, and a Yelp link to view more details.


## Lessons Learned:

I learned that the Yelp API does not provide the CORS headers necessary to use clientside JavaScript to directly make requests to the API. Also, the API doesn't allow more than 50 per request, but the API can return up to 1,000 results. You need to use the offset parameter to get the next page of results or the next 50 if you are using 50 as your limit.

## Other Projects:
Take a look at these other projects that I have in my own portfolio:

**Animo:** https://github.com/codingmypath/mvc-animo.git

**Peanut Gallery:** https://github.com/codingmypath/peanut-gallery.git

