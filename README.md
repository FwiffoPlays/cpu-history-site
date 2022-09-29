# CPU History Site

This project is for a static website built using HTML and CSS which aims to detail some of the history of the CPU and its development, remaining conscious of accessibility and responsiveness for a variety of devices.
A live version of the site can currently be found [here](https://fwiffoplays.github.io/cpu-history-site/)

![A mockup image of the website displayed on a variety of devices with varying screen sizes](assets/images/readme/Mockup.webp)

## Features

The majority of the content within site is contained within a single scrolling page, including navigation buttons at the top of the page to jump to a specific section and a 'back to top' button which allows the user to easily return to the top in order to navigate somewhere else. The scrolling nature of the main content allows for the user to read through the content without interruption but still allows for easy navigation through the use of the provided navigation buttons.

### Navigation Menu

This provides links to all the pages of the site and their subsections (In the case of the main page)
They allow for easy navigation through the site, including on mobile devices.

![A screenshot of the navigation menu in its row format for desktop](assets/images/readme/Nav_Bar_Row.webp)

This is the 'row' orientation of the navigation bar which is intended for widescreen devices such as a desktop computer.

![A screenshot of the navigation menu in its column format for mobile](assets/images/readme/Nav_Bar_Column.webp)

This is the 'column' orientation, intended for portrait screens or generally smaller screens.

### Back-to-top button

A 'Back-to-top' button was included on the main page of the site to allow for a quick return to the top of the page, which is useful as more content is added to the site and it takes longer to scroll back up.

![A screenshot of the back to top button](assets/images/readme/Back_To_Top.webp)

### 404 Page

A custom 404 page has been implemented on the site so that in the event a user navigates to an invalid page they can easily return to the index.

![A screenshot of the custom 404 error page](assets/images/readme/404_Image.webp)

### Suggestions Form

A suggestions form was included within the site so that the users can provide feedback.

The form contains the following fields and attributes:
Email (required, type=email)

Suggestions (required, type=text-entry)

Rating (required, type=radio)

![A screenshot of the suggestions form](assets/images/readme/Suggestions_Form.webp)

In this instance the form redirects to a 'submission success page' using the 'GET' method, but would typically use 'POST' and the details would be stored by the server in a database.

![A screenshot of the form submission success page](assets/images/readme/Form_Success.webp)

### Favicons

Favicons were created for the site to allow it to be easily distinguishable within a page tab on a web browser.
They were generated at https://favicon.io/

![A screenshot of the site's favicon](assets/images/readme/Favicons.webp)

## Design

A simple design is employed on the site, focusing primarily on a consistent 'metal grey' colour scheme in line with the theme of the CPU and technology, as well as a simple to navigate and understand layout which does not impede the user's reading of the content.

Responsiveness was also a focus for the site, allowing it to remain accessible and easy to use on a variety of hardware which enables a larger user base.

## Technologies

The primary technologies used for this project were:

- HTML
  - HTML is responsible for representing the content within the page
- CSS
  - CSS dictates the styling and formatting of the content which has been placed on the page through HTML
  - Flex-box formatting was used within CSS to align the pages' contents.
- All images displayed on the site were converted to the 'webp' format, offering better image compression and therefore smaller file sizes for faster page load times. This becomes more important as more pictures are added to the site, otherise the user could have to wait several seconds or more for the page's content to be correctly displayed, harming the user experience.

## Testing

Several forms of testing took place throughout the site's development. The most frequent and simple form being a visual check of the change which occured from code changes, done by hosting a web server within the Gitpod environment and navigating quickly throughout the site.

### Lighthouse Testing

Lighthouse testing was also carried out using the development tools built into Google Chrome. This was done in an incognito window so that extensions or cache could not influence the results.

The results for the site were as follows:

![An image of the results of the lighthouse testing carried out in Chrome](assets/images/readme/Lighthouse_Results_1.webp)

Here we can see that on most areas the site has done well, however the 'Performance' category has suffered a bit due to loading the 'Font Awesome' scripts.

![An image of the results of one of the suggestions made by the Lighthouse test](assets/images/readme/Lighthouse_Results_2.webp)

This could be mitigated by having the required icons local to the site, avoiding the requirement to run scripts when the page loads and therefore improving performance.

### Accessibility

Throughout the site's development the Wave Accessibility tool was used to verify its accessibility, which includes aspects such as:
* Good contrast between text/background for the visually impaired
* Including aria-labels on icons for screen readers
* Alt-texts were provided on images for screen readers
* Headings are used appropriately with the correct order being followed
* The main page's content is split using sections


### Validation

Validation tools were used to check both the HTML and CSS code for errors:

#### HTML

The site https://validator.w3.org/ was used to validate the HTML code:

![A screenshot of the HTML validation results](assets/images/readme/HTML_Validation.webp)

As shown, no HTML errors were found.

#### CSS

The site https://jigsaw.w3.org/css-validator/ was used to validate the CSS code:

![A screenshot of the CSS validation results](assets/images/readme/CSS_Validation.webp)

As shown, no CSS errors were found.

## Deployment

The final deployment of the site was completed using Github Pages. This is done by going to the settings of the site's repository, navigating to the 'Pages' section and clicking deploy. After a short time the site is deployed to your github directory. In my case, this would be 
https://fwiffoplays.github.io/cpu-history-site/suggestions.html

## Credits

Hero image from user 'tomeqs' on Shutterstock: https://www.shutterstock.com/g/tomeqs?q=cpu

Intel C4004 image from 'Thomas Nguyen' on Wikipedia: https://en.wikipedia.org/wiki/Intel_4004#/media/File:Intel_C4004.jpg

Intel Pentium P54C die image from 'Pauli Rautakorpi' on Wikipedia: https://en.wikipedia.org/wiki/Pentium_(original)#/media/File:Intel_Pentium_P54C_die.jpg

Apple M1 processor illustration from Henriok on Wikipedia: https://en.wikipedia.org/wiki/Apple_M1#/media/File:Apple_M1.jpg

Burning CPU image from StockFreeImages: https://www.stockfreeimages.com/8976244/Burning-processor.html

Happy CPU image from Heriyusuf on Vecteezy.com: https://www.vecteezy.com/vector-art/3439377-happy-processor-cartoon-playing-soap-bubble

Favicons were generated at: https://favicon.io/

Social link icons and scripts were provided by: https://fontawesome.com/