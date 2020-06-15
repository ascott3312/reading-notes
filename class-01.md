# Introductory HTML and JavaScript
 - HTML (Hypertext Markup Language) - is the code that defines the structure and text for a web page. HTML files have file extensions = .html
 - JavaScript - programming language used to create interactive effects within web browsers. JavaScript files have file extensions = .js
## How the Web Works
1. When you connect to the web you do it through an **Internet Service Provider** (ISP).
1. ***Next*** your computer contacts a network of servers called **Domain Name System** (DNS), which contains the *IP Address* for the requested domain name.
1. ***Next*** the IP Address from DNS is returned to **computer** which allows the web browser to contact the **web server** that hosts the website.
1. ***Next*** the web server sends the page you requested back to your web browser.

### HTML Structure - uses element tags to define an HTML structure of a page. Open tags <> and Ending tags </>
- html, head, body are called element tags of the html page. Order matters: See below example (open and ending tags are not shown)
- html
-   head
-    head
-   body
-    body
- html 

#### Markup

**Which is the most current version of HTML**
 1. HTML 4 or HTML 5 - Answer: __HTML 5_.   
 1. Doctypes define the HTML or XML code being used for the web page (ie. (!DOCTYPE html), without the tags)
 1. What is the correct way to add a comment: ___'!-- Comment--'_. (note in code you would need tags < start  ending >) 
 1. What does this Escape Character represent &copy: or &#169: __Copywrite symbol __. 
 1. Try another Escape Character: &cent: or &#162 ___Cent symbol__.
 * Block-level elements will appear to start on new line. Ex. <h1> Header 1, <p> Paragraph, <ul> Unordered list, <ol> Ordered list
 * Inline-Level elements will appear to continue on the same line. Ex. <a> Attribute, <b> Bold, <em> Emphasis, <img> Image 
 * ID and Class Attributes are ways to identify a specific element or class of elements. Name must start with a letter or underscore

 ##### HTML 5
  1. Improved elements provide clearer ways of defining multiple <div> or block elements for the HTML page. Note: Older versions browsers must be told which elements are block level elements.
  1. Header and Footer elements tags make it easier to define in the code the different section of the web page and also has made reading the code easier
  1. Heading groups elements are used to grouping headings from Heading 1 thru Headding 6.
  1. Section groups elements are a way to organize a section of the page using a specific heading for that section
  1. Navigation elements is used to contain the major navigational blocks of the site.

  ###### Process and Design
  - Important steps to take before coding a web site.
    1. Identify the target audience and why they are coming to the website and what information they to find.
    1. Site maps allow yout to planthe structure of a site. Card sorting helps identify the which information goes with each heading of the site map.
    1. Wireframe is a visual picture of what the web page will look like. Using blocks and descriptions to define the different blocks and where the navigational text will go.
    1. Visual hierarchy refers to the order in which your eyes perceive what they see. Size, color and style are keys in the visual hierarchy.    

###### ABC Programming
 - files extentsion in projects is .js
 - The script element defines the specific file that is associated with the current web page. Ideally placed after the body element
 - Flowcharts can guide you in design the JavaScript code using a functions.
 - Variables are used to declare a value each of the value - ran only once if not contained withing a function
 - Functions names are defined in () and the code associated with a function is defiend within the {} curly brackets 