[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# CSS: Layout with Bootstrap

## Prequisites

-   [ga-wdi-boston/html-css-layout](https://github.com/ga-wdi-boston/html-css-layout)
-   [ga-wdi-boston/html-css-sass](https://github.com/ga-wdi-boston/html-css-sass)

## Objectives

By the end of this lesson, students should be able to:

-   Create mobile-first, responsive site layouts using
    [bootstrap](http://getbootstrap.com).
-   Maintain semantic HTML markup using Sass mixins provided by
    `bootstrap-sass`.
-   Reference bootstrap documentation.
-   Add a modal to a front end project.

## Preparation

1.  [Fork and clone](https://github.com/ga-wdi-boston/meta/wiki/ForkAndClone)
    this repository.
1.  Install dependencies with `npm install`.

## Twitter Bootstrap

Bootstrap is a free and open-source collection of tools for creating websites
and web applications. It contains HTML- and CSS-based design templates for
typography, forms, buttons, navigation and other interface components, as
well as optional JavaScript extensions. It aims to ease the development of
dynamic websites and web applications.

Bootstrap is a front end framework, that is, an interface for the user, unlike
the server-side code which resides on the "back end" or server.

Bootstrap is the most-starred project on GitHub, with over 90K stars and more
than 38K forks.

[Bootstrap Wiki](https://en.wikipedia.org/wiki/Bootstrap_(front-end_framework))

Bootstrap is built on a grib like design that consists of rows and columns, like
a table. In each row, Bootstrap is utilized through a 12 column system.

![image](https://cloud.githubusercontent.com/assets/8379295/15674757/818a4ff2-270c-11e6-8ad3-9d5825f0c188.png)

## Lab: Review Sites Made With Bootstrap

In squads closely inspect the following site list.  Keeping these questions in
mind please write down your thoughts and we will discuss them as a class.

1.  How are the the pages similar?

1.  How is the HTML similar among the pages?

1.  As you interact with the site how does the DOM change (if at all)?

1.  How are elements on the pages horizontally arranged?

1.  Notice any similarities among bootstrap pages in general?


-   [Divinity in Tech](http://divinityintech.com/)
-   [UI Viking](http://uiviking.com/)
-   [MintVine](https://mintvine.com/)
-   [The Tool Smith](http://thetoolsmith.com/)
-   [Fansoro](http://fansoro.org/)
-   [Pave](http://pavingtheway.net/)

## Bootstrap Documentation

For components and jQuery plugins always reference the Bootstrap docs.

 [Bootstrap Documentation](http://getbootstrap.com/)

## Lab: 12-Column Grid

Lets get some firsthand experience writing Boootstrap it.  Using the
documentation we discussed earlier write a simple grid in the `index.html` file
located in this repo.  Make use of col-xs, sm, md, lg and xl. Try making an
evenly spaced 3x3 grid.

-   Place your column divs within a row div.
-   Place your row divs within a container div
-   Experiment with various viewport sizes

## Lab: Modals and More

Follow along as I add a bootstrap modal to our current sandbox page.

On your own:

-   Referencing the Bootstrap documentation add an input-group to your
    modal.
-   Using your knowledge of jQuery write a function so that when "save changes"
    is clicked the input in the input field is console logged in Chrome.
-   Refrencing the Bootstrap documentation add a navbar to your page.
-   Move the button that opens up the modal to the navbar.

## Demo: Using `bootstrap-sass` for Semantic Markup

Follow along as I use mixins to make our grid system more semantic.

```html
<div class="container">
  <div class="row">
    <div class="col-md-8">.col-md-8</div>
    <div class="col-md-4">.col-md-4</div>
  </div>
</div>

<div class="container">
  This is HMTL5, its makes our layout much more clean.
  <section>
    <article>Should be .col-md-8</article>
    <article>Should be .col-md-4</article>
  </section>
</div>
```

## Lab: Semantic Markup

1.  Using the code I used above in your `index.scss` file refactor on your own.
1.  Write your own mobile ready page using Bootstrap-Sass classes.
1.  Refactor your HTML from earlier to be more semantic (copy/paste your
previous code and refactor it using bootstrap-sass to make it semantic).

## Useful Resources

-   [Sitepoint Sass Mixins](http://www.sitepoint.com/5-useful-sass-mixins-bootstrap/)
-   [Bootstrap Grid Tricks](http://willschenk.com/bootstrap-advanced-grid-tricks/)
-   [Hongkait Grid Tricks](http://www.hongkiat.com/blog/bootstrap-and-sass/)
-   [Bootstrap Documentation](http://getbootstrap.com/)

## [License](LICENSE)

Source code distributed under the MIT license. Text and other assets copyright
General Assembly, Inc., all rights reserved.
