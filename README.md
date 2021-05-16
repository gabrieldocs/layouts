# layouts

Building Comprehensive and Abrangent Layouts for the web. 

<hr>

## Author 

Lucas Gabriel. Guilherme dos Santos 

Computer Engineer at Uninta
@lucgbrl @gabrieldocs


## About

This repo contains some layouts I am building with CSS Grid and CSS Flexbox to replace old Bootstrap pages. The layout itself is very shallow, but I am trying to make it compreehensive and abragent in order to fit desktop and mobile version and to have some flexibility in order to be converted to a VueJS or ReactJS project in the future.

The components appearance is not its final. The idea behind the project is to provide the layout and UI organization**. 
Cards, buttons, Font-families and more about the design system can be implemented by the interested-self. 

## Instalation 


### Import to HTML
To install Layouts CSS you need to link the css file to the html or js (if you're using ReactJS you probably are familiar with imports).

```
<link rel="stylesheet" href="dist/css/home.css">

```
### Import into a ReactJS component file 

The ReactJS style is the well-known ```import './location/to/file.css';``` : 

```javascript 
import React, { Component } from 'react';
import './home.css'; // Tell webpack that HomePage.js uses these styles

class HomePage extends Component {
  render() {
    // You can use them as regular CSS styles
    return(
      <section className="home">
        <header> ... </header>
        <main>...</main>
        <aside>...</aside>
        <footer>...</footer>
      </section>
    );
  }
}
```

That's it! We are now all set. 


### Styles

This project aims to provide a compiled layout solution, in order to enable developers and webdesigners to quickly setup any content in a giver pattern, so It does not cover complex UI elements such as cards, billboards, chips, buttons...anyway, but we have a few recommendations about typography and spacing.  

#### Typography

A nice font-family is 'Noto Sans JP'. The theme/_text.scss_ folders contains a import from Google Fonts that can be rewritten if needed. 
A convention on my layout was that h1 elements are 3em and all other heading elements get to keep their traditional size. 

#### Spacing 

When in need of vertical and horizontal padding use 12px 24px.
When in need of a container padding 12px looks good for most cases. 


#### Colors 

Choose nice contrasting colors when sketching yout layout / design system, some cool projects like...give you nice collections of colors and palletes in order to be accessible and harmonic. 


## Version 

I am still deciding the best strategie to control the versioning and name conventions. Ideas can be added in the issues section.

## Layout 01 - Dashboard

The image below illustrate the general structure of the dashboard in desktop view.
It uses the following elements to build the UI:

  - nav 
  - main 
    - header
    - section 
    - div 
      - header 
      - table 
  - aside
   

## Layout 02 - Homepage 

This is a desktop homepage sample.
