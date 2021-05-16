## layouts

A collection of responsive layouts for developers in a hurry. 

<hr>

## Author 

Lucas Gabriel. Guilherme dos Santos 
Computer Engineer at Uninta
@lucgbrl @gabrieldocs

"Building Comprehensive and Abrangent Layouts for the web"

## About

This repo contains some work I am doing with CSS Grid and CSS Flexbox to replace old Bootstrap/BulmaCSS pages. The project objective is very simple, but I am trying to make it compreehensive and abragent in order to fit desktop and mobile version and to have some flexibility on my development workflow. 

The components appearance is not its final. The idea behind the project is to provide prebuilt layouts and UI organization. 
Cards, buttons, Font-families and more about the design system can be implemented by the interested-part. 


### Contributing 
We welcome contributions!

📥 Pull requests and 🌟 Stars are always welcome.

This is still a very recent idea, buit I intend to find colaborators in order to provide a VueJS and ReactJS version of the project as it fits as a boilerplate to many different projects and purposes. 



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

This project aims to provide a compiled layout solution, in order to enable developers and webdesigners to quickly setup any content in a giver pattern, so It does not cover complex UI elements such as cards, billboards, chips, buttons...anyway, but we have a few recommendations about typography and spacing!  

#### Typography

A nice font-family is 'Noto Sans JP'. The theme/_text.scss_ folders contains a import from Google Fonts that can be rewritten if needed. 
A convention on my layout was that h1 elements are 3em and all other heading elements get to keep their traditional size. Other nice fonts can be found at [Google Fonts](https://fonts.google.com/). 

#### Spacing 

When in need of vertical and horizontal padding use 12px 24px.
When in need of a container padding 12px looks good for most cases. 


#### Colors 

Choose nice contrasting colors when sketching yout layout / design system, some cool projects like...give you nice collections of colors and palletes in order to be accessible and harmonic. 


## Version 
<hr>

The version name will follow the YYYY-MM-DD-Major-Minor-Correction convention. 

Example: 2021.05.12.1.0.0 for the current alpha version. 

## Layout 01 - Dashboard
<hr>
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
<hr>

This is a desktop homepage sample based on Cards and Billboard Captions.
It uses the following elements to structure the UI:
- nav 
- main
  - header  
  - section 
  - div
    -  header 
    -  div 
      -  div
      -  div

## Copyright and license
Code and documentation copyright 2021 L.G.G.Santos. Code released under the MIT License. Docs released under Creative Commons.

