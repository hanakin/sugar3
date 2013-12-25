
# Sugar3 – v1.0

Sugar3 is a powerful front-end framework based on the [SMACSS](http://smacss.com/) & [Atomic Design](http://bradfrostweb.com/blog/post/atomic-web-design/) principles

Sugar3 is a ultra–lean CSS framework built with LESS designed to provide you with a solid simple 
organized yet powerful workfow for designing & developing for all projects from simple sites to 
robust and complex applications. Built leveraging best practices and commonly used assests such 
as [Normalize](http://necolas.github.com/normalize.css/) to handle your reset, [Bootstrap](http://getbootstrap.com/css/#grid) grid system, [SMACSS](http://smacss.com/) & [Atomic Design](http://bradfrostweb.com/blog/post/atomic-web-design/) principles.

## The Approach
**Sugar3 starts by breaking down the css into four layers.**

* Global
* Core
* Sugar
* Theme

### Global
Consists of Two core parts, but you'll not find any design related styles here.

* Reset - Standardize all of the inconsistancies we see across the different browsers utilizing [Normalize](http://necolas.github.com/normalize.css/).
* Base - Establish a set of global styles for all the HTML components across all projects.

### Core
Consists of Three parts, laying the ground work for your projects.

* Common - Set some project specific styling for all the HTML components per project.
* Layout - A responsive forward think grid system used alongside powerful utilities to align and position elements for all devices based on [Bootstrap](http://getbootstrap.com/css/#grid).
* Atoms - Small useful classes on their own, equally effective at extending functionality to modules or components.

### Sugar
Consists of Two parts, build your library of objects in your web arsenal.

* Modules - Series of dynamically accessible commonly used elements that you might use in various projects.
* Components - Series of dynamically accessible commonly used blocks or sections of modules layed out in various ways.

### Theme
The last piece of the puzzle is a theme.less file which acts sort of like a catch all. Individualize everything in your custom built framework via the theme layer.   Set basic styles for each individual section.

**We then add on a framework layer.**

### Tools - contains mixins, default settings, & a blame.less file for quick fixs

* Mixins - A series of useful reuseable blocks of code most of which are based on [Bootstrap](http://getbootstrap.com/)
* Defaults - The true flexability of a framework comes in the form of variables. This sets the default values for all the variables in the framework that can be overidden in the vars.less file

## Browser support

Sugar3 is a modern framework for modern browsers. It takes advantage of
[Normalize](http://necolas.github.com/normalize.css/) and global
`box-sizing:border-box;` . As such, Sugar3 is intended for **IE8**
and above only, as well as firefox, chrome, & safari. 


## Credits

Sugar3, although produced and maintained by one developer, could not have
been possible without inspiration and work from an array of other people.

* **[Nicole Sullivan](https://twitter.com/stubbornella)** for her work on OOCSS
* **[Jonathan Snook](https://twitter.com/snookca)** for his work on SMACSS
* **[Nicolas Gallagher](https://twitter.com/necolas)** for his work on Normalize and SUIT
* **[Brad Frost](http://bradfrostweb.com/blog/post/atomic-web-design/)**for his article on Atomic Design
* **[Harry Roberts](http://inuitcss.com)** for is work with inuitcss and so much more
* **[Sergey Shmidt & Sergii Iurevych](http://designmodo.github.io/Flat-UI/)** for their work on a truely amazing UI kit, Responsive elements & Inspiring [Startup Framework](http://designmodo.com/startup/)

And probably more…

## License

Copyright 2013 mike miday, Licensed under the [MIT](http://opensource.org/licenses/MIT)

