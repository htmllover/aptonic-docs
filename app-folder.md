### App folder or project folder

This section is about the Aptonic File structure. I hope it will help to understand project files.

<img src="https://htmllover.github.io/aptonic-docs/app-folder.jpg"/>

```text
Aptonic
    |-- app
    |     |-- css
    |     |-- fonts
    |     |-- img
    |     |-- js
    |     |-- scss
    |     |-- webfonts
    |     ─ index.html
    |     ─ index-1.html
    |     - others .html files
    |-- gulpfile.js 
    |-- package.json 
    |-- package-lock.json
```


#### css folder

Below `css` files included in this css folder

```text
|-- css
|     |-- app.css
|     |-- bootstrap.min.css
|     |-- fontawesome.min.css
|     |-- mignific-popup.css
|     |-- owl.carousel.min.css
|     |-- owl.theme.default.css
|     |-- themify-icons.css
|   
``` 

* `app.css` fil contain all custom css. But don't write any css code here. Because we have used `scss` so when you will write or change any css on `scss` file then the `css` code automatic compiled here. **(make sure your local server is running)**.
* `bootstrap.min.css` file contain - [Bootstrap](https://getbootstrap.com/) css.
* `fontawesome.min.css` file contain - [Font Awesome](https://fontawesome.com/) icon css.
* `mignific-popup.css` file contain - [Magnific Popup](https://dimsemenov.com/plugins/magnific-popup/) Popup css. It's is a responsive lightbox & dialog script with focus on performance and providing best experience for user with any device.
* `owl.carousel.min.css` and `owl.theme.default.css` file contain - [Owl Carousel](https://owlcarousel2.github.io/OwlCarousel2/) custom carousel css. It's Touch enabled jQuery plugin that lets you create a beautiful responsive carousel slider.
* `themify-icons.css` file contain - [Themify Icons](https://themify.me/themify-icons) another line icon css.


#### fonts folder

This folder contain fonts.

```text
|-- fonts
|     |-- 
|     |-- 
|     |-- 
|     |-- 
|     |-- 
|     |-- 
```



#### img folder
All images with logo, favicon, client or customer, team, slider etc included this folder.
```text
|-- img
|     |-- 
|     |-- 
|     |-- 
|     |-- 
|     |-- 
|     |-- 
```


#### js folder
Js folder contain an `lib` folder, in this folder has all plugins like bootstrap, jquery, popper etc.
```text
js
|-- lib
|     |-- bootstrap.min.js
|     |-- jquery.easing.min.js
|     |-- jquery-3.4.0.min.js
|     |-- magnific-popup.min.js
|     |-- owl.carousel.min.js
|     |-- popper.min.js
|     |-- typed.min.js
|-- main.js

```
* `bootstrap.min.js` [Bootstrap](https://getbootstrap.com/) plugin js.
* `jquery.easing.min.js` [jQuery Easing](http://gsgd.co.uk/sandbox/jquery/easing/) it's jQuery plugin from [GSGD](http://gsgd.co.uk/) to give advanced easing options.
* `jquery-3.4.0.min.js` [jQuery](https://jquery.com/) plugin.
* `magnific-popup.min.js` [Magnific Popup Js](https://dimsemenov.com/plugins/magnific-popup/) is a responsive lightbox & dialog script with focus on performance and providing best experience for user with any device.
* `owl.carousel.min.js` [Owl Carousel](https://owlcarousel2.github.io/OwlCarousel2/) custom carousel css. It's Touch enabled jQuery plugin that lets you create a beautiful responsive carousel slider.
* `typed.min.js` [Typed.js](https://mattboldt.com/demos/typed-js/) is a library that types. Enter in any string, and watch it type at the speed you've set, backspace what it's typed, and begin a new sentence for however many strings you've set.
* `main.js` is contain all custom js.



#### scss folder
Aptonic relies on the powerful Sass features, letting you handle complex styles in a breeze. Below you can find all the SCSS partial files that are used accross all the template demos.

```text
scss
|-- base
|     |-- _buttons.scss
|     |-- _color.scss
|     |-- _form-elements.scss
|     |-- _global.scss
|     |-- _height-spacing.scss
|     |-- _typography.scss
|     |-- _variable.scss
|-- components
|     |-- _blog.scss
|     |-- _faq.scss
|     |-- _feature.scss
|     |-- _footer.scss
|     |-- _functions.scss
|     |-- _header.scss
|     |-- _hero.scss
|     |-- _image-background.scss
|     |-- _navigations.scss
|     |-- _pricing.scss
|     |-- _promo.scss
|     |-- _testimonial.scss
|     |-- _video.scss
|-- app.scss

```

##### base

I have included here `buttons`, `color`,`form-elements`, `global`, `height-spacing`, `typography` and `variable` scss files.

##### components

I have included here all section scss like- `header`, `footer`, `hero` etc.


#### app.scss

**app.scss** file are the heart of Aptonic style. Their main purpose is to centralize all styles. Every time you make a change in a partial file, it impacts the outputed `app.css`(in css folder) file resulting from the compilation process. This files start with imports of other partial SCSS files. Here is an example import statement:

```css
/*
Template Name: Aptonic - App Landing Page Template
Author: https://themeforest.net/user/htmllover
*/

/*! app.scss */

// Base
@import 'base/variable';
@import 'base/typography';
@import 'base/global';
@import 'base/color';
@import 'base/buttons';
@import 'base/height-spacing';
@import 'base/form-elements';

// Components
@import 'components/functions';
@import 'components/navigation';
@import 'components/image-background';
@import 'components/header';
@import 'components/hero';
@import 'components/promo';
@import 'components/feature';
@import 'components/video';
@import 'components/pricing';
@import 'components/blog';
@import 'components/testimonial';
@import 'components/faq';
@import 'components/footer';

```
!> Notice how partials are imported. Whereas the actual partial file name starts with an underscore and ends with a `.scss` extension, when you write imports inside your `app.scss` file, you have to remove the undescore and the `.scss` extension.


### webfonts folder

This folder contain - [Font Awesome](https://fontawesome.com/) icon fonts.

















                                                                  
