# Testing

> [!NOTE]  
> Return back to the [README.md](README.md) file.

## Feature-by-Feature Testing (TO DO)

In this section, you need to convince the assessors that you have conducted enough testing to legitimately believe that the site works well.
Essentially, in this part, you should go over all of your project's features, and ensure that they all work as intended,
with the project providing an easy and straightforward way for the users to achieve their goals.
Go through each feature of your portfolio site and detail the testing process for each.

Explain the functionality and demonstrate how it aligns with the intended purpose. This could include:

- Navigation: Ensuring smooth transitions between pages, links directing to the correct destinations.
- Responsive Design: Checking for compatibility across various devices and screen sizes.
- Portfolio Display: Verifying that projects are properly showcased with accurate descriptions, images, and links.
- Contact Form: Testing the form submission process, ensuring the user receives a confirmation, and you receive the message.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

When validating the index.html file, one warning came up which could be easily fixed (see screenshots below). After that, all files were validated with no errors or warnings.

| Directory | File | Screenshot | Notes |
| --- | --- | --- | --- |
|  | index.html | ![screenshot](documentation/validation/html-index.png) | On first validation, one warning was shown:<br>  ![screenshot](documentation/validation/html-index-warning.png)<br> A heading was missing in the hero image section, this was quickly fixed by adding a hidden heading and can be tracked in [this issue](https://github.com/theresaabl/pp-seminars/issues/8) .|
|  | upcoming.html | ![screenshot](documentation/validation/html-upcoming.png) | |
|  | participate.html | ![screenshot](documentation/validation/html-participate.png) | |
|  | participate-confirmation.html | ![screenshot](documentation/validation/html-participate-confirmation.png) | |
|  | contact.html | ![screenshot](documentation/validation/html-contact.png) | |
|  | contact-confirmation.html | ![screenshot](documentation/validation/html-contact-confirmation.png) | |
|  | newsletter.html | ![screenshot](documentation/validation/html-newsletter.png) | |
|  | newsletter-confirmation.html | ![screenshot](documentation/validation/html-newsletter-confirmation.png) | |
|  | 404.html | ![screenshot](documentation/validation/html-404.png) | |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate my CSS file.

| Directory | File | Screenshot | 
| --- | --- | --- | 
| assets/css | style.css | ![screenshot](documentation/validation/css.png) | 

## Browser Compatibility

I have tested my deployed project on multiple browsers to check for compatibility issues. The browsers I have tested on are:
- [Chrome](https://www.google.com/chrome)
- [Firefox](https://www.mozilla.org/firefox)
- [Edge](https://www.microsoft.com/edge)

| Browser | Home | Upcoming | Participate | Contact | Newsletter | Form confirmation pages| 404 page | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | -- |
| Chrome | ![screenshot](documentation/browsers/browser-chrome-home.png) | ![screenshot](documentation/browsers/browser-chrome-upcoming.png) |![screenshot](documentation/browsers/browser-chrome-participate.png) | ![screenshot](documentation/browsers/browser-chrome-contact.png) | ![screenshot](documentation/browsers/browser-chrome-newsletter.png) | ![screenshot](documentation/browsers/browser-chrome-participate-confirmation.png)<br> ![screenshot](documentation/browsers/browser-chrome-contact-confirmation.png) <br> ![screenshot](documentation/browsers/browser-chrome-newsletter-confirmation.png) | ![screenshot](documentation/browsers/browser-chrome-404.png) |  Works as expected |
| Firefox | ![screenshot](documentation/browsers/browser-firefox-home.png) | ![screenshot](documentation/browsers/browser-firefox-upcoming.png) |![screenshot](documentation/browsers/browser-firefox-participate.png) | ![screenshot](documentation/browsers/browser-firefox-contact.png) | ![screenshot](documentation/browsers/browser-firefox-newsletter.png) |  ![screenshot](documentation/browsers/browser-firefox-participate-confirmation.png)<br> ![screenshot](documentation/browsers/browser-firefox-contact-confirmation.png) <br> ![screenshot](documentation/browsers/browser-firefox-newsletter-confirmation.png) | ![screenshot](documentation/browsers/browser-firefox-404.png) |  Works as expected, with a slight difference in opacity of form placeholder text.|
| Edge | ![screenshot](documentation/browsers/browser-edge-home.png) | ![screenshot](documentation/browsers/browser-edge-upcoming.png) |![screenshot](documentation/browsers/browser-edge-participate.png) | ![screenshot](documentation/browsers/browser-edge-contact.png) | ![screenshot](documentation/browsers/browser-edge-newsletter.png) |  ![screenshot](documentation/browsers/browser-edge-participate-confirmation.png)<br> ![screenshot](documentation/browsers/browser-edge-contact-confirmation.png) <br> ![screenshot](documentation/browsers/browser-edge-newsletter-confirmation.png) | ![screenshot](documentation/browsers/browser-edge-404.png) |  Works as expected |

Note that the radio buttons in the participate and contact forms have been restyled due to accessibility reasons after taking these screenshots, these are only slight design changes and I have tested that they don't impact these results.

## Responsiveness

I have tested my deployed project on multiple devices to check for responsiveness issues. I first tested many different device sizes in Chrome DevTools (part of which are shown in the screenshots below). I then tested the site on different physical devices.

Note: For better readabilty I have not included screenshots of the form confirmation pages in this section (and following sections). Since they are styled using the same css classes as the actual form pages, it is sufficient to include the form pages only.

| Device | Home | Upcoming | Participate | Contact | Newsletter | 404 page | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Mobile (DevTools Samsung Galaxy S8+) | ![screenshot](documentation/responsiveness/responsive-mobile-home.png) | ![screenshot](documentation/responsiveness/responsive-mobile-upcoming.png) | ![screenshot](documentation/responsiveness/responsive-mobile-participate.png) | ![screenshot](documentation/responsiveness/responsive-mobile-contact.png) | ![screenshot](documentation/responsiveness/responsive-mobile-newsletter.png) | ![screenshot](documentation/responsiveness/responsive-mobile-404.png) | Works as expected |
| Tablet (iPad Mini) (DevTools) | ![screenshot](documentation/responsiveness/responsive-tablet-home.png) | ![screenshot](documentation/responsiveness/responsive-tablet-upcoming.png) | ![screenshot](documentation/responsiveness/responsive-tablet-participate.png) | ![screenshot](documentation/responsiveness/responsive-tablet-contact.png) | ![screenshot](documentation/responsiveness/responsive-tablet-newsletter.png) | ![screenshot](documentation/responsiveness/responsive-tablet-404.png) | Works as expected |
| Desktop (DevTools Laptop L) | ![screenshot](documentation/responsiveness/responsive-laptop-home.png) | ![screenshot](documentation/responsiveness/responsive-laptop-upcoming.png) | ![screenshot](documentation/responsiveness/responsive-laptop-participate.png) | ![screenshot](documentation/responsiveness/responsive-laptop-contact.png) | ![screenshot](documentation/responsiveness/responsive-laptop-newsletter.png) | ![screenshot](documentation/responsiveness/responsive-laptop-404.png) | Works as expected |
| XL Monitor (DevTools 4K) | ![screenshot](documentation/responsiveness/responsive-monitor-home.png) | ![screenshot](documentation/responsiveness/responsive-monitor-upcoming.png) | ![screenshot](documentation/responsiveness/responsive-monitor-participate.png) | ![screenshot](documentation/responsiveness/responsive-monitor-contact.png) | ![screenshot](documentation/responsiveness/responsive-monitor-newsletter.png) | ![screenshot](documentation/responsiveness/responsive-monitor-404.png) | Works as expected |
| Samsung Galaxy A41 (Mobile) | ![screenshot](documentation/responsiveness/responsive-galaxy-home.jpg) | ![screenshot](documentation/responsiveness/responsive-galaxy-upcoming.jpg) | ![screenshot](documentation/responsiveness/responsive-galaxy-participate.jpg) | ![screenshot](documentation/responsiveness/responsive-galaxy-contact.jpg) | ![screenshot](documentation/responsiveness/responsive-galaxy-newsletter.jpg) | ![screenshot](documentation/responsiveness/responsive-galaxy-404.jpg) | Works as expected |
| Galaxy Tab S6 Lite (Tablet) | ![screenshot](documentation/responsiveness/responsive-tab-s6-home.jpg) | ![screenshot](documentation/responsiveness/responsive-tab-s6-upcoming.jpg) | ![screenshot](documentation/responsiveness/responsive-tab-s6-participate.jpg) | ![screenshot](documentation/responsiveness/responsive-tab-s6-contact.jpg) | ![screenshot](documentation/responsiveness/responsive-tab-s6-newsletter.jpg) | ![screenshot](documentation/responsiveness/responsive-tab-s6-404.jpg) | Works as expected |
| Lenovo X1 Extreme (Laptop) | ![screenshot](documentation/responsiveness/responsive-lenovo-home.png) | ![screenshot](documentation/responsiveness/responsive-lenovo-upcoming.png) | ![screenshot](documentation/responsiveness/responsive-lenovo-participate.png) | ![screenshot](documentation/responsiveness/responsive-lenovo-contact.png) | ![screenshot](documentation/responsiveness/responsive-lenovo-newsletter.png) | ![screenshot](documentation/responsiveness/responsive-lenovo-404.png) | Works as expected |
| Lenovo ThinkVision P24h-10 (Monitor) | ![screenshot](documentation/responsiveness/responsive-thinkvision-home.png) | ![screenshot](documentation/responsiveness/responsive-thinkvision-upcoming.png) | ![screenshot](documentation/responsiveness/responsive-thinkvision-participate.png) | ![screenshot](documentation/responsiveness/responsive-thinkvision-contact.png) | ![screenshot](documentation/responsiveness/responsive-thinkvision-newsletter.png) | ![screenshot](documentation/responsiveness/responsive-thinkvision-404.png) | Works as expected |

Note that the radio buttons in the participate and contact forms have been restyled due to accessibility reasons after taking these screenshots, these are only slight design changes and I have tested that they don't impact these results.

### Issues with Responsiveness

Everything works as expected for the different devices. However, an issue arises when looking at small window sizes on a laptop or desktop device. 

When looking at very narrow screen widths, where the logo breaks into two or three lines, there is a very small pixel range, where the uppermost part of the main content is covered by the header. 

![screenshot](documentation/responsiveness/responsive-desktop-small-window-issue.png)

This issue is due to the scrollbar in desktop devices, which causes the media query breakspoints to be inconsistent with mobile devices and DevTools where no scrollbar is present. It arises at around 500px screen width, as well as at around 320px (depending on the size of the scrollbar). Everything works perfectly well when no scrollbar is present (as is the case for mobile devices), and this is our priority in the case of such small screen sizes. It is very unlikely for people to look at such narrow windows on a desktop device, and further, the issue only arises for a very small pixel range. There is no satisfying solution using just HTML and CSS alone (that I am aware of), which is the scope of this project. 

Therefore, this issue is left as an [unfixed bug](#unfixed-bugs) for this release and it can be tracked in [Github Issues](https://github.com/theresaabl/pp-seminars/issues/10).


## Lighthouse Audit

I have tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Notes | Desktop | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse/lighthouse-home-mobile.png) | Slower response time due to large images and layout shifts: <br> ![screenshot](documentation/lighthouse/lighthouse-home-mobile-details.png) | ![screenshot](documentation/lighthouse/lighthouse-home-desktop.png) | Some minor warnings |
| Upcoming | ![screenshot](documentation/lighthouse/lighthouse-upcoming-mobile.png) | Some minor warnings due to large images and layout shifts | ![screenshot](documentation/lighthouse/lighthouse-upcoming-desktop.png) | Some minor warnings |
| Participate | ![screenshot](documentation/lighthouse/lighthouse-participate-mobile.png) | Some minor warnings in latest report. <br> An earlier report showed lower accessibility ratings: <br> ![screenshot](documentation/lighthouse/lighthouse-participate-mobile-accessibility-issue.png) <br> ![screenshot](documentation/lighthouse/lighthouse-participate-mobile-accessibility-issue-details.png) <br> This was fixed by increasing size and spacing of all form radio buttons. | ![screenshot](documentation/lighthouse/lighthouse-participate-desktop.png) | Some minor warnings |
| Contact | ![screenshot](documentation/lighthouse/lighthouse-contact-mobile.png) | Slower response time due to large images and layout shifts. <br> The issues with the best practices score stem intirely from third party cookies from the google maps embedded in the page: <br> ![screenshot](documentation/lighthouse/lighthouse-contact-mobile-best-practices.png) | ![screenshot](documentation/lighthouse/lighthouse-contact-desktop.png) | Best practices issues same as for Mobile testing. |
| Newsletter | ![screenshot](documentation/lighthouse/lighthouse-newsletter-mobile.png) | Some minor warnings | ![screenshot](documentation/lighthouse/lighthouse-newsletter-desktop.png) | Some minor warnings |

Before performing these audits I had already converted all images to .webp using [![Cloudconvert](https://cloudconvert.com/webp-converter)](https://cloudconvert.com/webp-converter) and optimized their size using  [![Tinypng](https://tinypng.com/)](https://tinypng.com/) for a faster website. The Desktop audits show that the response time is good, there are remaining slow response time scores from the Mobile audits, which could be improved in a future release.

The site got full scores for accessibility, best practices and SEO, except for issues with third party cookies in the contact page.

## User Story Testing (TO DO)

 already got the stories defined on your README.

Most of your project's **features** should already align with the **user stories**,
so this should as simple as creating a table with the user story, matching with the re-used screenshot
from the respective feature.

User Experience Testing:

- Usability Testing: Have users (or simulated users) interact with the site and provide feedback. Document any issues encountered and the resolutions implemented.
- Accessibility Testing: Confirm compliance with accessibility standards (e.g., screen reader compatibility, proper alt text for images, keyboard navigation).


| User Story | Screenshot |
| --- | --- |
| As a new site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/features/feature01.png) |
| As a new site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/features/feature02.png) |
| As a new site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/features/feature03.png) |
| As a returning site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/features/feature04.png) |
| As a returning site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/features/feature05.png) |
| As a returning site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/features/feature06.png) |
| As a site administrator, I should be able to ____________, so that I can ____________. | ![screenshot](documentation/features/feature07.png) |
| As a site administrator, I should be able to ____________, so that I can ____________. | ![screenshot](documentation/features/feature08.png) |
| As a site administrator, I should be able to ____________, so that I can ____________. | ![screenshot](documentation/features/feature09.png) |
| repeat for all remaining user stories | x |

## Bugs

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-START OF NOTES (to be deleted)

This section is primarily used for JavaScript and Python applications,
but feel free to use this section to document any HTML/CSS bugs you might run into.

It's very important to document any bugs you've discovered while developing the project.
Make sure to include any necessary steps you've implemented to fix the bug(s) as well.

**PRO TIP**: screenshots of bugs are extremely helpful, and go a long way!

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-END OF NOTES (to be deleted)

- JS Uncaught ReferenceError: `foobar` is undefined/not defined

    ![screenshot](documentation/bugs/bug01.png)

    - To fix this, I _____________________.

- JS `'let'` or `'const'` or `'template literal syntax'` or `'arrow function syntax (=>)'` is available in ES6 (use `'esversion: 11'`) or Mozilla JS extensions (use moz).

    ![screenshot](documentation/bugs/bug02.png)

    - To fix this, I _____________________.

- Python `'ModuleNotFoundError'` when trying to import module from imported package

    ![screenshot](documentation/bugs/bug03.png)

    - To fix this, I _____________________.

- Django `TemplateDoesNotExist` at /appname/path appname/template_name.html

    ![screenshot](documentation/bugs/bug04.png)

    - To fix this, I _____________________.

- Python `E501 line too long` (93 > 79 characters)

    ![screenshot](documentation/bugs/bug04.png)

    - To fix this, I _____________________.

## Unfixed Bugs

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-START OF NOTES (to be deleted)

You will need to mention unfixed bugs and why they were not fixed.
This section should include shortcomings of the frameworks or technologies used.
Although time can be a big variable to consider, paucity of time and difficulty understanding
implementation is not a valid reason to leave bugs unfixed.

If you've identified any unfixed bugs, no matter how small, be sure to list them here.
It's better to be honest and list them, because if it's not documented and an assessor finds the issue,
they need to know whether or not you're aware of them as well, and why you've not corrected/fixed them.

Some examples:

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-END OF NOTES (to be deleted)

- On devices smaller than 375px, the page starts to have `overflow-x` scrolling.

    ![screenshot](documentation/bugs/unfixed-bug01.png)

    - Attempted fix: I tried to add additional media queries to handle this, but things started becoming too small to read.

- For PP3, when using a helper `clear()` function, any text above the height of the terminal does not clear, and remains when you scroll up.

    ![screenshot](documentation/bugs/unfixed-bug02.png)

    - Attempted fix: I tried to adjust the terminal size, but it only resizes the actual terminal, not the allowable area for text.

- When validating HTML with a semantic `section` element, the validator warns about lacking a header `h2-h6`. This is acceptable.

    ![screenshot](documentation/bugs/unfixed-bug03.png)

    - Attempted fix: this is a known warning and acceptable, and my section doesn't require a header since it's dynamically added via JS.

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-START OF NOTES (to be deleted)

If you legitimately cannot find any unfixed bugs or warnings, then use the following sentence:

🛑🛑🛑🛑🛑🛑🛑🛑🛑🛑-END OF NOTES (to be deleted)

> [!NOTE]  
> There are no remaining bugs that I am aware of.
