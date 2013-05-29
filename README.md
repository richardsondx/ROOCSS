### Welcome to ROOCSS.org : Rich Object Oriented CSS Pages.

ROOCSS is an ideology created by Richardson Dackam that make it easier to build stylesheet for medium and large ruby on rails websites.

### Guideline: An Introduction to Rich Object Oriented CSS (ROOCSS)

Forget the BEST PRACTISES you knew and apply the ROOCSS (pronounced "RO CSS") ideology:
* Separation of structure from skin
* Separation of containers and content
* **Grid set the width** and **Content set the height**
* CSS with the suffix "_debug" define the look
* (Almost) **Only use classes**
* Name your classes

```
Assets
- Images/
- Javascripts/
- Stylesheets/
-- Fonts/
-- Library.css
-- Layout.css
-- Grid.css
-- Grid_debug.css
-- Content.css
-- Content_debug.css
(HTML in the root)
```

Following this file structure will keep your file organized and make it easier to switch from one ROOCSS app to another and still understand whats going on. 

### Files Structure Explanation:

Library.css

 > Put any imported setup here (CSS Reset + Font Family + H1, H2, H3, H4, H5, H6, p)

Layout.css

 > Used to setup the core layout of the skin that will be used in the application.html.erb file (Body, Header, Navbar, Container & Footer). This is the only place where you can exceptionally use IDs.
Grid.css

 > The Grid system should be used to create classes that define the width of container, the space between container or content elements  and the position of container elements.

Grid_debug.css

> To set up the color of your containers.

Content.css

> Any Style that defines the form of content elements

Content_debug.css

> Any Style that defines the look of content elements

### Template:

I will soon add some template and example so that you can play with the template in Firebug to learn the basics of ROOCSS.

### Rails GEM:

I will soon release a gem to implement ROOCSS into your rails app.

### The Benefits Of ROOCSS

- ***Smaller file size:*** Less duplication should result in smaller file sizes
- ***Maintainable stylesheets:*** Modules of css can be added anywhere and it's easier to improve one block of code instead of many.
- ***Ease of maintenance:*** Code is located in one block instead of many
- ***Stay DRY:*** Do not repeat yourself
- ***Predictable:*** Once you get familiar with OOCSS it's easy to guess what classes to use.
- ***Flexible:*** It's very personal and yet can be quickly used by other people working on your site.
 

### FAQ

- Where ROOCSS come from?

> ROOCSS was inspired by OOCSS created by [Nicole Sullivan](https://github.com/stubbornella/).
  If you have any question about the OOCSS part of ROOCSS just visit   [https://github.com/stubbornella/oocss/wiki/faq](https://github.com/stubbornella/oocss/wiki/faq)



- How is ROOCSS different from OOCSS?

> ROOCSS was designed to fit my need as a Ruby on Rails Developer: It the OOCSS ideology applied for Rails. ROOCSS has a different file structure than OOCSS.


- Can I remove unused styles?

> Totally. If you are done building you're website and you don't need some element feel free to remove them.


### Authors and Credit

Richardson Dackam is a Senior Ruby on Rails Developer located in Toronto, Ontario, Canada.

You can contact the author at:
- [@richardsondx](http://www.twitter.com/richardsondx) on Twitter and [linkedin.com/in/richardsondx](http://linkedin.com/in/richardsondx) on LinkedIN
- Thanks to Nicole Sullivan for introducing OOCSS. Visit Nicole Sullivan's BLOG on OOCSS at [http://www.stubbornella.org/](http://www.stubbornella.org/content/category/general/geek/css/oocss-css-geek-general/)

### Support, Contribution or Contact

Having trouble with ROOCSS? create an issue on github and me or the community will help you sort it out.

If you'd like to contribute to this wiki and submit some detailed explanation feel free to send me a pull request. ROOCSS is an open source project and I would love to improve it. I am always open for suggestion: Fork & send me pull requests if you would like to contribute.

For anything else just email me at richardsondx@gmail.com.
