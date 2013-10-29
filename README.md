
# Sugar3 – v1.0

Sugar3 is a powerful front-end framework based on the [SMACSS](http://smacss.com/) & [Atomic Design](http://bradfrostweb.com/blog/post/atomic-web-design/) principles

Sugar3 is a ultra–lean CSS framework built with LESS designed to provide you with a solid simple 
organized yet powerful workfow for designing & developing for all projects from simple sites to 
robust and complex applications. Built leveraging best practices and commonly used assests such 
as [Normalize](http://necolas.github.com/normalize.css/) to handle your reset, [Bootstrap](http://getbootstrap.com/css/#grid) grid system, [SMACSS](http://smacss.com/) & [Atomic Design](http://bradfrostweb.com/blog/post/atomic-web-design/) principles.

## The Approach
**Sugar3 starts by breaking down the css into two categories.**

* Global
* Sugar

### Global
Consists of Three core parts, but you'll not find any design related styles here. Only consistancy and re-base styling as well as some usefull layout classes.

* Reset - [Normalize](http://necolas.github.com/normalize.css/)
* Base - Styleing some basic defaults for the html. 
* Layout - Grid system and layout helpers based on [Bootstrap](http://getbootstrap.com/css/#grid)

### Sugar
Consists of Two parts.

* Core - Add some theme specific styling to the base selectors
* Elements - these are individuals pieces that when combined comprise a module
* Modules - by cobining elements together we create modules

**We then add on a framework layer.**

* Tools - contains mixins, default settings, & a blame.less file for quick fixs

The last piece of the puzzle is a theme.less this acts sort of like a catch all for those few and far between outliers that do not fit into a module or an element on their own.


## Browser support

Sugar3 is a modern framework for modern browsers. It takes advantage of
[Normalize](http://necolas.github.com/normalize.css/) and global
`box-sizing:border-box;` . As such, Sugar3 is intended for **IE8**
and above only.  


## Credits

Sugar3, although produced and maintained by one developer, could not have
been possible without inspiration and work from an array of other people.

* **[Nicole Sullivan](https://twitter.com/stubbornella)** for her work on OOCSS
* **[Jonathan Snook](https://twitter.com/snookca)** for his work on SMACSS
* **[Nicolas Gallagher](https://twitter.com/necolas)** for his work on numerous
* **[Brad Frost](http://bradfrostweb.com/blog/post/atomic-web-design/)**for his article on Atomic Design
  CSS things
* **[Harry Roberts](http://inuitcss.com)** for is work with inuitcss and so much more

And probably more…

## License

Copyright 2013 mike miday, Licensed under the MiT

