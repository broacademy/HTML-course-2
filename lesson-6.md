# Lesson 6. Forms

**[Presentation](presentations/presentation-6.pdf)**<br />
**[Manual](manuals/manual-6.pdf)**<br />

**[Video record](https://drive.google.com/file/d/1JgGfRVoFj9hAjCO50C6AYQUwcEfY4mob/view?usp=drive_link)**
**[Practice](https://codepen.io/broacademy/pen/dyBRzjZ)**

<!-- 
**[Example project images Pharmify](https://github.com/broacademy/pharmify/tree/lesson-6)**<br /> -->

### Homework

1. **Complete the Lesson**  
   Follow the instructions in the [lesson](https://github.com/russmaxdesign/maxdesign-slides/blob/master/01-html/lesson05.pdf) and create the corresponding HTML markup in an editor or CodePen.

2. **Markup and Style Forms in Binabox**  
     - Contact page
     - Sidebar on the catalog page and search bar 
     - Subscription block in the footer

3. **Specify Button Types**  
   Ensure that all buttons on the site have the appropriate `type` attribute specified (`button`, `submit`, or `reset`).

4. **Validate Your Forms**  
   Review and test the forms you’ve created to ensure they validate correctly, including handling required fields, pattern matching, and other validation rules.

### Additional (Optional)

1. **Form Course**  
   Complete the [HTML forms course](https://www.freecodecamp.org/learn/2022/responsive-web-design/learn-html-forms-by-building-a-registration-form/step-1) on FreeCodeCamp (in English).

2. **Toggle Element Challenge**  
   - Mark up and style a toggle element using the following resources:
     - [Layout](https://www.figma.com/file/OjvYUpHSZSQaqO91KXu9S9/Challenge-2?type=design&node-id=0-1&mode=design&t=c5mMWlezhGtGGeVe-0)
     - [Behavior prototype](https://www.figma.com/proto/OjvYUpHSZSQaqO91KXu9S9/Challenge-2?node-id=1-33&viewport=415%2C395%2C0.8798602223396301&scaling=contain)
     - [Task](https://piccalil.li/blog/challenge-002-toggle-switch/)

3. **Survey Form Project**  
   Follow the step-by-step guide to [create a survey form](https://www.freecodecamp.org/learn/2022/responsive-web-design/build-a-survey-form-project/build-a-survey-form) on FreeCodeCamp (in English).

4. **Style a Select Element**  
   Style any `<select>` element using the Nice Select library. You can complete this task in an editor or on CodePen.

5. **Markup and Style Forms in Binabox additional pages**  
     - Feedback form in blog article 

### Additional materials 

🟢 [Effective HTML5 Form Structure](https://webdesign.tutsplus.com/solid-html-form-structure--CRS-200266c): This article provides an overview of the key components necessary for creating structured and accessible HTML5 forms. It includes tips on using the correct tags for different types of data, making forms more understandable and user-friendly. (eng)

### Introduction to Forms

I highly recommend reading it because this series of articles can give you a good understanding of forms, and you might not need to read anything else :)

[Web forms. Working with user data.](https://developer.mozilla.org/en-US/docs/Learn/Forms) This module provides a series of articles that will help you master the essentials of web forms. Web forms are a very powerful tool for interacting with users — most commonly they are used for collecting data from users, or allowing them to control a user interface. However, for historical and technical reasons, it's not always obvious how to use them to their full potential. In the articles listed below, we'll cover all the essential aspects of Web forms including marking up their HTML structure, styling form controls, validating form data, and submitting data to the server.

🟢 [Your first form.](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form) This article provides your very first experience of creating a web form, including designing a simple form, implementing it using the right HTML form controls and other HTML elements, adding some very simple styling via CSS, and describing how data is sent to a server. 

🟢 [How to structure a web form.](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form) With the basics out of the way, we'll now look in more detail at the elements used to provide structure and meaning to the different parts of a form.

🟢 [Basic native form controls.](https://developer.mozilla.org/en-US/docs/Learn/Forms/Basic_native_form_controls) We will look at the functionality of the different form controls, or widgets, in detail — studying all the different options available to collect different types of data. In this particular article, we will look at the original set of form controls, available in all browsers since the early days of the web.

🟢 [The HTML5 input types.](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types) We'll look at the functionality of newer form controls in detail, including some new input types, which were added in HTML5 to allow the collection of specific types of data. 

🟢 [Other form controls.](https://developer.mozilla.org/en-US/docs/Learn/Forms/Other_form_controls) We now look at the functionality of non-<input> form elements in detail, from other control types such as drop-down lists and multi-line text fields, to other useful form features such as the <output> element (which we saw in action in the previous article), and progress bars.

🟢 [Advanced form styling.](https://developer.mozilla.org/en-US/docs/Learn/Forms/Advanced_form_styling) In this article, we will see what can be done with CSS to style the types of form controls that are more difficult to style — the "bad" and "ugly" categories. 

🟢 [Styling web forms.](https://developer.mozilla.org/en-US/docs/Learn/Forms/Styling_web_forms) We'll show how to style forms in CSS.

🟢 [UI pseudo-classes.](https://developer.mozilla.org/en-US/docs/Learn/Forms/UI_pseudo-classes) In this article, we explore the different UI pseudo-classes available for styling forms in different states.

🟢 [Client-side form validation.](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation) Before submitting data to the server, it is important to ensure all required form controls are filled out, in the correct format. This is called client-side form validation, and helps ensure data submitted matches the requirements set forth in the various form controls. This article leads you through basic concepts and examples of client-side form validation.

[Sending form data.](https://developer.mozilla.org/en-US/docs/Learn/Forms/Sending_and_retrieving_form_data) Once the form data has been validated on the client-side, it is okay to submit the form. This article looks at what happens when a user submits a form — where does the data go, and how do we handle it when it gets there? We also look at some of the security concerns associated with sending form data.

[How to build custom form controls.](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_build_custom_form_controls) In this article, we will discuss how to build a custom control. To that end, we will work with an example: rebuilding the `<select>` element. We will also discuss how, when, and whether building your own control makes sense, and what to consider when building a control is a requirement.

### Tags

#### Textarea

🟢 [`<textarea>` tag](https://www.w3schools.com/tags/tag_textarea.asp): On this W3Schools page, you will find all the necessary information about the `<textarea>` tag in HTML. It is used to create a multi-line text input field, making it an ideal tool for entering large amounts of text. The page includes code examples, attributes that can be used with `<textarea>`, and tips for applying them to improve the user interface of your forms. (eng)

#### Datalist

🟢 [`<datalist>` tag](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/datalist): This article on MDN Web Docs is a comprehensive resource dedicated to the `<datalist>` tag in HTML. `<datalist>` allows you to create a list of suggestions that appear as auto-complete options for an `<input>` element. It is a perfect tool for enhancing the user interface by providing quick access to frequently used or recommended values. The article contains a technical description, usage examples, and tips on optimizing user interaction with forms. (eng)

[Improve the UX of the input element using the `<datalist>` element](https://www.studocu.com/in/document/savitribai-phule-pune-university/information-technology/improve-ux-of-input-element-using-datalist-element-1681762673/58460543): This resource shares examples and practical tips on using `<datalist>` to enhance user interaction with forms on your site. Through detailed examples and explanations, the authors help developers understand how best to implement this useful extension for input elements. (eng)

[Easy auto-complete suggestions for inputs with the HTML5 `<datalist>` tag](https://levelup.gitconnected.com/easy-autocomplete-suggestions-for-inputs-with-the-html5-datalist-tag-22fcfc409235): This article explains how to use the `<datalist>` tag to create auto-complete functionality in input fields. Suitable for anyone who wants to add a suggestion feature to their forms, making them more user-friendly and intuitive. The author provides simple and easy-to-follow code examples that are easy to reproduce and adapt to your needs. (eng)

[Introducing the HTML5 `datalist` Element](https://webdesign.tutsplus.com/introducing-the-html5-datalist-element--webdesign-9888t): An introduction to the HTML5 `<datalist>` element, facilitating the creation of suggestion lists for text fields, providing an improved user experience. (eng)

#### Form 

[`<form>` tag](https://www.w3schools.com/tags/tag_form.asp): This W3Schools page provides a comprehensive overview of the `<form>` tag in HTML, which is a fundamental element for creating forms on web pages. Here you will find descriptions of attributes, usage examples,
and best practices to help create effective and functional forms for collecting user data. (eng)

[`form action` attribute in HTML](https://www.scaler.com/topics/form-action-in-html/): This article discusses the `action` attribute of the `<form>` tag, which specifies the URL to which the form will be submitted after completion. The author explains how to use this attribute correctly to control the behavior of forms and ensure proper data processing on the server or other resource. (eng)

#### Fieldset & Legend 

[`<fieldset>` tag](https://www.w3schools.com/tags/tag_fieldset.asp): This W3Schools page covers the basics of using the `<fieldset>` tag to group related elements in a form. In addition to the basic explanation, it provides code examples demonstrating how `<fieldset>` improves form structure and makes them more understandable for the user. (eng)

🟢 [The Magical Use of Uncommon Labels Fieldset and Legend](https://medium.com/frontend-canteen/the-magical-use-of-uncommon-labels-fieldset-and-legend-d3b29df4fb14): This article on Medium explores unique ways to use the lesser-known `<fieldset>` and `<legend>` tags to enhance form accessibility and organization. The author shares practical tips and examples showing how these elements can significantly improve form structure. (eng)

[`<legend>` tag](https://www.w3schools.com/tags/tag_legend.asp): This W3Schools page presents the `<legend>` tag and its application within `<fieldset>` to create titles for groups of form elements. In addition to theoretical information, it provides examples demonstrating how `<legend>` enhances form readability and accessibility. (eng)

#### Input 

[HTML5 New Input Types](https://www.tutorialrepublic.com/html-tutorial/html5-new-input-types.php): This tutorial introduces new input types introduced in HTML5 that make it easier to collect information from users by providing more intuitive data entry forms. (eng)

[`input` element in HTML](https://webdesign.tutsplus.com/html-element-input--cms-93700a): A deep dive into the HTML `<input>` element, exploring its various types and how they can be used to create interactive and functional forms. (eng)

[Custom Styling Form Inputs With Modern CSS Features](https://css-tricks.com/custom-styling-form-inputs-with-modern-css-features/): This article demonstrates how to style form inputs using modern CSS features, creating custom checkboxes, radio buttons, and switches without using JavaScript. (eng)

##### Color

[Limiting `input type="color"` to a certain palette (from an image)](https://christianheilmann.com/2020/04/22/limiting-input-type-color-to-a-certain-palette-from-an-image): In this intriguing post, Christian Heilmann demonstrates how to restrict color selection in an `<input type="color">` element to a specific palette extracted from an image. The article explores an interesting approach to customizing the color picker user interface, making it more relevant to the given context. Along with a practical example, the post discusses the technical details of the implementation and possible applications of such an approach. (eng)

##### Text

🟢 [Designing a Textbox: The Unabridged Version](https://www.smashingmagazine.com/2018/09/designing-a-textbox-unabridged/): This article on Smashing Magazine is a comprehensive guide to designing textboxes, one of the fundamental elements of user interfaces. The author breaks down how to create intuitive, accessible, and visually appealing textboxes for forms. From typography to focus styles, validation to responsive design, here you will find everything you need to make your textboxes stand out. (eng)

##### File

[How you can style the input file type in forms using CSS](https://www.educative.io/answers/how-you-can-style-the-input-file-type-in-forms-using-css): This tutorial on Educative explains how to style the file input field in forms using CSS. It covers various methods and approaches that allow you to override the default appearance of the file upload field, making it better fit your design. The lesson contains practical examples and tips for creating attractive and functional user interfaces for file uploads. (eng)

[Styling the Native File Upload Input Field](https://www.viget.com/articles/styling-native-file-upload-input-field/): Viget offers a detailed guide on styling the native file upload input field. The article explores different techniques and strategies for integrating a styled file upload field that improves user interaction with your website. The authors share tried and true methods for hiding the default upload element and replacing it with a custom component that looks consistent across all browsers. (eng)

##### Checkbox

[`checkbox` element in HTML](https://www.scaler.com/topics/checkbox-in-html/): This overview material is dedicated to the `<input type="checkbox">` element in HTML. Readers will learn about the basic use of checkboxes in forms, methods of managing state, and accessibility for users with disabilities. (eng)

🟢 [Toggle switch component with CSS checkbox hack](https://webdesign.tutsplus.com/toggle-switch-component-with-css-checkbox-hack--cms-35011t): This article shows how CSS can transform a standard checkbox into a stylish toggle switch. Using CSS hacks, the authors demonstrate creating a creative user interface without JavaScript. (eng)

[Which tag creates a checkbox for a form in HTML?](https://www.scaler.com/topics/which-tag-creates-a-checkbox-for-a-form-in-html/): Here, the use of the `<input type="checkbox">` tag to create checkboxes in HTML is described in detail. The article includes code examples and best practices to ensure ease of use and accessibility. (eng)

🟢 [Inclusively Hiding & Styling Checkboxes and Radio Buttons](https://www.sarasoueidan.com/blog/inclusively-hiding-and-styling-checkboxes-and-radio-buttons/): Sara Soueidan offers an in-depth analysis of inclusive methods for hiding and styling checkboxes and radio buttons. The article contains tips for ensuring accessibility and code examples for creating beautiful and functional form elements. (eng)

[Easy CSS3 Checkboxes and Radio Buttons](https://webdesign.tutsplus.com/quick-tip-easy-css3-checkboxes-and-radio-buttons--webdesign-8953a): This article re-examines using CSS3 to style checkboxes and radio buttons. Through simple and effective techniques, the authors demonstrate how to improve the appearance of a form. (eng)

##### Radio

🟢 [Creating a Material Design Floating Label Effect](https://webdesign.tutsplus.com/recreate-material-design-floating-label--cms-37326t): Learn how to recreate the popular floating label effect characteristic of Material Design using HTML and CSS. This tutorial offers a step-by-step guide and code that can be easily adapted to your projects. (eng)

[`radio button` element in HTML](https://www.scaler.com/topics/radio-button-in-html/): This resource provides a detailed examination of the `<input type="radio">` element in HTML, offering recommendations on its use in forms to create mutually exclusive options. The article includes examples and tips for ensuring the best user interaction. (eng)

##### Date

[`date picker` element in HTML](https://www.scaler.com/topics/date-picker-in-html/): Learn how to use the date picker element in HTML to provide users with a simple and intuitive way to select dates. The article covers various attributes of `<input type="date">`, offering best practices and tips for improving the user interface. (eng)

##### Search 

🟢 [Search bar in HTML](https://www.scaler.com/topics/search-bar-in-html/): Learn how to add a search bar to your website using HTML. This article will guide you through creating and styling the search form element, providing tips for customization and optimization for better user experience. (eng)

#### Label 

🟢 [`label` tag](https://www.w3schools.com/tags/tag_label.asp): W3Schools offers a comprehensive overview of the `<label>` tag in HTML, including its syntax, attributes, and usage examples. Learn how the `<label>` tag improves forms, making them more accessible and user-friendly. (eng)

[`label` element in HTML](https://www.scaler.com/topics/labelr-tag-in-html/): This article provides a detailed guide on using the `<label>` element in HTML. You will learn how `<label>` improves interactivity and form accessibility, along with tips for effectively using it in your web projects. (eng)

#### Button

🟢 [Why it's important to give your HTML button a type](https://dev.to/clairecodes/why-its-important-to-give-your-html-button-a-type-58k9): This article explains why it is important to specify the `type` attribute for HTML buttons. Without a clearly defined type, buttons can behave unpredictably, especially when used in forms. Specifying the type helps ensure the correct behavior of the button. (eng)

[Button Design](https://uxdesign.cc/button-design-user-interface-components-series-85243b6736c7): Taras Bakusevich provides a detailed analysis of button design, highlighting their key significance in the interface. The article covers best practices for creating effective, user-friendly, and aesthetically pleasing buttons, supported by tips and illustrations. (eng)

[Styling the Good Old Button](https://ishadeed.com/article/styling-the-good-old-button): Ahmad Shadeed demonstrates how to apply modern CSS techniques to style traditional HTML buttons, making them look stylish and contemporary. The article includes many practical tips and code examples. (eng)

[CSS Buttons](https://sharkcoder.com/blocks/button): Learn all about the `<button>` tag in HTML, including ways to style CSS buttons and create floating buttons. The article contains tutorials and examples to help you understand button design and functionality. (eng)

#### Select

[`<select>` Tag](https://www.w3schools.com/tags/tag_select.asp): Learn how to use the `<select>` element in HTML to create a drop-down list. This element allows users to select one or more options from a list, making it an essential tool for forms. (eng)

[`selectmenu` element](https://css-tricks.com/the-selectmenu-element/): An introduction to `<selectmenu>`, a new element for creating customized drop-down lists, providing more in-depth styling and better accessibility compared to the classic `<select>`. (eng)

[`<select>` element in HTML](https://webdesign.tutsplus.com/html-element-select--cms-93261a): A complete guide to the `<select>` element in HTML, including ways to style and manage it through CSS and JavaScript. (eng)

[`<optgroup>` Tag](https://www.w3schools.com/tags/tag_optgroup.asp): Learn how to group related options in a drop-down list using the `<optgroup>` element, creating more structured and understandable forms. (eng)

[`<option>` Tag](https://www.w3schools.com/tags/tag_option.asp): This resource provides information about the `<option>` element used within `<select>`, `<optgroup>`, or `<datalist>` to define options that the user can choose. (eng)

🟢 [HTML `<select>` Tag – How to Make a Dropdown Menu or Combo List](https://www.freecodecamp.org/news/html-select-tag-how-to-make-a-dropdown-menu-or-combo-list/): A detailed guide on how to create a drop-down menu or combo list using the `<select>` element, including ways to style and improve user interaction. (eng)

🟢 [How TO - Custom Select Box](https://www.w3schools.com/howto/howto_custom_select.asp): A tutorial on creating a customized drop-down list using CSS and JavaScript, offering complete freedom in styling and behavior. (eng)

[Quick Tip: Don't Forget the `optgroup` Element](https://webdesign.tutsplus.com/quick-tip-dont-forget-the-optgroup-element--webdesign-9878a): A quick tip on using `<optgroup>` to improve structuring and organizing options within drop-down lists. (eng)

[The `<option>` Tag in HTML](https://www.scaler.com/topics/option-tag-in-html /): An analysis of the `<option>` element and its use in HTML to define choice options within `<select>`, `<optgroup>`, and `<datalist>` elements. (eng)

#### Progress

[The HTML5 `<progress>` Element](https://css-tricks.com/html5-progress-element/): This article on CSS-Tricks delves into the HTML5 `<progress>` element, offering usage examples and styling nuances to create intuitive progress indicators. (eng)

[Try the `<progress>` tag yourself!](https://www.w3schools.com/tags/tryit.asp?filename=tryhtml5_progress): W3Schools offers an interactive example that lets you try and experiment with the `<progress>` element directly in the browser. Explore its behavior and styling in practice. (eng)

[Progress bar in HTML](https://www.scaler.com/topics/progress-bar-in-html/): Discover how to create a progress bar in HTML using the `<progress>` element. The article includes detailed instructions and optimization tips for various uses, from file uploads to task completion tracking. (eng)

#### Meter

[The HTML5 `<meter>` Element](https://css-tricks.com/html5-meter-element/): This article from CSS-Tricks covers the HTML5 `<meter>` element, which is used to display scalar measurements or percentage values within a known range, such as disk usage or skill ratings. (eng)

[`<meter>` tag](https://www.w3schools.com/tags/tag_meter.asp): W3Schools provides a simple and clear explanation of the `<meter>` element, including its attributes and usage examples. Perfect for a quick understanding of basic concepts. (eng)

[`meter` element in HTML](https://www.scaler.com/topics/meter-tag-in-html/): Delve into the details of the `<meter>` element with this article, which explains its purpose, attributes, and ways to use it in HTML documents to display measurable values. (eng)

#### Range 

[Creating a custom range input slider consistent across browsers](https://www.smashingmagazine.com/2021/12/create-custom-range-input-consistent-browsers/): This article from Smashing Magazine demonstrates how to create a custom range input (`<input type="range">`) that looks and works consistently across different browsers. Ideal for those who want to offer users a convenient way to input numerical values using a slider. (eng)

### Toggle

[Switch](https://web.dev/patterns/components/switch?hl=en): Web developers can explore this resource from web.dev to create a switch component in their projects. An excellent way to add interactive control elements to your web pages. (eng)

[Building a switch component](https://web.dev/articles/building/a-switch-component?hl=en): This article provides a detailed guide on building a switch component, starting from basics to advanced techniques. Perfect for developers looking to improve their web applications' interfaces. (eng)

[On Designing and Building Toggle Switches](https://www.sarasoueidan.com/blog/toggle-switch-design/): Sara Soueidan shares her insights on designing and implementing toggle switches. The article contains useful tips and examples that can be helpful when incorporating this control element. (eng)

[HTML Toggle](https://www.scaler.com/topics/html-toggle/): An introduction to using toggles in HTML. A great starting resource for those looking to learn the basics of adding toggles to their web pages. (eng)

[Toggle switch component with CSS checkbox hack](https://webdesign.tutsplus.com/toggle-switch-component-with-css-checkbox-hack--cms-35011t): A unique way to create a toggle switch component using CSS and a checkbox hack. Useful for developers seeking creative solutions. (eng)

### Attributes 

🟢 [Disabled button](https://www.scaler.com/topics/button-disabled/): Learn how to use the `disabled` attribute for buttons in HTML to control the accessibility of form control elements for users. This is foundational for creating intuitive user interfaces. (eng)

🟢 [`inputmode`](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/inputmode): Discover the `inputmode` attribute, which allows developers to specify the type of keyboard that should be displayed on mobile devices, improving the user experience. (eng)

🟢 [`pattern` attribute](https://www.scaler.com/topics/pattern-attribute-in-html/): Explore the use of the `pattern` attribute for client-side validation using regular expressions, ensuring more robust form processing. (eng)

[Regular Expressions (Regex)](https://www3.ntu.edu.sg/home/ehchua/programming/howto/Regexe.html): Dive into the world of regular expressions with this comprehensive guide, covering basic and advanced techniques for string manipulation and data validation. (eng)

🟢 [`autocomplete`](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/autocomplete): Discover the benefits of using the `autocomplete` attribute in HTML to improve user interaction with forms by offering data auto-completion based on input history. (eng)

🟢 [`autofocus` attribute in HTML5](https://www.samanthaming.com/tidbits/42-html5-autofocus/): Master `autofocus`, an HTML5 attribute that automatically focuses on an element when the page loads, improving the user experience when interacting with forms. (eng)

🟢 [`download` attribute in HTML](https://www.samanthaming.com/tidbits/38-html-download-attribute/): Explore how the `download` attribute allows users to save resources directly from a hyperlink, simplifying the file download process. (eng)

[`contenteditable` attribute in HTML](https://www.samanthaming.com/tidbits/32-html-contenteditable/): Get acquainted with `contenteditable`, an attribute that makes any HTML element editable, opening doors for creating interactive web applications. (eng)

🟢 [Styling the placeholder with CSS](https://www.samanthaming.com/tidbits/88-css-placeholder-shown/): Learn how to style input placeholders using CSS to create forms with improved visual presentation and interaction. (eng)

🟢 [`name` attribute in HTML](https://www.scaler.com/topics/name-attribute-in-html/): Understand why the `name` attribute is critically important for handling and identifying form data and how to use it correctly in your web projects. (eng)

[`autofocus` in HTML](https://www.scaler.com/topics/html-autofocus/): Learn how the `autofocus` attribute helps improve form navigation and accessibility by automatically focusing on a key element. (eng)

### Styling

🟢 [`:autofill` selector](https://css-tricks.com/almanac/selectors/a/autofill/): Dive into the world of customizing the visual appearance of auto-filled forms using the `:autofill` selector. Learn how to override default browser styles to improve user experience. (eng)

🟢 [`focus-visible` pseudo-class in CSS](https://webdesign.tutsplus.com/css-pseudo-class-focus-visible--cms-37211t): Discover the `:focus-visible` pseudo-class and its importance in creating an accessible and visually distinguishable focus on interactive elements of the website. (eng)

🟢 [Introduction to styling HTML forms](https://webdesign.tutsplus.com/an-introduction-to-styling-html-forms--CRS-201004c): Start your journey through styling HTML forms with this comprehensive guide, covering the basics and advanced techniques for creating impressive forms. (eng)

[Simplifying form styles with accent color](https://www.smashingmagazine.com/2021/09/simplifying-form-styles-accent-color/): Learn how using an accent color can simplify form styling, making them more attractive and consistent across the website. (eng)

### Validation

🟢 [Bring your forms up to date with CSS3 and HTML5 validation](https://webdesign.tutsplus.com/bring-your-forms-up-to-date-with-css3-and-html5-validation--webdesign-4738t): This article helps you master the latest HTML5 and CSS3 capabilities for form validation, ensuring excellent user experience and enhancing overall form performance. (eng)

🟢 [HTML5 form validation with the `pattern` attribute](https://webdesign.tutsplus.com/html5-form-validation-with-the-pattern-attribute--cms-25145t): Learn how to use the `pattern` attribute in HTML5 to create powerful regular expressions that help you validate user input directly in the form. (eng)

### Best practices 

[11 HTML best practices for login & sign-up forms](https://evilmartians.com/chronicles/html-best-practices-for-login-and-signup-forms): Familiarize yourself with 11 best practices for login and registration forms to help you avoid common mistakes and improve user experience on your site. (eng)

[Creating a login page in HTML](https://www.scaler.com/topics/login-page-in-html/): Learn about the key elements and best practices for creating an attractive and secure login page on your site. (eng)

[Survey form project in HTML](https://www.scaler.com/topics/survey-form-project-html/): Dive into creating interactive survey forms using this project as a practical guide to implementing your own survey form. (eng)

[20 HTML forms best practices for beginners](https://webdesign.tutsplus.com/20-html-forms-best-practices-for-beginners--net-6593t): Familiarize yourself with 20 essential rules and recommendations to help beginners create effective and accessible HTML forms. (eng)

[Working with HTML forms](https://www.scaler.com/topics/html/html-forms/): This comprehensive guide to HTML forms covers everything from basic elements to advanced validation and styling techniques. (eng)

[CSS form elements problem](https://www.smashingmagazine.com/2013/02/css-form-elements-problem/): This article addresses common issues and challenges related to styling form elements in CSS and suggests solutions. (eng)

[Registration form in HTML](https://www.scaler.com/topics/registration-form-in-html/): A detailed guide on creating a registration form, emphasizing the importance of proper structure, validation, and security. (eng)

[Learn how to create dynamic and user-friendly input forms on your web pages with HTML](https://app.uxcel.com/courses/html-for-designers/html-forms-733): This online course will teach you how to create dynamic and user-friendly input forms on your web pages. (eng)

[Web forms — Working with user data](https://developer.mozilla.org/en-US/docs/Learn/Forms): Familiarize yourself with the key aspects of creating web forms and working with user data, ensuring best practices in accessibility and security. (eng)

[A Form of Madness](http://diveintohtml5.info/forms.html): Explore the depths of HTML5 forms with this detailed guide, diving into the history, purpose, and best practices for using forms on web pages. (eng)

[HTML Forms](https://sharkcoder.com/blocks/form): This article contains examples of HTML form designs with code. It will help you style your HTML form, create all types of custom inputs, and connect the form without using JavaScript or PHP. (eng)

[Sign-up form best practices codelab](https://web.dev/articles/codelab-sign-up-form-best-practices?hl=en): This practical course presents best practices for creating a registration form, ensuring a high level of user experience and conversion. (eng)

[Use cross-platform browser features to build a sign-in form](https://web.dev/articles/codelab-sign-in-form-best-practices?hl=en): This course explains how to use browser features to create a sign-in form, ensuring the best cross-platform compatibility. (eng)

[Payment form best practices codelab](https://web.dev/articles/codelab-payment-form-best-practices?hl=en): Learn the best practices for creating a payment form that helps improve usability and transaction security. (eng)

[Payment and address form best practices](https://web.dev/articles/payment-and-address-form-best-practices?hl=en#meaningful-html): This article provides a guide to best practices for payment and address forms, emphasizing the importance of proper HTML markup. (eng)

[Address form best practices codelab](https://web.dev/articles/codelab-address-form-best-practices?hl=en): A practical course offering the best methods for creating address forms to improve user interaction and data accuracy. (eng)

[Inclusively Hidden](https://www.scottohara.me/blog/2017/04/14/inclusively-hidden.html): Learn about accessible methods for hiding content on web pages that should not be visible to users but accessible to screen readers. (eng)

[The ‘Form’ Element Created the Modern Web. Was It a Big Mistake?](https://www.wired.com/story/form-element-modern-web-mistake/): An interesting reflection on how the `<form>` element has influenced the development of the modern web and whether it was a big mistake in web development history. (eng)

[5 best practices for better HTML forms](https://devdojo.com/abhiraj/5-best-practices-for-better-html-forms): This article offers five best practices for improving HTML forms, including tips on accessibility, validation, and user interface. (eng)

### Other

[`dropdown` element in HTML](https://www.scaler.com/topics/dropdown-in-html/): Learn the basics of creating dropdown menus in HTML, including various implementation methods to improve navigation and user interface. (eng)

[How to build a filtering component in pure CSS](https://webdesign.tutsplus.com/how-to-build-a-filtering-component-in-pure-css--cms-33111t): This tutorial teaches you how to create a powerful filtering component using only CSS, without JavaScript. (eng)

[Getting started with CSS multi-column layout](https://webdesign.tutsplus.com/getting-started-with-css-multi-column-layout--CRS-200942c): Explore CSS's capabilities for creating multi-column layouts that adapt to different screen sizes. (eng)

[`dropdown menu` in HTML](https://www.scaler.com/topics/dropdown-menu-in-html/): Discover techniques for creating flexible and responsive dropdown menus in HTML, enhancing user interaction. (eng)

[CSS Property: `cursor`](https://webdesign.tutsplus.com/css-property-cursor--cms-107395a): This article offers a complete guide to the CSS `cursor` property, allowing you to customize the mouse cursor for better user interaction. (eng)

### Courses 

[Learn HTML: Forms course](https://www.codecademy.com/learn/learn-html-forms): Codecademy presents an extensive course dedicated to everything related to HTML forms, starting from the basics and moving to more complex aspects. (eng)

[Learn Forms](https://web.dev/learn/forms): This course on HTML forms will help improve your web developer expertise, covering everything from creating forms to their validation and optimization. (eng)

### Demos 

#### Accent-color 

[Accent-color – light and dark](https://codepen.io/michellebarker/pen/OJgWNNZ?editors=1100): This CodePen demonstrates how the `accent-color` property can be used to customize the appearance of form elements in light and dark mode. (eng)

[Accent-color – showing two different colours](https://codepen.io/michellebarker/pen/GRErKpy?editors=1100): Here it is shown how `accent-color` can be used to set different colors for various form elements, improving the user interface. (eng)

[Accent-color – simple](https://codepen.io/michellebarker/pen/oNwYPRY): A simple example demonstrating the use of `accent-color` to set accent colors in form elements. (eng)

#### Examples of form elements

[All form elements](https://codepen.io/russweakley/details/GROXVML): This CodePen page is a comprehensive overview of all HTML form elements, including buttons, text fields, switches, and more. (eng)

[All input types](https://codepen.io/russweakley/details/LYOJwLm): An excellent resource for exploring various HTML input types, including text, password, date, and others. (eng)

[Input types](http://russmaxdesign.github.io/html-css-tests/sample-input-types/index.htm): This site demonstrates the capabilities and variety of input types in HTML, from text to date selection. (eng)

[Input playground](https://codepen.io/pete-otaqui/pen/zBbvbK): An interactive CodePen playground for experimenting with various HTML input types and their styling. (eng)

[UI input](https://codepen.io/chrisbautista/pen/KKQqPoZ?editors=1010): An example of styled input elements demonstrating how to improve the appearance of forms using CSS. (eng)

#### Forms

[Login/Registration Form](https://codepen.io/ig_design/pen/KKVQpVP): A modern design for a login and registration form, demonstrating good UX/UI design practices. (eng)

[Login Form](https://codepen.io/stack-findover/pen/OJRvPQv): An elegant login form with a minimalist design and smooth animations. (eng)

[Search Form](https://codepen.io/kathykato/pen/dzdgPJ): An interactive search form with advanced features and beautiful visual design. (eng)

[Payment Form](https://codepen.io/simoberny/pen/XgEgGg?editors=1010): An example of a payment form with field validation and a user-friendly interface. (eng)

[Form example](https://codepen.io/team/css-tricks/pen/GRvxOEN?editors=1010): A multifunctional form from the CSS-Tricks team with various types of fields. (eng)

[Form example](https://codepen.io/russweakley/pen/NWYVNYm): An excellent form example with detailed input fields and a clear structure. (eng)

[Standard Form Example](https://codepen.io/russweakley/pen/oNoMmJz): A classic form with basic input fields, suitable for many web projects. (eng)

[Subscribe Form](https://codepen.io/alexanderkwright/details/abeLrp): A subscription form with an attractive design and animated elements. (eng)

[Awesome CSS Select Styles You Can Use Right Now](https://www.sliderrevolution.com/resources/css-select-styles/): A set of creative styles for `<select>` elements with code examples. (eng)

[Flight Booking Form HTML Code](https://www.codepel.com/forms/flight-booking-form-html-code/): HTML code for a flight booking form, demonstrating the structure and interface elements of a booking system. (eng)

[Fieldset, legend, radio, checkbox, select, optgroup](https://codepen.io/maddesigns/details/xxXdQZ): A form example including the use of `<fieldset>`, `<legend>`, radio buttons, checkboxes, `<select>`, and `<optgroup>`. (eng)

[Fieldset, legend, number, range, color, checkbox, select](https://codepen.io/meodai/pen/GRyjQoZ): An interactive example showing the use of number fields, sliders, color pickers, checkboxes, and select lists. (eng)

[Fieldset, checkbox, radio, select, textarea](https://codepen.io/emgerold/pen/nabOYB): A demonstration of various form elements, including field grouping, checkboxes, radio buttons, select lists, and text areas. (eng)

#### Floating label 

[Floating label](https://codepen.io/team/css-tricks/pen/XVBLRM): An innovative example of a floating label that moves when focused on the field. (eng)

[Floating label](https://codepen.io/kvncnls/pen/MWmJaPw): An example of a floating label with an impressive animated transition, adding a touch of flair to UX design. (eng)

[Floating label](https://codepen.io/Metty/pen/NWpzexj): Another stylish example of a floating label, perfect for modern forms. (eng)

[Floating label on focus](https://russmaxdesign.github.io/floating-label/): A tutorial on creating a floating label effect, improving the visual perception of the form. 

#### Validation 

[Form validation without JS](http://codepen.io/sealeye/pen/JKBgkK): This example shows how form validation can be done on the client side without using JavaScript, using only HTML5 and CSS. (eng)

[Form validation](https://codepen.io/russweakley/pen/PoEdMZz): A demonstration of form validation highlighting fields with errors and providing feedback to the user. (eng)

[JS Validation](https://codepen.io/Maxim_Petrischak/pen/wmmBvJ?editors=1010): An example of form validation using JavaScript for additional checks and processing of user input. (eng)

[Form Validation with Pattern](https://codepen.io/davidhellmann/pen/OOLmYq?editors=1010): Using the `pattern` attribute in HTML for form validation, allowing data to be checked against a specified pattern. (eng)

[Form with errors](https://codepen.io/russweakley/pen/zYpMQex): An example of a form that displays error messages next to the corresponding input fields, enhancing user experience. (eng)

[How to mark an error message](https://codepen.io/russweakley/pen/gOXZdeK): This example shows an effective way to place error messages in forms, making them accessible and understandable for users. (eng)

#### Select

[Native select](https://codepen.io/russweakley/pen/GRXvYPb): A simple example using the native HTML `<select>` element without additional styles. This example demonstrates the basic functionality of the selection. (eng)

[Styled select](https://codepen.io/russweakley/pen/abayReK): An example of an HTML `<select>` element with custom styles that give it a unique look and improve the user interface. (eng)

#### Progress

[Progress](https://codepen.io/team/css-tricks/pen/PNNQxm): A demonstration of the `<progress>` element in HTML presented by the CSS-Tricks team. This example illustrates how to visualize task or upload progress using a standard HTML element and some CSS for styling. (eng)

#### Fieldset

[Fieldset Example](https://codepen.io/team/css-tricks/pen/yLaLXJb): This example from the CSS-Tricks team shows how to use the `fieldset` element to group related form elements, providing a clean and organized structure. A great way to improve the accessibility and usability of forms. (eng)

[How best to markup a group of checkboxes or radio buttons](https://codepen.io/russweakley/pen/ZEaqEON?editors=1010): Russ Weakley presents methods for optimal markup for groups of checkboxes and radio buttons, emphasizing accessibility and usability. Examples highlight the importance of proper structure for improving user interaction with the form. (eng)

[Fieldset](https://codepen.io/sivan/pen/eYMrgY): This example demonstrates how `fieldset` can be used to create visually appealing and logically organized form groups. Ideal for situations where information needs to be gathered in several logical blocks. (eng)

#### Input

[Disabled](https://codepen.io/russweakley/details/xxYBKeg): Russ Weakley shares an example of using the `disabled` attribute to disable form elements. This is useful when certain options are not available or when it is necessary to prevent form submission until certain conditions are met. (eng)

[Email Input with Inputmode](https://codepen.io/russweakley/pen/WNzXOWW): This example demonstrates using the `inputmode` attribute with an email input field to improve data entry on touch devices. This provides a more convenient and accurate user interaction. (eng)

[Where to use Label](https://codepen.io/russweakley/pen/wvmOMgX): In this example, Russ Weakley illustrates the proper use of the `label` element in forms. Using `label` enhances accessibility and improves user experience by linking text labels to corresponding input fields. (eng)

[Input Number](https://codepen.io/russweakley/pen/NWMbrWO): An example of a number input field using the `input type="number"`. This type of field allows users to easily enter and adjust numerical values, providing more efficient and targeted data entry. (eng)

[Autofocus examples](https://russmaxdesign.github.io/autofocus/index.html): A series of examples demonstrating the use of the `autofocus` attribute to automatically focus on a specific input field when the page loads. This improves user experience by directing the user's attention to the key element of the form immediately upon page load. (eng)

[Datepicker jQuery](https://codepen.io/gearmobile/pen/ggYBmm?editors=1010): This example shows how to integrate a jQuery datepicker into a web form to provide users with a convenient graphical interface for selecting dates. The datepicker enhances the intuitiveness of the date entry process. (eng)

[Datalist example](https://codepen.io/russweakley/details/KKyxOQg): An example of using the `datalist` element to provide users with an auto-completed list of options in an input field. This simplifies the data entry process by offering the user options based on their initial input. (eng)

##### Radio

[Star Rating](https://codepen.io/lsirivong/pen/nRNLYL): This example demonstrates implementing a star rating system using HTML and CSS. Users can easily express their rating by selecting the appropriate number of stars. (eng)

[Fieldset, Legend, Radio](https://codepen.io/jkantner/pen/eLMgWa): This example shows using the `fieldset`, `legend`, and `radio` elements to create a group of radio buttons with a clearly defined title. This enhances form structuring and accessibility. (eng)

[Fieldset, Legend, Radio](https://codepen.io/albebonv/pen/qBoKLQ): A similar example demonstrating the structuring of a group of radio buttons using `fieldset` and `legend`. The example emphasizes the importance of semantic markup to improve user experience. (eng)

[Fieldset, Checkbox, Radio, Disabled](https://codepen.io/elmahdim/pen/AVVJVe): This example includes using `fieldset` to group checkboxes and radio buttons. It also demonstrates the use of the `disabled` attribute to disable certain options. (eng)

##### Checkbox 

[Custom Checkbox Styling](https://codepen.io/sealeye/pen/JRoeqp): This example shows how to customize the appearance of checkboxes using only CSS, making them more attractive and fitting into the overall design of the site. (eng)

[Checkboxes](https://codepen.io/Momciloo/details/ZELzadv): Various styles for checkboxes are presented here, demonstrating CSS's flexibility in creating unique and interactive form elements. (eng)

[Fieldset and Checkbox](https://codepen.io/patrickkunka/pen/eYYaZB): An example combines `fieldset` and checkboxes, showing how to group form elements to improve navigation and accessibility. (eng)

[Styling Radio and Checkbox](https://codepen.io/russweakley/pen/LYXEBGv): This demo showcases different ways to style radio buttons and checkboxes, making them more noticeable and user-friendly. (eng)

[Checkboxes and Radio Buttons with Background Image](https://codepen.io/michellebarker/details/QWgMZNd): Using background images to create a unique appearance for checkboxes and radio buttons. This allows further customization of form elements to fit the site's overall style. (eng)

[Old Skool Custom Checkbox Styling](https://codepen.io/michellebarker/pen/qBjqeEG): A return to classic methods of styling checkboxes, offering a vintage and unique design that stands out against modern interfaces. (eng)

##### Toggle

[Toggle Examples Using Checkbox](https://russmaxdesign.github.io/switch-checkbox/): This resource demonstrates how checkboxes can be used to create effective and stylish toggles. The examples show that even simple HTML elements can be transformed into functional and visually appealing interface components. (eng)

[Toggles](https://codepen.io/aardrian/pen/WPWVvw): An overview of various styles and behaviors for creating toggles using accessible web standards. These examples highlight the importance of universal design and accessibility in interface development. (eng)

##### Pattern

[Patterns for Input](https://codepen.io/patik/details/WxoWLG): This example illustrates how patterns can be used for validating data entered into form fields. It demonstrates a variety of regular expressions to ensure the correctness of user input, making interfaces more user-friendly and reliable. (eng)

[Input Pattern](https://codepen.io/JesGraPa/pen/YPZvZK): This resource provides a practical example of using the `pattern` attribute in HTML input elements. It helps ensure data is entered in the required format, preventing form submission with incorrect data and enhancing the overall user experience. (eng)

##### Placeholder

[How to style placeholder](https://russmaxdesign.github.io/placeholder/): This resource offers guidelines and examples for styling placeholders in form fields, ensuring better visualization and improving the user experience. (eng)

[Placeholder test](https://codepen.io/russweakley/pen/RwyRBEO): An interactive demo allowing you to experiment with styles for placeholders and see the changes in real-time. (eng)

### Tools 

[Choosing `<input>` elements for mobile devices](https://better-mobile-inputs.netlify.app/): This tool helps you choose `<input>` elements and their attributes for optimal use on mobile devices, enhancing the user experience. (eng)

[Example of form tags](https://farm6.static.flickr.com/5085/5730351194_69b599cc03_o.png): An image demonstrating various form elements and their structure. (eng)

[Forms Cheatsheets on Codecademy](https://www.codecademy.com/learn/learn-html-forms/modules/html-forms/cheatsheet): A quick reference to all HTML form elements, offering quick access to information about different input types and their usage. (eng)

[WTF forms?](http://wtfforms.com/): A resource for styling form elements using CSS, designed for modern browsers, including IE9+ and the latest versions of Chrome, Safari, and Firefox. (eng)

[Input Type Sandbox](https://inputtypes.com/?ref=tiny-helpers): An interactive tool for experimenting with various `<input>` types, allowing you to see how they display in different browsers. (eng)

[Useful Regex Patterns](https://projects.lukehaas.me/regexhub/): A collection of useful regular expression patterns for developers, simplifying text data manipulation. (eng)

[Formlinter](https://formlinter.com/): Check all forms on the site, for example, the service can find the following errors:     
- Incorrect form element types.    
- Non-unique identifiers.     
- Missing required fields.     
- Lost buttons.     

### Plugins for styling form elements

[Range Slider Plugin](https://rangeslider.js.org/): A plugin for creating range selection sliders, offering flexible settings and styling. (eng)

[AL Range Slider on GitHub](https://github.com/Aleinbanger/al-range-slider): Another plugin for creating range sliders with touch device support and customizable design. (eng)

[Air Datepicker](https://air-datepicker.com/examples): A plugin for creating a calendar and date picker, offering extensive settings and easy integration. (eng)

[jQuery Nice Select](https://jqueryniceselect.hernansartorio.com/): A plugin for replacing the standard `<select>` element with a customized dropdown, improving the appearance and user experience. (eng)