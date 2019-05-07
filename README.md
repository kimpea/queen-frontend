# Queen - User Centric Frontend Development Website

## UX

This web application is an frontend website for the famous 1970s rock band 'Queen'. It is designed to allow fans of the band to browse through samples of the band's music, watch a music video, keep up to date with the band's whereabouts and hire the band to perform at events such as weddings and parties. This application is specifically aimed towards the fans of 'Queen' and would be of no interest to any other type of target market.

This type of user will want to be able to listen to some of the band's music and watch one of their music videos. This user will also want to know about upcoming events that the band will take part in, and also any available music for purchase. The user might be interested in finding our more about each member of the band, and therefore would perhaps like to read mini biographies for these members. Additionally, the user will want to keep up to date with the band's upcoming events and can do this by subscribing to a weekly newsletter. Lastly, the user will need a means of being able to hire the band for events such as weddings and parties. My project is a suitable way of achieving this because it provides various audio clips that the user can listen to, a music video embedded into the website that the user can watch, forms for subscribing to the band's newsletter and also hiring the band for events, a gallery full of the band's photos and mini biographies about each member of the band. 

For a more detailed explaination on the UX design phase of this website, please read [documentation/ux_planes.pdf](documentation/ux_planes.pdf). 

#### General User Stories

As a user type:
 - I want to be able to listen to samples of the band's music.
 - I want to be able to watch one of the band's music videos.
 - I want to read information on every member of the band.
 - I want to see a variety of photos of the band performing at live events.
 - I want to hire the band to perform at a wedding.
 - I want to keep updated with the band's whereabouts with a weekly newsletter.
 - I want to follow the band on Facebook, Twitter and YouTube.
 - I want to see what upcoming concerts the band is going to perform at, and also buy one of their albums.

#### Real-life User Stories

 - User 1: I want to listen to a sample of Radio Ga Ga.
 - User 2: I want to watch the music video for Another One Bites The Dust.
 - User 3: I want to find out more about Freddie Mercury.
 - User 4: I want to see some photos of Queen performing at live.
 - User 5: I want to hire Queen to perform at my cousin's wedding!
 - User 6: I want to subscribe the Queen's weekly newsletter.
 - User 7: I want to find Queen on Facebook and YouTube.
 - User 8: I want to see where Queen are going to perform next, and also buy their latest album.

#### Wireframes

Wireframes have been created with [wireframe.cc](https://wireframe.cc/). I have created wireframes for mobile, tablet and desktop views - these are to help me plan out how I want my website to look.
 - [Mobile wireframes](documentation/mobile_wireframes)
 - [Tablet wireframes](documentation/tablet_wireframes)
 - [Desktop wireframes](documentation/desktop_wireframes)

## Features

 - Sample clips - these will allow the users to listen to some of the band's most popular songs.
 - Embedded music video - this will let the user watch one of the band's most popular music videos.
 - Gallery - this will allow the user to browse through the band's photos, ranging from photos of the members to their live performances.
 - Mini biographies - this will let the user read descriptions on each member of the band.
 - Contact form (no backend functionality) - this will allow the user to fill in a form letting them hire the band for events.
 - Newsletter subscription form (no backend functionality) - users can enter their email address in order to subscribe to a weekly newsletter service.
 - Social media links - these will direct the users to the band's social media pages, including Facebook, Twitter and YouTube.
 - List of upcoming events - this will display a list of the band's upcoming tours/concerts.

### Existing Features 
 - Audio/sample clips - User 1 is able to listen to a sample of Radio Ga Ga thanks to the embedded Spotify Play Button feature in the auditorium section.
 - Embedded music video - User 2 can watch a live performance of Another One Bites The Dust. When the band updates this website frequently, they can change the video on display to any video of their choice, e.g. a music video or an interview with the band.
 - Mini biographies - User 3 can find out information about Freddie Mercury, and any other band member. 
 - Gallery - This allows User 4 to view various images of Queen performing live. As with the embedded video, images can be added by the band to expand the gallery.
 - Contact form - This will allow User 5 to contact the band regarding hiring them to perform at their cousin's wedding.
 - Newsletter subscription form - User 6 is able to enter their email address into the subscription form and sign up for a weekly newsletter received via email.
 - Social media links - This will allow User 7 to find the band on Facebook and Youtube, as well as Twitter and Spotify.
 - List of upcoming events - User 8 is able to see where Queen is going to perform next and also buy their latest album.

### Features Left To Implement
 - Backend functionality could be considered for the contact form and subscription form in future builds of the application.
 - Back-to-top button could be implemented with JavaScript in the future so that users can return to the top of the website easily.

## Technologies Used
- HTML
    - This project uses **HTML** to build the foundation of the web application and includes links to Bootstrap 4, Bootstrap JS, CSS, and Font Awesome.
- CSS
    - This project uses **CSS** to style the features of the web application, including the header, sections and footer. It is also used to modify Bootstrap 4 styles.
- [Bootstrap 4](https://getbootstrap.com/)
    - This project uses **Bootstrap 4** to speed up the development process and provide a clear, consistent layout for the website. I have also used Bootstrap's 'Journal' theme (and modified it with my own CSS).
- [Youtube](https://www.youtube.com/)
    - This project uses **Youtube** for the embedded video in the Cinema section.
- [Spotify Play Button](https://developer.spotify.com/documentation/widgets/generate/play-button/)
    - This project uses **Spotify Play Button** for the embedded audio clips in the Auditorium section.
- [JavaScript](https://www.javascript.com/)
    - This project uses **JavaScript** to provide the functionality for the W3.CSS Slideshow feature.
- [Font Awesome](https://fontawesome.com/)
    - This project uses **Font Awesome** to provide icons for the application.
- [Wireframes.cc](https://wireframe.cc/)
    - This project uses **Wireframes CC** for the Skeleton and Surface Plan, providing desktop, tablet and mobile views of the web application.

# Testing

### Manual Testing 

Below are scenarios which a user may experience while navigating the website. These have been used to manually test the website's features and sections.

1. Home
    1. Click on 'Home' in the navigation bar and be directed to the 'Home' section.
    2. Optionally, click on the 'Queen' logo in the navigation bar and be directed to the 'Home' section.

2. Auditorium 
    1. Click on 'Auditorium' in the navigation bar and be taken to the 'Auditorium' section on the website.
    2. Press the play button on any audio clip and listen to a sample of the song you have chosen. 

3. Cinema
    1. Click on 'Cinema' in the navigation bar and be taken to the 'Cinema' section on the website.
    2. Press the play button on the embedded video and watch the live performance of Another One Bites The Dust.
    3. Control the volume, enter fullscreen mode and also change quality settings when clicking on the cog symbol on the video player.

4. Shows
    1. Click on 'Shows' in the navigation bar and be taken to the 'Shows' section on the website.
    2. Click on any of the tabs for the upcoming tour dates and see the dates and locations for each show. 
    3. Click on 'BUY TICKET' for any show and be directed to a link where the user can purchase a ticket for the show.
    4. Optionally, from the 'Home' section, click on 'TICKETS AVAILABLE NOW' button and be taken to the 'Shows' section.
    5. Click on 'AVAILABLE NOW' and be directed to a website where the user can buy the album on display.

5. About
    1. Click on 'About' in the navigation bar and be taken to the 'About' section on the website.
    2. Read the description under 'From Smile to Queen...'
    3. Click on any of the band member names and read the content in the dropdown. 
    4. Click on the link given in any of the band member dropdowns and be taken to a Wikipedia page displaying more information on the chosen band member.

6. Gallery
    1. Click on 'Gallery' in the navigation bar and be taken to the 'Gallery' section on the website. 
    2. Click on either the left or right indicators to see images of the band, along with the year that each picture was taken.

7. Contact & Subscribe
    1. Click on 'Contact' in the navigation bar and be taken to the 'Contact' section on the website. 
    2. Fill in the contact form and click 'Submit' - there is no backend functionality to the form yet (this is something to consider for future versions of the website).
    3. Fill in the subscription form and click 'Subscribe' - there is no backend functionality to the form yet (this is something to consider for future versions of the website).
    4. If any fields are missing, be advised that the field is required.

8. Social media links
    1. Click on 'Contact' in the navigation bar and be taken to the last section of the website. Social media links are in the footer.
    2. Click on the Facebook, Twitter, YouTube and Spotify icons and be taken to the specific links for each social platform. 

### Responsive Testing

I have tested out the website on both Google Chrome and Mozilla Firefox - the website functions well on both web browsers. I have used Chrome's Developer Tools and Firefox's Developer Tools to try out the website on different device screen sizes, from mobile to desktop. The website functions well on most screen sizes, especially for the iPhone 6/7/8 and iPad. I have also tested out the website on an Asus Zenfone 3 Max and an Amazon Kindle Fire - as expected, it functions normally.

### Code Validation

After using the [official HTML code validation service](https://validator.w3.org/), a few errors had been found. The validator states that the allowtransparency and frameborder attributes for the iframe element are obselete, however, removing these makes the appearance of the audio clips and embedded video look inconsistent and untidy - as a result of this, I have left these attributes alone. The [officla CSS validation service](https://jigsaw.w3.org/css-validator/) revealed no errors within my CSS code.

### Bugs 

 - White space to the right of the viewport - this has been fixed with hidden overflow in my CSS code. 

## Deployment

### To run this locally...

1. Create a new workspace in Cloud9 with a workspace name and description.
2. Clone the project with either `https://github.com/kimpea/queen-frontend.git` or `git@github.com:kimpea/queen-frontend.git` in the 'Clone from Git' field.
3. Select a blank template and once the workspace has loaded, open the index.html tab and click 'Run'. 
4. Click on the link which appears in the terminal for index.html to view the website.

### Production vs. Deployed

Whilst the website was in production mode, the sources for all images did not require the /queen-frontend/, however, in the deployed version, for the images to appear in GitHub pages, I had to place /queen-frontend/ in front of all images sources. I also had to do the same for the external JavaScript file. 

# Credits, Acknowledgements and Media

The Queen logo which I used for the navbar and home section can be found [here](https://upload.wikimedia.org/wikipedia/commons/7/74/Queen_Logo.png).
The album cover which I used in the shows section can be found [here](https://dvfnvgxhycwzf.cloudfront.net/media/SharedImage/image500/.f795-N2T/SharedImage-13049.jpg?t=e8cd0e49e6e9cd5df0d5).
The audio clips are made by the original artists themselves and have been embedded through [Spotify's Play Button](https://developer.spotify.com/documentation/widgets/generate/play-button/) feature.
The music video found in the cinema section can be found [here](https://youtu.be/NVIbCvfkO3E). I used [Embed Responsively](https://embedresponsively.com/) to help me embed the YouTube video into my code and make it responsive on all device screen sizes.
I have used Wikipedia links which can be seen in each of the band member's dropdowns.

Background images that I have used are linked here:
 - [Home section background](https://www.rollingstone.com/wp-content/uploads/2018/06/queen-news-of-the-world-opener-c5bda6ed-0bdf-42c0-8d93-7b29ec5c4259.jpg?crop=900:600&width=440)
 - [Music video section background](https://cdn.cnn.com/cnn/interactive/2018/11/opinions/queen-live-aid-cnnphotos/media/01.jpg)
 - [About section background](http://images.tritondigitalcms.com/6616/sites/395/2019/01/09164809/GettyImages-2636592.jpg)
 - [Forms section background](http://www.asset1.net/tv/pictures/show/queen-live-in-budapest/Queen-Live-In-Budapest-02-16x9-1.jpg)

Band member images which I have used are linked here:
 - [Freddie Mercury](https://media.them.us/photos/5afc954001bb27001030e020/master/w_1280,c_limit/GettyImages-75509443.jpg)
 - [Roger Taylor](https://www.udiscovermusic.com/wp-content/uploads/2019/04/Queen-Roger-Taylor.jpg)
 - [Brian May](https://images.radiox.co.uk/images/34052?width=5261&crop=16_9&signature=yMKBDrExPGdpdgarU1jm83FLJjk=)
 - [John Deacon](http://www.queenonline.com/global/assets/modules/site/images/band/john_bio3.jpg)

For the gallery section, I was originally going to use Bootstrap 4's carousel feature, however after complications I encountered whilst modifying the CSS, I decided to use [W3.CSS's slideshow feature](https://www.w3schools.com/w3css/w3css_slideshow.asp) instead. Images used for this slideshow are referenced here:
 - [Slide 1](http://www.queenonline.com/global/assets/modules/site/images/gallery/1975_001.jpg)
 - [Slide 2](http://www.queenonline.com/global/assets/modules/site/images/gallery/1976_002.jpg)
 - [Slide 3](http://www.queenonline.com/global/assets/modules/site/images/gallery/1977_002.jpg)
 - [Slide 4](http://www.queenonline.com/global/assets/modules/site/images/gallery/1978_003.jpg)
 - [Slide 5](http://www.queenonline.com/global/assets/modules/site/images/gallery/1980_003.jpg)
 - [Slide 6](http://www.queenonline.com/global/assets/modules/site/images/gallery/1981_002.jpg)
 - [Slide 7](http://www.queenonline.com/global/assets/modules/site/images/gallery/1981_004.jpg)
 - [Slide 8](http://www.queenonline.com/global/assets/modules/site/images/gallery/1984_008.jpg)
 - [Slide 9](http://www.queenonline.com/global/assets/modules/site/images/gallery/1985_006.jpg)
 - [Slide 10](http://www.queenonline.com/global/assets/modules/site/images/gallery/1986_006.jpg)
 - [Slide 11](http://www.queenonline.com/global/assets/modules/site/images/gallery/1986_012.jpg)
 - [Slide 12](http://www.queenonline.com/global/assets/modules/site/images/gallery/1986_016.jpg)
 - [Slide 13](http://www.queenonline.com/global/assets/modules/site/images/gallery/1986_028.jpg)
 - [Slide 14](http://www.queenonline.com/global/assets/modules/site/images/gallery/2014.JPG)