# Code Refactor Starter Code


## Bootcamp Challenge 1

The purpose of this excercise is to "refactor" existing code, completing the tasks as oulined in the "acceptance criteria", create a properly structured README.md file and deploy a live URL to meet the grading requirements

- Motivation: Test what has been learned through practical application and testing of code refactoring, GitHub repository and committing files

- Project: Take the lessons learned from HTML and CSS to review and refractor existing code.  Implement best practices for scout rule, coding, GitHub repository building, README.md construction.

- Problem Solved: Code has been made more efficient, links tested and fixed, semantic HTML now used for cleaner reading of the code, flow of code has been changed to follow logical sequence of events

- Lessons Learned: How to identify opportunties for streamlining code from skills learned to date in HTML and CSS, use of semantic HTML, following sequential order of code flow, GitHub cloning from one repository then "pushing" to different repository, identify non working links, look for missing code (ex; missing "alt" tabs from <img? element>)


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
Git repository (Challenge1A) to hold reworked code and README.md
https://github.com/RauchDavis13/Challenge1A.git

- Successfully created live Git based URL
https://rauchdavis13.github.io/Challenge1A/


## Thank you's....
Dustin Erwin (TA)
Robert Evanik
Nicholas Perel