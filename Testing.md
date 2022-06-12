## Testing

### Automated testing

[Google chromes Lighthouse](https://developer.chrome.com/docs/lighthouse/) built-in developer tool was used for automated testing of the pages in both desktop and mobile views.

### Testing Summary:

- Performance
  - The worst metric was due to issues around The hero image size on the index.html page when viewed in mobile.
  - A lower score was given on the survival.html due to the larage amount of images
- Accessibility
  - The lowest score given was 100%
- Best Practices
  - The main issue with the best practice audit was due to my embedded youtube video on the Enlist.html page
- SEO
  - The lowest score given was 100%

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

### HTML Validation

[W3C Markup Validation Service](https://validator.w3.org/) Used on all pages of website, all passed

<details><summary>Home page</summary><img src="assets/readme-assets/validation/validator-index.png"></details>
<details><summary>Zombies page</summary><img src="assets/readme-assets/validation/validator-zombies.png"></details>
<details><summary>Survive page</summary><img src="assets/readme-assets/validation/validator-survival.png"></details>
<details><summary>Enlist page</summary><img src="assets/readme-assets/validation/validator-enlist.png"></details>

### CSS Validation

[jigsaw.w3 css-validator](https://jigsaw.w3.org/css-validator/) Used on all pages of website, all passed

<details><summary>Home page</summary><img src="assets/readme-assets/validation/w3c-css-validator-pass-index.png"></details>
<details><summary>Zombies page</summary><img src="assets/readme-assets/validation/w3c-css-validator-pass-zombies.png"></details>
<details><summary>Survive page</summary><img src="assets/readme-assets/validation/w3c-css-validator-pass-survival.png"></details>
<details><summary>Enlist page</summary><img src="assets/readme-assets/validation/w3c-css-validator-pass-enlist.png"></details>

## User Stories Testing

| As a client I want                                           |
| ------------------------------------------------------------ |
| Educate a wide range of visitors                             |
| Visitors to be engaged as soon as they enter the site        |
| An intuitive non-complex interface that's easy to navigate   |
| Visitors to be able to reach out and connect if they want to |

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

5. As a first-time visitor I want To be able to access and understand the site regardless of my disability><br>
   I met this by making the site to a high standard using good practices and accessibility guidelines, testing for accessibility during development

![Use of aria](assets/readme-assets/testing/aria-use.png)
![Assessment of best practices and accessibility](assets/readme-assets/testing/100-in-all.png)

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
