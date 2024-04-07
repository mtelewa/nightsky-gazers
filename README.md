<h1 align="center">Stargazers Website</h1>

[View the deployed project here](https://mtelewa.github.io/nightsky-gazers/gear.html)

STARGAZERS is a website for amateur and professional astronomers to get to know top stargazing locations and a basic understanding of the gear involved and most importantly to meet up. The website thrives on getting the astronomer community closer on a global scale.

![Mockup](documentation/features/mockup.png)

## Contents
* [User Experience (UX)](#user-experience-ux) 
* [Design](#design)
    * [Color scheme](#color-scheme)
    * [Typography](#typography)
    * [Imagery](#imagery)
    * [Wireframes](#wireframes)
    * [Accessibility](#accessibility)
* [Features](#features)
* [Technologies Used](#technologies-used)
    * [Languages](#languages)
    * [Frameworks and Libraries](#frameworks)
* [Deployment & Local Development](#deployment-development)
    * [Deployment](deployment)
    * [Local Development](#development)
* [Testing](#testing)
    * [Validator Testing](#validator)
    * [Browser Compatibility](#compatibility)
    * [Test Cases and Results](#test-cases)
    * [Known Bugs](#bugs)
* [Credits](#credits)
    * [Code Used](#code-used)
    * [Content](#content)
    * [Media](#media)
    * [Acknowledgement](#acknowledgement)

- - -

## User Experience (UX)

### User Stories

#### First Time Visitor Goals

* I want to join a stargazing community nearby, I am interested in astronomy but I don't know where and how to begin
* I want to understand the difference between different stargazing equipment
* I want to meet up with people sharing the same interest
* I want the site to be responsive to my device
* I want the site to be easy to navigate

#### Returning Visitor Goals

* I want the information about stargazing locations to be in one place
* I want the site to be responsive to my device
* I want the site to be easy to navigate

#### Frequent Visitor Goals

* I am travelling around and want to check new places for stargazing and meet other stargazers there
* I want to contact the organisation to give feedback or ask questions

- - -

## Design

### Colour Scheme

The colors chosen were based on the background image of a stary night sky. The colors shall give the user a feeling of a calm night in the desert or from a mountain top - just like how it would be when stargazing. The color palette used is inspired by
<br>
<br>

<p align="center">
    <img src="documentation/design/color-palette.png" alt="Color Palette" width="50%">
</p>

Aside from the dark blue background image, I have used mainly 

* `rgba(191,191,191,0.4)` for `div` boxes border and shadow
* `rgba(7, 3, 51, 0.6)` for the footer background
* `color:rgb(253, 165, 0)` for hover effects
* `#ffffff` for the font to provide contrast against the background

### Typography

Google Fonts was used to import the chosen fonts. The three main fonts used across the website are

* For the `h1` and navigation icons `nav` in the header, [Montserrat](https://fonts.google.com/specimen/Montserrat) 

* For the paragraphs `p` and `h3`, [Hind Madurai](https://fonts.google.com/specimen/Hind+Madurai)

* For everything else, [Lora](https://fonts.google.com/specimen/Lora)

The choice was inspired by [Font joy](https://fontjoy.com/#).

### Imagery

The website calls for looking up into the stars, so I wanted to give this experience with minimum distraction from the content. The image was pulled from [Freepik](https://www.freepik.com/).

## Wireframes

Wireframes were based on hand sketches on my personal tablet using a stylus. Since the initial wireframes differ a lot from the final website, I decided not to include them here. However, for future projects, I am sure [Balsamiq](https://balsamiq.com/) or [Figma](https://figma.com/) will be essential.

### Accessibility

The website is as accessible as possible. Specifically by following these good-practice guidelines

* Accessible Rich Internet Applications (Aria) labels on interactive elements, links and icons
* Semantic HTML
* Using a hover state on all buttons on the website

<p align="center">
  <img src="documentation/design/button-accessibility.png" alt="button contrast"/>
</p>

* Sufficient color contrast throughout the site including dark blue background as a fallback color in case the background images do not load (this was later removed as it made the website look buggy as it loads!)

I used the chrome extension [Web Disability Simulator](https://chrome.google.com/webstore/detail/web-disability-simulator/olioanlbgbpmdlgjnnampnnlohigkjla) to check for **total** as well as **Yellow-blue color blindness (Tritanopia)** color blindness. The latter was checked as blue is the prevailing color throughout the website. The reults are shown here, respectively.


<p align="center">
<img src="documentation/design/total-color-blindness.png" alt="total blindness" width="45%">
<img src="documentation/design/tritanopia.png" alt="tritanopia" width="45%">
</p>

As can be concluded, there is still enough contrast between the text and the background.

- - - 

### Features

The website consists of 
* Home page with quick links to other pages and about-us information
* Locations page to show top stargazing sites
* Gear page to present the comonly-used telescopes and their differences
* Join Us! page for sign-up and writing feedback or any message

The main features of the website are

* A **favicon** in the browser tab.

<p align="center">
<img src="documentation/features/favicon.png" alt="favicon" width="20%">
</p>

* The header and navigation bar **on every page** to **facilitate steering** on the website. With **hovering effects** (in orange) and **underline** to **show the current page**. The navigation bar also has **icons** from [Font Awesome](https://fontawesome.com/) for **easier visualisation**

<p align="center">
<img src="documentation/features/nav-bar.png" alt="navigation bar" width="80%">
</p>

* The home page features three main boxes at the top of the page. The **headings of these boxes are clickable** and **navigate the user** to the corresponding page. The "Where to look?" leads to "Locations" page, the "How to look?" leads to the "Gear" page and the "Want to join the community?" leads to the "Join Us!" page

<p align="center">
<img src="documentation/features/home-page.png" alt="home page" width="80%">
</p>

* **Toggle dialog boxes** to present additional information about our inspirational figures **without filling the page with text**.

<p align="center">
<img src="documentation/features/toggle-box.png" alt="home page" width="80%">
</p>


* **Interactive `iframe`** adopted from [Nasa](https://eyes.nasa.gov/apps/solar-system/#/home) at the bottom of the home page. This allows the user to **check the current sky alignment**, also go back and forward in time to visualise the solar system in the past as well as the future as predicted by Nasa 

<p align="center">
<img src="documentation/features/iframe.png" alt="iframe" width="80%">
</p>

* **External links** for additional information on our stargazing sites

<p align="center">
<img src="documentation/features/external-links.png" alt="iframe" width="50%">
</p>

* **Responsive design** to different display sizes (more on that in the [Testing](#testing) section)

* **Message/Feedback** box for contacting the organisation

<p align="center">
<img src="documentation/features/form-responsive1.png" alt="large display" width="70%">
<img src="documentation/features/form-responsive2.png" alt="small display" width="20%">
</p>

* How the features support user stories

* Future Implementations that shall allow returning and frequent users to visit more often

    * Create a forum for users to communicate with each other on the platform
    * Add 'News' section to share the latest in the astronomy community 
    * Add an up-to-date 'Gallery' page to showcase the images taken by our astrophotographers community
    * Add 'search' box in the navigation bar 
    * Add 'Fun facts' pop-ups to make the website more interacive and include all ages


