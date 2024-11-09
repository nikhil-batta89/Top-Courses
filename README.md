Top-Courses

Steps


Navbar Component
First, you need to create a Navbar component to display the main title of app. This component can be a simple function that returns a heading element with the app title.

Explore and Import Data
Import the Cards data from data.js into your project. This data should be an array of objects, with each object representing a Cards and containing properties such as title, price, image URL, and description.

State Value
Set up the menu items data as a state variable in the App.jsx component using the useState hook. This will allow you to modify the data and have those changes automatically reflected in the rendered output.

Render Items
Pass the menu items state value down to the Menu.jsx component. In the Menu component, iterate over the list of menu items using the map method, and for every item, render a MenuItem component.

In the Cards component, render an image element, a title, a price, and a description. You can use the data from the Cards items array to fill in the information for each component.

Unique Categories
In the App.jsx component, set up functionality to get only the unique categories from the Cards data and store them in a separate array. Add an "all" category to this array to display all Cards . 

State Value and Render Categories
Set up the categories array as a state variable in the App.jsx component using the useState hook. This will allow you to modify the data and have those changes automatically reflected in the rendered output.

Create a Categories component and pass the categories state value down to this component. In the Categories component, iterate over the categories array and render buttons for each category.

Filter Functionality
Set up filter functionality where once the user clicks on the button, only the menu items that belong to the selected category are displayed. To do this, define a function that takes a category as a parameter and updates the state to show only the menu items that belong to that category. You can then pass this function down to the Filter component as a prop, and attach it to the buttons.

When the user clicks on a category button, the filter function should be called with the selected category as a parameter. The function should then update the state to show only the Cards that belong to the selected category.


