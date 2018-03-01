# NanodegreeProjectPortfolioSiteSusanneDedecke

Udacity Logo
Logout
PROJECT SPECIFICATION
Build a Portfolio Site

Design

CRITERIA
MEETS SPECIFICATIONS
Required Elements

The page at minimum includes all of the following:

at least 4 images
title text (h1, h2, etc.)
regular (paragraph) text
a logo.
Semantic HTML

HTML5 semantic tags such as <header>, <footer>, <article>, <section> etc. are used to add meaning to the code.

No <div> or <section> tags are without a CSS class or id.

Check out the W3C documentation on HTML Structural Elements to learn more!

Custom Design

Provide at least one of the following customizations:

Customize images and text.
Customize placement of the elements on the page (grid layout) with HTML, CSS or both.
Customize CSS styles applied at minimum to paragraph and heading elements.
Grid-Based Layout

Page utilizes a grid-based layout with styles making use of the flexbox layout or a framework like Bootstrap, Foundation, etc.
If you're using Bootstrap: the rows and columns of the grid must be wrapped in an element with a container class.

Responsiveness

CRITERIA
MEETS SPECIFICATIONS
Cross-Device Compatibility

All content is responsive and displays on all display sizes. This includes:

Desktop
Mobile: Google Nexus 5
Tablet: Apple iPad
An image's associated title and text renders next to the image in all viewport sizes.

TIP: Test responsiveness with Chrome Developer Tools device emulation by right-clicking anywhere on page, selecting ‘Inspect Element’, clicking the rectangle to the left of the Elements tab, select Apple iPad or Google Nexus 5 from Device drop-down list, and click reload.

Provide All Content

All content is rendered on all three devices. No content should be hidden on mobile devices.

Viewport meta Tag

Viewport meta tag is included in HTML. (i.e. <meta name=”viewport” …)

Responsive Images

If a CSS framework is used, classes provided by the CSS framework are used to make images responsive, otherwise media-queries are used to ensure responsiveness of images.

Separation of Concerns

CRITERIA
MEETS SPECIFICATIONS
Styles Separated From HTML

Portfolio completely separates structure (HTML) from design/style (CSS). There are no style attributes present in the body of the HTML document. There are no <style> elements in the document.

Note: It is acceptable to include height and width attributes in <img> elements.

File structure

Files are organized with a directory structure that separates files based on functionality. For example:
css/ for stylesheets
img/ for images
js/ for JavaScript files

Code Quality

CRITERIA
MEETS SPECIFICATIONS
HTML Formatting rules

All code ( HTML element names, attributes, attribute values) is lowercase (except text/CDATA).
Code does not have trailing white spaces.
Indentation is consistent (either all tabs or all 2 spaces or all 4 spaces etc).
Code uses a new line for every block, list or table element and indent every such child element (it's acceptable to put all <li> elements in one line).
[Optional] When quoting attribute values, code uses double quotation marks.
HTML Style Rules

HTML documents use HTML5 <!doctype html>.
Code passes HTML and CSS validators.
*[Optional] Code does not use entity references unless necessary e.g. characters with special meaning in HTML (like < and &) as well as control or “invisible” characters (like no-break spaces).
[Optional] Code omits type attributes for style sheets and scripts.
CSS Formatting Rules

Code does not have trailing white spaces.
Indentation is consistent (either all tabs or all 2 spaces or all 4 spaces etc).
Code indents all block content, that is rules within rules as well as declarations to reflect hierarchy and improve understanding.
Code uses a semicolon after every declaration for consistency and extensibility reasons.
Code always uses a space after a property name's colon, but no space between property and colon, for consistency reasons.
Code always use a single space between the last selector and the opening brace that begins the declaration block.
Code always start a new line for each selector and declaration.
Code always put a blank line (two line breaks) between rules.
[Optional] Code uses double quotation marks for attribute selectors or property values. Do not use quotation marks in URI values (url()).
CSS Style Rules

Code uses meaningful or generic ID and class names that are as short as possible but as long as necessary.
Code does not use element names in conjunction with IDs or classes.
Code uses shorthand properties where possible.
[Optional] Code omits unit specification after 0 values.
[Optional] Code includes leading 0s in decimal values for readability.
[Optional] Code uses 3-character hexadecimal notation where possible.
[Optional] Code separate words in ID and class names by a hyphen.
[Optional] Code avoids user agent detection as well as CSS "hacks"—try a different approach first.
General Meta Rules

HTML templates and documents use UTF-8 encoding. (no BOM) i.e. <meta charset="utf-8">.
*[Optional] Mark todos and action items with TODO
Suggestions to Make Your Project Stand Out!
Use srcset in the img elements to provide optimized images to users on all device sizes.

Include additional JavaScript functionality, while maintaining required components. For example: Bootstrap Navbar, Polymer Components.

Student FAQ

How do I Complete this Project?
All of the lessons you'll need to help you build this can be found in the lessons in this part of your Nanodegree program.

Depending on your background knowledge of HTML and CSS, you may not need to complete all lessons to build this project. To evaluate what you'll need to know, start by downloading the mockup we've provided, and review the Project Rubric.

Be sure to follow the Project Rubric closely when designing your page. For example, note that HTML5 semantic (structural) elements must be used to organize content.

Instructions:

Download the design mockup file from the Downloadables section (in the lower right hand corner of your screen, just below this text) and review it.
Identify the various boxes you will need to build in order to recreate this design.
Write your HTML and CSS files, continue to iterate until your work is representative of the design mockup.
Take the time to personalize your portfolio with custom colors, additional content and your own images.
Validate your HTML and CSS against the W3C's Validators. Note: the validators consider the following errors, whereas Udacity accepts these errors as acceptable:
HTML5: Bad value X-UA-Compatible for attribute http-equiv on element meta when using the X-UA-Compatible meta tag.
CSS3: Property [some property here] is an unknown vendor extension when using vendor prefixed properties (like -moz-box-sizing).
Additional resources
Here are some tools you will find useful in checking your work —

Udacity HTML/CSS Style Guide
HTML Validator
CSS Validator
Supporting Materials

Project:
Build a Portfolio Site
 1. Project Overview
 2. Project Details
 3. Project: Build a Portfolio Site
Mentorship
Get support and stay on track

Build a Portfolio Site
DUE
22.3.2018
Project Submission
You will be provided with a design mockup as a PDF-file and must replicate that design in HTML and CSS. You will develop a responsive website that will display images, descriptions and links to each of the portfolio projects you will complete throughout the course of your Nanodegree program.

The design mockup is located here.

Evaluation
Your project will be evaluated by a Udacity Code Reviewer according to the Build a Portfolio Project Rubric. Be sure to review it thoroughly before you submit. All criteria must "meet specifications" in order to pass.

Submit here.

Please note the HTML and CSS style guidelines below - following these is necessary to make sure your code passes the Code Quality rubric point.

Style Guidelines
CSS Guidelines
CSS - Use consistent indentation (tabs or spaces). (See: CSS General Formatting Rules-Indentation)
CSS - Selectors, properties and property values (with the exception of strings) should be lowercase, including letters in hexadecimal color values. For example #f06c13 instead of #F06C13 and #ccc rather than #CCC. (See: CSS-General Formatting Rules-Capitalization.)
CSS - Use IDs and class names that are meaningful or generic. (See: CSS-ID and Class Naming.)
CSS - Use ID and class names that are as short as possible but as long as necessary. (See: CSS-ID and Class Naming.)
CSS - Use Shorthand properties in all possible places for margin, border, padding, background. Examples: https://developer.mozilla.org/en-US/docs/Web/CSS/Shorthand_properties. (See: CSS Style Rules-Shorthand Properties.)
CSS - Indent block content between curly braces. (See: CSS Formatting Rules-Block Content Indentation.)
CSS - End all declarations with a semicolon. (See: CSS Formatting Rules-Declaration Stops.)
CSS - Add single spaces after each property name’s colon (See: CSS Formatting Rules-Property Name Stops.)
CSS - Remove trailing white spaces from code. (See: CSS General Formatting Rules-Trailing Whitespace)
CSS - Include a single space before the opening curly brace. (See: CSS-Declaration Block Separation.)
CSS - ID and class names should not be used with type selectors. (See Style Guide: CSS Style Rules-Type Selectors.)
CSS - Separate style rules with a blank line. (See: CSS-Rule Separations.)
CSS - Remove units of measure after 0 values. (See: CSS Style Rules-0 and Units.)
CSS - Use leading zeros for values in the code. (See: CSS Style Rules-Leading 0s.)
CSS - Use 3 character hexadecimal notation for color in all possible places. For example #ccc rather than #cccccc. (See: CSS Style Rules-Hexadecimal Notation.)
CSS - Separate words in ID and class names with a hyphen. (See: CSS Style Rules-ID and Class Name Delimiters.)
CSS - Remove CSS hacks or user detection from code. (See: CSS Style Rules-Hacks.)
CSS - Separate selectors and declarations with new lines. (See: CSS-Selector and Declaration Separation.)
CSS - Use double quotes for all attribute selectors and property values. (See: CSS Formatting Rules-CSS Quotation Marks.)
CSS - Identify groups of related style rules with section comments. (See: CSS Meta Rules-Section Comments.)
HTML Guidelines
HTML - Element and attribute names should all be lowercase. (See: Capitalization.)
HTML - Use HTML5. (See: HTML Style Rules-Document Type.)
HTML - Use UTF-8 as character encoding. (See: General Meta Rules-Encoding.)
HTML - Place all block/list/table elements on a separate line and indent child elements. (See: HTML-General Formatting.)
HTML - Use semantic tags. (See: HTML Style Rules-Semantics.)
HTML - Provide alternate content for multimedia. (See: HTML Style Rules-Multimedia Fallback.)
HTML - Remove trailing white spaces from code. (See: HTML - General Formatting Rules - Trailing Whitespace.)
HTML - Use consistent indentation (tabs or spaces) (See HTML - General Formatting Rules - Indentation)
HTML - Use comments to explain the code. (See: General Meta Rules-Comments.)
HTML - Mark action items with TODO. (See: General Meta Rules-Action Items.)
HTML - Remove entity references. (See: HTML Style Rules-Entity References.)
HTML - Remove type attribute from link and script elements. (See: HTML Style Rules-Type Attributes.)
HTML - Use double rather than single quotation marks for attribute values. (See: HTML-HTML Quotation Marks.)
Submission
The master branch is the default Github repository branch. If you wish to submit another branch, you'll need to set it as the new default branch inside your Github repository.
When you're ready to submit your project go back to your Udacity Home, click on Project 1, and we'll walk you through the rest of the submission process. Due to the high volume of submissions we receive, please allow up up to 7 business days for your evaluation to be returned.
If you are having any problems submitting your project or wish to check on the status of your submission, please email us at frontend-project@udacity.com or visit us in the discussion forums.
What's Next?
You will get an email as soon as your reviewer has feedback for you. In the meantime, review your next project and feel free to get started on it or the courses supporting it!

Supporting Materials
 Videos Zip File
 Design-Mockup-Portfolio
You have not submitted the project yetSUBMIT PROJECT
