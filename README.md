# DIVENTURE - Top Dive Sites in and around South East Asia

## Interactive Front-end Web Development Project - Code Institute

## DEMO

A live demo website can be found here : <https://boonhui91.github.io/User-Centric-Frontend-Development-Project1/>

![Responsive](/images/responsive.gif)


## Context
This project primary focus is on building a static website to showcase the top diving sites in South East Asia. Being a tropical region, the underwater world of South East Asia offers a vibrant and high level of biodiversity of marine life, warm water and a unique mixture of cultures/languages on shore.
As an avid diver myself, I often find myself listening enthusiastically when other divers share their dive stories and favourite dive sites. Through the website, I hope that both experienced divers and new divers will be able to explore and share their favourite dive sites around the region.

# UX
### STRATEGY
* Target audience
    - Divers looking to explore new diving location
    - Non-divers who are interested in taking up Scuba Diving

* Goals
	- to promote South East Asia diving spots (Owner)
	- to showcase the best diving spots around SEA (Owner)
	- to check out South east Asia dive spots (User)
	- diver/non-divers planning for a dive trip (User)

### SCOPE
* User Story
    - I am a diver, I want to explore more dive sites around SEA so that I can plan for my next dive trip
	- I am a diver, I want to find out the season information at Dive site X, so that i can plan my schedule for it
	- I am a non-diver, I want to source for more information for the dive sites around the region, so that i can plan for my first trip

* Requirements
	- User to be able to view top Dive sites 
	- User to see a general history of SEA diving on landing page
	- User to be able to subscribe to mailing list
	- User be able to see top post from other users(instagram)

### Information Architecture
Diventure is strucutured in a linear flow with a mobile first approach. When user visits the site, user will be greeted with a large header video of a couple taking a plunge into the water. This gives the user a sense of an idea what this website relates to. Scrolling down, a fixed background image(not available on mobile responsive) seperates the header video with the start of the content. The content begins with the introduction of diving in South East Asia, followed by content of top three diving spots and lastly the subscribe section. Along the page, user will be able to find a 'Back to top' button on the lower right corner and a Navigation bar on the top. User will be able to navigate to each section through the navigation bar.

On the three dive sites content, user will be able to navigate to their individual page which showcase a few featured Instagram post on the particular dive site. Nav bar will also be available to allow user to navigate back to home page.

On the bottom of the page, a 'Subscribe' section is available and a footer bar with social media icons at the end. The subscribe box has a slight opacity over the dark background, giving it a stark contrast. 

### Sitemap
The sitemap was created to help me conceptualise the User Flow when visiting the website. It can be viewed [here](images/SiteMap.PNG).


### Wireframe
The wireframe helps me to visualise the page layout in different screen sizes. It can be viewed [here](images/WireframeMobile.png) for mobile and [here](images/WireframeDesktop.png) for desktop.

For viewport size larger than 992px, a background image is added after the video header to give user a smooth transition to the content.
The background is fixed to give the visual effect of diving deeper into the water as user scrolls down.
Larger viewport allows for the juxtaposition of the word content beside the video slide show. User will be able to read the information about the particular Dive site and enjoy the slideshow imagery at the same time.


# UI

### Colors
The colors are chosen with reference to 'Ocean Theme' color palette found online. On the home page, the colors at the top are of a lighter tone (white nav bar background, opacity on video), and the color progressively gets darker ending with a dark colored subscribe section. I want to to create a visual effect that mimics as if the user is diving deeper into the ocean as the page scrolls down.

### Fonts
The font types chosen belongs to the Serif family as I would like to express the overall layout to be sleek and modern. The color contrast well with their respective background.

### Nav-Bar
Nav bar is designed to be responsive, changing to a 'Hamburger' bar in mobile screen size. I've decided to fixed the Nav Bar at the
top, so that the content appears neater and cleaner as the user scrolls down. Nav bar can be easily accessed through the 'Back to top' button. Background and text color of Nav bar blends well with the light colored theme on the top. 

### Video Slideshow
The video slideshows were created using HTML and CSS with reference to <https://www.cssscript.com/css-only-crossfading-background-slideshow/>. The keyframe and each animation duration time was calculated with reference to the formula provide on Demo3 on <http://css3.bradshawenterprises.com/cfimg/> Calculation for a smooth slideshow transition(no overlapping of pictures) was made based on 3 pictures per slide show with a display time of 4 seconds per picture. The initial attemps at the slideshow resulted in all the pictures overlapping after the first rotation.

### Subscribe
The dark background image with bioluminescent jellyfishes were chosen as if fits perfectly as being a deeper part of the ocean as user scrolls to the bottom. An opacity box overlays to create the subscribe box. Footer bar also has a black background color with the social media icons having a white outline which changes color when on hover. 

## FUTURE FEATURES
* An interactive map that allows user to see all the dive sites available when they click on a region
* Detailed information such as weather, depth, average temperature be available as user clicks on the dive site
* Allows user to submit their Instagram post to be featured 


# TECHNOLOGIES USED
* HTML5
* CSS3
* Javascript (Back to top button)
* <http://draw.io> (Sitemap)
* Balsamiq (Wireframe)
* Am I Responsive(<http://ami.responsivedesign.is/>)
* Screen To Gif(<https://www.screentogif.com/>)
* Google fonts (<https://fonts.google.com/>)
* Github/Gitpod/Visual Studio Code

# TESTING
Requested my friends to test out the website on both mobile and laptop screen width and to provide me feedbacks on how I can improve on the website.

### Manual Testing
- Navigation bar is available on every page and directs user to the specific content when clicked. Shows a highlight effect when hover upon. Changes to a 'Hamburger' Bar when screen size is below 992px. 
-slideshow animations are working with no overlap of images.
-When hovering over the 'SEE MORE', an underline effect is shown. Upon clicking, user will be directed to a new page with the Instagram post. Instagram posts embeded and centered.
-Back to top button works well on both mobile and laptop.
-Clicking on the subscribe button without inputting a Name and proper email address format, an "invalid" prompt will show up.

### BUGS
- Slideshow does not fade in well on first rotation
- Extra white spaces on the right at the top of page

# DEPLOYMENT
This site is hosted using GitHub pages, deployed directly from the master branch. This site can be viewed [here](https://boonhui91.github.io/User-Centric-Frontend-Development-Project1/). 
The deployed site will update automatically upon new commits from the master branch. For the site to be deploy correctly on 
GitHub pages, the landing page must be named 'index.html'.

To run locally, clone this repository directly into the editor of your choice by pasting git clone 
https://boonhui91.github.io/User-Centric-Frontend-Development-Project1/ into your terminal. To cut ties with this GitHub repository, 
type git remote rm origin into the terminal.


# CREDITS
* Nav-bar logo
    - <https://www.flaticon.com/authors/freepik>
* Video
    - <https://www.pexels.com/video/couple-swimming-under-the-sea-854397>
* Images
    - Intro Map (<https://www.underwaterasia.info/dive-guide-asia/dive-guide-asia.php>)
* slideshows images
	- http://divesitesofmalaysia.blogspot.com/2013/05/sabah-pulau-sipadan-island.html
	- https://www.amazingborneo.com/
	- https://www.pinterest.com/pin/355925176803720165/
	- http://nomads-expeditions.com/2017/12/underwater-guide-to-raja-ampat-indonesia/ 
	- https://www.pexels.com/photo/aerial-photo-of-islands-on-sea-2583852/
	- https://www.uwphotographyguide.com/epic-photo-destinations-raja-ampat
	- https://www.iq-dive.com/en/divingatthesimilanislands-12.html
	- http://www.divephotoguide.com/underwater-photography-travel/article/underwater-photographers-guide-similan-islands-surin-islands
	- https://phuket-diving-thailand.net/3-days-trip-richelieu-rock-similan-islands/
* Subscribe Background image
	- https://unsplash.com/photos/dr_9oxbVnuc

# Acknowledgements
* Animate on scroll (<https://michalsnik.github.io/aos/>)
* Scroll to top button (<https://www.adlyticmarketing.com/blog/squarespace-how-to-add-a-back-to-top-button/>)
* Social media icons (<https://codepen.io/eskside_design/pen/RNemLB/>)

**This is for educational use**