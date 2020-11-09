# [In The Band](https://hollyford.github.io/in-the-band/)
## This website showcases BADELF which is a band based in Nottingham, UK

### UX
#### Site user's goals:
The users are potential and existing fans who wish to know more about the band. 
 
* As a site user, I want to view images of the band to compliment the audio files
* As a site user, I want to hear music from the band, so that I can hear new and existing tracks
* As a site user, I want to be able to view a list of tour dates and venues, so that I can see when the band have a gig I am able to attend
* As a site user, I want to be able to view the bio of the band members, so that I can learn more about them
* As a site user, I want to have links to the band's social media pages, so that it is easy to find
 
 
#### Site owner's goals:
* As a site owner, I want the website to increase the band's profile
* As a site owner, I want band member information to be accessible for fans, to increase the individual band member's profiles
* As a site owner, I want to increase the band's fan base and to keep existing fans engaged, so that users return on a regular basis
* As a site owner, I want tour dates to be visible, to increase attendance at gigs
 
### Scope
#### Functional requirements
* Media player
* Images
* Navigation bar which is simple and easy to navigate
* Social media links
* Mailing list subscription form
 
#### Content requirements
* Images of the band
* Bio of band members - text
* Tour dates / venues - text
* Music files
* Video files
 
### Structure
#### Interaction design:
* User friendly interface
* Responsive and visible links to pages - change on hover
* Buttons change colour when clicked
* Ability to exit pop ups
 
#### Information Architecture:
* Navigation bar at the top of the page - sticky to the top so always visible
* Responsive navigation bar - minimising for mobile 
* Images of the appropriate viewing size, moving to 1 or 2 columns of pictures when minimising for mobile
* All features appropriate size for mobile and desktop viewing
* All information is appropriate and relative to the band and not misleading or hard to find
 
### Skeleton
 
#### Mobile 
[Wireframes - mobile](assets/readme-links/wireframe-mobile.pdf)
 
#### Desktop
[Wireframes - desktop](assets/readme-links/wireframe-desktop.pdf)
 
### Surface
Decisions about typography colours etc to be made once basic layout of website has been created
 
## Features
#### Existing
1. Hero image
2. Meet the band
3. Youtube video
4. Image gallery
5. Tour dates list
 
#### Left to implement
1. Sound file
 
## Bugs
1. Meet the band images were oval rather than round
    1. Fix: Found conflicting CSS content created for different sections of the website and amended this so that the CSS was under unique classes
2. I wanted the text in the footer bar to be centered vertically however, I was unable to find a simple way for this to work   
    1. Fix: I added padding to the footer to enable the text to be vertically aligned. This had the added bonus of making the footer look better as it was larger
3. Hero image on home/index.html page is not resizing correctly on smaller screens
    1. Fix: I replaced the jumbotron with a just img html rather than adding the url in the css. One side effect was that this removed the centering of the text and images in the meet the band section.
4. Images in the meet the band section are impacted as per above Bug
    1. Fix: The mtb-style class had been in the removed html of the jumbotron. Re-added this to the meet the band section.
5. Adding an embedded youtube video caused the sizing of the page to show as justified to the left. I believe this is because it made the page width bigger but this didn’t apply to the other content
    1. Fix: I used the bootstrap example to simplify the code provided by youtube. This removed some of the styling elements youtube added and ensured the video was fully responsive without impacting the layout of the remainder of the page
6. The table added to display the tour dates was not fully responsive meaning the end user needed to scroll on mobile devices
    1. Fix: Rather than using a table, I recreated the content in the bootstrap grid system. The content is now responsive and wrapps appropriately so no scrolling is required
 
## Technologies used
* Bootstrap - https://getbootstrap.com/
* Google fonts - https://fonts.google.com/
* Font awesome - https://fontawesome.com/
* www.validator.w3.org
* http://www.css-validator.org/
* Git
* Gitpod
* GitHub
* Google Chrome
* http://www.responsinator.com/

## Testing
1. Tested website responsiveness using http://www.responsinator.com/
    1. Results: The website is responsive to all device sizes
2. Tested the image size to ensure no image is to large and impacting the website loading times. I used the Google Inspect - Network
    1. Results: All images showing as green in the results. The total website loading time is 603ms
3. Tested the HTML using https://validator.w3.org/
    1. Results - index.html: Document checking completed. No errors or warnings to show.
    2. Results - gallery.html: Document checking completed. No errors or warnings to show.
    3. Results - tour-dates.html: Document checking completed. No errors or warnings to show.
4. Tested the CSS using http://www.css-validator.org/
    1. Results - style.css: Congratulations! No Error Found.
5. Tested the website on the Google Chrome browser Version 86.0.4240.183 (Official Build) (64-bit)
    1. Results: The website was responsive and the elements performed in the way they were intended to
6. Tested the website on the Microsoft Edge browser Version 86.0.622.63 (Official build) (64-bit)
    1. Results: The website was responsive and the elements performed in the way they were intended to
7. Tested the website on the Internet Explorer browser Version 11.572.19041.0
    1. Results: The website was responsive and the elements performed in the way they were intended to
8. Tested the website on the Firefox browser Version 82.0.3 (64-bit)
    1. Results: The website was responsive and the elements performed in the way they were intended to

## Deployment
1. Create a new repository or access an existing repository
2. Click the green Gitpod button to launch the project in Gitpod
3. Create an index.html file
4. Add the file to the staging area using the git add Functional
5. Commit the file using the git commit function, adding an appropriate commentary
6. Push the file to GitHub using the git commit function
7. Refresh your GitHub repository and click the 'Settings' tab
8. Scroll to the GitHub Pages section and select a publishing source
9. Click 'Save'
10. Click the URL created within the Settings - GitHub Pages section

## Credits
I used these sources for example code which I then edited. They were also brilliant sources for troubleshooting the bugs I found along the way
* https://stackoverflow.com/
* https://www.w3schools.com/
* https://getbootstrap.com/
### Content
The content was created by the web developer based on the general makeup of the band Badelf.
 
Some elements are fiction created to make the website engaging
 
### Media
* As the band do not have any videos published online, I used: Youtube - Metallica - Nothing else matters
    * https://www.youtube.com/watch?v=tAGnKpE4NCI

* Badelf's facebook image gallery:
    * https://www.facebook.com/Badelfmusic/photos
* Badelf members personal facebook image galleries:
    * https://www.facebook.com/dannyboylarcombe/photos
    * https://www.facebook.com/richey.shrimpton/photos
    * https://www.facebook.com/hendrie.jooste/photos
    * It is deliberate that only three of the four band members sites have been referenced. The fourth member does not have a social media account
 
### Acknowledgements
 
Band members who allowed me to use their personal facebook pages, their images and the band details
* Scott Ford
* Hendrie Jooeste
* Daniel Larcombe
* Richey Shrimpton
 
My mentor Antonio Rodriguez who has provided me with guidance and support through the project