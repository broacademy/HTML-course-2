# Lesson 8. Grid

**[Presentation](presentations/presentation-8.pdf)**<br />
**[Manual](manuals/manual-8.pdf)**<br />

 <!--
**[Video record](https://drive.google.com/file/d/1hfN5zd4a9B_ZLXWi7jsRCg3cY9dKqldO/view?usp=drive_link)**
**[Practice](practice/practice-7.pdf)**

**[Example project images Pharmify](https://github.com/broacademy/pharmify/tree/lesson-8)**<br /> -->

# Homework

1. I suggest starting to learn grids with any of the following games:

- [Grid Attack](https://codingfantasy.com/games/css-grid-attack) is expertly designed and will provide you with a fun and interactive way to learn about CSS Grid. The objective is to use CSS Grid to alter the landscape to defeat demons. With 80 levels to play through, you'll have plenty of opportunities to practice and master this important web development skill.     
- [Grid Garden](https://cssgridgarden.com/) teaches players about the CSS grid layout system by challenging them to grow a garden by writing CSS code. Players must use grid properties to arrange plants in a grid, working through various levels.     
- [Grid Garden](https://cssgridgarden.com/) An interactive game for learning CSS Grid. Grid Garden provides interactive tasks to teach you how to apply CSS Grid.      
- [Grid Critters](https://gridcritters.com/) is another interactive challenge-based platform to learn the different parts of the Grid Layout spec in a video-game-like environment. The course includes 10 chapters, each broken down into various levels, some as many as 20-26 levels. Very cool, but expensive.    

This will allow you to quickly get into the technology.     

2. You need to add theory:        
[Interactive grid course](https://www.freecodecamp.org/learn/2022/responsive-web-design/learn-css-grid-by-building-a-magazine/step-1) 

Optional: Practice creating grids. Start with simple small examples. Rewrite the same examples you did with flex into grids. Take the [page](https://www.freecodecamp.org/learn/2022/responsive-web-design/build-a-product-landing-page-project/build-a-product-landing-page) as the final example.    

4. Add grids to your work where they are more convenient than flex layouts.
    For example: 
    - about us 
    - how to binabox work
    - partners
    - catalog layout
    - definition list in catalog item page

# Additional Materials

**[Don’t Overthink It Grids](https://css-tricks.com/dont-overthink-it-grids/)**: An article on CSS-Tricks urging not to complicate grid creation. Explains how to simplify the process with straightforward linear solutions.
**[Full-Bleed Layout Using CSS Grid](https://www.joshwcomeau.com/css/full-bleed/)**: An elegant solution for creating full-width layouts using CSS Grid.
**[Ten modern layouts in one line of CSS](https://web.dev/articles/one-line-layouts?hl=en)**: Ten modern layouts, each created with a single line of CSS.
**[Understanding CSS Grid Systems from the Ground Up](https://www.sitepoint.com/understanding-css-grid-systems/)**: Understanding CSS grid systems from scratch.
**[Avoiding layout shift by putting the CSS in charge - HTTP 203](https://www.youtube.com/watch?v=7EKEav7Io5Y)**: A video about avoiding layout shift by letting CSS take charge.
**[Position Sticky and CSS Grid](https://ishadeed.com/article/position-sticky-css-grid)**: Combining `position: sticky` and CSS Grid to create interesting layouts.
**[Introduction to CSS Grid Layout with Examples](https://webdesign.tutsplus.com/introduction-to-css-grid-layout-with-examples--cms-25392t)**: An introductory guide to CSS Grid with visual examples.
**[Using Grids in Web Design](https://webdesign.tutsplus.com/using-grids-in-web-design--CRS-17c)**: How to use grids to improve your web page designs.
**[Building a Production-Ready CSS Grid Layout](https://www.smashingmagazine.com/2017/06/building-production-ready-css-grid-layout)**: A step-by-step guide to creating a production-ready CSS Grid layout.
**[Naming Things in CSS Grid Layout](https://www.smashingmagazine.com/2017/10/naming-things-css-grid-layout)**: Best practices for naming elements in CSS Grid layouts.
**[Understanding the CSS Grid Container](https://www.smashingmagazine.com/2020/01/understanding-css-grid-container)**: A deep understanding of the CSS Grid container and its capabilities.
**[Generated Content and Grid Layout](https://www.smashingmagazine.com/2018/02/generated-content-grid-layout)**: Using generated content within a CSS Grid layout.

🟢 **[Inspect CSS grid layouts in DevTools](https://developer.chrome.com/docs/devtools/css/grid)**: This guide shows you how to discover CSS grids on a page, examine them, and debug layout issues in the Elements panel of Chrome DevTools.


## Properties

**[The `grid` Property in CSS](https://css-tricks.com/almanac/properties/g/grid/)**: Detailed explanation and guide to the `grid` property in CSS. Learn how this property can be a shorthand for setting `grid-template-rows`, `grid-template-columns`, and `grid-template-areas`.

### grid-column-*

**[The `grid-column` Property in CSS](https://css-tricks.com/almanac/properties/g/grid-column/)**: This guide explores the `grid-column` property in CSS, which allows you to simultaneously set the start and end columns for a grid item. Learn how this property simplifies placing elements within the grid.
**[The `grid-column-start` Property in CSS](https://css-tricks.com/almanac/properties/g/grid-column-start/)**: Overview of the `grid-column-start` property, which defines the starting column line of a grid item. Learn how to use this property to control element positioning.
**[The `grid-column-end` Property in CSS](https://css-tricks.com/almanac/properties/g/grid-column-end/)**: Explore the `grid-column-end` property, which determines the ending column line of a grid item. This article helps you understand how to properly apply this property for effective grid design.

### grid-row-*

**[The `grid-row` Property in CSS](https://css-tricks.com/almanac/properties/g/grid-row/)**: An article dedicated to the `grid-row` property, which allows you to simultaneously set the start and end row lines for grid items. This property simplifies managing the vertical alignment of items in your layout.
**[The `grid-row-start` Property in CSS](https://css-tricks.com/almanac/properties/g/grid-row-start/)**: Overview of the `grid-row-start` property functionality, which sets the starting row line for a grid item. This is a key tool for structuring content within CSS grids.
**[The `grid-row-end` Property in CSS](https://css-tricks.com/almanac/properties/g/grid-row-end/)**: Learn how `grid-row-end` helps define the ending row line for grid items in CSS Grid. The article explains how to use this property to achieve clear and understandable page layouts.

### grid-auto-*

**[Understanding the CSS Grid Auto-Placement Algorithm](https://webdesign.tutsplus.com/understanding-the-css-grid-auto-placement-algorithm--cms-27563t)**: Detailed explanation of the auto-placement algorithm in CSS Grid. The article helps you understand how the Grid distributes space between items without explicit positioning instructions.
**[The `grid-auto-flow` Property in CSS](https://css-tricks.com/almanac/properties/g/grid-auto-flow/)**: Overview of the `grid-auto-flow` property, which controls how items are automatically placed within a grid container, helping manage the flow direction of items and their automatic positioning.
**[The `grid-auto-rows` Property in CSS](https://css-tricks.com/almanac/properties/g/grid-auto-rows/)**: Examines the `grid-auto-rows` property, which sets the size of rows created automatically in a grid layout. This is a key element for adaptive and flexible layouts.
**[The `grid-auto-columns` Property in CSS](https://css-tricks.com/almanac/properties/g/grid-auto-columns/)**: This article covers the `grid-auto-columns` property, which defines the sizes of columns that are automatically created when new items appear in a grid container. This simplifies working with dynamic layouts.

### grid-template-*

**[The `grid-template` Property in CSS](https://css-tricks.com/almanac/properties/g/grid-template/)**: Overview of the `grid-template` property, which combines `grid-template-rows`, `grid-template-columns`, and `grid-template-areas` into a single compact declaration. This allows developers to more efficiently create complex grid layouts.
**[The `grid-template-areas` Property in CSS](https://css-tricks.com/almanac/properties/g/grid-template-areas/)**: Explanation of the `grid-template-areas` property, which allows developers to set the layout of the grid using named areas. This makes CSS Grid layouts more readable and easier to maintain.
**[The `grid-template-rows` Property in CSS](https://css-tricks.com/almanac/properties/g/grid-template-rows/)**: Detailed study of `grid-template-rows`, the property for defining the height of rows in a CSS Grid layout. The article discusses how to set fixed and flexible sizes for rows, which is critical for adaptive layouts.
**[The `grid-template-columns` Property in CSS](https://css-tricks.com/almanac/properties/g/grid-template-columns/)**: Exploration of `grid-template-columns`, a key property for setting the width of columns in CSS Grid. It provides flexible options for creating orderly structural layouts on web pages.

### grid-area 

**[The `grid-area` Property in CSS](https://css-tricks.com/almanac/properties/g/grid-area/)**: Detailed description of the `grid-area` property, which is used to simultaneously set the position and size of items in a CSS Grid layout. It simplifies placing elements by combining `grid-row-start`, `grid-column-start`, `grid-row-end`, and `grid-column-end`.
**[Using Grid Named Areas to Visualize and Reference Your Layout](https://css-tricks.com/using-grid-named-areas-to-visualize-and-reference-your-layout/)**: Explains the benefits and methodology of using named areas (`grid-template-areas`) in CSS Grid to create intuitive layouts, making code visualization and maintenance easier.
**[The Grid Area Property in CSS Grid](https://ishadeed.com/article/grid-area)**: Overview of the `grid-area` functionality in creating CSS Grid layouts. The article helps understand how this comprehensive approach to defining areas can make layouts more adaptive and manageable.
**[Understanding CSS Grid Template Areas](https://www.smashingmagazine.com/understanding-css-grid-template-areas/)**: In-depth dive into the `grid-template-areas` property, demonstrating how defining named areas improves the structuring and scalability of CSS Grid layouts.

### min-max

**[CSS Grid Minmax](https://ishadeed.com/article/css-grid-minmax)**: Highlights the use of the `minmax()` function in CSS Grid, which allows setting minimum and maximum bounds for grid track sizes. This capability significantly expands layout flexibility, making design more adaptive and resilient to content of varying sizes.
**[Min Content Size in CSS Grid](https://ishadeed.com/article/min-content-size-css-grid)**: Explores the concept of `min-content` in the context of CSS Grid. The article thoroughly examines how the minimum content size can determine grid track sizes and impact the overall page layout.
**[CSS Grid: More Flexibility with Minmax()](https://css-irl.info/more-flexibility-with-minmax/)**: Discusses the advantages of using the `minmax()` function to create more flexible and adaptive layouts in CSS Grid. The article details how to correctly apply `minmax()` for optimizing layout responsiveness to various display conditions.

### auto-fill / auto-fit

**[Auto-Sizing Columns in CSS Grid: `auto-fill` vs `auto-fit`](https://css-tricks.com/auto-sizing-columns-css-grid-auto-fill-vs-auto-fit/)**: This article on CSS-Tricks focuses on the difference between the `auto-fill` and `auto-fit` properties in CSS Grid. It describes how each of these properties affects the automatic sizing of columns based on available container space, providing examples and best practices for their use in adaptive layouts.

## subgrid 

**[Exploring CSS Grid’s Implicit Grid and Auto-Placement Powers](https://css-tricks.com/exploring-css-grids-implicit-grid-and-auto-placement-powers/)**: The article explores the concepts of implicit grids and auto-placement in CSS Grid, discussing how these mechanisms can be used to simplify the layout of complex web pages.
🟢 **[Learn CSS Subgrid](https://ishadeed.com/article/learn-css-subgrid)**: Ahmad Shadeed explains how to use Subgrid in CSS Grid for more precise control over layouts that require nested grid structures.
**[Display: Grid and Subgrid](https://www.smashingmagazine.com/2019/05/display-grid-subgrid/)**: An article on Smashing Magazine that describes in detail the use of Subgrid in CSS Grid, allowing for even more detailed and complex layouts.
**[Subgrid is here](https://css-irl.info/subgrid-is-here/)**: An introduction to Subgrid, a new addition to CSS Grid that promises to simplify the creation of more complex layouts with enhanced grid property inheritance.
**[CSS subgrid](https://web.dev/articles/css-subgrid?hl=en)**: This section is dedicated to the new Subgrid feature in CSS, offering developers greater flexibility and control over layouts.
**[Editorial Design Patterns with CSS Grid and Subgrid](https://www.smashingmagazine.com/2019/10/editorial-design-patterns-css-grid-subgrid-naming/)**: Discusses the role of CSS Grid and Subgrid in creating editorial layouts, particularly in media and publishing.
**[CSS Grid 2.0: What’s New](https://www.smashingmagazine.com/2018/07/css-grid-2/)**: An overview of new features in the CSS Grid update, including improved support for Subgrid and other significant additions.

## Flex vs grid 

🟢 **[Flexbox vs CSS Grid: Which Should You Use?](https://webdesign.tutsplus.com/flexbox-vs-css-grid-which-should-you-use--cms-30184a)**: This article on Webdesign Tuts+ dissects the differences between Flexbox and CSS Grid, helping developers determine which tool is better suited for their specific layout needs.
**[To Grid or to Flex?](https://css-irl.info/to-grid-or-to-flex/)**: A discussion analyzing situations for using CSS Grid and Flexbox to determine the best approach for page layout.

## Lines

🟢 **[Understanding CSS Grid Lines](https://www.smashingmagazine.com/2020/01/understanding-css-grid-lines/)**: This article on Smashing Magazine provides a comprehensive guide to lines in CSS Grid, explaining how they work and how they can be used to create complex layouts. Understanding these basics can greatly simplify grid development.
**[Quick Tip: Name Your CSS Grid Lines](https://webdesign.tutsplus.com/quick-tip-name-your-css-grid-lines-just-in-case--cms-27844t)**: A short guide offering tips for naming grid lines in CSS Grid to improve code readability and ease of project maintenance.
**[Negative Grid Lines](https://css-irl.info/negative-grid-lines/)**: Explanation of using negative grid line numbers in CSS Grid, allowing developers to more flexibly manage the placement of elements within the grid.

## Best practices 

🟢 **[CSS Grid](https://una.im/css-grid/?ref=hackernoon.com)**: Una Kravets presents an interactive introduction to CSS Grid that allows you to see in real-time how various settings affect the layout. This is a great resource for beginners to master Grid.
**[CSS Grid Gotchas: Troubles and Stumbling Blocks](https://www.smashingmagazine.com/2017/09/css-grid-gotchas-stumbling-blocks/)**: An article on Smashing Magazine that discusses potential difficulties with using CSS Grid and offers solutions to common problems developers might encounter.
**[Best Practices for Grid Layout](https://www.smashingmagazine.com/2018/04/best-practices-grid-layout/)**: This guide offers strategies and best practices for optimizing the use of CSS Grid to create clean and flexible web page layouts.

## Guides and Cheat Sheets 

**[A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)**: This comprehensive guide from CSS-Tricks provides all-encompassing information about CSS Grid, including all key properties and usage examples. Perfect for those looking to dive deeply into Grid’s capabilities.
**[CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)**: Official documentation from MDN, offering a deep understanding of CSS Grid and its application for creating complex web layouts. An excellent resource for developers looking to maximize web standards.
**[CSS Grid Cheat Sheet](https://alialaa.github.io/css-grid-cheat-sheet/?ref=tiny-helpers)**: A cheat sheet for CSS Grid containing the main commands and templates for quick access and use in projects. A useful tool for quickly mastering and applying Grid.
**[CSS Grid Tutorial for Beginners (with Interactive Examples)]**: An extensive tutorial explaining the basics of CSS Grid with interactive examples, making the learning process more understandable and enjoyable.
**[Learn CSS Grid](https://learncssgrid.com/)**: A complete guide to CSS Grid designed to improve understanding and learning how to work with two-dimensional web layouts. This resource offers a structured approach to learning Grid, suitable for both beginners and advanced developers.
**[CSS Grid Tutorial](https://sharkcoder.com/layout/grid)**: A comprehensive guide to CSS Grid from SharkCoder, including key grid properties with practical examples. A great resource for those looking to deeply understand the mechanics of CSS Grid.
**[Learn CSS: Grid Cheatsheets](https://www.codecademy.com/learn/premium-intermediate-css-css-grid/modules/premium-learn-css-grid/cheatsheet)**: Cheat sheets for CSS Grid from Codecademy, providing concise and accessible information on the key aspects of working with CSS Grid. Ideal for quickly familiarizing with the capabilities and features of grids.

## Miscellaneous

**[Awesome CSS Grid](https://github.com/valentinogagliardi/awesome-css-grid)**: This GitHub resource is a collection of useful links, articles, tutorials, and code examples dedicated to CSS Grid. A great starting point for those looking to deeply understand and apply CSS Grid in their projects.
**[Enhancing CSS Layouts with Floats, Flexbox, and Grid](https://www.smashingmagazine.com/2017/07/enhancing-css-layout-floats-flexbox-grid/)**: An article on Smashing Magazine discussing how the combination of Floats, Flexbox, and CSS Grid can transform layout creation methods on the web, making them more flexible and convenient for developers.
**[CSS Grid and Flexbox: Alignment and Grids](https://www.smashingmagazine.com/2016/11/css-grids-flexbox-box-alignment-new-layout-standard/)**: This article explains how CSS Grid and Flexbox change approaches to alignment and grid creation in web design, offering a new standard for more efficient web development.
**[Quantity Ordering with CSS](https://www.smashingmagazine.com/2015/07/quantity-ordering-with-css/)**: An overview of techniques for managing the order of elements on a page through CSS, including the use of CSS Grid and Flexbox for more precise control over content placement.

## Courses 

**[Learn CSS Grid](https://learncssgrid.com/)**: This educational site is a powerful tool for creating two-dimensional layouts on web pages. The guide is designed to help you better understand and master Grid, explaining key concepts and techniques in a structured and clear manner.
**[Mastering CSS Grid](https://www.coltsteele.com/tutorials/mastering-css-grid/css-grid-basics/enabling-css-grid)**: A free video course on CSS Grid offered by Colt Steele. The course is aimed at detailed study of the basics and advanced techniques of working with CSS Grid, including practical examples and exercises.

## Tools

**[Compound Grid Generator](https://codepen.io/michellebarker/pen/zYOMYWv)**: An interactive generator for creating compound grids in CSS. The tool allows you to easily experiment with different grid configurations and instantly see the results.
**[Grid by Example](https://gridbyexample.com/examples/)**: A cheat sheet for CSS Grid with many examples and templates. It offers specific demonstrations and code that can be used as a starting point for your own projects.
**[Grid Lover](https://www.gridlover.net/try)**: An interactive tool for creating vertical rhythm and scaling typography. It allows you to customize styles for headings and paragraphs, seeing the result immediately.
**[The CSS Grid Cheat Sheet](https://alialaa.github.io/css-grid-cheat-sheet/)**: A visual and interactive guide to CSS Grid. It allows you to select grid items and change their properties through a settings panel to better understand the Grid Layout specification.
**[Grid Cheatsheet](https://yoksel.github.io/grid-cheatsheet)**: Yulia Bukhvalova offers a cheat sheet combining documentation and interactive examples for a visual and understandable study of CSS Grid. 
**[CSS Grid Calculator](http://gridcalculator.dk/?ref=tiny-helpers)**: A useful tool for calculating CSS Grid parameters. It allows you to set sizes and the number of columns and rows, automatically generating the necessary code.
**[Layoutit Grid](https://grid.layoutit.com/)**: An interactive interface for creating CSS Grid layouts. It provides a simple way to visualize and generate code for complex layouts.
**[CSS Grid Layout Generator](https://css-grid-layout-generator.pw/)**: A professional tool for visually creating complex CSS grids. It supports automatically generated grid tracks, minmax(), fit-content(), and the ability to export to JSX and Styled Components.
**[CSS Grid Template Builder](https://codepen.io/anthonydugois/pen/RpYBmy)**: A simple tool for creating complex CSS Grid templates. It allows you to edit the template string below or drag areas in the preview, with changes reflected on both sides.

## Demos 

**[A Grid of Squares](https://css-tricks.com/video-screencasts/179-a-grid-of-squares/)**: A video tutorial on creating a grid of squares using CSS Grid. Useful for understanding the basic principles of grids in web design.
**[CSS Grid Layout – New Terminology](https://codepen.io/stacy/pen/ObmjeZ)**: Demonstration and explanation of new terms and concepts in CSS Grid that you need to know when working with this technology.
**[Box-Sizing Model](http://codepen.io/lizzzzzy/pen/LbVXPd)**: An interactive demo showing how the `box-sizing` property affects element sizes in CSS.
**[CSS Grid Layout by Example](https://gridbyexample.com/examples/)**: A cheat sheet with many examples of layouts created using CSS Grid, great for learning and inspiration.
**[CSS Grid and Flexbox – Examples](https://labs.jensimmons.com/)**: A collection of demonstrations of various layouts implemented with CSS Grid and Flexbox, featuring a creative approach to layout.
**[CSS Grid Collection](https://codepen.io/collection/XRRJGq/)**: A collection of interactive examples demonstrating various aspects and techniques of using CSS Grid in different layouts.
**[Auto Hexagonal CSS Grid Layout](https://codepen.io/Kseso/pen/xqNdmO)**: A demonstration of creating a hexagonal grid using CSS Grid, useful for mastering unconventional layouts.
**[Mondrian Art in CSS Grid](https://codepen.io/jensimmons/pen/aNjXLz)**: A creative example of using CSS Grid to recreate Piet Mondrian's art, illustrating the flexibility of grids.
**[[CSS Grid] Layout Slideshow](https://tympanus.net/Development/GridLayoutSlideshow/)**: An interactive presentation with examples of using CSS Grid to create complex slideshow layouts.
**[50+ GRID-LAYOUT UI DESIGN EXAMPLES](https://frontendin.com/css-grid/)**: A large collection of interface examples created with CSS Grid, an excellent source of inspiration for designers.
**[Auto-fit/auto-fill](https://codepen.io/michellebarker/pen/BaYmNgN)**, **[Fit-content](https://codepen.io/michellebarker/pen/JjprLEz)**, **[Aspect ratio grids](https://codepen.io/michellebarker/pen/YzeqRrP)**, **[Subgrid](https://codepen.io/michellebarker/pen/WNMbgEw)**, **[Flex or Grid?](https://codepen.io/michellebarker/pen/JgEYxv)**, **[Auto-fill vs. auto-fit](https://codepen.io/michellebarker/pen/oNvpBBX)**: A series of interactive examples demonstrating various aspects and techniques of working with CSS Grid and Flexbox, allowing for effective layout solutions.

**[Grid Layout with Negative Line Numbers](https://codepen.io/michellebarker/pen/ReLYwp)**: Demonstrates a layout using negative line numbers in CSS Grid.    
**[Implicit Tracks](https://codepen.io/michellebarker/pen/dgVVRq)**: An example illustrating the creation of implicit tracks in CSS Grid.    
**[Grid Practice - Named Lines](https://codepen.io/michellebarker/pen/ZRjZVO)**: A practical example using named lines in CSS Grid.    
**[grid-template-areas](https://codepen.io/michellebarker/pen/jKYBRv)**: An example demonstrating the use of `grid-template-areas` in CSS Grid layouts.    
**[CSS Grid vs Flexbox Layouts](https://codepen.io/michellebarker/pen/PJjmJL?editors=1100)**: A comparison of layouts created with CSS Grid and Flexbox.    
**[Auto-fill vs. auto-fit 6](https://codepen.io/michellebarker/pen/LYPexmG)**: An example comparing the properties `auto-fill` and `auto-fit` in CSS Grid.    
**[Auto-fill vs. auto-fit 3](https://codepen.io/michellebarker/pen/MWgrpZe)**: Another example comparing the properties `auto-fill` and `auto-fit` in CSS Grid.    
**[Grid and Flexbox Alignment](https://codepen.io/michellebarker/pen/jONKQxr?editors=1100)**: An example of aligning elements using CSS Grid and Flexbox.    
**[Different Ways to Force Equal Width for Two List Items](https://codepen.io/michellebarker/pen/gOOQyyL)**: Demonstrates different ways to force equal width for two list items.    
**[Flex/Grid Cluster Layout](https://codepen.io/michellebarker/pen/JjYxYqv?editors=1100)**: An example of a cluster layout using Flexbox and CSS Grid.    
**[Layout with `fr` Units](https://codepen.io/michellebarker/pen/PMbBPX)**: An example layout using `fr` units in CSS Grid.    
**[0.2 `fr` Grid](https://codepen.io/michellebarker/pen/YmWrMR)**: An example grid using 0.2 `fr` in CSS Grid.    
**[`minmax()` Grid](https://codepen.io/michellebarker/pen/JgKrXW?editors=1100)**: An example using the `minmax()` function in CSS Grid.    
**[Basic Auto Placement](https://codepen.io/michellebarker/pen/MNKQEm?editors=1100)**: A basic example of auto-placing elements in CSS Grid.    
**[Expected vs. Actual Auto-Flow Behavior](https://codepen.io/michellebarker/details/pXOXyg)**: Demonstration of expected and actual auto-flow behavior in CSS Grid.    
**[Auto-Flow and Distribution](https://codepen.io/michellebarker/pen/MMqLdK)**: An example of auto-flow and distribution of elements in CSS Grid.    
**[Grid Placement and Auto-Flow](https://codepen.io/michellebarker/pen/ZdMXKE)**: An example of placing elements in a grid and auto-flow in CSS Grid.    
**[`minmax()` and `fr`](https://codepen.io/michellebarker/pen/MdpBME)**: An example using the `minmax()` function together with `fr` units in CSS Grid.    
**[`fr` Tracks with Fixed Tracks](https://codepen.io/michellebarker/pen/NVpMrp)**: An example of using `fr` units with fixed tracks in CSS Grid.    
**[Simple `fr` Track Demo](https://codepen.io/michellebarker/pen/ZNeobr)**: A simple example using `fr` units in CSS Grid.    
**[`fr` Units with `minmax()`](https://codepen.io/michellebarker/pen/ZNBeQw)**: An example using `fr` units with the `minmax()` function in CSS Grid.    
**[`fr` Units](https://codepen.io/michellebarker/pen/vwyyWV)**: An example of using `fr` units in CSS Grid.    
**[Another Example with `fr` Units](https://codepen.io/michellebarker/pen/LoRGBj)**: An additional example using `fr` units in CSS Grid.    
**[Flexbox and CSS Grid Layout Examples](https://codepen.io/michellebarker/pen/xeXgqy)**: Comparison of layout examples created with Flexbox and CSS Grid.    
**[Auto-Fill Grid Example](https://codepen.io/michellebarker/pen/bzvGaE)**: An example using the `auto-fill` property in CSS Grid.    
**[Grid Auto-Flow Issues](https://codepen.io/michellebarker/pen/rPzLoV)**: Examples of issues arising with grid auto-flow in CSS Grid.    
**[Grid Auto-Flow](https://codepen.io/michellebarker/pen/WLRqrJ)**: An example using the `grid-auto-flow` property in CSS Grid.

### Grid Examples

**[CSS Grid + nth-child](https://codepen.io/michellebarker/details/bPmwmo)**: An example of using CSS Grid in combination with the nth-child pseudo-class to style specific child elements.
**[CSS Grid + nth-child](https://codepen.io/michellebarker/pen/XLxjex)**: Another example of using CSS Grid with the nth-child pseudo-class to style specific child elements.
**[CSS Grid + nth-child](https://codepen.io/michellebarker/pen/vqVJqX)**: Yet another example of using CSS Grid in combination with the nth-child pseudo-class to style child elements.
**[CSS Grid + nth-child](https://codepen.io/michellebarker/pen/rbzQQo?editors=1100)**: An example of using CSS Grid in combination with the nth-child pseudo-class to manage the styles of specific child elements.
**[CSS Grid + nth-child](https://codepen.io/michellebarker/pen/EJvwmv)**: Continuation of demonstrating the use of CSS Grid with the nth-child pseudo-class to style child elements.
**[CSS Grid + nth-child](https://codepen.io/michellebarker/pen/mgMBrQ)**: Another example of applying CSS Grid with the nth-child pseudo-class to style specific child elements.
**[CSS Grid + nth-child](https://codepen.io/michellebarker/pen/NmvrNp)**: Yet another example of using CSS Grid in combination with the nth-child pseudo-class to style child elements.
**[CSS Grid + nth-child](https://codepen.io/michellebarker/pen/aMVLxb)**: An example of using CSS Grid with the nth-child pseudo-class to manage the styles of child elements.
**[CSS Grid + nth-child + auto-fill experimental](https://codepen.io/michellebarker/pen/ywzrVM)**: An example using the experimental auto-fill functionality with CSS Grid and the nth-child pseudo-class.
**[CSS Grid + nth-child for Managing Last Row Behavior](https://codepen.io/michellebarker/pen/KEXErp)**: Demonstrates using CSS Grid with the nth-child pseudo-class to control the behavior of the last row.
**[Example of Using CSS Grid](https://codepen.io/michellebarker/pen/OmEqJJ)**: An example of a simple layout created using CSS Grid.
**[Another Example of Using CSS Grid](https://codepen.io/michellebarker/pen/aWKXmJ)**: An additional example of a layout created with CSS Grid.
**[Is it Time to Ditch the Design Grid?](https://css-irl.info/is-it-time-to-ditch-the-design-grid/)**: An article discussing whether it is time to abandon the design grid for web pages.
**[Debugging CSS Grid. Part 1: Understanding Implicit Tracks](https://css-irl.info/debugging-css-grid-part-1-understanding-implicit-tracks/)**: The first part of a series of articles on debugging CSS Grid, dedicated to understanding implicit tracks.
**[Debugging CSS Grid. Part 2: What is `fr`?](https://css-irl.info/debugging-css-grid-part-2-what-the-fraction/)**: The second part of a series of articles on debugging CSS Grid, discussing the `fr` unit.
**[Debugging CSS Grid. Part 3: Auto-Flow, Order, and Item Placement](https://css-irl.info/debugging-css-grid-part-3-auto-flow-order-and-item-placement/)**: The third part of a series of articles on debugging CSS Grid, describing auto-flow, order, and item placement.
**[Aspect Ratio Cells](https://css-irl.info/aspect-ratio-cells/)**: An article about creating cells with a specified aspect ratio using CSS Grid Layout.
**[Using Pseudo-Elements with CSS Grid](https://css-irl.info/using-pseudo-elements/)**: An article on how to use pseudo-elements with CSS Grid.