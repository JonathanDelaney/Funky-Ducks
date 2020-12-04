<h1 align="center">Funked Up Chicks</h1>

Live website :arrow_down:<br>
<a href="https://jonathandelaney.github.io/Funked-Up-Chicks/index.html">![alt](./assets/images/readme/templateimage.png)</a>

## About

This is a fictitious band's website. The Funked Up Chicks' online presence is the result of a lack of inspiration for something good to do without the help of JS and preferring music bands to the other suggested topics.

## User Stories

- The casual stumbler

  - I want to know immediately what the band is about and what kind of musical experience to expect.
  - I want to be able to navigate the site easily.
  - I'd like for the website to be engaging and interesting to look at and explore without having the allure of a band i like encouraging me to look around.

- Someone who has heard of the band but knows little or nothing about them

  - (See previous user story)
  - I want to be able to jump directly to the page which has the information I want.
  - I should see the relevant information on each page to allow me to "get into" the band.

- A fan or someone who knows the band
  - I want to see the band represented the way i know/love them.
  - I would like to see all the info I need to keep up with their work.
  - I would want to be able to book them should i like or find out where/when I can see them.

## Design and Creation

I wanted to create a website that was representative of the genre of music but had character of its own as well. When designing the website I first came up with the genre I wanted the band to be in. I chose funk because it's a great genre of music, and one that I love very much, but also because it seemed like a colourful genre in which I could explore lots of different ideas and be creative. <br>
<br>
The next phase was coming up with the name, something which would pin down some points of the character of the band and thus the website. "Pumped up kicks" by Foster the People served as inspiration for the name, the derviation obvious there. A group of women who've got their funk on!<br>
<br>
With an image of the band now in my mind I could see what their image would be. I pictured three women with colorful hair and style and wearing sixties/seventies clothes. I don't know why myabe because that is when funk came into existance first. Nonetheless it was formed in my mind as such and so I would commit to it. With this now sort of old school image in place I liked the idea of using records in the website and having them play a central role in tying the site together.<br>
<br>
I went to work on the mockups, piecing things together as i went. The records took a backseat and onkly one ended up as the backdrop to the homepage and a record shop featured in a couple of other pages, however the old school style came through other design features such as brown paper backdrops and floral header creations. It was only when programming the website that I found inspiration to use the records more effectively in the design of the website. 

## Mockups

* ### Mobile

<img src="./assets/images/readme/iphone1.jpg" height="400px" /> <img src="./assets/images/readme/iphone2.jpg" height="400px" /> <img src="./assets/images/readme/iphone3.jpg" height="400px" /> <img src="./assets/images/readme/iphone4.jpg" height="400px" /> <img src="./assets/images/readme/iphone5.jpg" height="400px" />

* ### Tablet

<img src="./assets/images/readme/ipad1.jpg" height="400px" /> <img src="./assets/images/readme/ipad2.jpg" height="400px" /> <img src="./assets/images/readme/ipad3.jpg" height="400px" /> <img src="./assets/images/readme/ipad4.jpg" height="400px" /> <img src="./assets/images/readme/ipad5.jpg" height="400px" />

* ### Desktop

<img src="./assets/images/readme/web1.jpg" height="400px" /> <img src="./assets/images/readme/web2.jpg" height="400px" /> <img src="./assets/images/readme/web3.jpg" height="400px" /> <img src="./assets/images/readme/web4.jpg" height="400px" /> <img src="./assets/images/readme/web5.jpg" height="400px" />

## Features

* ### Header

    - The header has a flex display with the height set with a calc() so it scales without a media query. The hover effect gives the heading psychodelic "pop".
    - The menu items are aligned to the bottom of the header and are media queried to disappear for medium and smaller screen sizes when a bootstrap dropdown menu appears below the header in the left corner. Hover effects on the menu items let them appear as though they are file tags coming off the background slightly.

* ### Homepage

    - The homepage menu items are layed out on record sleeves which are positioned inline-block. Some rotate and margin gives them an arched layout.
    - The hover effect is to simulate the records falling out of the sleeves. The sleeves have a rotate, shadow and scale transition. the records have an opacity, shadow and translate(Y) transition.
    - The responsiveness is given by changing the margin around the sleeves and the padding of the container.

* ### The Band page

    - The layout of the container is done with flex. Stevie align to start and the others centered to give a stepped look. The info box is gien asbolute to not disturb the layout of the flexbox and is centerd at the bottom of the page.
    - The hover effects on the pictues and titles are to scale up and then delay the return to normal so that the info box has time to collapse in first. Likewise the info box is delayed to not appear before the faces scale up. The effect on the info boxes is on scale and the transform origin is set to make it appear as though the info boxes are coming from the faces.
    - The media query changes the container to a flex column and makes the info boxes visible and below their respective band members. Calc() allows these to scale from medium to small with only padding adjusted for small screens.

* ### The Events page

    - The events page is layed out using bootstrap as its grid layout was the simplist for responsiveness.
    - The background is a blend-multiply of a paper image and galaxy map to achieve a vintage/modern marriage.
    - The height of the background was really all that needed to change with media query.

* ### The News page

    - The layout is done with flex in two containers. The one for the reports has a start and end alignment for each of the articles respectively.
    - The media query changes the padding and height of the background and changes the flexbox to column fro small displays. Calc() is once again instrumental in scaling all the divs on the page.

* ### The Bookings page

    - This page contains two flex containers. The form is align centrally with the submit button given a percentage width and margin so it's responsive and the rest of the container responds as a flex box and only relys ona media query for small screens to adjust the padding and margin.
    - The social media container has the fontawesome icons acting as links to the social media and music platforms. The margins on these change and the height of the container to give a nicer layout for smaller screens.

## Technologies Used

-  HTML5
-  CSS3
-  AdobeXD
-  Vectr

## Testing

<img src="./assets/images/readme/webtest.png" height="100px" />

## Credits

I got my images from pixabay.com and freeimages.com. None of the images used require license to publish.
Kevin Powell's youtube channel and various github and stackoverflow posts gave me ideas but I typed every line of code myself.