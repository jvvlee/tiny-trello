### About

Tiny Trello is a very light-weight version of the popular project management software [Trello](http://trello.com). In Tiny Trello, there is only "Board", with many lists. This board is loaded by default each time you load the app, without any authentication or persistence.

### Details

If you're familiar with Trello, most of this should be pretty obvious. This is a very dumbed-down version, and the requirements are listed out below. There are also example wireframes in docs/wires.pdf which you might find helpful.

**IMPORTANT** You should implement this as an Ember.js app. If you haven't used Ember before, you may find it helpful to read through the Getting Started, and maybe work through the tutorial as well, available in the [Ember Guides](https://guides.emberjs.com).

* The default state of the app should be a board with one, empty list named "Default List"
* There is no authentication necessary, anyone visiting this app should automatically see the "Default List"
* There is no persistence. Reloading the app should reset to the default state
* A user can add item to the list by clicking the "Add an item" link at the bottom of the list (see the examples in docs/wires.pdf).
* A user can add a list by clicking the "Add a list" link to the right of the last board (see the examples in docs/wires.pdf).
* Clicking an item in a list opens a modal window with a "detail" view of the item that was clicked. This includes the title and a description. (see docs/wires.pdf)
* An item's Title and Description are editable in-line in the detail view described earlier
* Clicking "Close" from the detail view closes the detail view (see docs/wires.pdf)
* Clicking "Delete" from the detail view asks for confirmation and, if approved, deletes the item.
* It is *not* required to implement drag/drop for reordering items or lists.
