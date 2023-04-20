README.md 

# Kiwi Cocktail Bar 

Kiwi Cocktail Bar is a bustling new cocktail bar set in the heart of Cardiff. This site aims to entice customers to visit the bar by showing them whats to offer and giving them the opportunity to sign-up to a newsletter for upcoming events. The target audience will see a sophisticated and vibrant atmosphere which they will hopefully want to be a part of. This site will be useful for customers to see what is on offer, where the bar is located and be notified on upcoming events. 

This website has been made to complete the first project within the Code Institute Full Stack Developer course and focuses on the use of HTML5 and CSS3 in a responsive manner. 

[Add in responsive screenshot using “Am I Responsive?”]

[View the live project here - LINK]

# User Experience

The target audience for this site a young to middle age demographic who are looking for a classy place to socialise and enjoy their evening. The site is intended to attract new users and keep current users updated.


New User Goals:
- As a new user, I want to use a search engine, such as Google, to show me socialising venues within the area.
- As a new user, I want the site to present the decor, styling and feel of how the bar is going to be.
- As a new user, I want to be able to navigate the site in an easy and intuitive fashion.

Current User Goals:
As a current user, I want to see updates to the menu as guest cocktails come and go.
As a current user, I want to be notified when new cocktails are release and / or when events are happening.
As a current user, I want to be able to navigate the site in an easy and intuitive fashion.

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

[Add in structure of the website]
 
## Skeleton
In order to visualise how the content will be presented and where the features will be placed, some initial wireframes were used. Using wireframes at this stage of the projects allows the basic feel of the website to be visualised in a relatively quick way without the need for laborious coding.

Balsamic was used to create the following wireframes:

[Create wireframes and add in]

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
- The navigation links to move around the site are located in the top right of the screen. These are About Us, Menu, Sign-Up and Contact Us which link to their relevant sections of the site. 
- The font chosen is stylish to in-keep with the branding of the bar and colours are contrasting to ensure easy reading.
- The navigation links are consistent across the website which makes moving around the site easy and displays the information in a clear manner.  

[Add screenshot of the nav bar]

Issues to fix: 
Image “float” left so when re-sizing the pouring stays in the hero image - fixed with “no-repeat center left”
Images stacked on top of each other - does each image need a container? <section> doesn’t seem enough to stack the images…?

## The Header
- This section provides a clear overview of what the site is about and who it is for. 
- The header text is styled to continue the stylish / sophisticated theme which the blue colour showing the name of the bar KIWI COCKTAIL BAR and the text below in a contrasting 
- Header image zooms in slightly to give some movement to the page. The image has been carefully chosen to allow an effective display responsive to different screen sizes.

[Add screenshot of the header section]

## The About Us Section
- Aims to show off the vibe of the bar which will be a sophisticated and stylish environment.
- Information will be included to explain what the bar is about and how the offerings work. It’ll explains the classic menu which is always available as well as the guest cocktails which change regularly to keep customers interested. 
- The information displayed is easily readable with contrasting colours and a background image which complements the overall aesthetic of the site. 

[Add screenshot of the About Us section]

## The Sign-Up Form
- Gives customers the opportunity to be notified of upcoming events and new mixes that are being launched. 
- The form captures First Name, Last Name, Email Address and Alcohol Preferences which’ll be used to tailor the communications.

[Add screenshot of the Sign-Up Form]


## Contact us 
- Contact information and a location map
- Opening hours 

[Add screenshot of the Contact Us section]


## The Footer
- Social links includes to give the customer opportunity to stay connected on other platforms such as Instagram and Facebook 
- Summary of contact details 
- Footer stays as a slim bar across the bottom of the page at all times to ensure the social links and contact details are easily accessible. 

[Add screenshot of the footer section]

## Features to add in the future

[if there are any….]


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

# Testing

User stories 

[Test out the user stories above]

Manual Testing

[Clicking through the page to test out links, functionality, etc]

Bugs - solved bugs

Validator Testing 

Unfixed Bugs

Deployment 


# Credits 

Content

Media:
Images were taken from Pexels 

Code:
W3Schools

Acknowledgements:

[Test using slack community]
