# Scattered Photo and Video Gallery by 54ka

Version 2.48

![Image](https://raw.githubusercontent.com/54ka/Scattered-Photo-and-Video-Gallery/main/Screenshots/Screenshot_001.jpg)

Scattered Photo and Video Gallery by <54ka> creates a Flat or 3D gallery of scattered pictures and videos, with many and easy ways to modify.

Scattered Photo and Video Gallery is Pure (Vanilla) JavaScript Image Gallery.

Scattered Photo and Video Gallery it's Compatible with Responsive design and is extremely easy to visually modify and use. Through it, you can create both static HTML and be integrated into dynamically generated content.

[More Info - Live Demos and Examples](https://www.54ka.org/apps/scattered-photo-and-video-gallery)


# Features

Images
-----------
* Modify photos in gallery  
* Displayed Horizontal and Vertical shots  
* Determine size on the long side  
* Easily create a Polaroid gallery  
* Image border control  
* Control of shadow intensity  

Scattered
-----------
Choose between two types of scattering

* Internally  
* Externally  

Navigation
-----------
Show or Hide navigation dots

Flat and 3D
-----------
Choice between Flat and 3D Scattered gallery

* Flat Scattered   
* Flat Straight   
* 3D Scattered  
* 3D Straight

Screen
-----------
Choosing a way to visualize

* View Full Screen in the browser  
* You can restrict the gallery only within part of the screen

Photo info
-----------
Control of visualized text information - on/off  

* Text box overlay the photo  
* Text box below the photo  
* Text field under the photo (Polaroid type)  


# How to use

1. Add CSS: ffka-sc-photo.css

```html
<html>
<head>

    <link rel="stylesheet" href="ffka-sc-photo.css" type="text/css">

</head>
<body>
```

2. Add Images in DIV with id="ffka_sc_wrap"  
(src - Image file path / alt - Info text / srcset - YouTube or Vimeo embed link)

```html
    <div id="ffka_sc_wrap">
        <!-- Example: Image, Info, Video -->
        <img src="001.jpg" alt="add info here..." srcset="add YouTube or Vimeo embed link here">
        <!-- Example: Image, Video -->
        <img src="002.jpg" srcset="add YouTube or Vimeo embed link here">
        <!-- Example: Image -->
        <img src="003.jpg" >
    </div>
```

3. Add ffka-sc-photo-2.48.js аt the bottom of the page

```html
    <script src="ffka-sc-photo-2.48.js" type="text/javascript"></script>

</body>
</html>
```


# Customize settings


```js
// Image size - For the long side
var PhotoSize = 595;

// Border size - use 0 if you don't wanna image border
var BorderSize = 10;

// Photos Shadow - from 0 to 99
var PhotoShadow = 30;

// Fullscreen or limit in parent element
// true - Fullscreen - Use Browser size 
// false - Use element size
var Screen = true;

// Scattering type
// true - Internally 
// false - Externally
var Scattering = true;

// Scattered Variation - 1,2,3 or 4
// 1 - Scattered
// 2 - Straight 
// 3 - Scattered 3D 
// 4 - Straight 3D
var Arstr = 1;

// Photo info
// true - Show info 
// false - Hide info
var PhotoInfo = true;

// Info screen Design - 1,2 or 3
// 1 - Touched under the picture
// 2 - Below the photo
// 3 - Overlay on the photo
var Info_Style = 3;

// Dots Navigation
// true - Show Navigation 
// false - Hide Navigation
var ShowNavigation = true;

// Slideshow Settings /////////

// Auto Slideshow
// true - Auto play slide show 
// false - Disable slide show
var AutoSlideShow = false;

// Slideshow time duration in seconds
var TimeDuration = 2;
```


# License

Scattered Photo and Video Gallery by 54ka is licensed under the GPLv3 [http://choosealicense.com/licenses/gpl-3.0] license for all open source applications. A commercial license is required for all commercial applications (including sites, themes and apps you plan to sell). 

Copyright (c) 2021, www.54ka.org

Buy License from:
https://54ka.org/apps/scattered-photo-and-video-gallery/