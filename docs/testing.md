# **Windows Simplified - Testing**
 
![Image from amiresponsive](/assets/testing-images/amiresponsive.png)
Image from [Am I Responsive?](https://ui.dev/amiresponsive)
 
[Windows Simplified live on GitHub Pages](https://welshy92.github.io/windows-simplified/)
 
## **Contents**

* [Back to README](../README.md)
* [Automated Testing](#automated-testing)
    * W3C Validator (HTML)
    * W3C Validator (CSS)
    * Lighthouse Tool
* [Manual Testing](#manual-testing)
    * Testing User Story
    * Full Testing
* [Bugs](#bugs)
    * Solved Bugs
    * Known Bugs
 
Testing was a regular occurrence during the development of this project. My mentor [Jubril Akolade](https://www.linkedin.com/in/jubrillionaire/) provided some invaluable feedback during my sessions with him. Advised me on things such as content alignment, padding various areas of the site and adding a seperate nav bar styling for desktop size screens. Also showed me areas where the contrast seemed poor and general readability could be improved.
 
I used the OperaGX tools frequently to try and see problems and mess around with tags before actually changing the code. It was especially useful when implementing my 'Flex' displays or adjusting padding.
 
## **Automated Testing**
The HTML of every page was validated by [W3C Validator](https://validator.w3.org)
![index.html validation](/assets/testing-images/index-html-valid.png)
![maintenance.html validation](/assets/testing-images/maintenance-html-valid.png)
![shortcuts.html validation](/assets/testing-images/shortcuts-html-valid.png)
![links.html validation](/assets/testing-images/links-html-valid.png)
![404.html validation](/assets/testing-images/404-html-valid.png)
 
The CSS was also validated by [W3C Validator](https://jigsaw.w3.org/css-validator/)
![CSS validation](/assets/testing-images/css-validation.png)
 
Lighthouse tool powered by [PageSpeed Insights](https://web.dev/measure/) was used to test the performance, accessibility, best practices and SEO of the website.
![index](/assets/testing-images/index-lighthouse.png)
![keyboard shortcuts](/assets/testing-images/shortcuts-lighthouse.png)
![maintaining your system](/assets/testing-images/maintenance-lighthouse.png)
![useful sites and software](/assets/testing-images/links-lighthouse.png)
![404 error](/assets/testing-images/404-lighthouse.png)
 
High scores across the board with the exception of performance on some pages. This was caused mainly by the large banners for index.html and 404.html. The maintenance.html page scored low due to the embedded YouTube video on the page. A fix for this would likely only be achievable when I learn more about javascript.
***
## **Manual Testing**
 
A full spelling and grammar check of the content was complete by copying the code into Google Docs.
 
### **Testing User Story**
 
#### **First time visitors**
* I want to keep my machine performing well for a longer period of time -> Users can navigate to the 'System Maintenance' page to learn tips or even watch a video tutorial to help achieve this goal.
* I want to easily navigate the website to find the information I require -> A hamburger menu was developed and placed in the top right corner of the page that is always visible regardless of how far down the page a user is. The menu contains clear options for navigation.
* I want my time using a computer to be a bit smoother -> Users can navigate to the 'Keyboard Shortcuts' or 'Useful Sites & Software' pages which will provide them with some tips to allow them to work faster and more efficiently.
 
#### **Returning visitors**
* I want to quickly remind myself of a specific keyboard shortcut. -> Users can navigate to the 'Keyboard Shortcuts' page and goto the appropriate section to find the shortcut.
* I want to remind myself of the steps required to perform certain maintenance operations. -> Users can navigate to the 'System Maintenance' page and goto the appropriate section to find the steps required.
* I want to revisit one of the useful websites. -> Users can navigate to the 'Useful Sites & Software' page and find the link they were looking for. Icons for each website are shown to help a user spot the one they want quicker.
 
### **Full Testing**
 
Full testing was performed on the following devices:
 
* My self-built PC. Windows 10 64-bit Home edition. Tested on a 24" 1080 horizontal monitor and 27" vertical 4K monitor.
    * OperaGX
    * Google Chrome
    * Microsoft Edge
    * Mozilla Firefox
 
* My Lenovo Ideapad 3i 14" laptop. Windows 11 64-bit Home edition.
    * OperaGX
    * Google Chrome
 
* My Sony Xperia 1 II. Android 12.
    * Google Chrome
    * OperaGX
 
Navigation testing (all pages)
* Title goes back to home page when clicked - Passed
* Open hamburger menu - Passed
* Close hamburger menu - Passed
* All links lead to correct page - Passed
* Navbar sticks to the top of the page - Passed
 
Footer testing (all pages)
* Contact email correctly opens email application - Passed
* YouTube link leads to correct place + opens in seperate tab - Passed
* Back to top takes you back to top of the page - Passed
* Footer sticks to the bottom of the page - Passed
 
index.html specific testing
* Hero image and cover text scales and positions correctly with screen size - Passed
* All content padding the nav and footer scales with screen size - Passed
* Lightbulb icon is only visible on larger screen sizes - Passed
* Audio player plays correct audio and has controls - Passed
* Newsletter form requires a name and email to be submitted and verification of submission is shown - Passed
 
shortcuts.html specific testing
* All padding between nav and footer scales with screen size - Passed
* All images reduce in size on smaller screens - Passed
* The security menu image switches on smaller screen sizes for a more visible image - Passed
* All images captions are centred underneath their respective images - Passed
 
maintenance.html specific testing
* All padding between nav and footer scales with screen size - Passed
* All images reduce in size on smaller screens - Passed
* All images captions are centred underneath their respective images - Passed
* YouTube video does not autoplay and is completely functional regardless of screen size. It also resizes responsively - Passed
* No broken links - Passed
 
links.html specific testing
* All padding between nav and footer scales with screen size - Passed
* No broken links - Passed
* All links open in a new tab - Passed
 
404.html specific testing
* All padding between nav and footer scales with screen size - Passed
* Banner image reduces in size on smaller screens - Passed
* Clicking on the banner image takes you back to index.html - Passed
 
## **Bugs**
 
### **Solved Bugs**
 
* 405 - POST error occurred when submitting form. Caused by having multiple actions in the Form tag. Removed redundant tag and it is now working correctly.
* Large amount of whitespace below the form on the mobile view. Caused by the hidden lightbulb image. Changed the image size to 0 and added an upscale to the media query for it.
* Trying to commit a large video to the repository failed, and crashed my workspace. Video has been uploaded to youtube and is now embedded on the site.
* Incorrect active page showing on the nav bar for all pages except index.htm. Moved the active class to correct nav list items for each page.
* Some external links on the links.html page are not opening in a new tab. Added target="_blank" to the relevant anchor tags.
* No gap between the heading and paragraph text. Added line breaks
* Images clipping into the elements above them. Added a top margin to space it out a bit.
* All images with the picture class tag fail to load on github pages (404 error for each image). Works fine in preview. Fixed by changing all file paths to relative.
* Some links across the site incorrectly used an absolute file path which isn't allowed with Github. Changed to relative file path.
* Hero image on index.html not stretching to edges of the viewport. Caused by some body padding and margins. Both are now removed.
* Video embed on maintenance.html not resizing correctly. Placed it into its own div and given its own padding.
* Can't interact with YouTube player buttons at all on all screen sizes. Changed z-index from -1 to 1 and increased the z-index of header and footer to compensate for the overlap.
* Hamburger menu not working on maintenance.html. Class tag spelling corrected to fix it.
* h2 text too spread out on mobile views of maintenance.html and links.html. Caused by .content styling. move the text alignment to target specific elements of .content as opposed to the whole class.
* Form on index.html doesn't get the same level of padding as the rest of the content. Added specific padding to their class + elements.
* Captions not aligning correctly. Put captions in separate divs to rest of the content and moved the class definer to the respective divs.
* It was too easy to 'fat finger' the inputs on the newsletter form. Input heights increased to stop this from happening.
 
### **Known Bugs**