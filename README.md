# Bad Arts Entertainment Webpage

This webpage has been designed for a Limerick based rap label which represents 8 distinct artist/group of artists.
The objective of the project is to create an all-in-one platform for Bad Arts Entertainment to connect their social media presence which is spread across multiple websites. This website would pull content from Twitter & Youtube while also linking to Spotify & Bandcamp.
The website will also be used as a promotional tool for the label to advertise album & merchandise releases. Previous concerts they have done will also be on display. This will help the label to build a community of fans.


## UX

Before designing the wireframes and choosing the colour scheme, I reviewed the label's current online presence.
Bad Arts Entertainment already had a logo, an orange smiley face on a black background with red lettering.

![alt text goes here](assets/img/logo4.jpg)

When starting the design process, a major goal of mine was to design a UX which worked in haromony with their logo & brand indentity.
Irish rap music is quite a niche genre and the UX had to engage this small target audience. 
To reflect the tone of the music, I used a black background paired with the logo's bold orange colouring. White was then used to highlight certain pieces of text, making the overall content more legible by creating contrast.
For title within the navbar, I chose a dramatic font called Holtwood One SC. All other text was styled using thehighly legible Kanit font.



1. As a fan of Bad Arts Entertainment I want:

    * The ability to easily find music and videos from each individual artist so that they can listen to a specific artist depending on what mood the site visitor is in.
    * A clearly defined navigation bar so that I can move around the site effectively.
    * Information pertaining to each artist and their connections with each other to get a better understanding of the label as a whole.
    * A place to be able to purchase physical merchandise/album releases or digital music files.
    * A way to view their social feed without having to leave the webpage.
    * A method to interact with the label's social media content which is split across several external sites. 


2. As a music venue promoter:

    * A place to review the label's music and videos to see if they are a suitable act for their venue.
    * The ability to view previous events that the label has been a part of.
    * A method to get in contact with the label in order to book their artists for concerts.


3. As a music PR agent:



## Existing Features

Homepage:





## Technologies Used

JQuery 
https://jquery.com/ - The Jquery script tag is required in order to load Bootstrap.

Bootstrap
https://getbootstrap.com/ 
Bootstrap was one of the technologies that was requested for us to use for our milestone project. 
I decided to use this framework to implement several features on the site including the navbar, a carousel and a grid containing 4 cards (each having an image, some text and a link).


CSS grid
https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout
Having learnt about grid layouts from the Bootstrap example, I decided that I wanted to learn how to implement them natively using CSS.
All other grid layouts, such as the footer, artist's profile, shop and videos page have been programmed using CSS grid.

Youtube Video Embedding tool
https://www.classynemesis.com/projects/ytembed/
This technology was used to convert youtube videos into html iframe elements.

Image Resizer
https://picresize.com/
At times, working with images can be a difficult task. This free image resizing website has helped me tremendoulously with my milestone project.

Google Fonts
https://fonts.google.com/
The site used to choose and implement custom fonts.

Icons
https://fontawesome.com/
Website used to source footer icons

Photo Editing Software:
https://www.gimp.org/
Used to create custom event ticket container



## Credit


General CSS knowledge:

https://www.youtube.com/watch?v=jx5jmI0UlXU&t
https://www.w3schools.com/cssref/css3_pr_background-size.asp
https://www.w3schools.com/css/css_align.asp
https://www.w3schools.com/css/css3_object-fit.asp
https://www.w3schools.com/cssref/sel_before.asp
https://www.w3schools.com/tags/tag_strike.asp
https://css-tricks.com/snippets/sass/black-white-opacity-mixins/
These videos and articles helped me understand certain cructial CSS properties such as position, background, object-fit and text-align.

Form Styling:

https://blog.logrocket.com/how-to-style-forms-with-css-a-beginners-guide/
I don't believe that I copied any code directly from this site but it influenced my decisions relating to the footer contact form styling.

Hover text effect associated with shop.html:

https://www.youtube.com/watch?v=ltxxNidblts


Bootstrap Navbar and associated issues:

https://stackoverflow.com/questions/44988543/bootstrap-navbar-transparent-on-mobile
https://stackoverflow.com/questions/22383547/bootstrap-dropdown-menu-is-not-working
https://stackoverflow.com/questions/19204937/div-doesnt-position-itself-below-bootstrap-fixed-navbar
I used these stackoverflow articles to troubleshoot the bugs outlined in the above section.

Video Gallery:

https://fancyapps.com/fancybox/3/

Bootstrap custom icon colour:

https://stackoverflow.com/questions/46249541/change-arrow-colors-in-bootstraps-carousel

Customising the Google Map:

https://developers.google.com/maps/documentation/javascript/styling
https://developers.google.com/maps/documentation/javascript/adding-a-google-map

Text over image:

https://css-tricks.com/design-considerations-text-images/

Flyout Modal:

https://www.solodev.com/blog/web-design/bootstrap/how-to-create-a-flyout-bootstrap-modal.stml

Card Flip Carousel:
https://www.youtube.com/watch?v=jVhwJgLOoGw
https://mdbootstrap.com/snippets/jquery/alexpiffero-it/696600


Internal Links:

https://www.yourhtmlsource.com/text/internallinks.html
I've implemented for one of the buttons on the navbar to bring you to the bottom of the page, to the contact section.



## Media


#### Bad Arts Entertainment Videos & Images:

This section will cover the majority of videos and images used in this project. 
As this site will be used by a real musical organisation, I was given permission to use any videos or images owned bt Bad Arts Entertainment.


#### External Images:

In shop.html I have used 5 external images sourced from google images using the search term 'merch'.





## Deployment

#### How to run this project locally:

To clone this project into Gitpod you will need:
1. A Github account
2. Use the Chrome browser

Then follow these steps:
1. Install the gitpod browser extensions for Chrome
2. After installation, restart the browser
3. Log into gitpod with your gitpod account
4. Navigate to the github project repository
5. Click the green 'gitpod' button at the top right corner of the repository
6. This will trigger a new gitpod workspace to be created from the code in github where you can work locally


To work on the code within a local IDE such as VScode:
1. Follow this link to the github repository
2. Under the repository name, click 'clone' or 'download'
3. In the clone with the https section, copy the clone URL for the repository
4. In your local IDE, open the terminal
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type 'git clone', and then paste the URL copied in step 3

git clone https://www.github.com/USERNAME/REPOSITORY

7. Press enter. Your local clone will be created.




## Testing

* W3C CSS validator
* W3C Markup validator
    *The developer used W3C CSS validation service and   W3C Markup validation service to check the validity of their code.
  
Client stories Testing

Most common paths through the website:

* Home > Videos

* Home > Shop > Product
* A back button was added to each product page to ensure that site visitors can easily return to the shop page. A link in the navbar also has this functionality, the second button was added as it follows modern online shopping conventions.

Home > Contact




#### Testing client's stories outlined in the readme:

1. As a new visitor to the website, I want to be able to navigate the site easily and be able to find what I want quickly.
    
    i. No matter what page a new visitor lands on, they're able to easily find and use the navigation bar.
    ii.The logo image is a link that always leads back to the Homepage.
    iii.The landing section of the homepage contains a desription of the music label, their genre and location.


2. As a new visitor to the site, I am interested in a specific artist on the label.

    i. On the home page, all artist's profiles are grouped together in order to aid the site visitor find the indended artist quickly.


3. As a new visitor to the website, I want to find some personal information for each artist so I can understand their lyrics better.

    i. Each artist profile contains a concise biography and their latest video release.


4. As a fan, I want the ability to purchase digital copies of their music.
   
    i. On the homepage, each artist's profile has a link to their bandcamp page where potential customers can purchase their music digitally.


5. As a potential employer, I would like to see what previous events they have done in order to make a wise business decision.

    i. The events section on the homepage outlines previous events that the label has taken part in as well as any upcoming gigs planned.


6. As a potential customer, I would like to view their merchandise with clearly indicated pricing.

    i. In the shop, prices are outlined for each product once you hover over them. Also within the product page, the current and previous product price is clearly outlined.


## Bugs Discovered:

#### Solved bugs

1. Z-index of navbar on mobile
    
    * The navbar dropdown tile worked on every page besides index.html [FIXED] Dropdown on index.html.
    * After requesting help from the tutor team at Code Institute, we found that the issue was arrising due to the z-index of the navbar in relation to the carousel. 
    * The navbar has now been given a z-index:10 and the problem has been resolved.


2. Bootstrap accordion not collapsing

    * The accordion wouldn't collapse once it had been opened. You could see the browser attempting to close the accordion looking almost like a glitch.
    * After scouring the bootstrap documentation, I tried several potential solutions.
    * A JS script was needed to close the accordion

      $('.open-close1').collapse('toggle', {
            parent: '#accordion1'
        });  


3. Rotating card carousel not mobile friendly

    * As the browser window decreased to mobile size, a 3 card carousel wouldn't fit aesteticely.
    * I created 2 separate carousels, a 3 card carousel for screens 768px and above & a single card carousel for screens 768px and below.
    * The bootstrap class names used to achieve this; Desktop[ d-none d-md-block ] & Mobile [ d-md-none ].


