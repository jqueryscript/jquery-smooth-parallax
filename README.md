# Jquery smooth parallax
A clean parallax in jquery, simple to integrate, and totally responsive.

Original Author: https://github.com/Najdaoui

Live Demo : [https://www.jqueryscript.net/demo/parallax-image-smooth/](https://www.jqueryscript.net/demo/parallax-image-smooth/).

## Getting Started

These instructions will provide you with a copy of the operational project for development and testing purposes. Remember that any code depends on the context of your project.

### Prerequisites

Make sure that in your css style, the width and height of the body and html tags are set to 100%.

However, you can add the line below to your css file to make sure it works.

```
html, body {width: 100%; height: 100%}
```
This plugin uses ```reset.css```. You can use it yourself too. For more information on ```reset.css``` [click here](https://gist.github.com/DavidWells/18e73022e723037a50d6 "Source code - reset.css").

## Installation

First of all, place this tags below in your head:

```
<script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
<link rel="stylesheet" href="jquery-smooth-parallax.css">
<script src="jquery-smooth-parallax.js"></script>
```

Be sure to mention the branch where you will place ```jquery-smooth-parallax.css``` and ```jquery-smooth-parallax.js```

If your folder is called assets, the src and href attributes will be like that: ```assets/jquery-smooth-parallax.css``` and ```assets/jquery-smooth-parallax.js```

Copy the hero section in your project:

```
<section name="hero" class="hero-section">
  <img src="YOUR-IMAGE" alt="" class="hero-image">
  <div class="hero-wrapper">
    <div class="hero-content">
      <h1 class="hero-title">YOUR TITLE</h1>
      <p class="hero-subtitle">YOUR SUBTITLE</p>
      <a href="">YOUR BUTTON</a>
    </div>
  </div>
 </section>
```

### Two button case

If you want to put two buttons in the hero section, use the following code:

```
<section name="hero" class="hero-section">
  <img src="YOUR-IMAGE" alt="" class="hero-image">
  <div class="hero-wrapper">
    <div class="hero-content">
      <h1 class="hero-title">YOUR TITLE</h1>
      <p class="hero-subtitle">YOUR SUBTITLE</p>
      <div class="hero-btns">
        <div class="btn">
          <a href="">YOUR BUTTON 1</a>
        </div>
        <div class="btn">
          <a href="">YOUR BUTTON 2</a>
        </div>
      </div>
    </div>
  </div>
 </section>
```

## Deployment

By default, the opacity of the image is set to 0.55 to create an overlay, and the background of the section is black. To change it, follow these instructions:

### Opacity

#### Step 1:
In line 10 of the ```jquery-smooth-parallax.css``` file, change the ```opacity``` from ```0.55``` to the value you want.

#### Step 2:
In lines 11, 13, 25 of the ```jquery-smooth-parallax.js``` file, change the opacity from ```0.55``` to **the value that you set in the css file**.

### Background
In line 2 of the ```jquery-smooth-parallax.css``` file, change the ```background``` from ```#000``` to the color you want.

## Credits

* JQuery : [Source code](https://code.jquery.com/jquery-3.4.1.min.js "Version 3.4.1").
* Css - reset.css : [Source code](https://gist.github.com/DavidWells/18e73022e723037a50d6 "Source code - reset.css").
* Image : Photo by [Daan Huttinga](https://unsplash.com/@daanhuttinga) on [Unsplash](https://unsplash.com/).

