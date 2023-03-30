# STILL LIFE

## Outline: 

'still life' is a photography site showcasing my own photography (which helpfully sidesteps copyright issues related to using other people's photography). There are 3 pages of content. Text is kept to a minimum for stylistic reasons so as to keep the focus on the images.

A contact form is provided for users to ask questions or comment, with a view to providing prints of photographs, or organising commissions or collaborations. 

# Live site
https://caketaster.github.io/Portfolio-Project-1---still-life/

# Repository
https://github.com/caketaster/Portfolio-Project-1---still-life

# Author
Benjamin Norman
https://github.com/caketaster

# Table of Contents
** add later **

# UX

 # Target Audience
 [Film] photography enthusiasts, people looking for photographic art prints to hang on their walls, photographers looking for collaborative projects, or anyone who would be interested in photographic commissions in the style presented. As such I aimed for a dark, intuitive, minimalist design with little text and a focus on the images. 

 # Project Goals
 To present images to the target audience in a stylish and intuitive way.
 To develop my own HTML and CSS skills whilst creating a viable website. 

# User Stories
## Site User Stories
## Website Owner Stories
## Developer Stories
** to be added **


# Design Choices

## Colours
I wanted a dark theme, which ties into the mood of the photography (which is generally devoid of people, and often dark scenes that have a shaft of light creating a glow in the shot). The glowing blue-white text stands out clearly against the dark background whilst also echoing the mood of the images, and the tertiary dark red colour also stands out and contrasts well. 
Ultimately I did make slight variations in text colour and glow colour just by intuition, and I don't feel this detracts from the overall consistency of the palette in a noticable way.
https://coolors.co/palette/181b1e-d3d8dd-d1d5d8-a1b9d2-4280be-b66f77

## Typography
I stuck to 2 fonts, Della Respira for the logo and Cantarell for the general body text. I used https://fontjoy.com/ to create the pairing. Ultimately I went on feeling as to what fonts would work best and fit the mood of the site. 
I decided to keep all text lowercase and avoid any commas, full-stops, punctuation etc. for stylistic reasons.

## Imagery
As this is a photography site I tried to be selective with the imagery. The aim was to have a semi-consistent mood/voice but have different styles of image in terms of content, aspect ratio etc. All images are my own, so any copyright issues are avoided. 

The icons all came from https://fontawesome.com/. I wanted to keep a consistent dark theme for the icons. 

## Animations and Transitions

The hero-image has a slow zoom animation. The aim was to draw the user into the image. The animation lasts 10 seconds, I wanted the transition to be subtle and thoughtful, which fits the aims of the site as a whole. 

Links glow on hover, as do the social icons, which echo the fixed glow on the logo. Gallery images lighten (which has a similar feeling to the text glow) on hover. This brings consistency to the whole site. 

# Site Structure
This is a 3-page site, Home, Gallery and Contact. The homepage loads by default. Primary navigation takes place using the nav menu bar at the top of each page, though clicking the logo returns you to the homepage from any other page, and the word 'contact' also links drectly to the contact page. Social links are naturally also clickable and open the relevant sites in separate tabs. 

Having 3 pages gives some separation to the site - the homepage has little function, the only real uses are to navigate to the Gallery or Contact pages, or social sites, but it does set the mood and feeling of the site as a whole in an uncluttered a way as possible. 

# Wireframes
Basic wireframes were created for desktop and mobile in Balsamiq, although the final design and function did change. 
** can I link to the balsamiq project, or should I add screenshots? **

# Features

## Implemented Features

### Homepage: 
Links all 'glow', as do the social media links, the site logo also has a fixed glow. The hero image has a slow zoom-in animation.
### Gallery: 
Flexbox used for gallery images, works with responsive design to look good on all screen sizes. Images brighten (similar feeling to the glow on the links) and have pop-up semi-translucent spans with image numbers when hovered over. Pop-ups on hover also help prevent users screenshotting the images - important if you're trying to sell images. 
### Contact page: 
The Send [Submit] button glows, roughly in line with other clickables on the site.

## Future Features
I would love the images to expand to full-screen on being clicked (or possible hovered over), and for hover-links to appear to, for example, add them to a section of the contact form. A user could thus click on each image they were interested in and the image numbers would populate the contact form. This would save the user having to remember specific image numbers before filling the contact form in. I believe this would involve javascript abilities that I do not yet possess. 

I originally envisioned this as mainly a sales site, so did have a Basket page, but decided against this for a few reasons. Firstly I didn't want the site to feel like a shopping site - it's a bit crass, and the mood of the site does not fit this functionality. Secondly it seemed easier in terms of coding to go with a simple contact form from which to open a dialogue about sales, if that's what the user is looking for. 

# Testing
** to be added **

# Validation Testing
** do after I've done Responsive design **
## CSS Validation
https://jigsaw.w3.org/css-validator/
## HTML Validation
https://validator.w3.org/
(insert a screenshot for each page)

# Compatibility and Responsive Testing
** Test on min. 3 screen sizes (I think) **


I used the Love-Running walkthrough project as a basic skeleton for the page, including the nav menu and hero-image zoom.

On the advice of my mentor I decided to use flexbox rather than floats, so made use of YouTube tutorials to give myself the knowledge to use them.

YouTube flexbox tutorial series:

https://www.youtube.com/watch?v=Y8zMYaD1bz0&list=PL4cUxeGkcC9i3FXJSUfmsNOx8E7u6UuhG&ab_channel=TheNetNinja

For the Gallery page I again used flexbox for a gallery responsive to different image dimensions with the help of the following website:

https://blog.logrocket.com/responsive-image-gallery-css-flexbox/#creating-responsive-image-gallery-uniform-image-dimensions

I used W3schools for the basics of making text (or number) boxes appear upon hover for the Gallery page:

https://www.w3schools.com/cssref/sel_hover.php

I used this page to create a textarea in the contact form

https://www.w3schools.com/tags/tag_textarea.asp


Testing:


Issues: 

1 top menu spacing seems uneven (due to different word lengths?) FIXED
2 cover-text not centered vertically, uneven space comparing top and bottom padding FIXED
2.1 likewise the cover numbers on the Gallery page FIXED
3 logo breaks when screen shrinks - using <br> in html and it's ugly and inefficient - need a solution FIXED
4 socials now on each page, decided (almost certainly) to have a Form page to submit quries to buy prints etc. (this will be the Contact page). Basket page to be binned. FIXED
5 still unsure what happens when you click an image..? Fills screen ideally. And what info is there? - add to query, close image, next image, ..? User can contact me about specific image(s)? 
6 still unsure of the purpose of the site haha. Maybe can select images then send email referencing each image clicked
7 the gallery images don't always keep their correct dimensions, it depends on the page size. annoying. FIXED
8 gallery hover-numbers sometimes more or less visible depending on the background.
9 can I style the placeholder text on the contact form? FIXED
10 the contact form is high in the div, not centred FIXED

What I would like to add:

Images to expand upon select (possibly with a menu embedded - image number, image info (camera/film used etc) and a link to add to the form, as explained below).

A way to link clicking on each image to the form, so that users can click on the image(s) they want to ask about and the form add that image number automatically.

# Deployment

## Production
This website was deployed to GitHub Pages. 
The following steps were taken to deploy: 
1. Click the Settings cog on GitHub
 ![Screenshot 2023-03-25 at 10 53 42](https://user-images.githubusercontent.com/97278488/227685366-aa2acd1f-76de-4cbf-8d1f-ae794b745e2c.jpg)

2. In the left-hand nav, click on the Pages tab 
 ![Screenshot 2023-03-25 at 10 57 03](https://user-images.githubusercontent.com/97278488/227686313-9f440a2f-a4b8-4d86-ba57-0f8143da7a07.jpg)
 
3. In the Branches section, select Main
  ![Screenshot 2023-03-25 at 11 01 19](https://user-images.githubusercontent.com/97278488/227687270-2369bfaa-76f0-4fc7-ac36-bc75ab97ff1b.jpg)

4. Click Save
![Screenshot 2023-03-25 at 11 01 48](https://user-images.githubusercontent.com/97278488/227687445-0de90a4f-d984-4845-986c-ddaaf7402abf.jpg)

5. Site is now deployed
 ![Screenshot 2023-03-25 at 11 05 34](https://user-images.githubusercontent.com/97278488/227688005-077f6d54-4af4-4d55-aadc-3075d38cf3c2.jpg


Fixed contact form alignment
Increased opacity on hover numbers