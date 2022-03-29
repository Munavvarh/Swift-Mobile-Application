# Swift-Mobile-Application

Objective:

In this lab, we’ll create a zoo application that lands on a section page that allows us to select a type of animal which takes us to a list of breed examples of that type of animal.  

Follow the steps below to get started with the Zoo Swift Mobile Application:

1.	Create an XCode Project named Zoo

2.	Create 2 View Controllers

     a.	UIViewController  (this comes by default)
  
     b.	UITableViewController – this will need a code file

3.	Add some elements to your view controller

     a.	One Label – Name of your app
  
     b.	Two (or more) Images – These will be types of animals (Dogs, Cats, Birds, etc.)
  
     c.	Corresponding buttons under each image

4.	Connect all UI to code (Images / buttons)

5.	Connect buttons to action methods.  Each button should take the user to the table view controller which should display a list of the types of animals selected in the prior view

6.	Create classes to hold your animal data (image, breed, description)

7.	Create a segue transition that passes the selected animal type to the next VC

8.	Display a list of animals in a tableview.  Each row should have image, breed, description

9.	At the end, program should allow the user to click a button under each animal type and move to the list of animals as well as return back to the home page and make a different selection.
