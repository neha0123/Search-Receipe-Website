# Forkify

Forkify is a vanilla JavaScript application that interacts with the food2fork API to fetch and display recipe food data. This app uses modern JavaScript tools, such as Webpack to bundle the modules, and Babel to convert ES6, ES7 and ES8 back to ES5. The user can search for a specific recipe, and add ingredients to a shopping list or save to a favourites list via local storage. I created a simple Express server in order to host the app via Heroku.

The app is deployed and available to use -

# Features Available
1.Query an ingredient to recieve a list of recipes containing that ingredient.
2.Easily bookmark or edit the servings of the selected recipe.
3.Create your own recipes and store them as user recipes.
4.Remove bookmarks or delete user recipes.
5.LocalStorage keeps the data when users exit the app.

## Added functionality to allow user to manually add ingredients to the shopping list, rather than adding the whole recipe at once.
I created checkboxes for each ingredient in the recipe. A seperate function was created to loop over the items and only add to list if box is checked.

## Clear Shopping List Button.
I added a clear shopping list button, allowing the user to clear the list completely, compared to deleting items one at a time.


## Save shopping list data in local storage.
When the page re-loads, the user's shopping list is restored, along with the likes list as well. 
