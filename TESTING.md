# Testing

> [!NOTE]  
> Return back to the [README.md](README.md) file.

## Manual Testing

I tested the following features of the deployed website in a manual testing process:

| Feature | Expectation | Action | Outcome |
| --- | --- | --- | --- |
| Logo | When clicked the home page will open | Click the logo | Home page opened when clicked |
| Home navbar button | When clicked the home page will open | Click the logo | Home page opened when clicked |
| Upcoming navbar button | When clicked the upcoming talks page will open | Click the Home nav button | Upcoming talks page opened when clicked |
| Participate navbar button | When clicked the participate page will open | Click the Participate nav button | Participate page opened when clicked |
| Contact navbar button | When clicked the contact page will open | Click the Contact nav button | Contact page opened when clicked |
| Dropdown menu for mobile devices | When clicked the dropdown menu opens <br>  When clicked again the dropdown menu closes | Click the burger icon <br> Click the burger icon again | Dropdown menu opens <br> Dropdown menu closes |
| Newsletter icon button | When clicked the newsletter sign-up page will open | Click the newsletter icon button | Newsletter sign-up page opened when clicked |
| Social media icons in footer | When clicked the social media pages will open in new tab | Click the social media icons | Social media pages are opened in new tab when clicked |
| Links in the about section | When clicked the contact page will open | Click the links in the about section | The contact page opens when clicked |
| Links in the upcoming talks section | When clicked correct page opens in new tab | Click the links in the upcoming talks section | The correct page opens when clicked |
| Participate form name and email fields | When active autocomplete suggestions show | Activate the name and email fields | The name and email fields show autocomplete suggestions when active |
| Participate form reset button | When clicked the form will be reset | Click the form reset button | The form is reset when the reset button is clicked |
| Participate form submit button | When clicked with valid input the form will send and the participate confirmation page will show <br> When clicked with invalid input or empty fields a warning will show | Click the submit button  <br>  | The form sends and the confirmation page shows when submit button is clicked with valid input <br> A warning shows when there is invalid input or empty fields |
| Participate confirmation page | After 10 seconds the home page shows | Wait 10 seconds | The home page shows after 10 seconds |
| Links on the Participate confirmation page | When clicked the contact page or home page will show respectively | Click the contact or home page links | The contact or home page show when the respective link is clicked |
| Contact form name and email fields | When active autocomplete suggestions show | Activate the name and email fields | The name and email fields show autocomplete suggestions when active |
| Contact form reset button | When clicked the form will be reset | Click the form reset button | The form is reset when the reset button is clicked |
| Contact form submit button | When clicked with valid input the form will send and the contact confirmation page will show <br> When clicked with invalid input or empty fields a warning will show | Click the submit button  <br>  | The form sends and the confirmation page shows when submit button is clicked with valid input <br> A warning shows when there is invalid input or empty fields |
| Contact confirmation page | After 10 seconds the home page shows | Wait 10 seconds | The home page shows after 10 seconds |
| Links on the Contact confirmation page | When clicked the contact page or home page will show respectively | Click the contact or home page links | The contact or home page show when the respective link is clicked |
| Newsletter form name and email fields | When active autocomplete suggestions show | Activate the name and email fields | The name and email fields show autocomplete suggestions when active |
| Newsletter form reset button | When clicked the form will be reset | Click the form reset button | The form is reset when the reset button is clicked |
| Newsletter form submit button | When clicked with valid input the form will send and the newsletter confirmation page will show <br> When clicked with invalid input or empty fields a warning will show | Click the submit button  <br>  | The form sends and the confirmation page shows when submit button is clicked with valid input <br> A warning shows when there is invalid input or empty fields |
| Newsletter confirmation page | After 10 seconds the home page shows | Wait 10 seconds | The home page shows after 10 seconds |
| Link on the Newsletter confirmation page | When clicked the home page will show | Click the home page link | The home page shows when the link is clicked |
| Error 404 page | When entering a URL to a page that does not exist on this website an error page will show | Enter a URL to a page that does not exist on this website | An error page shows when entering a URL to a page that does not exist on this website |
| Link on the error 404 page | When clicked the home page will show | Click the link on the error 404 page | The home page shows when the link is clicked |

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

When validating the index.html file, one warning came up which could be easily fixed (see screenshots below). After that, all files were validated with no errors or warnings.

| Directory | File | Screenshot | Notes |
| --- | --- | --- | --- |
|  | [index.html](https://validator.w3.org/nu/?doc=https://theresaabl.github.io/pp-seminars/index.html) | ![screenshot](documentation/validation/html-index.png) | On first validation, one warning was shown:<br>  ![screenshot](documentation/validation/html-index-warning.png)<br> A heading was missing in the hero image section, this was quickly fixed by adding a hidden heading and can be tracked in [this issue](https://github.com/theresaabl/pp-seminars/issues/8) .|
|  | [upcoming.html](https://validator.w3.org/nu/?doc=https://theresaabl.github.io/pp-seminars/upcoming.html) | ![screenshot](documentation/validation/html-upcoming.png) | |
|  | [participate.html](https://validator.w3.org/nu/?doc=https://theresaabl.github.io/pp-seminars/participate.html) | ![screenshot](documentation/validation/html-participate.png) | |
|  | [participate-confirmation.html](https://validator.w3.org/nu/?doc=https://theresaabl.github.io/pp-seminars/participate-confirmation.html) | ![screenshot](documentation/validation/html-participate-confirmation.png) | |
|  | [contact.html](https://validator.w3.org/nu/?doc=https://theresaabl.github.io/pp-seminars/contact.html) | ![screenshot](documentation/validation/html-contact.png) | |
|  | [contact-confirmation.html](https://validator.w3.org/nu/?doc=https://theresaabl.github.io/pp-seminars/contact-confirmation.html) | ![screenshot](documentation/validation/html-contact-confirmation.png) | |
|  | [newsletter.html](https://validator.w3.org/nu/?doc=https://theresaabl.github.io/pp-seminars/newsletter.html) | ![screenshot](documentation/validation/html-newsletter.png) | |
|  | [newsletter-confirmation.html](https://validator.w3.org/nu/?doc=https://theresaabl.github.io/pp-seminars/newsletter-confirmation.html) | ![screenshot](documentation/validation/html-newsletter-confirmation.png) | |
|  | [404.html](https://validator.w3.org/nu/?doc=https://theresaabl.github.io/pp-seminars/404.html) | ![screenshot](documentation/validation/html-404.png) | |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate my CSS file and it passed with no errors or warnings.

| Directory | File | Screenshot | 
| --- | --- | --- | 
| assets/css | [style.css](https://jigsaw.w3.org/css-validator/validator?uri=https://theresaabl.github.io/pp-seminars) | ![screenshot](documentation/validation/css.png) | 

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

Note, there is a typo in commit [0c4412e](https://github.com/theresaabl/pp-seminars/commit/0c4412e5392eed68cfa3d7dda98f8f54178e4f89). The screenshots were added to documentation/responsiveness and not to assets/responsiveness.

### Issues with Responsiveness

Everything works as expected for the different devices. However, an issue arises when looking at small window sizes on a laptop or desktop device. 

When looking at very narrow screen widths, where the logo breaks into two or three lines, there is a very small pixel range, where the uppermost part of the main content is covered by the header. 

![screenshot](documentation/responsiveness/responsive-desktop-small-window-issue.png)

This issue is due to the scrollbar in desktop devices, which causes the media query breakspoints to be inconsistent with mobile devices and DevTools where no scrollbar is present. It arises at around 500px screen width, as well as at around 320px (depending on the size of the scrollbar). Everything works perfectly well when no scrollbar is present (as is the case for mobile devices), and this is our priority in the case of such small screen sizes. It is very unlikely for people to look at such narrow windows on a desktop device, and further, the issue only arises for a very small pixel range. There is no satisfying solution using just HTML and CSS alone (that I am aware of), which is the scope of this project. 

Therefore, this issue is left as an [open issue](#open-issues) for this release and it can be tracked in [Github Issues](https://github.com/theresaabl/pp-seminars/issues/10).


## Lighthouse Audit

I have tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Notes | Desktop | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse/lighthouse-home-mobile.png) | Slower response time due to large images and layout shifts: <br> ![screenshot](documentation/lighthouse/lighthouse-home-mobile-details.png) | ![screenshot](documentation/lighthouse/lighthouse-home-desktop.png) | Some minor warnings |
| Upcoming | ![screenshot](documentation/lighthouse/lighthouse-upcoming-mobile.png) | Some minor warnings due to large images and layout shifts | ![screenshot](documentation/lighthouse/lighthouse-upcoming-desktop.png) | Some minor warnings |
| Participate | ![screenshot](documentation/lighthouse/lighthouse-participate-mobile.png) | Some minor warnings in latest report. <br> An earlier report showed lower accessibility ratings: <br> ![screenshot](documentation/lighthouse/lighthouse-participate-mobile-accessibility-issue.png) <br> ![screenshot](documentation/lighthouse/lighthouse-participate-mobile-accessibility-issue-details.png) <br> This was fixed by increasing size and spacing of all form radio buttons. | ![screenshot](documentation/lighthouse/lighthouse-participate-desktop.png) | Some minor warnings |
| Contact | ![screenshot](documentation/lighthouse/lighthouse-contact-mobile.png) | Slower response time due to large images and layout shifts. <br> The issues with the best practices score stem intirely from third party cookies from the google maps embedded in the page: <br> ![screenshot](documentation/lighthouse/lighthouse-contact-mobile-best-practices.png) | ![screenshot](documentation/lighthouse/lighthouse-contact-desktop.png) | Best practices issues same as for Mobile testing. |
| Newsletter | ![screenshot](documentation/lighthouse/lighthouse-newsletter-mobile.png) | Some minor warnings | ![screenshot](documentation/lighthouse/lighthouse-newsletter-desktop.png) | Some minor warnings |

Before performing these audits I had already converted all images to .webp using [Cloudconvert](https://cloudconvert.com/webp-converter) and optimized their size using  [Tinypng](https://tinypng.com/) for a faster website. The Desktop audits show that the response time is good, there are remaining slow response time scores from the Mobile audits, which could be improved in a future release.

The site got full scores for accessibility, best practices and SEO, except for issues with third party cookies in the contact page.

## User Story Testing

The user stories were presented in the [README.md](README.md) file. To test them, I checked whether there is a feature that clearly fulfills the users goal for each of the user stories.

| User Story | Screenshot |
| --- | --- |
|As an internal researcher, I would like to see an overview of upcoming talks, so that I can attend seminars and stay up-to-date on latest research developments. | ![screenshot](documentation/features/upcoming-laptop.png) |
|As an internal researcher, I would like to see details of upcoming talks, so that I can prepare myself before attending. | ![screenshot](documentation/features/upcoming-laptop.png) |
|As an internal researcher, I would like to sign up to a weekly newsletter with details on upcoming talks, so that I can attend seminars regularly without having to look up details every week. | ![screenshot](documentation/features/newsletter-form.png) |
|As an internal researcher, I would like to sign up to give a talk in the lunch seminar, so that I can promote my own research or find possible collaborators. | ![screenshot](documentation/features/participate-form.png) |
|As an internal researcher, I would like to sign up to suggest a paper for the journal club, so that I can discuss recent developments and get input from my peers. | ![screenshot](documentation/features/participate-form.png) |
|As an internal researcher, I would like to access information about external speakers of upcoming talks, so that I can find new talent to hire. | ![screenshot](documentation/features/upcoming-laptop.png) |
|As an external researcher, I would like to see what types of seminars are organised and where and when they take place, so I can see which ones I want to attend or contribute to. | ![screenshot](documentation/features/about-laptop.png) |
|As an external researcher, I would like to see an overview of upcoming talks, so that I can attend seminars and stay up-to-date on latest research developments. | ![screenshot](documentation/features/upcoming-laptop.png) |
|As an external researcher, I would like to see details of upcoming talks, so that I can prepare myself before attending. | ![screenshot](documentation/features/upcoming-laptop.png) |
|As an external researcher, I would like to acces contact information, so that I can see how to get to the seminars or how to contact the organisers with any questions. | ![screenshot](documentation/features/contact-laptop.png) |
|As an external researcher, I would like to sign up to give a talk in the lunch seminar, so that I can promote my own research, find possible collaborators or find someone to hire me. | ![screenshot](documentation/features/participate-form.png) |
|As an external researcher, I would like to sign up to suggest a paper for the journal club, so that I can discuss recent developments and network with researchers from the organising group. | ![screenshot](documentation/features/participate-form.png) |
|As a student, I would like to see what types of seminars are organised and where and when they take place, so I can see which ones I want to attend. | ![screenshot](documentation/features/about-laptop.png) |
|As a student, I would like to see an overview of upcoming talks, so that I can attend seminars and stay up-to-date on latest research developments. | ![screenshot](documentation/features/upcoming-laptop.png) |
|As a student, I would like to see an overview of upcoming talks, so that I can attend seminars to network with researchers and find someone to hire me. | ![screenshot](documentation/features/upcoming-laptop.png) |
|As a student, I would like to see details of upcoming talks, so that I can prepare myself before attending. | ![screenshot](documentation/features/upcoming-laptop.png) |
|As a student, I would like to sign up to a weekly newsletter with details on upcoming talks, so that I can attend seminars regularly without having to look up details every week. | ![screenshot](documentation/features/newsletter-form.png) |
|As a student, I would like to acces contact information, so that I can contact the organisers with any questions. | ![screenshot](documentation/features/contact-laptop.png) |

## Bugs

I have tracked my bugs with **GitHub Issues** :

[![GitHub issue custom search](https://img.shields.io/github/issues-search?query=repo%3Atheresaabl%2Fpp-seminars%20label%3Abug&label=bugs)](https://github.com/theresaabl/pp-seminars/issues?q=is%3Aissue+is%3Aclosed+label%3Abug)

### Fixed Bugs

All previously closed/fixed bugs can be tracked [here](https://github.com/theresaabl/pp-seminars/issues?q=is%3Aissue+is%3Aclosed).

| Bug | Status |
| --- | --- |
| [file site.webmanifest:1 not found](https://github.com/theresaabl/pp-seminars/issues/1) | Closed |
| [Font color change in .active class does not apply](https://github.com/theresaabl/pp-seminars/issues/2) | Closed |
| [margins in about section different for different screen widths](https://github.com/theresaabl/pp-seminars/issues/3) | Closed |
| [Fail to show mathematical formulas](https://github.com/theresaabl/pp-seminars/issues/4) | Closed |
| [404 message not displayed correctly on all screens](https://github.com/theresaabl/pp-seminars/issues/5) | Closed |
| [header covers main content for specific pixel range](https://github.com/theresaabl/pp-seminars/issues/6) | Closed |
| [Contrast ratio too low in forms](https://github.com/theresaabl/pp-seminars/issues/7) | Closed |
| [Missing heading in hero-image section](https://github.com/theresaabl/pp-seminars/issues/8) | Closed |
| [Missing autocomplete attribute in forms](https://github.com/theresaabl/pp-seminars/issues/9) | Closed |

Note, there is a typo in commit [b0b9f53](https://github.com/theresaabl/pp-seminars/commit/b0b9f53012f4becabd3c53748760d7618b1c9486). It should say "Fix" instead of "Solve" for the issue to be closed with the commit.

### Open Issues

[![GitHub issues](https://img.shields.io/github/issues/theresaabl/pp-seminars)](https://github.com/theresaabl/pp-seminars/issues)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/theresaabl/pp-seminars)](https://github.com/theresaabl/pp-seminars/issues?q=is%3Aissue+is%3Aclosed)

Any remaining open issues can be tracked [here](https://github.com/theresaabl/pp-seminars/issues).

See also the [Issues with Responsiveness section](#issues-with-responsiveness).
