# IP Address Tracker

## Welcome! 👋

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [How to setup the project](#how-to-setup-the-project)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Discover the location, timezone, and ISP of any IP address with the IP Address Tracker! 

This webpage allows users to
- View the optimal layout for each page depending on their device's screen size.
- See hover states for all interactive elements on the page.
- Find their own IP address on the map on the initial page load. 
Users can also search for any IP addresses or domains and see the key information and location.

## Author 
<b><strong>Vinay Joshi</strong><b>
-Email - Vinay.joshi1608@gmail.com


### Built with

- HTML5
- CSS3
- JavaScript
- Leaflet.js (for the map)
- IP Geolocation API (for fetching IP address details)

You will find all the required assets in the `/design` folder. The assets are already optimized.

There is also a `style-guide.md` file containing the information you'll need, such as color palette and fonts.

### What I learned

This project is great at understanding how to execute basic CSS features like flexbox, responsive layout using media queries for both desktop and mobile and all sizes in between as shown below-

```css
@media (max-width: 920px) {
    .info-field {
        font-size: .9rem;
    }
}

@media (max-width: 770px) {
    #ip-input {
        width: min(380px, 70%);
    }

    .info {
        width: 85vw;
    }
}

@media (max-width: 600px) {
    .top {
        height: 35vh;
        padding: .7rem;
    }

    .title {
        font-size: 1.5rem;
    }

    .info {
        width: 75vw;
        flex-direction: column;
        text-align: center;
        gap: 1.1rem;
        top: 12%;
    }

    .box {
        width: 100%;
        border: none;
    }
}

