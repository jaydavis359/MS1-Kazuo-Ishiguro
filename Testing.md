# Testing

* All HTML code verified through [W3C HTML Validation Service](https://validator.w3.org/).
HTML Code was run through this validator, and no issues were found.
* All CSS code verified through [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/).
CSS code was run through this validator and no issues were found.
* Basic responsiveness checked through [Am I Responsive?](http://ami.responsivedesign.is/).
* [Chrome developer tools](https://developers.google.com/web/tools/chrome-devtools) - was in constant use throughout the 
project to check responsiveness and to check formatting, margins, font size etc. on the fly.

## User Stories Testing

* 'As a visitor to the website, I want the navagation to be instantly Understandable.' 
This I think has been achieved succesfully, the navbar you are greeted with on the home page, appears identically
across the entire website, and its headings are unambigious.
* 'As a visiter to the website, I want to learn more about the author and his background.'
This is dealt with by the 'About' page which has an edited [Wikipedia](https://en.wikipedia.org/wiki/Kazuo_Ishiguro)
bio, and a video with the author.
* 'As a visitor to the website, I want to view a full bibliography of the authors work.' This was handled by the 'works'
page, where a back catalogue of the authors books can be seen.
* As a visitor to the website, I want to be offered sign up options, to be kept up to date with future releases and events.
This need is met in the footer section of each page, where an email sign up box is available.
* As a visitor to the website, I want to be able to purchase the authors books from the website. This can be achieved 
on the 'works' page where under each gallery entry is a link button which opens an external link to [Amazon](amazon.co.uk).
* As a visitor to the website, I want the option to follow the author on social media. This also can be achieved in the 
footer section, where clickable icons are positioned, which direct to the corresponding social media site on a new tab.
* As a visitor to the website, I want the option to engage professionally with the authors agents for bookings. This can be 
done on the 'contacts' page where there is a form which can be filled in to contact the authors agent with any queries.

## Responsiveness

* Chrome dev. tools was used at every stage of designing the website to ensure that the core structure and style of 
the website remained the same across all devices.

### Home page

* In desktop / Notebook / Large tablet screen size, the navagation bar has four written word links,
when screen size is reduced to regular tablet or phone size, these written links collapse to a three line or hamburger
menu to take up less space on the screen.
* The center hero image, remains full screen and centered across all device sizes, adjusting its size accordingly.
* The welcome jumbotron also remains full screen and centered across all device sizes, wrapping the words to the next line 
where necessary.
* The footer is made with three columns of content, three across on large screens, two across on medium screens,
the third column wraping to the next line, and one across on smaller screens so that they list single file vertically.

### About page

* The navagation bar responds as before.
* The photo of the author always occupies the same width of the screen across all device sizes, reducing the size of the entire 
photo without any cropping of the image.
* The bio text remains centered and justified accross all device sizes, expanding vertically as the screen size gets smaller.
* The embedded youtube video is centered and keeps its aspect ratio across all device sizes, reducing the size of the video 
container without any cropping.
* Footer responds as before.

### Works page

* The navagation bar responds as before.
* The Gallery of the authors novels is arranged in columns, these appear three across on larger screens,
switch to two across on medium size screens, and appear single file vertically on smaller screens.
* Footer responds as before.

### Contact page

* The navagation bar responds as before.
* The form element remains centered and justified across all device sizes, losing only the empty border at either side as
screen size is reduced.

## Aditional Testing

* Navagation bar elements tested and functional across all device sizes, each link directing to the appropriate page
and from each page back.
* Website title heading in the navagetion bar acts as alternate home button link as intended.
* Hamburger navagation menu, expands correctly, without affecting other elements, in all screen sizes.
* Order now button under the new book picture on the home page, changes color on being hovered over and when clicked directs to 
an external website in a new tab as expected.
* Email sign up box will only accept a valid email address and returns a confirmation when the submit button is pressed,
as intended.
* Social media icons change color on being hovered over and when clicked direct to their respective external website in 
a new new tab.
* Embedded youtube video is playable in the page as expected.
* The buttons under the books on the 'works' page change color when hovered over, and when clicked each one directs to
 an external website in a new tab.
 * The form on the 'contact' page only accepts information when entered correctly, and returns a confirmation when send
 button is pressed.

## Bugs 

* Title and hamburger menu on navagation bar would wrap down on smaller screen devices, taking up a large portion of the 
screen, this was addresssed by using a 'media query' which adjusted the letter spacing padding of the title, to 
allow the title and menu toggle to sit on the same line. This also fixed an issue of the navbar covering the top of the hero 
image on smaller devices.

* On very large screen devices the book items on the 'works' page would spread out quite far apart, this was also 
fixed with a 'media query' setting a max-width of 80% for the books container on screens larger than 1200px.

* On older versions of safari on apple devices, the 'new-book.jpg' fails to load, I have not yet resolved this issue.

## Devices 

In addition to emulated devices in chrome dev tools the Website was inspected on the following physical devices:
* Surface pro 4 12" screen
* Surface pro 4 connected to 27" monitor.
* Samsung Galaxy S9 Plus
* Apple Macbook Air 2017
* Apple iphone 6s

## Browsers used
* Google Chrome on Windows 10
* Microsoft Edge on Windows 10
* Firefox on Windows 10
* Safari on Mac OS
* Safari on ios



