# Criteria for HTML Course Quality
**for Bro Academy**

**Purpose:**<br />
When developing a website, there are many conditions that must be met to ensure the site displays correctly.

❤️ Mandatory for passing the course <br />
💛 Required for the highest grade <br />
💚 Optional  <br />
 
## 1. HTML

1. ❤️
**The document must begin with ```<!DOCTYPE HTML>```.**  
A correct doctype ensures the pages display according to standards.  

2. ❤️
**Each page must have the lang attribute set according to the page's language.**  

3. ❤️
**The document must have a specified encoding.**  
UTF-8 is universal and compatible; it is the current standard.  

4. ❤️
**Title Tag must be set on all pages.**  
SEO: Google trims titles between 472 to 482 pixels, so the title length should be around 55 characters.  
```<title>``` must be unique on each page.  

5. 💛
**Description meta tag must be set**  
The ```<meta type=”description”>``` must be unique and less than 150 characters.  
It appears in search engines below the title.  

6. 💚
**Favicon icons display correctly.**  
Format – ico, png, svg.  
Sizes – 16х16, 32х32, 48х48, 64х64.  

7. ❤️
**All elements must be marked up and styled.**  

8. ❤️
**No gross markup errors.**  

   *Gross errors:*  
   Using tags other than ```<a>``` for links.  
   Using ```<span>``` for large layout blocks.  
   Using ```<br>``` for line breaks in text.  
   And so on...  

   *Not gross errors:*  
   Absence of semantic tags.  
   Violating the hierarchy of headings.  

9. ❤️
**Semantic Markup**  
Use semantic tags like ```<header>, <main>, <footer>, <nav>,``` etc.  
Headers should use ```<h1>``` to ```<h6>```, paragraphs ```<p>```, and ```<div>``` for containers.  
   
   *Bad:*  
   ```
   <div class="hr"></div>
   <div class="header"></div>
   ```
   
   *Good:*  
   ```
   <hr>
   <header></header>
   ```

10. ❤️
**The layout must be valid.**  
HTML must pass validation at https://validator.w3.org/  

11. 💛
**Classes are named correctly:**  
No transliteration in class names, attributes, etc.  
Only lowercase letters are used.  
If a class name consists of several words, use hyphens between the words: slider-block, etc.  
Do not use presentational classes that specify styles (fz-15, color-green, block-left).  
The class name should reflect the purpose (semantics) of the block, not its appearance.  

12. 💛
**Use the minimum possible number of HTML elements.**  
No unnecessary wrappers in the markup.  
There should be no empty blocks for presentational purposes. Use pseudo-elements for this.  
🚩 If an element has no styles or they can be transferred to the nearest enclosing element.  

13. 💛
**The logo on internal pages should lead to the home page.**  
On the home page, the logo should not lead to any page.  

14. ❤️
**All pages should be linked and checked for broken links.**  

15. 💛
**External links should have the attribute ```target="_blank"```.**  

16. ❤️
**Each page must have an ```<h1>``` tag that is different from the page title.**  

17. 💛
**The heading tree structure is maintained.** <br />
From the headings, a table of contents can be formed like in a book. <br />
Heading levels go in order from top to bottom and are not skipped. <br />
Check it on https://yoksel.github.io/html-tree.  <br />

18. ❤️
**Appropriate types for input are specified.**  <br />
This is especially important for mobile devices as they use different keyboards for different input types.  <br />
https://mobileinputtypes.com 

19. ❤️
**Each form element should have a ```<label>```.** <br />
If there is no explicitly set text for the label, then add it to the markup and hide it accessibly. 

20. 💛
**Resizing ```<textarea>``` should not break the layout.** 

21. ❤️
**Basic HTML form validation should be implemented.** <br />
The form cannot be submitted with empty fields. <br />
Data in fields must match the field format. <br />


## 2. CSS

1. ❤️
**Single CSS File** <br />
Use a single CSS file for all pages (style.css). <br />
Normalize.css should be included as an additional file. 

2. 💛
**Include Normalize.css** <br />
https://necolas.github.io/normalize.css/  <br />
Normalize.css should be linked before the main style file. 

3. ❤️
**All fonts used in the design are connected to the pages.** <br />
Preferably from Google Fonts. 

4. ❤️
**Provide fallback fonts and family types at the end of the font list.** 
For example:  ```font-family: Roboto, Arial, sans-serif;``` 

5. ❤️
**Do not use !important in CSS.** <br />

   *Bad:* 
   ```
   .link {color: red !important;}
   ```

   *Good:*
   ```
   .selector .link {color: red;}
   ```

6. ❤️
**Do not use #id for styling.** <br />

   *Bad:* 
   ```
   #link {color: red;}
   ```

   *Good:*
   ```
   .link {color: red;}
   ```

7. 💛
**Avoid nesting selectors more than two levels deep.**  <br />

   *Bad:*
   ```
   .header .nav .nav-item .nav-link {}
   ```

   *Good:*
   ```
   .nav-link {}
   .nav-link, 
   .text-link {}
   .header .nav-link {}
   .footer .nav-link {}
   ```

8. 💛
**Avoid styling tags directly** <br />
except for body, ul, a, img. <br />

   *Bad:*
   ```
   section {}
   header {}
   ```

   *Good:*
   ```
   body {}
   ul {}
   a {}
   img {}
   .page-header {}
   .block-section {}
   ```

9. 💛
**Elements with background images should have a matching background color.** 
   ```
   section {
      background-image: url(sunset.jpg);
      background-color: orange;
   }
   ```

10. ❤️
**Use consistent units for element sizes and positioning.** <br />
   Do not mix px and em. <br />
   If the font-size/height is set in em, then set the margin/padding in em as well. 

   *Bad:* 
   ```
   .link {
      font-size: 12px;
      line-height: 2em;
   }

   .text {
      padding: 8px;
      margin: 2.5em;
   }

   ```
   *Good:*
   ```
   .link {
      font-size: 12px;
      line-height: 2px;
   }

   .text {
      padding: 8px;
      margin: 2.5px;
   }
   ```

11. 💛
**Colors should be in a consistent format (hex or rgba).** <br />
Color notation is either in hex ```(#000)``` or rgba if there is transparency. <br />
Keywords are not used. <br />

   *Bad:* 
   ```
   .link {
      color: black;
   }
   ```

   *Good:*
   ```
   .link {
      color: #000;
   }
   ```

12. ❤️
**Use flex or grid for layouts** <br />
Do not use tables or positioning. 

13. ❤️
**Use appropriate properties for animations.** <br />
Use transform, translate, rotate, scale, opacity. <br />
Do not use properties that cause the page to repaint:  <br />
width, height, position, padding, margin. <br />
   
   *Bad:* 
   ```
   .link:hover {
      left: 50px;
   }
   ```

   *Good:*
   ```
   .link:hover {
      translate: 50px;
   }
   ```

14. ❤️
**All element states from the style guide are implemented.** 

15. ❤️
**Links must respond to ```:hover, :active и :focus```.** <br />
If not specified in the design, you can use underline, color change, etc. <br />
All links, except for menu items, must respond to the ```:visited``` state. 

16. 💛
**Interactions( ```:hover, :active и :focus```) should not change the document flow.** <br />
Adjacent elements should not change their position and size unless specified in the style guide. 

17. 💛
**Use vendor prefixes generated according to supported browsers.** <br />
CSS vendor prefixes are used and generated according to supported browsers. <br />
🛠  Autofrefixer https://autoprefixer.github.io/  

18. 💛
**Minify CSS files.** <br />
🛠 Minify https://www.minifier.org/  <br />
🛠CSS Minifier  https://www.toptal.com/developers/cssminifier  <br />
🛠 CSS Minify https://www.cleancss.com/css-minify/  <br />

19. 💛
**Remove unused CSS styles.** <br />
🛠 UnCSS Online https://uncss-online.com/  <br />
🛠 PurifyCSS https://github.com/purifycss/purifycss  <br />
🛠 PurgeCSS https://github.com/FullHuman/purgecss  <br />
🛠 Chrome DevTools Coverage https://developers.google.com/web/updates/2017/04/devtools-release-notes#coverage  
 
20. 💛
**CSS should be error-free and valid.** <br />
🛠 CSS Validator https://jigsaw.w3.org/css-validator/  <br />
🛠 Stylelint https://stylelint.io/  

21. 💚
**Use CSS variables for repeated values – colors, sizes, etc.** 

22. 💚
**Comment magic numbers in functions and browser hacks.** 


## 3. Images

1. ❤️
**Correct Image Format** <br />
Use JPEG or WEBP for photos;  <br />
SVG for low-color images and icons. 

2. ❤️
**Extract images without style filters from the design.** <br />
Shadows, rounded corners, filters, blend modes, gradients, transparency, and others should be added using CSS. 

3. ❤️
**Image Insertion** <br />
Use ```<img>``` for content images <br />
background-image for decorative images. 

4. ❤️
**Specify dimensions for all images.** <br />
Do not use px in attributes. <br />
```<img src=”example.jpg” width=”100” height=”100”>``` 

5. ❤️
**Provide alt text for all images.** <br />
https://axesslab.com/alt-texts/  <br />
```<img src=”example.jpg” alt=”photographer with nikon camera”>``` 

6. 💛
**Optimize images for browser rendering.** <br />
WebP format can be used for critical pages, such as the homepage. <br />
🛠 Imagemin https://github.com/imagemin/imagemin  <br />
🛠 ImageOptim https://imageoptim.com/  <br />
🛠 Kraken.io – alternative for optimizing png and jpg up to 1 Mb for free. https://kraken.io/web-interface  <br />
🛠 TinyPNG – for optimizing png, apng (animated png), and jpg without loss of quality. Available in both free and paid versions. https://tinypng.com/  <br />
🛠 ZorroSVG jpg-like compression for transparent images using svg masks. http://quasimondo.com/ZorroSVG/  <br />
🛠 SVGO  a Node.js tool for optimizing SVG files. https://github.com/svg/svgo  <br />
🛠 SVGOMG a web version of SVGO for online SVG file optimization.https://jakearchibald.github.io/svgomg/  <br />

7. 💚
**Use vector sprites where applicable.** <br />
Complete guide to SVG sprites https://medium.com/@hayavuk/complete-guide-to-svg-sprites-7e202e215d34  


## 4. Other 

1. ❤️
**The site should have a GitHub repository.** 

2. ❤️
**The root document should have folders like css, img, js.** 

3. ❤️
**The main page should be named index.html.** 

4. ❤️
**File names and extensions should be lowercase without spaces.** <br />

   *Bad:*
   ```
   Style.css
   Images
   catalog page.html
   loginPage.html
   ```

   *Good:*
   ```
   style.css
   img
   index.html
   catalog-page.html
   ```

5. ❤️
**Files should be uniformly formatted.** <br />
The same number of indents - tabs or spaces inside one file. <br />
The same number of empty lines before/after elements. <br />
Correct code nesting is maintained. <br />
It's easiest to use automatic alignment in the code editor for this. <br />
   
   *Bad:*
   ```
   .link:before {
      font-size:         12px;
   line-height:  14px; 
   }

   .link::after {
             font-size: 10px;
         line-height:  20px; 
   }
   ```
   
   *Good:*
   ```
   .link::before {
      font-size: 12px;
      line-height: 14px; 
   }
   .link::after {
      font-size: 10px;
      line-height: 20px; 
   }
   ```
   
6. ❤️
**The layout should match the design exactly with Perfect pixel** <br />
Block placement should be 1:1 compared to the design. <br />
A discrepancy of up to 5px for text is allowed. <br />
Corrections to the size and placement of poorly drawn blocks (1-2px difference on different pages) are allowed and even encouraged. 

7. ❤️
**The layout should display identically in the latest versions of Chrome, Opera, Firefox, Safari, and Edge.** <br />
BrowserShots.org <br />
Browserling.com <br />
BrowserStack <br />
LambdaTest <br />
CrossBrowserTesting <br />

8. ❤️
**The site should look good on all screen resolutions.** <br />
At a width of 1280, the site should match the design. <br />
At widths less than the design width, the site should either scale or have a horizontal scroll. <br />
At widths greater than the design width, the site content should remain centered, and all backgrounds should stretch to the full screen width. There should be no horizontal scroll. 

9. ❤️
**The site should handle content overflow gracefully.** <br />
When adding more text to elements; <br />
Text should not fall out of objects; <br />

When using images of inappropriate sizes; <br />
Overflow of content blocks should not break the grid. <br />

10. 💛
**Unnecessary code should be removed before production.** <br />
The layout should not contain commented-out "just in case" pieces of code, unnecessary unused files, old versions of files, etc. 

11. 💚
**Use a typographer for text formatting.**  

12. 💛
**There should be no errors in the browser console.** 

