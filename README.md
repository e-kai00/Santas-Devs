# Expressive E-Cards

Expressive E-Cards is a harmonious fusion of technology and heartfelt sentiments that emerged from a spirited hackathon project! Immerse yourself in the festive spirit with our delightful creation, offering users the joy of crafting personalized digital greeting cards that transcend the ordinary.

View the live project [here](https://e-kai00.github.io/Santas-Devs/).

![Project](/assets/images/readme/hackathon-dec23.png)

## Table of Contents

- [Design](#design)
  - [Typography](#typography)
  - [Color Scheme](#color-scheme)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Future Features](#future-features)
- [Development](#development)
  - [Card Generator - Creating the Card](#card-generator---creating-the-card)
  - [Card Generator - Sharing the Card Using a Link](#card-generator---sharing-the-card-using-a-link)
  - [Snow Animation Explanation](#snow-animation-explanation)
    - [Front Image Layer](#front-image-layer)
    - [Middle Layer (Snow Animation)](#middle-layer-snow-animation)
    - [Rear Layer (Full Image without Transparency)](#rear-layer-full-image-without-transparency)
- [Deployment](#deployment)
- [Credits](#credits)
  - [Content](#content)
  - [Members of Santa Dev's Team](#members-of-santa-devs-team)


## Design

### Typography

Th following [Google Fonts](https://fonts.google.com/) were used for this project:

- *Courgette* is utilized for the project's logo and headers.
- *Poppins* serves as the default font.
- *Great Vibes* is selected as a secondary font and brings a touch of sophistication to specific text elements.

Icons
[FontAwesome](https://fontawesome.com/) and [Bootstrap](https://icons.getbootstrap.com/) icon libraries are used to enhance the visual appeal and usability of the website.

### Color Scheme

Expressive E-Cards employs a captivating color scheme, thoughtfully to create a dynamic contrast:

- #FDF4E3 (Cream):
This pale yellow hue is used for fonts on darker backgrounds to maintain readability with a soft and inviting touch.

- #A02C2C (Maroon):
Deep and rich, this maroon shade adds a touch of sophistication to key elements, creating a visually striking contrast.

- #0B3D2E (Forest Green):
Dark green reminiscent of a lush forest, used strategically to bring depth and balance to the overall design.

- #DAA520 (Goldenrod):
A vibrant and cheerful shade of gold, used as an accent color to highlight key features and elements, adding a festive flair.

![Color palette](/assets/images/readme/color-scheme.png)

## Technologies Used

The key technologies employed in the project include:

- HTML 
- CSS 
- JavaScript
- Bootstrap 5

## Features

### Ambience Animation
- Snow
  - The user is able to see snow falling in the room window to create a scenic atmosphere.

### Christmas Countdown Timer
- Live countdown to Christmas
  - The user can visibly see a countdown timer running up till Christmas day.
### Card Generator
- Creation of card
  - Users can create and preview a greeting card.
- Sharing a URL link of created card
  - Users can click a link that will create a URL that can be shared with their receipient - viewing it in an internet page. 
- Saving of card to device
  - Users can download a copy to their local device.
### Music Player
- User controlled music player
  - Users can click to play music and change tracks whilst on the website. It can be paused and played aswell as navigating to the next track and previous track.
### Help and Instructions
  -  Users have access to information modals to help them navigate their way around the website.
### About Us Page
  - Users can see the profiles of the developers behind the website and click to the Github pages.

## Future Features

- Glow creation and image enhancement.
  - The candles have been animated to glow giving a 3d experience.

## Development

### Card Generator - Creating the Card

- A Bootstrap carousel displays background images for user selection via a dropdown menu.
- The input options allow a user to add a recipient, greeting message, and a sender.
- The chosen background and text can be viewed as a preview window using HTML canvas.
- The chosen design - both image and text can be seen in real-time.
- Users can add text and change text before being ready to share.
- Once ready, they can click the share button to get a shareable link.

### Card Generator - Sharing the Card Using a Link

When the user clicks the 'create link' button on the card generator form, a 
link is created containing the encoded form field values which the user can 
send to the recipient to share the card.  

When the recipient follows the link, their card and personalized message are 
displayed.

A detailed description of how this functionality was implemented can be found 
here: [https://github.com/hypergeek-dev/Santas-Devs/issues/17#issuecomment-1858987879](https://github.com/hypergeek-dev/Santas-Devs/issues/17#issuecomment-1858987879)

### Snow Animation Explanation

I've implemented a captivating snow animation on my website using three distinct layers, each playing a crucial role in creating the desired effect. Let me break it down for you:

#### Front Image Layer

- This is the foremost layer in the animation. It features an image with transparency applied to the window tiles, adding depth and realism to the overall scene.
- The transparent window tiles allow viewers to peer through and see the layers beneath, simulating the idea of looking out from a cozy interior onto a snowy landscape.

#### Middle Layer (Snow Animation)

- The middle layer is where the magic happens. I've utilized JavaScript to craft a dynamic snow animation that gracefully falls from the top of the viewport to the bottom.
- Snowflakes or snow particles gently drift down the screen, creating a serene and wintery ambiance.

#### Rear Layer (Full Image without Transparency)

- This layer serves as the background canvas for the entire scene. It contains the complete image without any transparency effects.
- By positioning this layer behind the others and adjusting its z-index, I've ensured that it provides the static backdrop for the animation.

The use of z-indexing in CSS allows these three layers to harmoniously interact, resulting in a visually appealing and immersive snow animation on my website. It's a delightful way to engage visitors and set a festive mood during the winter season.


## Deployment

This project is published on the GitHub Pages, thus deploying it is a straightforward process. Follow these steps to make your project live:

1. Begin by forking the Expressive E-Cards repository. Click the "Fork" button at the top right of the repository page. This creates a copy of the project under your GitHub account.
2. Navigate to your forked repository on GitHub.
3. In your forked repository, click on the "Settings" tab.
4. From the left-hand menu, select the "Pages" tab.
5. Under the "Source" section, choose the "Main" branch from the drop-down menu.
6. Click the "Save" button to apply the selected branch as the source for GitHub Pages.
7. Once saved, a confirmation message will indicate a successful deployment to GitHub Pages.
8. Visit the provided live link to explore the deployed project in action.

## Credits

### Content

- The front-image used in the landingpage is free of use from [Vecteezy](https://www.vecteezy.com/)
- All vector graphics originate from [Pixabay](https://pixabay.com/)

### Members of Santa Dev's Team 

- [Ruksana](https://github.com/BegumDev)
- [Charley Roberts](https://github.com/charleymroberts)
- [Atchutchi Ferreira](https://github.com/atchutchi)
- [Ekaterina](https://github.com/e-kai00)
- [Dennis Jensen](https://github.com/hypergeek-dev) (Scrum master)



