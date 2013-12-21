
# Sugar3 – v1.0

Sugar3 is a powerful front-end framework based on the [SMACSS](http://smacss.com/) & [Atomic Design](http://bradfrostweb.com/blog/post/atomic-web-design/) principles

Sugar3 is a ultra–lean CSS framework built with LESS designed to provide you with a solid simple 
organized yet powerful workfow for designing & developing for all projects from simple sites to 
robust and complex applications. Built leveraging best practices and commonly used assests such 
as [Normalize](http://necolas.github.com/normalize.css/) to handle your reset, [Bootstrap](http://getbootstrap.com/css/#grid) grid system, [SMACSS](http://smacss.com/) & [Atomic Design](http://bradfrostweb.com/blog/post/atomic-web-design/) principles.

## The Approach
**Sugar3 starts by breaking down the css into Three categories.**

* Global
* Sugar
* Theme

### Global
Consists of Four core parts, but you'll not find any design related styles here. Only consistancy and re-base styling as well as some usefull layout classes.

* Reset - [Normalize](http://necolas.github.com/normalize.css/)
* Base - Styling some basic defaults for the html as well as fixing some consistancy to lay the ground work. 
* Layout - Grid system and layout helpers based on [Bootstrap](http://getbootstrap.com/css/#grid)

### Sugar
Consists of Three parts.

* Core - Add some theme specific styling to the base selectors
* Modules - these are individual reuseable objects commonly used acrossed multiple projects
* Components - by cobining elements together we create components. Think odf these as indvidual sections of a page or a page itself.

**We then add on a framework layer.**

### Tools - contains mixins, default settings, & a blame.less file for quick fixs

* Mixins - A series of useful reuseable blocks of code most of which are based on [Bootstrap](http://getbootstrap.com/)
* Defaults - The true flexability of a framework comes in the form of variables. This sets the default values for all the variables in the framework that can be overidden in the vars.less file
* Atoms - Individual bits of css that can be added directly to you HTML as standalone classes or used to extend modules.

The last piece of the puzzle is a theme.less file which acts sort of like a catch all for those few and far between outliers that do not fit into an atom, module or component on their own. As well as provide a place to overide any part of the framework during development


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

And probably more…

## License

Copyright 2013 mike miday, Licensed under the [MIT](http://opensource.org/licenses/MIT)

