# freeCodeCamp Responsive Web Design Curriculum Projects

These Projects were built for the purpose of getting the freeCodeCamp Responsive Web Desig Curriculum Certificate. <br> 
All the projects inside this repository are built using only pure HTML5 and CSS3. <br>

*Preview of one Project built throught out this repository*

![Product Landing Page Project Preview](https://user-images.githubusercontent.com/84383548/131246700-7465bf31-e10a-4949-a4ad-be5056aacbe0.png)

## Projects built:

1. [Tribute Page](#tribute-page)
1. [Survey Form](#survey-form)
1. [Product Landing Page Projects](#product-landing-page)
1. [Technical Documentation Webpage](#technical-documentation)
1. [Personal Portfolio Website](#personal-portfolio-website)

## Projects Description 

This section provides details about each projects

1. Tribute Page 

This Project purpose was to build a Tribute page about a random person (basically anyone you'd like) and make responsive on different devices and screen sizes.

You can Find the Code of this project either in this repo or on [my Codepen](codepen.io/Nicaisse/full/XWRObzL)

Some random CSS code from the project :

```css
#main {
    background-color: black;
    color: white;
    font-family: Poppins, sans-serif;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
}

figure {
    background-color: white;
    width: 100%;
    height: 70vh;
    margin-left: 0;
    padding-top: 2.5rem;
}

#img-div {
    display: flex;
    flex-direction: column;
    justify-content: center;
    background-color: transparent;
    width: 50%;
    height: 90%;
    margin: auto;
    margin-bottom: 1.5rem;
}
```

**Preview :**
[![Tribute Page Project Preview](https://user-images.githubusercontent.com/84383548/131246871-a5b46701-9e1c-4a7f-a6c2-c1e8c05f54aa.png)](codepen.io/Nicaisse/full/XWRObzL)

1. Survey Form

This project was all about forms to help master the HTML form element and how to properly style forms

You can Find the Code of this project either in this repo or on [my Codepen](codepen.io/Nicaisse/full/OJgyRqM)

Some random CSS code from the project :

```css
#dropdown:focus {
    background-color: rgb(228, 228, 255);
    border: 0px solid rgb(252, 245, 245);
}

.radio {
    border: 0px;
    margin-bottom: 1rem;
}

.radio legend {
    text-align: center;
    margin-bottom: 0.5rem;
}

.radio input {
    margin-bottom: 1rem;
}

.checkbox {
    margin-bottom: 1.5rem;
    border: 0px;
}

.checkbox legend {
    text-align: center;
    margin-bottom: 0.5rem;
}

.checkbox input {
    margin-bottom: 1rem;
    border: 0px;
```

**Preview :**
[![Survey Form Project Preview](https://user-images.githubusercontent.com/84383548/131246878-040e9c22-ea55-4593-8665-e490da3700b6.png)](codepen.io/Nicaisse/full/OJgyRqM)

1. Product Landing page

This projects focused much more on building layouts (responsive layouts) mostly **CSS flexbox** but also *CSS grid*

You can Find the Code of this project either in this repo or on [my Codepen](codepen.io/Nicaisse/full/OJgyRqM)

Some random CSS code from the project :

```css
@media (min-width: 62.5rem) { /* 100px screen and above */
    #main {
        padding-left: 15rem;
        padding-right: 15rem;
        display: flex;
        gap: 2rem;
        justify-content: space-around;
        align-items: center;
    }
    
    .main-intro {
        flex: 0 0 75%;
        text-align: left;
        margin-bottom: 1.5rem;
    }

    .main-img {
        flex-shrink: 0;
    } 

    #about {
        display: flex;
        flex-direction: column;
        justify-content: center;
    }

    .features-container {
        margin: auto;
        width: 57.5rem;
        margin-top: 3rem;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .about-cards {
        display: grid;
        grid-template-rows: repeat(2, 1fr);
        grid-template-columns: repeat(2, 1fr);
    }
```

**Preview :**
[![Product Landing Page Project Preview](https://user-images.githubusercontent.com/84383548/131246700-7465bf31-e10a-4949-a4ad-be5056aacbe0.png)](codepen.io/Nicaisse/full/dyRYyMW)

1. Technical Documentation Page

In this project we built a responsive technical documentation page using *css grid*

You can Find the Code of this project either in this repo or on [my Codepen](codepen.io/Nicaisse/full/NWgNZEM)

Some random CSS code from the project :

```css
body {
  margin: 0rem;
  display: grid;
  grid-template-areas: "navbar main-doc";
  grid-template-columns: 30% 70%;
}

#navbar {
  padding: 1rem 0.5rem;
  background-color: white;
  color: white;
  grid-area: navbar;
  position: fixed;
  top: 1rem;
  right: 72.5%;
  width: 23%;
  background-color: hsl(0, 8%, 17%);
  color: white;
  overflow-y: auto;
}

#navbar header {
  font-size: 1.1rem;
  text-align: center;
  padding-bottom: 1rem;
  border-bottom: 1px solid white;
}
```

**Preview :**
![Technical Documentation Page Preview](https://user-images.githubusercontent.com/84383548/131806430-98827246-2d2a-4976-a585-ec52c1736467.png)

1. Personal Portfolio Website

*Still working on it*
