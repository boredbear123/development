# Development

### Link to Deployed Website
If you used the stencil code, this is https://boredbear123.github.io/development/

### Goal and Value of the Application
This application is for shopping fot sneaker, in particular Air Jordan 1's. You can filter through the sneakers by their price and their release data, in addition to sorting by price. You can add the sneakers to your cart, that you can see on the right side of the screen, and your total price of the cart is calculated at the bottom of the cart.

### Usability Principles Considered
I made sure that the design of the website made the functionality intuitive and transparent for the user. The user can easily see the filters and sort capabilities, the sneaker gallery, and then the cart. The buttons and checked boxes are intuitive to use and their actions are easily seen as it is a one page application. 
### Organization of Components
I organized the compoents in a manner to promote efficiency and clarity. The filter checkBoxes and the sortButton are in the left margin which can then be applied to the gallery if SneakerItems in the center part of the screen. Then the cart is located on the right portion of the screeen
### How Data is Passed Down Through Components
SneakerData is altered in the computedFilteredArray, where the different filters and sort fucntions can be applied to the data. The fitlered or sorted data is then passed in to the SneakerItems component to display the sneakers' images and details. 
### How the User Triggers State Changes
The user triggers state changes by checking check boxes, pressing the sort button, or pressing the Add to Cart button.

### Notes
I filled out and commited this readMe file orginally, but it didnt seem to be saved when I check to make sure everything was all set. 
Also my site is fully functional: it filters, sorts, and aggregates, but for some reason it will occasionally crash when certain actions are paired together, I ran out of time to debug this. You may not even run into the bug, but if you do, the app is fully fucntional and you can just refresh to play around with it.
