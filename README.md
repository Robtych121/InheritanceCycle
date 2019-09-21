# The Inheritance Cycle Website

This project is for the User Centric Frontend Development Milestone Project By Code Institute

This website was created to present inforation about the book series "The Inheritance Cycle" written by Chrisopher Paolini. It will display information on the main characters as well as brief look at the 4 books that make up the series.

You can view this website via this [link](https://robtych121.github.io/InheritanceCycle/)

## UX
This website was designed for fans of the "The Inheritance Cycle" by Chrisopher Paolini so i wanted to keep the look and feel of the website close to the books, for example the blue buttons is a similar colour to the main characters dragon in the story.

* As a fan of the series, I wanted to list the main characters separate to the stories themselves so that fans could see this quickly without having to click too many times.

I created some Wireframes of each page (showing both desktop and mobile view). These can be found within the Wireframes folder.

## Features
The website uses some custom javaScript to change the colour of the header after you have started scrolling. 
### Features Left to Implement
I would like to increase the amount of characters within the characters page and also provide a way of filtering the types (i.e show all human characters or show just dragon characters)

## Technologies Used
1. HTML
2. CSS
3. Bootstrap (v4.3.1)

## Testing
I have achieved the user story for the fan by providing the following for them:
* They are able to see the character information on the characters page with images, this also includes links to an external website with even more information
* They are able to see a brief summary of each book from the stories page and images
* The homepage is layed out with information of the author so that fans can see other works from the author.
* The homepage also includes links to Amazon so people can purchase these easily
 
All of the of the links have been tested manually and set to use the `target="_BLANK"` so that users won't be taken away from the website and can easily get back once they are done with the information.

The contact form has been tested to ensure that correct information is given. This was done on the email field. If you do not enter a valid email, it will show an error message and wont let you continue. If all fields are correct, no errors will be shown and an email will be sent.

The website structure has been tested mostly within Chrome Developer Tools but has also been tested on Google Chrome For Android, Microsoft Edge, Mozilla Firefox.

## Deployment
This website is hosted using the Github pages, using the master branch. Because of this, everytime i push across changes using Git, the website is automatically updated without any additional input from myself. When creating the website, i had to ensure that the main file for the website was index.html otherwise browsers wouldnt be able to load it properly.

If you wanted to run this locally, you can clone this repository directly into your editor by using the following command : `git clone https://github.com/Robtych121/InheritanceCycle.git` in the terminal. Once it has finished copying all the files you will need to run `git remote rm origin` so that any changes I make won't affect your local copy.

## Credits

#### Content
The content shown on this website was taken from the [Fandom Wiki](https://inheritance.fandom.com/wiki/) and edited for this website.

#### Media
Homepage Banner was found here : [image](https://wall.alphacoders.com/big.php?i=342383)

All images (such as book covers/characters etc) are from the [Fandom Wiki](https://inheritance.fandom.com/wiki/) and have been edited to site the website


#### Acknowledgements
The scroll effect used on the header(to make it go white when you scroll) was based off this Stack Overflow [post](https://stackoverflow.com/questions/23706003/changing-nav-bar-color-after-scrolling).