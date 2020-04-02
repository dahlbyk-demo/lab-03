# lab-03
Templating and Flexbox

User Acceptance Tests
- add pagination to your image gallery.
- refactoring your photo gallery in two ways: you will use Mustache for templating and you will use Flexbox for styling.
- the ability for the user to sort the images


# Feature 1: Pagination
- As a user, I want to have the ability to view additional images so that my view does not become cluttered.
- Given that a user opens the application in the browser When the user clicks on a button or link to another page Then the other set of images should be dynamically displayed

## Implementation
- Add navigation for the user to switch between two pages. Each page should render a unique set of images from one of the two provided JSON files.
- Reset the filters, then repopulate them using only keywords from the images currently being displayed.


## Time Estimate
- Number and name of feature: Pagination
- Estimate of time needed to complete: 3 hours
- Start time: 9:45
- Finish time: 
- Actual time needed to complete: 


# Feature 2: Templating
- As a user, I want all of the images to be displayed in a consistent manner, so that it is easy to scan the collection of images.
- Given that a user opens the application in the browser When the images are displayed on the screen Then each image should be rendered according to a template

## Implementation
Create the appropriate Mustache template in your HTML with the same <h2>, <img>, and <p> elements as the jQuery template from the prior lab.
Refactor the method that renders your images to use Mustache instead of making a copy with jQuery.

## Time Estimate
- Number and name of feature: Templating
- Estimate of time needed to complete: 2 hours
- Start time: 
- Finish time: 
- Actual time needed to complete: 

# Feature 3: Styling with Flexbox
- As a user, I want a simple, clean looking UI so that my photo gallery clearly displays the images.
- Given that a user opens the application in the browser When the user navigates to the home page Then the images should be displayed in columns, as screen width allows

## Implementation
Refactor your CSS to use Flexbox instead of floats. You are welcome to use a combination of floats and Flexbox, as you see fit.

# Time Estimate
- Number and name of feature: Styling with Flexbox
- Estimate of time needed to complete: 1 hour
- Start time: 
- Finish time: 
- Actual time needed to complete: 

# Feature 4: Sort the images
- As a user, I want to be able to sort the images so that there is an order to their rendering.
- Given that a user is presented with sort options When the user clicks on one option Then the images should be sorted accordingly

## Implementation
- Add the ability for the user to sort the images by either title or by number of horns.
- Sort the images by one of the properties on page load. This should also apply to the second page of images.

# Time Estimate
- Number and name of feature: Sort the images
- Estimate of time needed to complete: 1 hour
- Start time: 
- Finish time: 
- Actual time needed to complete: 

# Stretch Goal: Detail view
- As a user, I want the image to be displayed in a larger size and with the description shown so that I can view the details of a single image.
- Given that a user wants to view the details of the image When the user clicks on an individual image Then the image should render larger on the screen with the description displayed

## Implementation
- Add a detail view which will display the image in a larger size in the center of the screen with a colored background.
The description should be shown now, as well.
- When the user clicks off of the image, return to the grid view.
- Use a transition or animation to show and hide the detail view of an image.

# Stretch Goal: Fuzzy search
- As a user, I want the ability to search my images so that I can view only the images containing specific titles or keywords.
- Given that a user enters wants to view specific images When the user enters a character into the search field Then only the images matching the current set of characters should be displayed on the screen

## Implementation
- Create an input element to allow users to search for an image. It is up to you and your partner to decide if the user should be able to search by title, keyword, or both.
- Write a regular expression pattern to create a fuzzy search so that the results are narrowed down and displayed every time the user enters or removes a character from the input.