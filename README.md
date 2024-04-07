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

The colors chosen were based on the background image of a stary night sky. The colors shall give the user a feeling of a calm night in the desert or from a mountain top - just like how it would be when star gazing. The color palette used is inspired by
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

### Accessibility

The website is as accessible as possible. Specifically by following these good-practice guidelines

* Accessible Rich Internet Applications (Aria) labels on interactive elements, links and icons
* Semantic HTML
* Using a hover state on all buttons on the website

<p align="center">
  <img src="documentation/design/button-accessibility.png" alt="button contrast"/>
</p>

* Sufficient color contrast throughout the site including dark blue background as a fallback color in case the background images do not load

I used the chrome extension [Web Disability Simulator](https://chrome.google.com/webstore/detail/web-disability-simulator/olioanlbgbpmdlgjnnampnnlohigkjla) to check for **total** as well as **Yellow-blue color blindness (Tritanopia)** color blindness. The latter was checked as blue is the prevailing color throughout the website. The reults are shown here, respectively.


<p align="center">
<img src="documentation/design/total-color-blindness.png" alt="total blindness" width="45%">
<img src="documentation/design/tritanopia.png" alt="tritanopia" width="45%">
</p>

As can be concluded, there is still enough contrast between the text and the background.

- - - 

