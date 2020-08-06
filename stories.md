# Cardio User Stories

This document assumes some familiarity with Trello's features. It's recommended that you spend a little time using https://trello.com/ before beginning.

## Major Features

1. User Registration and Login
1. View, Create, Edit, Archive and Unarchive Boards
1. View, Create, Edit and Remove Lists on a Board
1. View, Create, Edit and Remove Cards on a List
1. Reorder Lists on a Board
1. Reorder Cards on a List
1. Manage Labels on a Card
1. Make Boards publicly available or private to the user who created them
1. Searching Boards, Lists and Cards

## Stories

As a potential Cardio user, I would like to create an account so that I can login and use Cardio.

---

As a Cardio user, I would like to login to Cardio, so that I can use its features.

---

As a Cardio user, I would like to view a list of my active (not archived) Boards in reverse order of date created, so that I can easily find my most recent boards.

---

As a Cardio user, I would like to Create a new Board with a Title so that I can add manage Lists and Cards for a particular purpose.

> **NOTE:** By default a Board should only be Viewable by its creator. Future stories will provide a "Publish" feature.

---

As a Cardio user, I would like to Edit a Board's title, so that I can correct any mistakes or make the title better describe the Board's purpose.

---

As a Cardio user, I would like to Archive a Board that I no longer wish to use, so that I can focus on the Boards that I am actively using.

> **NOTE:** An archived board should not be deleted, but should be marked as inactive.

---

As a Cardio user, I would like to View all my Archived Boards, so that I can unarchive them when I need to.

> **NOTE:** There should be link or button on the main Board List that, when clicked, will show the user their Archived Boards.

---

As a Cardio user, I would like to unarchive a Board that is currently Archived, so that I can begin using it again.

---

As a Cardio user, I would like to View the Lists on a Board, so that I can see the content of a Board.

> **NOTE:** Lists should be displayed as columns on the screen ordered left to right. When there are more lists than can be shown at one time, the page should allow the user to scroll horizontally.

---

As a Cardio user, I would like to add Lists to a Board, so that I will have places to add and arrange Cards.

> **NOTE:** A List should have a Title and an Position in the Board. The "Position" should determine what order the List is displayed. For example, a List with Position `2` should be displayed as the second column from the left of the Board.

---

As a Cardio user, I would like to Edit the Title of a List, so that I can correct any mistakes or make the Title better describe the List's purpose.

---

As a Cardio user, I would like to use my mouse to drag a List left or right, so that I can reposition it on the board.

---

As a Cardio user, I would like to View all Cards in each List on a selected Board, so that I can efficiently see the information I've added to the Board.

> **NOTE:** Cards should appear in a Vertical column within a List with one Card above another. A Card's "Position" should determine its location in the List with lower numbers being closer to the top.  
> Each Card should display its text Content.

---

As a Cardio user, I would like to add a Card to a List, so that I can add a specific item to the more general-purpose List.

> **NOTE:** For now a Card should only contain free-form text Content and a Position in the List.

---

As a Cardio user, I would like to Edit the Content on a Card, so that I can correct mistakes or improve the wording of the Card's text.

---

As a Cardio user, I would like to Remove a Card from a List, so that I don't have to see Cards that are no longer important to me.

> **NOTE:** Cards should be removed from the database and not archived.

---

As a Cardio user, I would like to Remove a List, so that I can clear away a List that is no longer needed.

> **NOTE:** Removing a List should remove any Cards that are on the List.  
> Lists should be removed from the database and not archived.

---

As a Cardio user, I would like to use my mouse to drag a Card up and down a List, so that I can reposition it.

> **NOTE:** An example use of this feature is prioritizing cards on a list.

---

As a Cardio user, I would like to use my mouse to drag a Card from one List to another, so that I can move Cards to a more appropriate list.

> **NOTE:** An example use of this feature is moving a card from a "ToDo" to "Doing" List.

---

As a Cardio user, I would like to Add a Label to a Card, so that I can better keep track of related Cards.

> **NOTE:**
>
> - Labels should consist of a short Title and a Color.
> - Initially Labels should come from a "lookup" table in the database and should not be alterable by users.
> - Label Management is a good candidate for a future feature.

---

As a Cardio user, I would like to see any Labels associated with a Card appear below the text Content of the Card, so that I can easily spot Cards with the same Label.

---

As a Cardio user, I would like to Remove a Label from a Card, so that I can un-associate a Card with the particular term a Label represents.

---

As a Cardio user, I would like to Publish a Board, so that I can share my Board with anyone on the Internet.

> **NOTE:** A Published Board should be visible to both authenticated and unauthenticated users. A user does not need an account to see a Published Board.

---

As a Cardio user, I would like to Un-publish a Board, so that I can hide a Board from publish view.

---

As a Cardio user, I would like to Search my Boards with a simple text search field, so that I can quickly find a Board I'm looking for.

> **NOTE:**  
> The Search feature should:
> * Match search words against Board Titles, List Titles, Card Content and Card Labels
> * Perform a case-insensitive search
> * Allow multiple words to be entered
> * Require ALL words to be present for a successful match
> * Search each word individually. For example, the search term `Hello World` should match a Card that whose content is `Hello there, world!`
> * Return a list of Boards that contain the search term. Clicking on an element in the list should take the user to that Board

---

## Ideas for Additional Features

1. More information to a Card
    1. A larger "description" text field
    1. Clickable hyperlinks
    1. A "To-Do" checklist
    1. A due date
1. Move Lists and Cards from one Board to another
1. Allow multiple users to collaborate on a single Board.
1. Publish a Board to particular users, so that only they can see it
