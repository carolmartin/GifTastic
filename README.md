# GifTastic
Gif Assignment
Buttons are loaded onto a page for various topics.

An input form is also available for a user to add another topic button to the list of buttons.

When the user clicks on a button for a specific topic, an API call is made to query api.giphy.com for 10 images.
The ten images are returned and displayed on the web site in a 'still' format with the rating listed.
When the user clicks on an image, it will toggle from 'still' to 'animated' or vis versa. 

An AJAX call is used to retrieve images. 

Buttons are rendered from an array of 'topics' and also created when add-topic button is selected from a form. 

Note the event.preventDefault() command is used to prevent the submit of the form from processing as the form will not be sending data to an external storage. 
