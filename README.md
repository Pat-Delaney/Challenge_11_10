# Challenge_11_10

# Introduction

This program is a refinement of the example file provided as part of the week 1 challenge of the UW coding bootcamp, whose objective is to ensure accessibility standards.

# Requirements

This program requires the provided assets folder, including the images and css folder and contents.

# Design Choices

As a part of the refinement process, the header and footer classes were worked out of the design, instead using header and footer elements, similarly, the three content classes, eg. "social-media-marketing", "online-reputation-management" and "search-engine-optimization" were forgone for the more general "main-content" while keeping respective ids for the sake of possible future specific changes, also changing the div "content" to "main-box" to differentiate the classes while making sure the classes are similar. Similary, the seperate classes for the content on the right side was swapped out for the more general "general-item" tag, so as to clean up redundancy. On the suggestion of David MacDonald's article on alt-text for background images (http://www.davidmacd.com/blog/alternate-text-for-css-background-images.html) the div used for the "hero" class image was switched to an empty span, so as to add an "aria-label" that a screen reader may read. On the subject of accessibility, alt text was added to each image on the page, and the title was changed to reflect the content of the page as "Horiseon - About", as well as adding Keywords and a description for search engines.