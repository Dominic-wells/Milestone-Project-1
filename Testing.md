# Testing

## Contents

- [Automated Testing](#automated-testing)
- [Testing Summary](#testing-summary)
  - [Lighthouse Images](#lighthouse-in-devtools) -[Home page](#home-page) -[Zombie page](#zombie-page) -[Survival page](#survival-page) -[Enlist page](#enlist-page)
- [HTML Validation](#html-validation)
- [CSS Validation](#css-validation)
- [Manual Testing](#manual-testing)
- [User Stories Testing](#user-stories-testing)
- [Client stories](#client-stories)
- [First Time Visitor](#first-time-visitor)
- [Returning Visitor](#returning-visitor)
- [frequent Time Visitor](#frequent-visitor-goals)
- [Bugs](#bugs)

---

## Testing

### Automated testing

[Google chromes Lighthouse](https://developer.chrome.com/docs/lighthouse/) built-in developer tool was used for automated testing of the pages in both desktop and mobile views.

### Testing Summary

- Performance
  - The worst metric was due to issues around The hero image size on the index.html page when viewed in mobile.
  - A lower score was given on the survival.html due to the larage amount of images
- Accessibility
  - The lowest score given was 100%
- Best Practices
  - The main issue with the best practice audit was due to my embedded youtube video on the Enlist.html page
- SEO
  - The lowest score given was 100%

[Back to top](#Contents)

---

## Lighthouse images

### Home page

![Lighthouse Homepage Mobile](assets/readme-assets/lighthouse/lighthouse-index.png)

<details><summary>Lighthouse Homepage Dekstop</summary><img src="assets/readme-assets/lighthouse/lighthouse-index-desktop.png"></details><br>

### Zombie page

![Lighthouse Zombie page Mobile](assets/readme-assets/lighthouse/lighthouse-zombie.png)

<details><summary>Lighthouse Zombie page Dekstop</summary><img src="assets/readme-assets/lighthouse/lighthouse-zombie-desktop.png"></details><br>

### Survival page

![Lighthouse Survival page Mobile](assets/readme-assets/lighthouse/lighthouse-survival.png)

<details><summary>Lighthouse Survival page Dekstop</summary><img src="assets/readme-assets/lighthouse/lighthouse-survival-desktop.png"></details><br>

### Enlist page

![Lighthouse Enlist page Mobile](assets/readme-assets/lighthouse/lighthouse-enlist.png)

<details><summary>Lighthouse Enlist page Dekstop</summary><img src="assets/readme-assets/lighthouse/lighthouse-enlist-desktop.png"></details><br>

[Back to top](#Contents)

---

### HTML Validation

[W3C Markup Validation Service](https://validator.w3.org/) Used on all pages of website, all passed

<details><summary>Home page</summary><img src="assets/readme-assets/validation/validator-index.png"></details>
<details><summary>Zombies page</summary><img src="assets/readme-assets/validation/validator-zombies.png"></details>
<details><summary>Survive page</summary><img src="assets/readme-assets/validation/validator-survival.png"></details>
<details><summary>Enlist page</summary><img src="assets/readme-assets/validation/validator-enlist.png"></details>

[Back to top](#Contents)

### CSS Validation

[jigsaw.w3 css-validator](https://jigsaw.w3.org/css-validator/) Used on all pages of website, all passed

<details><summary>Home page</summary><img src="assets/readme-assets/validation/w3c-css-validator-pass-index.png"></details>
<details><summary>Zombies page</summary><img src="assets/readme-assets/validation/w3c-css-validator-pass-zombies.png"></details>
<details><summary>Survive page</summary><img src="assets/readme-assets/validation/w3c-css-validator-pass-survival.png"></details>
<details><summary>Enlist page</summary><img src="assets/readme-assets/validation/w3c-css-validator-pass-enlist.png"></details>

[Back to top](#Contents)

---

## Manual Testing

The website was viewed with browsers: Google Chrome, Microsoft Edge and Firefox and viewed on Pixle 6/find x 2 Neo phone. All four pages were viewed and the following was checked:
-The Nav bar worked with no issues on any links<br>
-The Nav bar resizes correctly<br>
-The modal form opens and closes<br>
-The modal form resized correctly<br>
-The "required" code works on the modal form requiring the visitor to enter the correct information<br>
-The Footer worked with no issues on any links<br>
-The Footer resizes correctly<br>
-Social medial links worked<br>
-Email me link works<br>
-All "Hover" effcts worked on desktops.

On the Home page I cheaked in particular:<br>
-The text section and image section both resized correctly and displayed in the order I wanted (text on top image on bottom)

On the Zombie page I checked in particular:<br>
-The cards resized correctly on various screen sizes

On the survive page I checked in particular:<br>
-The text section and image section both resized correctly and displayed in the order I wanted (image on top and text on bottom)<br>
-The amazon link worked on the water section <br>
-The "details" worked and displayed the text correctly<br>
-The list in the weapon section would transform from Two rows to one column on smaller screens<br>
-The Carousel displayed correctly when resized and was able to change the image by the directional arrows within the image on hover or click on phones/tablets.<br>
-The tools video displayed correctly when resized and was able to be played on click of video and paused on click on video<br>

On the Enlist page I checked in particular:<br>
-The striped table displayed correctly when resized to smaller screens<br>
-The youtube video displayed correctly when reiszed to a smaller screen<br>
-The youtube video repsoned to vistor inputs such as play, pause and fullscreen.<br>

I had my friends test the site on their computers and phones they reported no bugs just isuss with grammer and spelling
![Fix one](assets/readme-assets/testing/grammer-fix1.png)
![Fix two](assets/readme-assets/testing/grammer-fix2.png)

[Back to top](#Contents)

---

## User Stories Testing

## Client stories

1. As a client I want, to educate a wide range of visitors.<br>
   I met this in the first time visitor section

2. As a client I want, visitors to be engaged as soon as they enter the site.<br>
   I met this by making a call to action buttion with a question one of the first items they see when visting the site

![Call to action](assets/readme-assets/testing/call-to-action.png)

3. As a client I want, An intuitive non-complex interface that's easy to navigate.<br>
   I met this in the first time visitor section.

4. As a client I want, Visitors to be able to reach out and connect if they want to.<br>
   I met this in the frequent visitor section.

[Back to top](#Contents)

---

## First Time Visitor

1. As a first-time visitor, I want to understand the main use of the site within the first 10 seconds.<br>
   I met this by naming the site and adding a logo with an identifying clear name" zombie Survival UK" furthermore I added an introduction to the first page the user would visit.

![Logo](assets/readme-assets/testing/logo-testing1.png)
![Introduction](assets/readme-assets/testing/website-intro1.png)

2. As a first-time visitor I want an intuitive non-complex interface that's easy to navigate to the conntent I want to see.<br>
   I met this by building a site with standard format and a well known website layout (Navbar, Main, Footer) I also avoided distracting effects and colours.

![Navbar-desktop](assets/readme-assets/testing/navbar-desktop.png)
![Navbar-mobile](assets/readme-assets/testing/navbar-mobile.png)
![Footer](assets/readme-assets/testing/footer.png)

3. As a first-time visitor I want to be able to view the site at my convenience at any location on my available device .<br>
   I met this by making the website viewable across a wide range of devices, web browser and operating systems.

   <details><summary>viwed on different screen sizes</summary><img src="assets/readme-assets/testing/muti-screen1.png"></details>
   <details><summary>viwed on Chrome web browser</summary><img src="assets/readme-assets/testing/chrome-screenshot.png"></details>
   <details><summary>viwed on Firefox web browser</summary><img src="assets/readme-assets/testing/firefox-screenshot.png"></details>

4. As a first-time visitor I want to learn about zombies and survival in the UK.<br>
   I meet this by displaying a wide range of information on survival and general zombie knowledge.

   <details><summary>Zombie information</summary><img src="assets/readme-assets/testing/zombie-info1.png"></details>
   <details><summary>Zombie information</summary><img src="assets/readme-assets/testing/zombie-info2.png"></details>
   <details><summary>Survival information</summary><img src="assets/readme-assets/testing/survival-info1.png"></details>
   <details><summary>Survival information</summary><img src="assets/readme-assets/testing/survival-info2.png"></details>

5. As a first-time visitor I want To be able to access and understand the site regardless of my disability.><br>
   I met this by making the site to a high standard using good practices and accessibility guidelines, testing for accessibility during development

![Use of aria](assets/readme-assets/testing/aria-use.png)
![Assessment of best practices and accessibility](assets/readme-assets/testing/100-in-all.png)

[Back to top](#Contents)

---

## Returning Visitor

1. As a returning visitor, I want to conveniently access social media links so that I can follow on my chosen platforms after visiting the site.<br>
   I met this by building social media links with icons that open a new tab when clicked conveniently located in the footer of every page (not Thankyou.html)

![Image of links](assets/readme-assets/testing/social-media-links.png)
![Code used](assets/readme-assets/testing/social-media-link-code.png)

2. As a returning visitor, I want to have fast access to the information and not get distracted by advertisements.<br>
   I met this by making use of tools such as lighthouse to optimize the website to improve loading times, I will not load advertisements

   ![Site performace](assets/readme-assets/testing/site-performance.png)
   <details><summary>Audits Passed 1</summary><img src="assets/readme-assets/testing/audits-passed1.png"></details>
   <details><summary>Audits Passed 2</summary><img src="assets/readme-assets/testing/audits-passed2.png"></details>

3. As a returning visitor, I want to be able to find the information I want conveniently, not having to read the whole site.<br>
   I met this by making multiple pages with a different subjects. I also included header titles of different topics within the different pages.

   ![Image of links](assets/readme-assets/testing/pages.png)
   ![Image of links](assets/readme-assets/testing/page-files.png)
   ![Image of links](assets/readme-assets/testing/web-title-water.png)
   ![Image of links](assets/readme-assets/testing/h1-title.png)

4. As a returning visitor, I want To be able to receive updates about zombie survival.<br>
   I met this by adding a form for the user to be able to interact with the site by adding their contact informatio,the information is not processed as it is beyond scope of this project, once the visitor as entered information they will be directed to a "thank you page").<br>

![Form](assets/readme-assets/testing/modal-form-desktop.png)
![Thank you page text](assets/readme-assets/testing/thank-you-page.png)

<details><summary>Form page text</summary><img src="assets/readme-assets/testing/modal-form-code.png"></details>

[Back to top](#Contents)

---

## Frequent Visitor Goals

1. As a frequent visitor, I want to be able to contact the site owner to ask questions and build a connection.<br>
   I met this by adding an email link in the footer that opens open for the visitor to be able to email me directly

   ![Email link](assets/readme-assets/testing/email-link.png)
   ![email link code](assets/readme-assets/testing/email-link-code.png)

[Back to top](#Contents)

---

### Bugs

When developing the website I found issues and bugs.
| Bug | Solution |
| ------------- |:-------------:|
| I found issues where the logo image and icon links would extend under the navbar when viewed on smaller screens | After researching on StackOverflow and documentation on the bootstrap website I found I made the nav bar too small and needed to increase the height due to my logo being larger than standard text. |
| I found an issue where the logo and nav links were too close even after increasing the navbar size after fixing the previous issue, I however didn't want to increase the height of the current navbar as I had my desired hight already | I resolved this by making a media query where I would increase the navbar height when the website was viewed on smaller screens allowing me to add some padding and centre links and logo |
| I found an issue with my hero image on my index.html page would not fill the width of the screen, even when I set the padding to o on both sides. It would only work on desktops (larger screens) | I then realised I was using the wrong container and did not need to contain it all within another div, as it added padding |
| When positioning the "call to action hero box" I wanted the box to not it in the way of the zombie's face during desktop viewing | I increased the padding but found when viewing on small screens such as the Galaxy Fold that the box would be far too low and I didn't like the look, I made a media query to lower some of the padding on smaller screens |
| I had an issue with a section under my hero section that on viewing with smaller screens it would prioritize the photo first above the text. | After researching I found that I could reorder using the order classes(.order-) making the image an order-last and the text order-first |
| I had an issue when embedding a youtube video it was not responsive | After researching on google I found some useful information at(https://jasonmkelly.com/jason-m-kelly/2020/3/17/making-your-youtube-videos-responsive). Code and CSS from the above site were used to make the video responsive; I however found the video too large. I resolved this by placing the responsive video into my own made container allowing me to place and size at my own discretion whilst still keeping the resized video properties |
| I found an issue with images not loading in GitHub pages | I had used the wrong file path, the one I used would work on my local live page but with Github pages |
| Github would not load videos from my files | I had to use the full address they stored it at( https://github.com/Dominic-wells/Milestone-Project-1/raw/main/assets/images/Axe.mp4 ) |
| When making the footer I wanted to add a link for the users to be able to email me directly but the link wouldn't open correctly | I needed to add <b>mailto</b> in my herf tag(guidance how to do this at (https://www.w3schools.com/tags/tag_address.asp)) |
| The Site would not load as fast as I wanted it to| I Improved performance by changing file types and sizes from jpgs to webp|
| The Progress bars on the card sections were not alining right correctly| I placed them in the wrong div|

## [Back to top](#Contents)

---
