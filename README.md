Outline: 

'still life' is a photography site showcasing my own photography (which helpfully sidesteps copyright issues related to using other people's photography). There are 3 pages of content. Text is kept to a minimum for stylistic reasons so as to keep the focus on the images.

Features:

* Homepage: links all 'glow', as do the social media links, the site logo also has a fixed glow. The hero image has a slow zoom-in animation.
* Gallery: flexbox used for gallery images, works with responsive design to look good on all screen sizes. Images brighten (similar feeling to the glow on the links) and have pop-up semi-translucent items with image numbers when hovered over. 
* Contact: 

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

1 top menu spacing seems uneven (due to different word lengths?)
2 cover-text not centered vertically, uneven space comparing top and bottom padding
2.1 likewise the cover numbers on the Gallery page
3 logo breaks when screen shrinks - using <br> in html and it's ugly and inefficient - need a solution
4 socials now on each page, decided (almost certainly) to have a Form page to submit quries to buy prints etc. (this will be the Contact page). Basket page to be binned.
5 still unsure what happens when you click an image..? Fills screen ideally. And what info is there? - add to query, close image, next image, ..? User can contact me about specific image(s)? 
6 still unsure of the purpose of the site haha. Maybe can select images then send email referencing each image clicked
7 the gallery images don't always keep their correct dimensions, it depends on the page size. annoying. 
8 gallery hover-numbers sometimes more or less visible depending on the background.
9 can I style the placeholder text on the contact form?
10 the contact form is high in the div, not centred

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
