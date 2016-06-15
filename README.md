# \<input-grid\>

_**This element is still at an early stage and not ready for use yet**_

Generate input elements to append data in a grid and quickly get the value of the appended data

The idea is that an array with the required inputs is provided and for each input type the approperiate HTML element is rendered along with an "Add" button.

When the Add button is clicked, the entered values are inserted into an array called "data" that is also rendered as rows along with a remove button.

Public functions

* setInputs(), sets the inputs array from Javascript.
* getData(), Returns the data array

Events

* grid-ready, fires when the grid is rendered in the DOM and ready for use
* row-added, fires when the "Add" button is clicked and the data is inserted in the "data" array, it sends the object that has been inserted that can be accessed with "detail.row" (see demo file)
* row-removed, fires when an object is removed from the "data" array, when the "Remove" button is clicked.


####See the demo file for usage details.