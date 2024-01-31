# La Patata

![Mockup image of the site](readme-files/mockup-image.png)

La Patata is a fictional food truck business selling Spanish tortillas in different food markets in London, UK.

The purpose of this website is to promote the business to London residents as well as people visiting London. The website provides information about the menu, ingredients used, as well as the locations and opening times of the food truck. It also provides a function to pre-order tortillas for collection. This is aimed at local people who would like to order several tortillas, for example, for private family events.

The deployed site can be found here: [La Patata website](https://jonnlai.github.io/la-patata/)

## Table of Contents

## User Experience (UX)

### Business Goals

* This is a Business to Consumer (B2C) website that aims to increase the number of people who visit the food truck.
* The website provides information about the menu and ingredients used to convince potential customers of the quality of the product.
* The website conveys the feeling of a relaxed and fun urban eating experience.
* The website offers the option of pre-ordering tortillas to encourage customers to order larger amounts.

### User Stories

* As a visitor to London, I want to be able to find information about the locations and opening times easily using my mobile phone so that I can find the business while on the move.
* As a local food-lover, I want to be able to find information about the product and the ingredients used so that I can understand more about the quality of the product.
* As a regular customer, I want to be able to buy several tortillas so that I can serve them at my family event.

### Colour Palette

![Color Palette](readme-files/lapatata-color-palette.png)

The colour palette was created from the Hero image using [Coolors](https://coolors.co/) colour palette generator. The shades of brown, yellow, and green reflect the colours of a tortilla and its ingredients. The generator suggested using #020000, but this was replaced with #000 during the development process, and the palette was updated to reflect this.

The colours of the palette were used throughout the site, except for the font of the menu. White was used as the font colour to give the impression that the menu had been hand-written on a chalkboard using a piece of chalk.

### Typography

The main font used is Sanchez, with serif as the fallback font. Dekko was used for the main headings (h1 and h2), with cursive as the fallback. Shantell Sans, with cursive as the fallback, was used for the menu to give it a hand-written feel.

### Wireframes

[Balsamiq](https://balsamiq.com/) User Interface wireframing tool was used to design the structure of the website.

|  Page    |                         Mobile                                  |                         Desktop                                   |
|  ---     |                         ---                                     |                         ---                                       |
|  Index   |![Mobile Index wireframe](wireframes/mobile-index.png)    |![Desktop Index wireframe](wireframes/desktop-index.png)    |
|  Find Us |![Mobile Find Us wireframe](wireframes/mobile-find-us.png)|![Desktop Find Us wireframe](wireframes/desktop-find-us.png)|
|  Order   |![Mobile Order wireframe](wireframes/mobile-order.png)    |![Desktop Order wireframe](wireframes/desktop-order.png)    |

## Features

### General

* The site was developed using a "mobile first" development approach to ensure good User Experience for those using mobile phones and other smaller devices.
* The site is fully responsive across all device sizes.
* Consistant style, including colours and fonts, were used across all the pages.

#### Favicon

* The Favicon is a simple black letter P on a light brown background, and it uses the same font as the main heading "La Patata". The background colour is the same colour that is being used across the site for the headers and footers. The letter P stands for patata, potato in Spanish, which is the name of the business and the main ingredient of the product.

![Favicon image](readme-files/favicon.png)

#### Header

* The header contains an illustration of a food truck to clearly communicate to the customers the type of food business.
* The header clearly shows the name of the business, "La Patata", which means potato in Spanish, making reference to one of the main ingredients of Spanish tortilla, potato.
* The navigation bar for mobile phones and tables is a dropdown menu that can be toggled open/close to save space on smaller screens. The idea for the menu was taken for Code Acedemy's Love Running Project. When the menu is open, it has a transparent background and is displayed slightly on top of the hero image on the index.html page.  
![Header for mobiles and tablets](readme-files/header-mobile.png)
* When using a larger device than a tablet the navigation menu is displayed horizontally. The background of the navigation menu remains slightly transparent and the menu is displayed over the hero image.  
![Header for larger devices](readme-files/header-laptop.png)

#### Footer

* The footer has Facebook and Instagram icons that contain links to the social media sites as well as a mail icon that users can click to send an email to the company. The footer also contains the Copyright information. When using a mobile phone the social media icons are located on the left-side, and when using a tablet or a larger device, the icons are in the centre.  
![Footer for mobiles](readme-files/footer-mobile.png)
![Footer for tablets and larger devices](readme-files/footer-laptop.png)

### Landing Page

* The landing page contains all the key information and eye-catching images to encourage potential customers to try the product.
* The page was designed to convey the feeling of a high-quality product being sold by a small, friendly, urban business.

#### Hero Image

* The Hero image shows a Spanish tortilla and some of its raw ingredients placed on a wooden board. The image conveys authenticity, quality and freshness of the product and gives a friendly, homely feel to the customer. The image gives the customer an insight into the business's traditional approach to making tortilla.
* The Hero image is fully responsive, and the size of the image adjusts according to the screen size always ensuring that the product (tortilla) catches the customer's attention.  
![Hero image of tortilla](readme-files/hero-image.png)

#### Tortilla Menu

* The tortilla menu lists all the different types of tortillas available and their prices. The menu lists all the ingredients so that customers with dietary requirements are able to make an informed decision about whether the product is suitable for them.
* The tortilla menu has been designed to represent a menu hand-written on a chalkboard that are commonly used in food markets. The font style was selected because it is clear but gives the impression that it has been hand-written and font colour is white to represent chalk.  
![Menu image](readme-files/tortilla-menu.png)

#### About Us

* The About Us section gives customers information about the business owners and demonstrates their passion for Spanish food and making high-quality products.
* The section has a link to the "Find Us" page as a call to action to visit one of the food markets where the food truck operates.  
![About Us page image](readme-files/about-us.png)

#### Tortilla images

* An image of a tortilla slice is displayed when mobile phones and tablets are being used. This image gives the customer an idea of the portion they would be purchasing.
* When a laptop is being used, three images are displayed: an image of a tortilla slice, an image of the ingredients, and an image of a full tortilla cut into six slices.
* On larger desktop screens, only the tortilla slice image is being displayed again to make the layout of the page more visually appealing and avoid the images from looking too spread out on the larger screens.  
![Tortilla slice image](readme-files/tortilla-slice.png) ![Tortilla images for laptops](readme-files/tortilla-images-laptop.png)

#### How to Enjoy Section

* The How to Enjoy Section gives light-hearted suggestions on how and when to eat tortillas. The section encourages customers to engage with the business and try the product.
* The section includes two calls to action to encourage customers' to try the product: a link to the Find Us page and a link to the Order page.  
![How to Enjoy section image](readme-files/how-to-enjoy.png)

### Find Us page

* The Find Us page lets the customers know when and where they can visit the business and how to contact the business via email or phone.

#### Where to Find Us section

* This section shows the names and addresses of two locations where the food truck stops and gives the opening times.
* Both locations are also shown on a Google map using an iframe to allow customers to find the business easily. This function serves especially customers who are on the move and using a mobile phone to look for a place to eat now.  
![Locations image](readme-files/where-to-find.png)

#### Contact us section

* This section shows a photo of the fictional food truck to help customers to locate the business when visiting a food market.
* The business's mobile phone number and email address are displayed to allow customers to contact the business easily.  
![Contact us image](readme-files/contact-details.png)

### Order page

* This page allows regular customers to place a larger order.

#### Order information

* This section explains how to pre-order tortillas and reminds customers of the days and locations when they can collect their order.
* The terms and conditions have been placed inside a disclosure widget to improve user experience by saving space on customers' screens when they are not reading the terms and conditions.  
![Order information](readme-files/pre-order-info.png) ![TAC open](readme-files/tac-widget-open.png)

#### Order form

* The form allows customers to pre-order a larger number of tortillas for collection easily.
* The form uses built-in client-side form validation to ensure that all the required data is submitted in correct format to prevent issues and delays with orders.  
![Order form](readme-files/order-form.png)

## Technologies Used

### Languages Used

* [HTML5](https://html.com/html5/)
* [CSS3](https://www.w3.org/Style/CSS/)

### Frameworks, Libraries and Programmes Used

* [Balsamiq](https://balsamiq.com/) was used for designing the project and creating wireframes to communicate the vision.
* [Codeanywhere](https://codeanywhere.com/) was used for writing, committing, and pushing code to GitHub.
* [GitHub](https://github.com/) was used for storing the project.
* [Google Fonts](https://fonts.google.com/) was used to import the selected fonts.
* [Font Awesome](https://fontawesome.com/) was used to add icons to the site to give the user a visual representation of some of the information presented.
* [Chrome DevTools](https://developer.chrome.com/docs/devtools) were used regularly throughout the development of the project to test and troubleshoot.
* [Pixelied](https://pixelied.com/convert/) was used to convert the images to webp format.
* [TinyPNG](https://tinypng.com/) was used to optimise the images by reducing their size.
* [Favicon.io](https://favicon.io/) was used to create the Favicon.
* [Responsive Design Checker](https://www.responsivedesignchecker.com/) was used to check the site's responsiveness on different devices.
* [Am I responsive?](https://ui.dev/amiresponsive) was used to create the mockup image of the landing page on different devices.

## Testing

### User Stories Testing

1. As a visitor to London, I want to be able to find information about the locations and opening times easily using my mobile phone so that I can find the business while on the move.
   * The site was developed using a mobile-first approach, and testing shows that the site works effectively on mobiles.
   * The maps are easy to open and enlarge using a mobile phone.
2. As a local food-lover, I want to be able to find information about the product and the ingredients used so that I can understand more about the quality of the product.
   * The menu displays the different options clearly and lists all the ingredients used. The menu also displays the prices.
   * The About section explains more about the ingredients and the approach that the business owners are taking to creating their product.
3. As a regular customer, I want to be able to buy several tortillas so that I can serve them at my family event.
   * The Order form allows an order to be placed online using a UK mobile phone number and an email address. An order can also be placed via email if the customer does not want to or cannot place an order using the form.

### Code Validation

* The [W3C Markup Validator](https://validator.w3.org/) and [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) were used to validate all the pages to ensure that the project meets the current Web Standards and is free from any unintended syntax errors and mistakes that could cause issues with accessibilty and usability.

* The pages were validated once half-way through the development. In index.html, W3C Markup Validator found two issues: the *hero image* section and the *tortilla images* section did not contain a heading. This was rectified by replacing these section tags with div tags. No issues were found on the other pages or with the CSS code. The Validator highlighted several times that the trailing slash on void elements had no effect. However, these were not removed as they had been added by Prettier when the code had been formatted.

  * Warning messages: ![Code Validator Warnings 17.01.24](readme-files/code-validator-warnings-1701.png)
  * Info messages after the highlighted issue was resolved: ![Code Validator Info messages 17.01.2024](readme-files/info-messages-1701.png)

* The pages were validated again after all development had finished. No issues were identified.
  
  * Landing page: ![Code validator Index page 29.01.24](readme-files/code-validator-index-2901.png)
  * Find Us page: ![Code validator Find Us page 29.01.24](readme-files/code-validator-find-us-2901.png)
  * Order page: ![Code validator Order page 29.01.24](readme-files/code-validator-order-2901.png)
  * CSS: ![Code validator - CSS](readme-files/code-validator-css-2901.png)

### Manual Testing

#### Browser compatibility

The website was tested on the following browsers:

* Google Chrome - no issues identified.
* Mozilla Firefox - no issues identified.
* Microsoft Edge - no issues identified.

#### Device compatibility

The website was tested on the following devices:

* Sony Xperia 10 III - no issues identified.
* Samsung Galaxy A52s - no issues identified.
* Lenovo Yoga s730 - no issues identified.
* Sony VAIO 15" - no issues identified.
* Dell P2419H 24" screen - no issues identified.
* Samsung Galxy Tab S4 - no issues identified.

Even though no issues with functionality, appearance, or responsiveness were identified, it was noted that in order to improve user experience, it would be beneficial to increase the font size of the navigation bar items as well as the gap between them to make it easier for people with bigger fingers to select the correct link when using a mobile device or a tablet. This was updated.

#### Common Elements Testing

* **Navigation toggle:** When using a small device, the navigation bar opens and closes correctly when toggled. The active page is underlined.
* **Navigation bar:** The navigation bar is displayed correctly under the header when using a laptop or a desktop. The active page is underlined.
* **Footer contact icons:** Social media links open the appropriate website, and the email "mailto" link opens a new email.
* **Call to action links:** Call to action links on the landing page open the Find Us and Order pages correctly.
* **Landing page images:** When using a laptop, the landing page is correctly displaying three images instead of one.
* **Maps:** The maps on the Find Us page display the correct location and allow the user to enlarge them and zoom in/out.
* **TAC widget:** The terms and conditions widget on the Order page correctly displays the terms and conditions when clicked. When using a larger device, the summary element changes colour when hovered to encourage the user to click it open.
* **Email addresses:** When the email address links are clicked, a new email to the business is opened. There was an issue with one of the links on the Order page caused by an incorrectly typed email address. This was solved by adding the missing .com to the email address in question.
* **Order form:** The form on the Orger page correctly checks that all fields have been completed, validates the information inputted, and requires terms and conditions to be accepted before the form can be submitted. The form submits the information correctly.

### Performance and Accessibility

Chrome DevTool Lighthouse report indicated that the site was performing poorly due to the large image sizes. The images were resized to improve user experience. The report also highlighted that the iframes used to display maps on Find Us page did not have titles. These were added to improve accessibility. It was confirmed that the selected fonts are easy to read on different devices.

Lighthouse reports after the above-mentioned issues were addressed:

* Landing page:  
![Landing page lighthouse report](readme-files/lighthouse-index-2901.png)
* Find Us page:  
![Find Us page lighthouse report](readme-files/lighthouse-find-us-2901.png)
* Order page:  
![Order page lighthouse report](readme-files/lighthouse-order-2901.png)

### Responsiveness

In addition to manual checks, responsiveness was tested using [Chrome DevTools](https://developer.chrome.com/docs/devtools) and [Responsive Design Checker](https://www.responsivedesignchecker.com/). No issues were identified.

### Solved Bugs

The following bugs were noticed and fixed during the development phase:

* The body element had *height: 100vh* instead of *min-height: 100vh* which meant the footer did not stick to the bottom as planned. This was fixed by changing it to *min-height: 100vh*. However, this resulted in the hero image disappearing as its height had been set using a percentage. This was fixed by setting the height of the Hero image using *vh* instead.
* The order form has been set to have max-width to prevent it from getting unnecessarily wide. On screens smaller than 768px, the form had been given a margin of 10px on its left and right sides to prevent it from getting too close to the sides. This looked good on mobile phone screens, but during the development process, it was noticed that this meant that when the screen size got larger than the max-width+20px, the form remained 10px from the left-side. This was fixed by setting the margin of the *form* element to *0 auto* and setting the left and right margin of the *fieldset* element to *10px*.

## Deployment

This project was developed using [Codeanywhere](https://codeanywhere.com/) integrated development environment, and the project was deployed to GitHub pages. The project was deployed in the early stages of the development process to allow the developer to test the site on different devices and identify and fix any issues.

### GitHub pages

The project was deployed to GitHub pages by taking the following steps:

1. Log into **GitHub** and locate your GitHub repo.
2. Open the **Settings** tab of your GitHub repo.
3. Locate the **Code and automation** section on the side menu, and select **Pages**.
4. Under **Build and Deployment**,
   1. set **Source** to Deploy from Branch,
   2. set **Branch** to Main Branch,
   3. set **Folder** to / (root) and
   4. click **Save**.
5. Open the **Code** tab and refresh your page after a couple of minutes.
6. Under **Deployment**, select 'github-pages' and click the link under **Active Deployments**.

## Finished Product

The project was developed for four screen sizes: mobile (320px to 767px), tablet (768px to 991px), laptop (992px to 1320px), and desktop (>=1320px). The decision to use 1320px as the final breakpoint instead of the standardised breakpoint of 1200px was made based on the design of the index page, especially the layout of the three images and the *How to Enjoy* section.

|            | Mobile  | Tablet  |  Laptop  |  Desktop  |
| ---        | ---     |  ---    |   ---    |   ---     |
|Landing Page|![mobile index](readme-files/mobile-index.png)|![tablet index](readme-files/tablet-index.png)|![laptop index](readme-files/laptop-index.png)|![desktop index](readme-files/desktop-index.png)|
|Find Us Page|![mobile find us](readme-files/mobile-find-us.png)|![tablet find us](readme-files/tablet-find-us.png)|![laptop find us](readme-files/laptop-find-us.png)|![desktop find us](readme-files/desktop-find-us.png)|
|Order Page  |![mobile order](readme-files/mobile-order.png)|![tablet order](readme-files/tablet-order.png)|![laptop order](readme-files/laptop-order.png)|![desktop order](readme-files/desktop-order.png)|

## Credits

### Content

All the content was written by the developer.

### Media

#### Images

* The Hero image, the images of tortilla and the image of tortilla ingredients were taken by the developer.
* The menu background image: a photo by [Peter Gargiulo](https://unsplash.com/@grndezyns) on [Unsplash](https://unsplash.com/).
* The visit us food truck image: a photo by [Kampus Production](https://www.pexels.com/@kampus/) on [Pexels](https://www.pexels.com/).
* The illustration of the food truck was created by the developer's partner.

#### Icons

* All icons are from [Font Awesome](https://fontawesome.com/).

### Code

* The idea for the Navigation menu toggle using only HTML and CSS was taken from Code Institute's Love Running project. The HTML structure was taken from the project, but it was styled differently by the developer to meet the needs of this project.
* The resources of Part 1 of Code Institute's Diploma in Full Stack Software Development were regularly consulted for ideas.
* [W3Schools](https://www.w3schools.com/), [Stack Overflow](https://stackoverflow.com/) and [MDN Web Docs](https://developer.mozilla.org/en-US/) were consulted for ideas and to ensure understanding.
* Code Institute's HTML learning resources and [MDN Web Docs](https://developer.mozilla.org/en-US/) were consulted to create the disclosure widget to display and hide the full terms and conditions.

### Commit messages

* The developer was introduced to [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) by her mentor, Marcel Mulders. The use of Conventional Commits was implemented halfway through the project.

## Features not implemented

The following features were considered during the development of this project, but it has not been possible to implement them yet.

* **Fixed header** It could improve user experience to have a fixed header to give the users an easy access to the navigation bar at all times.
* **404 page** Having an interesting 404 error page could improve user experience in case of any broken links or the user entering the address incorrectly.
* **Thank you page** User experience could be improved by directing users to a Thank you page once they have submitted their order.
* **Order form** The order form requires the users to select from a dropdown list their preferred collection location and the day of the week when they would like to collect their order. However, when selecting the date of collection, the users are able to select any date, including those that do not match their selected day of the week. Ways to validate this user input with Javascript could be explored in the future.
