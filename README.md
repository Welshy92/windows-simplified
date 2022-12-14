# **Windows Simplified**
 
The Windows Simplified website is designed to be a responsive website allowing for viewing on various types of devices. It showcases some very simple tips that can help a user look after their computer and slightly increase their efficiency while doing some basic tasks.
 
![Image from amiresponsive](/assets/testing-images/amiresponsive.png)
Image from [Am I Responsive?](https://ui.dev/amiresponsive)
 
[Windows Simplified live on GitHub Pages](https://welshy92.github.io/windows-simplified/)
 
## **CONTENTS**

* [User Experience (UX)](#user-experience-ux)
* [Design](#design)
* [Technologies Used](#technologies-used)
* [Deployment & Local Development](#deployment)
* [Testing](#testing) - [External document here](/docs/testing.md)
* [Credits](#credits)
 
***
## **User Experience (UX)**
 
### Initial Discussion
 
Windows is an operating system that is used by around [1.4 billion users](https://www.techadvisor.com/article/745681/windows-now-has-1-4-billion-users-but-how-many-are-on-windows-11.html#:~:text=Back%20To%20School-,Windows%20now%20has%201.4%20billion%20users%2C%20but,many%20are%20on%20Windows%2011%3F&text=Windows%2010%20and%20Windows%2011,active%20devices%2C%20Microsoft%20has%20confirmed.) according to an article written by techadvisor, which is a huge majority of desktop/laptop users.
 
This number has been ever increasing since the initial outbreak of COVID. However a lot of users do not know how to do much more than web browsing or using the specific software associated with their jobs because it is not taught to them. This results in them potentially taking longer to do some basic tasks such as moving a block of text from one part of a document to another. The computers themselves will usually have a shorter lifespan as the users are not aware of how to keep it well maintained.
 
#### Key information for the site
 
* A list of keyboard shortcuts that will cut down time while performing some basic tasks.
* Useful tips to help maintain your system. These include;
    - Using Windows features such as Windows Updates (contains a video tutorial), Task manager and Startup tasks.
    - Backing up files using Physical media or cloud backup such as OneDrive
* A list of useful programs or websites that can add a user to make their life with a computer a bit easier.
 
### **User Stories**
 
#### Client Goals
 
* To be able to view the site on a variety of devices.
* To teach users shortcuts to help with work efficiency.
* To show users some basic computer maintenance that will increase the lifespan of their machines.
* To point users towards some software/website that will make their computing experience a bit smoother.
 
#### First Time Visitor Goals
 
* I want my time using a computer to be a bit smoother.
* I want to keep my machine performing well for a longer period of time.
* I want to easily navigate the site to find the information I require.
 
#### Returning Visitor Goals
 
* I want to quickly remind myself of a specific keyboard shortcut.
* I want to remind myself of the steps required to perform certain maintenance operations.
* I want to visit one of the useful websites.
 
***
## **Design**
 
### **Colour Scheme**
 
I have chosen a colour scheme that is close to the 'classic' Black and green contrast of old computer screens but less of a harsh contrast.
The colour palette was created using the [coolers](https://coolors.co) website. The main background was white.
 
![My original chosen colour scheme](/assets/images/colour-scheme.png)
 
However while in development, Lighthouse testing was showing that the way I was using the colours did not contrast well. So I adjusted the dark green to be a bit darker and the light green to be a bit brighter.
 
### **Typography**
 
[Google fonts](https://fonts.google.com) was used for the following fonts:
* Inter is used for the headings on the site. It is a sans-serif font.
* Noto Sans is used for the body text on the site. It is a sans-serif font.
 
### **Imagery**
 
* Logos used in the 'Useful Sites and Software' were taken from their respective websites. Credits can be found [here](#credits)
* Hero images for index.html and 404.html, as well as the site-wide favicon were taken from [Pixabay](https://pixabay.com). All images modified by myself. The [licence](https://pixabay.com/service/license/) does allow modifications.
 
 
### **Wireframes**
 
Wireframes created using Balsamiq. I originally created wireframes for both mobile and desktop versions but, after seeing how well the mobile layout transferred to desktops, I scraped them in favour of using a similar layout to the mobile frames.
 
#### Index Page Wireframes
![Index Page Wireframe](/assets/wireframes/index-mobile.png)
#### Keyboard Shortcuts Wireframes
![Keyboard Shortcuts Wireframe](/assets/wireframes/keyboard-shortcuts-mobile.png)
#### Maintaining Your System Wireframes
![Maintaining Your System Wireframe](/assets/wireframes/system-maintenance-mobile.png)
#### Useful Sites and Software Wireframes
![Useful Sites and Software Wireframe](/assets/wireframes/useful-sites-software-mobile.png)
#### 404 Error Wireframes
![404 error Mobile](/assets/wireframes/404-mobile.png)
 
### **Features**
 
The website is made up of 5 pages. The index page, Keyboard Shortcuts, Maintaining Your System, Useful Sites and Software and 404 Error pages. All pages, with the exception of the 404 error page, are accessible from a responsive navigation menu at the top right of the page. To the left of that is the site logo, which will be placed under the navigation menu on smaller screens with a media query. All pages will also contain a footer that displays copyright details, contact information, a link to the site's youtube channel and a 'back to top' link.
 
The index page is divided into sections. Below the Navigation is a large Hero image taking up the width of the screen. Below that is an introduction to what the site and its purpose is with an audio player at the top of it for a user to alternatively listen to the text of the page. Below that is a form that offers a signup to a newsletter.
 
The Keyboard Shortcuts page contains lists of shortcuts that are divided into different sections, word processing, system navigation and miscellaneous. Each shortcut will show an image of the keys with an explanation of what is achieved by using them, using a GIF to help showcase that if necessary.
 
The Maintaining your system page if split into a few categories. Windows updates, Task manager, Startup tasks and backing up files. Each section will be split up into sub-categories that will walk a user through, step by step, some basic maintenance tasks for their machine.
 
The Useful Sites and Software page contains a list of websites and software that could potentially aid a user in simplifying some tasks or allowing their system to run better, as well as some common popular pieces that have a variety of sources of information that they can use to help them further.
 
The 404 error page will pop up if there is a broken link clicked within the site. It will simply contain a 404 error message and a link back to the homepage.
 
### **Future Implementations**
 
The main thing to consider adding would be audio for all pages, not just the index page. As well as completing the implementation of the newsletter so that it actually works. (It uses a placeholder dump at the moment.)
 
### **Accessibility**
 
While coding this site I have been mindful to ensure that the website is accessible and friendly. I have achieved this by:
  * Using semantic HTML
  * Using descriptive alt attributes on images all around the site.
  * Making sure that there is sufficient colour contrast throughout the entire site.
***
## **Technologies Used**
 
### **Languages used**
HTML, CSS
 
### **Frameworks, Libraries & Programs Used**
 
* [Balsamiq](https://balsamiq.com) - Used to create wireframes.
* [Git](https://git-scm.com) - For version control.
* [Github](https://github.com) - To save and store all the files of the site.
* [Gitpod](https://www.gitpod.io) - To write all the HTML & CSS. Also used to write the README.
* [coolers](https://coolors.co) - To create a colour scheme for use across the site.
* [Google Fonts](https://fonts.google.com) - To import the fonts used on the site.
* [Font Awesome](https://fontawesome.com) - For the iconography of the site.
* [OperaGX](https://www.opera.com/gx) - Dev Tools to troubleshoot and test features, solve issues with responsiveness and styling.
* [Am I Responsive?](https://ui.dev/amiresponsive) - To show the website image on a variety of devices.
* [Lighthouse](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=en) - Chrome DevTool extension that I use on my OperaGX browser.
* [Audacity](https://www.audacityteam.org) - A voice recording software. Used for the index.html audio clip.
* [Open Broadcasting Software (OBS)](https://obsproject.com) - A video recording/streaming software. Used to create the video tutorial.
***
## **Deployment & Local Development**
 
### **Deployment**
The site is deployed using GitHub Pages. Visit the deployed site [here.](https://welshy92.github.io/windows-simplified/)
 
To do this I:
1. Logged into my Github.
2. Went to the repository for this project, [windows-simplified](https://github.com/Welshy92/windows-simplified).
3. Clicked on the Settings tab.
4. Clicked on Pages under the Code and Automation section.
5. Set the branch to main and clicked save.
6. Waited a few minutes and then refreshed the page for my deployed site link.
 
### **Local Development**
 
#### How to Fork the repository
 
1. Log in (or sign up) to Github.
2. Go to the repository for this project, [windows-simplified](https://github.com/Welshy92/windows-simplified).
3. Click the Fork button in the top right corner.
 
#### How to Clone the repository
 
1. Log in (or sign up) to GitHub.
2. Go to the repository for this project, [windows-simplified](https://github.com/Welshy92/windows-simplified).
3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.
***
## **Testing**
Click [here](/docs/testing.md) to view details on testing and bugs
***
## **Credits**
***
This website is a solo project created by [myself.](https://github.com/Welshy92)
 
### **Learning Resources**
 
There are a few different sites that I used to learn the required skills to develop this website. I also refer back to these when I'm unsure of certain tags.
* [Code Institute](http://codeinstitute.net) - Full Stack Developer course material used to learn essentials of HTML and CSS.
* [CSS-Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Used to learn about flexbox and how to apply it to my own development.
* [W3Schools](https://www.w3schools.com) - Used to quickly look up various tags to verify I am applying them correctly.
* [Traversy Media YouTube](https://www.youtube.com/watch?v=DZg6UfS5zYg&ab_channel=TraversyMedia) - Watched their 'Pure CSS Hamburger Menu & Overlay' video to learn how to make a hamburger menu.
* [Stack Overflow](https://stackoverflow.com) - Used to check how to change an img src based on screen size in CSS.
[Markdown Guide](https://www.markdownguide.org/basic-syntax/) - Used to help with learning markdown syntax.
### **Content**
* [Font Awesome](https://fontawesome.com) - Icons used for footer icons + hamburger navigation icon.
* [Code Institute](https://codeinstitute.net) - Form dump link used to show working form on index.

### **Code Used**
* Hamburger menu icon animation CSS taken from a [Traversy Media YouTube video](https://www.youtube.com/watch?v=DZg6UfS5zYg&ab_channel=TraversyMedia). Noted within the actual CSS itself.
 
### **Media**
* Hero image by [Sathesh D](https://www.pexels.com/@sathez994/) on Pexels image site, used on index.
* Favicon image modified by myself. Original image by raphaelsilva on [Pixabay](https://pixabay.com/users/raphaelsilva-4702998/)
* 404 image modified by myself. Original image by turgut_arslan0 on [Pixabay](https://pixabay.com/users/turgut_arslan0-660197/)
* Icons for links.html were taken from the respective companies websites favicons.
  * [Opera GX](https://www.opera.com/gx) - by Opera Limited
  * [WinRar](https://www.win-rar.com/) - by Eugene Roshal
  * [Team Viewer](https://www.teamviewer.com) - by  TeamViewer AG
  * [Advanced System Care](https://www.iobit.com/en/advancedsystemcarefree.php) - by IOBit. *Icon taken from software installation directory*
  * [OneDrive](https://onedrive.live.com/) - by Microsoft
  * [Dropbox](https://www.dropbox.com) - by Dropbox
  * [Gmail](https://mail.google.com) - By Google
* Windows Update tutorial created by myself and uploaded to a brand new [YouTube channel](https://www.youtube.com/channel/UCbXMDllJ-kBipa4N4l31GFg) to match the brand of the website. Made using [Open Broadcasting Software(OBS)](https://obsproject.com).
* Audio able to be played on the index page recorded by myself using [Audacity](https://www.audacityteam.org).
 
### **Acknowledgments**
 
[Kera Cudmore](https://github.com/kera-cudmore) - Provided a [README](https://github.com/kera-cudmore/readme-examples) example that I read through to make sure I had all required content.
 
[Microsoft Support Site](https://support.microsoft.com) - Used to verify that keyboard shortcuts are used on multiple Windows operating systems.
 
[Webfx](https://www.webfx.com/web-design/hex-to-rgb/) - Used to convert a hex colour to RGB for use on my hero image cover text box.
 
[Dave Horrocks](https://www.linkedin.com/in/davejhorrocks/) - Some fantastic tips on specificity and accessibility.
 
[Simen Daehlin](https://www.linkedin.com/in/simendaehlin/) - Explaining the difference between relative and absolute file paths and why we can't always use both.
 
[Ed Bradley](https://www.linkedin.com/in/ed-bradley-4b841686/) - My Code Institute August 2022 cohort tutor. Provided the invaluable tip of telling me to read up on flexbox and avoid using float.

[Jubril Akolade](https://www.linkedin.com/in/jubrillionaire/) - My Code Institute course mentor that provided invaluable tips and feedback about many things.