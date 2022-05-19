## User story - client request/goal of project

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

## Acceptance Criteria to tick off

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
Research for how to optimise html for SEO

https://www.greengeeks.com/blog/html-tags-for-seo/

## Actions taken

1. Marked up html to note what needed doing https://github.com/AJoanBell/week1_challenge/blob/master/assets/images/images%20for%20READme%20doc/htmlmarkup.png

2. Researched accessability standards https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML

3. website title <website/> renamed for SEO to >Horiseon SEO< to capture company name and also the services they offer for when people are googling

4. <h1>Hori<span class="seo">seo</span>n</h1> This needs heading for accessability 

4. Optimised images for SEO. 
Research: https://www.searchenginejournal.com/on-page-seo/image-optimization/
https://www.searchenginejournal.com/on-page-seo/image-optimization/

Images should be no more than 20MB, best practice from my experience is keep them under 1MB, no more than 2MB. jpg ideal but some of these images had transparent backgrounds so needed to retain png format
renamed images to be more SEO friendly
added alt tags for SEO and accessability

compressed images using photoshop script and preview for png to under 2MB each and renamed to optimise SEO and put new image addresses in html
updated CSS .hero with new link to compressed image. Left in CSS and didn't write in html as not critical to SEO and accessability

5. Search Engine Optimization in header not linking to section on page. Added ID in html to resolve
Screenshot of ID added in html: https://github.com/AJoanBell/week1_challenge/blob/master/assets/images/images%20for%20READme%20doc/IDforheaderlink.png

6. Added link to Horiseon in header so that it refreshes the page

10. updated copyright to 2022

11. Link to final live deployment: https://ajoanbell.github.io/week1_challenge/
