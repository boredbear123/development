# Development

### Link to Deployed Website
If you used the stencil code, this is `https://<your GitHub username>.github.io/<name of your repository>`

### Goal and Value of the Application
  The goal of this application is to act as an online store for Air Jordans. It allows users to easily search through jordans by filtering based on price and release date, and sorting from low price to high price
### Usability Principles Considered
  
### Organization of Components
  I used two major components, one being the CheckedBox component to filter the sneaker items, and the other being SortButton to sort the sneakers by price. 
### How Data is Passed Down Through Components
  The CheckBox component adds and removes filters that are then applied to the sneaker data, so when you check the "$0-$500" box then the 0-500 price filter is then applied to the data, and these filters can be stacked on one another. Similiarly the SortButton alternates the sort algo applied to the sneaker data, by default it is set to random, and when you press the button the first time it switches the sort algo to an ascending (low to high price) sort which is then applied to the data. The sort and filters can build of one another. 
### How the User Triggers State Changes
  Users trigger state changes by, clicking button sor check boxes
  - checking a unchecked check box will apply that filter to the sneaker data 
  - unchecking a checked check box will remove that filter from the sneaker data 
  - clicking the sort by price button will sort the sneaker data by price
  - if you click the sort by price button again it will unsort the sneaker data
  - Add to cart button will add that sneaker to the cart 


