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

1. Marked up html to note what needed doing eg: https://github.com/AJoanBell/week1_challenge/blob/master/assets/images/images%20for%20READme%20doc/htmlmarkup.png

2. Researched accessability standards https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML

3. website title <website/> renamed for SEO to >Horiseon SEO< to capture company name and also the services they offer for when people are googling

4. <h1>Hori<span class="seo">seo</span>n</h1> Ideally I would say this needs heading written uninterrupted in full "Horiseon" for accessability and SEO. When I inspect element it has heading Horiseon. I left as it seemed the styling was important. One solution could be to use an image instead of writing their business name/logo and then have alt tag for image.

5. Added header tags into body around contents in header

6. Add nav tags for menu items in header

7. Optimised images for SEO. 
Research: https://www.searchenginejournal.com/on-page-seo/image-optimization/
https://www.searchenginejournal.com/on-page-seo/image-optimization/

8. Images should be no more than 20MB, best practice from my experience is keep them under 1MB, no more than 2MB. jpg ideal but some of these images had transparent backgrounds so needed to retain png format
renamed images to be more SEO friendly
added alt tags for SEO and accessability

compressed images using photoshop script and preview for png to under 2MB each and renamed to optimise SEO and put new image addresses in html
updated CSS .hero with new link to compressed image. Left in CSS and didn't write in html as not critical to SEO and accessability

9. Search Engine Optimization in header not linking to section on page. Added ID in html to resolve
Screenshot of ID added in html: https://github.com/AJoanBell/week1_challenge/blob/master/assets/images/images%20for%20READme%20doc/IDforheaderlink.png

10. CSS selectors and properties consolidated and organized to follow semantic structure.

11. Commented on CSS and changes made to CSS

12. Footer not in final png for reference that was provided but I have left it in as footer is best practice in website. Added dummy terms and conditions and privacy policy. Updated copyright to 2022.

13. Cleaned up html with formatting, indentation, moving tags to reduce lines and make it easier to locate elements and sections.

14. right column in body not formatting properly across all browsers and devices (the px where it ends) but must ignore for purposes of this exercise.

15. Link to final live deployment: https://ajoanbell.github.io/week1_challenge/ and link to screenshot/png here: https://raw.githubusercontent.com/AJoanBell/week1_challenge/master/assets/images/images%20for%20READme%20doc/Horiseon%20SEO.jpg
