# Restaurant Ordering App


## About This App

This is an example frontend app that does the following:

* Loads menu items from the data.js file into the UI
- On clicking on a menu item it gets added to an order list and displayed in a new UI component for order summary.
- When the Complete Order Button is clicked a Pay Modal is loaded to enter your name, card number and security code.
- Finally the pay modal submits the data and an event listner handles the submit to hide the modal and order summary.

The main signifigance of this project is the following in the JavaScript code:

* An onclick event listener that handles all clicks of the document in a conditional branch.
* The onclick event listener uses the dataset to see if one of the menu buttons were clicked to add an item to the order based on item ID
* The onclick event listener also uses a dataset value for removing order items based on the item ID

