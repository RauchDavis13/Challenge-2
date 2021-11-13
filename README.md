# Code Refactor Starter Code


## Bootcamp Challenge 2

The purpose of this excercise is to create a ground up webiste featuring a self portfolio of information Aoubt Me, examples of My Work and Contact information.

- Motivation: Utilize skills learned in CSS and HTML in building a website.  In this process, reinforce knowledge learned through practical application of CSS styling and positioning, as well as HTML construction.

- Project: Build a ground up website.  Make the theme a "self portfolio" of information About Me, examples of My Work and Contact information.  In each of these sections, make separate <div>'s to contain additional containers, and then is CSS, use Flex styling for use with various media.  Also, made a subsection in the category <div> along the left side to hold the link from the header and align to the sub <div> holding the About Me, My Work, etc.  In the header, I used CSS positioning to fine tune placement of the pic used for aesthetcs, as well as the pic used for the <div> just under the header.  

- Lessons Learned: Many...  Positioning certain elements were challenging.  For the header, I wanted to use an existing pic of my motorcycle, but align a slice of it to feature the Harley Davidson emblem and the kayaker.  For the <div> just underneath the header, also had to fine tune positioning to feature a slice of the pic used.  The main <div>'s, the <div> ".side" class and the <div>  

## Refactoring

- Replaced all <div> elements with semantic HTML

- Identified non operable link for Seach Engine Optimization (line 13) and fixed by adding the id "search-engine-optimization" under <main class="content" / figure class="content-pic">, line 32

- Changed <title> from "website" to "Horiseon", line 6

- Moved <header> into <head>

- Condensed separate classes for ".search-engine-optimization", ".online-reputation-managment" and ".social-media-marketing", down to one class called ".content-pic", which also flows to it's respective <img> and <h2> elements 

- Condensed separate classes for ".benefit-lead", ".benefit-brand" and ".benefit-cost" down to one class called ".benefit-sub", which also flows to it's respective <h3> and <img> elements in .css

- Added "alt" tags to all images under
  <main class="content">, line 31
  <section class="benefits">, line 56

- Reorganized css style classes for better top down flow 

- Comments added to both HTML and CSS

## Git

- Successfully cloned started code to local computer and created new 
Git repository (Challenge-2) to hold reworked code and README.md
https://github.com/RauchDavis13/Challenge-2.git

- Successfully created live Git based URL
https://rauchdavis13.github.io/Challenge-2a/

## Thank you's....
Dustin Erwin (TA)
Robert Evanik
Nicholas Perel
