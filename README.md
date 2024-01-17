# La Patata

La Patata is a fictional food truck business selling Spanish tortillas in different food markets in London, UK.

The purpose of this website is to promote the business to London residents as well as people visiting London. The website provides information about the menu, ingredients used as well as the locations and the timetable of the food truck. It also provides a function to pre-order tortillas for collection to local people who would like order several tortillas for example for private family events.

## User Experience (UX)

### Business Goals

* This is a Business to Consumer (B2C) website that aims to increase the number of people who visit the food truck.
* The website provides information about the menu and ingredients used to convince potential customers of the quality of the product.
* The website conveys the feeling of relaxed and fun urban eating experience.
* The website offers the possibility to pre-order tortillas to encourage customers to order larger amounts.

### User Stories

* As a visitor to London, I want to be able to find information about the locations and opening times easily using my mobile phone so that I can find the business while on the move.
* As a local food-lover, I want to be able to find information about the product and the ingredients used so that I can understand more about the quality of the product.
* As a regular customer, I want to be able to buy several tortillas so that I can serve them in my family event.

### Wireframes

[Balsamiq](https://balsamiq.com/) User Interface wireframing tool was used to design the structure of the website.

|  Page    |                         Mobile                                  |                         Desktop                                   |
|  ---     |                         ---                                     |                         ---                                       |
|  Index   |![Mobile Index wireframe](assets/wireframes/mobile-index.png)    |![Desktop Index wireframe](assets/wireframes/desktop-index.png)    |
|  Find Us |![Mobile Find Us wireframe](assets/wireframes/mobile-find-us.png)|![Desktop Find Us wireframe](assets/wireframes/desktop-find-us.png)|
|  Order   |![Mobile Order wireframe](assets/wireframes/mobile-order.png)    |![Desktop Order wireframe](assets/wireframes/desktop-order.png)    |

## Testing

### Code Validation

* The [W3C Markup Validator](https://validator.w3.org/) and [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) were used to validate all the pages to ensure that the project meets the current Web Standards and is from any unintended syntax errors and mistakes that could use issues with accessibilty and usability.

* The pages were validated once half-way through the development. In index.html, W3C Markup Validator found an issue of two sections, hero image and tortilla images, not containing a heading. This was rectified by replacing these section tags with div tags. No issues were found on the other pages or with the CSS code. The Validator highlighted several times that the trailing slash on void elements had no effect. However, these were not removed as they had been added by Prettier when the code had been formatted.

  * Warning messages: ![Code Validator Warnings 17.01.24](assets/readme-files/code-validator-warnings-17.01.png)
  * Info messages after the highlighted issue was resolved: ![Code Validator Info messages 17.01.2024](assets/readme-files/info-messages-17.01.png)