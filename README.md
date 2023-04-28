README.md 

# Kiwi Cocktail Bar 

Kiwi Cocktail Bar is a bustling new cocktail bar set in the heart of Cardiff. This site aims to entice customers to visit the bar by showing them whats to offer and giving them the opportunity to sign-up to a newsletter for upcoming events. The target audience will see a sophisticated and vibrant atmosphere which they will hopefully want to be a part of. This site will be useful for customers to see what is on offer, where the bar is located and be notified on upcoming events. 

This website has been made to complete the first project within the Code Institute Full Stack Developer course and focuses on the use of HTML5 and CSS3 in a responsive manner. 

![Am I Responsive? screenshot of Kiwi Cocktail Bar website](/assets/readme_images/AmIResponsive%20-%20Kiwi.PNG)

Link to live project: https://tr94.github.io/Kiwi-cocktail-bar/


# User Experience

The target audience for this site a young to middle age demographic who are looking for a classy place to socialise and enjoy their evening. The site is intended to attract new users and keep current users updated.


New User Goals:
- As a new user, I want to find local socialising venues within the area (Cardiff).
- As a new user, I want the site to present the decor, styling and feel of how the bar is going to be.
- As a new user, I want to be able to navigate the site in an easy and intuitive fashion.

Current User Goals:
- As a current user, I want to see updates to the menu as guest cocktails come and go.
- As a current user, I want to be notified when new cocktails are release and / or when events are happening.
- As a current user, I want to be able to navigate the site in an easy and intuitive fashion.

# Development Planes

To develop the site into further incorporating the user stories and the commercial needs, the 5 development planes have been considered. Working through these planes in a systematic way allows the site to be fleshed out methodically and should allow the initial version of the site to be much closer to the desired final output.

## Strategy

Branding of the bar is a critical element to the appeal and customer loyalty. The website must be able to echo the Kiwi Cocktail brand accurately to ensure users connect with the branding across multiple platforms and in the bar itself. 

Business Objectives:
The website must:
- Introduce the brand
- Advertise the bar through effective search engine optimisation
- Show a social and vibrant place to be which’ll engage potential customers
- Draw in new customers and retain current

Data gathering:
The website should be able to feedback useful data on the customers such as:
- Using google analytics to see the traffic, user time and demographic of users
- Gather details of users such as name, email address and marketing preferences if the user wants to sign-up to a mailing list

User requirements:
The website needs to allow the user to:
- Get a feel for the bar - its aesthetic, atmosphere and decor
- Understand what is on offer, specifically with access to a menu
- Dive deeper into the creation, goals and how to offerings work
- Sign-up to be notified of events and new additions to the menu if they want to

## Scope
Defining the scope allows the project of building the website to have clear expectations and deliverables. This is where the features and content are agreed up front - at least for the initial release. 

Based on the Strategy above, the content requirements are:
The user will be looking for:
- Getting a feel of the bar’s aesthetic and atmosphere 
- Understanding how the bar was established and its values / aims 
- The drinks on offer in the form of a menu 
- The option to sign-up for updates to be mailed to the user

Functionality requirements are:
The user will be able to:
Navigate the website easily to find the information they require
Easily sign-up to a mailing list if they want to

## Structure
Based on the strategy and scope above the site map shows a tree diagram of how the website will be constructed. This gives a brief overview of the pages and content:

![Site Map for Kiwi Cocktail Bar website](/assets/readme_images/site_map.png)
 
## Skeleton
In order to visualise how the content will be presented and where the features will be placed, some initial wireframes were used. Using wireframes at this stage of the projects allows the basic feel of the website to be visualised in a relatively quick way without the need for laborious coding.

Balsamic was used to create the following wireframes:

### Home Page: 
The Home page wireframes can be seen below, these consider the layout on a full size screen and a mobile screen:

![Home page wireframe full width](/assets/readme_images/Home%20-%20Full%20Width%20wireframe.png)

![Home page wireframe mobile width](/assets/readme_images/Home%20-%20mobile%20screen%20wireframe.png)

### Menu Page:
The Menu page wireframe can be seen below:

![Menu page wireframe](/assets/readme_images/Menu%20wireframe.png)

### Gallery Page:
The Gallery page wireframes can be seen below, these consider the layout on a full size screen and a mobile screen:

![Gallery page wireframe full width](/assets/readme_images/Gallery%20-%20wide%20screen%20wireframe.png)

![Gallery page wireframe mobile width](/assets/readme_images/Gallery%20-%20mobile%20screen%20wireframe.png)

### Sign-Up Page:
The Sign-Up page wireframe can be seen below:

![Sign-up wireframe](/assets/readme_images/Sign-Up%20wireframe.png)

At this stage, the wireframes are reviewed against the original strategy and goals of the project to ensure they’re aligned satisfactorily. There is an opportunity to circle back and update as required to achieve the desired output before coding begins.

## Surface

### Colour:
With branding being such an important aspect of this site, the colour palette is a key factor in the look and feel of the page. 

The matt blue (hex code: #4D6971) is considered the colour of the Kiwi Cocktail Bar logo and its core brand colour. Using “color space” this colour was compared to find complementary colours that could also be used. These had to retain the core values of the brand, sophisticated and classic.

The final colour palette is:
Hex colour #F1F2EF, “off-white” used for background space 
Hex colour #9CACA7, “light grey” used for text
Hex colour #4D6971,  “matt blue” used for the logo and background space to contrast with the off-white

### Font:
The font of the logo is a key consideration for the branding of the site. Using Google Fonts, the logo font used is “Comfortaa”. 

For the main body of the site, a complementing font is used which was recommended using Font Joy. The main body font pairing is “Proza Libre”. 

These fonts have been imported into the CSS file but the font family styling uses “sans-serif” as a fall-back font in case the import fails. 

### Images:
The images are stored within the “assets’ folder of the site and have been sourced from Pexel. These have been carefully selected to match the branding values of the bar. 

The User’s first impressions of the site are predominately based on the home page image so it is important the right messages are portrayed. In this case, the image of the bartender creating a cocktail show sophistication, some show and dramatics along with a modern environment. 

The rest of the imagery throughout the site has been selected to meet the original business objectives and branding. 

### Icons:
The “Kiwi” logo is an icon from Font Awesome. This is embedded into the html code using an <I> element which is copied directly from the Font Awesome website. 

Other icons are used to add some visual flavour to the site and become useful to save space when viewed on smaller screens. 

# Features

## Navigation and Logo
The logo and text: 
- KIWI COCKTAIL BAR in the top left corner of the page show off the branding for the bar and link to the home page as is traditional website convention. 
- The navigation links to move around the site are located in the top right of the screen. These are Home, Menu, Sign-Up and Contact Us which link to their relevant sections of the site. 
- The font chosen is stylish to in-keep with the branding of the bar and colours are contrasting to ensure easy reading.
- The navigation links are consistent across the website which makes moving around the site easy and displays the information in a clear manner. They are also interactive with an underline showing which page the user is on and the text transforming to uppercase when hovered over.  

![Navigation bar screen grab](/assets/readme_images/nav_bar.PNG)

Issues to fix: 
Image “float” left so when re-sizing the pouring stays in the hero image - fixed with “no-repeat center left”
Images stacked on top of each other - does each image need a container? <section> doesn’t seem enough to stack the images…?

## The Header
- This section provides a clear overview of what the site is about and who it is for. 
- The header text is styled to continue the stylish / sophisticated theme which the blue colour showing the name of the bar KIWI COCKTAIL BAR and the text below in a contrasting 
- The image has been carefully chosen to allow an effective display responsive to different screen sizes.

![Header screen grab](/assets/readme_images/Header_hero_image.PNG)

## The About Us Section
- Aims to show off the vibe of the bar which will be a sophisticated and stylish environment.
- Information is included to explain what the bar is about and how the offerings work. It explains the classic menu which is always available as well as the guest cocktails which change regularly to keep customers interested. 
- The information displayed is easily readable with contrasting colours and a background image which complements the overall aesthetic of the site. 

![About-Us screen grab](/assets/readme_images/About_Us.PNG)

## The Sign-Up Form
- Gives customers the opportunity to be notified of upcoming events and new mixes that are being launched. 
- The form captures First Name, Last Name, Email Address and Alcohol Preferences which’ll be used to tailor the communications.

![Sign-up form screen grab](/assets/readme_images/Sign-up_form.PNG)

## Contact us 
- Contact information and a location map
- Opening hours 

![Contact-Us screen grab](/assets/readme_images/Contact-Us.PNG)

## The Footer
- Social links included to give the customer opportunity to stay connected on other platforms such as Instagram, Facebook, Youtube, Twitter. 
- Summary of contact details 
- Footer stays as a slim bar across the bottom of the page and is consistent across all the pages. 

![Footer screen grab](/assets/readme_images/Footer.PNG)

## Features to add in the future
- Interactive walk through of the bar when its full of life would be a great way to engage potential customer further.
- Making cocktails is a performance with dramatics and show - the website would benefit from more animation and movement to relfect this.

# Technologies Used
Coding languages used:
- HTML5
- CSS3

## External resources used:
Google Fonts:
Imported the “Comfortaa” and “Proza Libre” fonts into the CSS file. These are the only two fonts used in the project.

### Font Joy:
Used to pair the “Comfortaa” logo font with a suitable body text font - this was “Proza Libre”.

### Font Awesome:
Icons linked into the HTML file - these include the “Kiwi” logo icon as well as visual icons throughout the site (such as social media links).

### Am I Responsive?:
Used to test out how friendly the site is across various screen sizes. The responsive nature of the site is shown at the top of this document in the mock-up. 

### Balsamiq:
Wire-framing during the drafting stage of the project to discuss and agree the initial structure and content of the site. 

### Git-Hub / Git-Pod:
Git-hub stored the project files and is used to host the site 
Git-pod is linked into Git-hub through a browser extension and is the coding platform.

# Accessibility 
Accessibility is a key consideration for any website which ensures the content is accessible to all. For this websire the following aspects have been included:
- Aria labels on links to social media websites and navigation links 
- Alt labels on the images   

# Testing

## User goals 
Going right back to the Stratgey behind the site, we must test the user goals to make sure the site provides the correct user experience.

### New User Goals:
"As a new user, I want to find local socialising venues within the area (Cardiff)."
- Search Engine Optimisation (SEO) has been considered in the meta data for the site. The keywords and description within the index.html file give search engines the information they need to present the site to the relevant searches. From a commerical stand-point the business would need to pay for advertising and sponsored links in order to improve the SEO.

"As a new user, I want the site to present the decor, styling and feel of how the bar is going to be."
- The images, colour schemes and fonts used have been carefully chosen to give a fair representation of the brand and the bar. This was considered during the "surface plane" phase of design. 
- The gallery page gives the user the chance to see more images of the bar

"As a new user, I want to be able to navigate the site in an easy and intuitive fashion."
- The navigation links, logo and footer stay consistent across all the pages. 
- The logo acts as a home button which is convention across all websites. 
- Social links represented with conventional icons are included as these are expected by the user. 

### Current User Goals:
"As a current user, I want to see updates to the menu as guest cocktails come and go."
- Using the navigation links, a menu of the classic cocktails can be viewed. 
- The guest cocktails can be viewed on social media using the icon links.
- Users have the option to sign-up for latest news and offers which'll include releases of new cocktails.
 
"As a current user, I want to be notified when new cocktails are released and / or when events are happening."
- Using the navigation links, a sign-up option is presented, this'll provide latest news and offers which'll include releases of new cocktails and events. 
 
"As a current user, I want to be able to navigate the site in an easy and intuitive fashion."
- The navigation bar at the top of the site is a standard convention that'll make the site easy to navigate. The bar is static to not take up too much screen space when scrolling. 
- For small devices such as a mobile, the navigation bar manages to say full-size for easy navigation.

## Manual Testing

Functionality:
Home page testing:
- Click on navigation bar to check the links work, underline to indicate page is functioning, hover to uppercase is working - confirmed to work.
- Click on logo/icon to check this goes back to home page on each page - confirmed to work.
- Embedded map is displayed and functional 
- Click each social icon in footer to check link and opens in new tab -confirmed to work for each page.

Menu page testing:
- Logo, navigation and footer already tested above

Gallery page testing:
- Logo, navigation and footer already tested above
- All images displayed as expected 
- Video autoplays on mute as expected

Sign-Up page testing:
- Logo, navigation and footer already tested above
- Form required fields for First Name, Last Name and Email Address return a prompt to fill in as expected
- Checkboxes action as expected when clicked
- Submit button returns error response as no database to link to - hover changes style of the button as intended

Responsive testing:
- Using google dev tools, screen szies for mobile (Iphone XR), tablet (Ipad air), computer screen and larger screen (up to 1500px) the responsiveness for each page is tested.
- Home page and Sign-up page images causing nav bar to not work on anything smaller than a computer screen around 950px

Validator Testing 
Validation tesing using W3C Mark-Up Validation Service:
- Home page: 2 errors returned which were both related to the sizing of the iframe embedding the map. It recommends not setting the sizing values as percentages however I found this is the best way to make the map responsive to screen sizes so I will keep the values as percentages. 
- Menu page: no errors returned
- Gallery page: 1 error returned which is related to the sizing of the embedded video. It recommends not setting the sizing values as percentages however I found this is the best way to make the map responsive to screen sizes so I will keep the width value as a percentage.
- Sign-Up page: Mistake made in the form with a duplicated ID, fixed. 2 errors related to the iframe of the embedded map - see home page errors above for this issue. 

Bugs

Solved bugs:

- Navigation bar not working on smaller screens:
This became a problem when the navigation bar moved underneath the header and caused the images on the home and form page to overlap the elements. Using the dev tool allowed the box model to be easily viewed and help understand what was happening. To fix this, I removed the float styling and opted for flexbox styling instead to control these elements. I found flexbox much easier to control compared to float.

- File paths not working after deployment:
During deployment the absolute links to the file structure were not working which lead to the site having no styling and some of the imaging wasn't showing. This was fixed by removing the "/" from these file paths allowing the browser to follow the links as intended.

![screen grab of the deployed page with no CSS](../Kiwi-cocktail-bar/assets/readme_images/deployment_css_issue.png)

Similar to the problem above, the gallery images were not displaying on the first deployment. This was fixed by ammending the file paths. 

![screen grab of the deployed gallery page with no images](../Kiwi-cocktail-bar/assets/readme_images/deployment_gallery_issue.png)

Unfixed Bugs

-Cover text over hero image positioning:
Between 550px and 750px the cover text doesn't quite sit on the image correctly. Having checked the devices on the dev tools this doesn't cause a viewing issue but can be seen when the browser is not at full size and sits between these widths. This cover text element has caused lots of issues throughout the development of this website and I'd like to completely start a fresh with the image and cover text to get it working in a more stable manner. 

![cover text box hanging below image](/assets/readme_images/unsolved_bug_cover_text.png)

# Deployment 

The project was developed using GitPod and all changes were pushed to GitHub to keep track and store the code. The website is deployed using GitHub pages which provides a link to the website once it has been published.

# Credits 

Media:
- Images were taken from Pexels 
- Video was taken from Pexels 

Words:
- About Us text taken from https://www.northcote.com/northcote-cocktail-bar/
- Menu items taken from Lost and Found Cocktail Bar, https://the-lostandfound.co.uk/restaurant/bristol

Code:
- W3Schools and Stack Overflow helped with various coding challenges 

Acknowledgements:
- Thank you to my mentor, Seun, for her time, patience and guidance on the development of this website. 
- Thanks also are given to the Code Institute Slack Community who are always on hand to help at a moments notice.