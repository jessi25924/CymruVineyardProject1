# TESTING

## Code Validation


To validate all HTML files, the recommended validator service by Code Institute which is [HTML W3C](https://validator.w3.org/) was used.


| Validator | Page | Comment | Screenshot |
| --- | --- | --- | --- |
| [W3C](https://validator.w3.org/) | Home | No Errors | ![screenshoot](assets/documentation/html-validation-home.webp) |
| [W3C](https://validator.w3.org/) | Gallery | No Errors | ![screenshoot](assets/documentation/html-validation-about.webp) |
| [W3C](https://validator.w3.org/) | Book Now | No Errors | ![screenshoot](assets/documentation/html-validation-booking.webp) |
| [W3C](https://validator.w3.org/) | Booking Confirmation | No Errors | ![screenshoot](assets/documentation/html-validation-bc.png) |
| [W3C](https://validator.w3.org/) | 404 | No Errors | ![screenshoot](assets/documentation/html-validation-404.png) |

---

To validate the CSS file, the recommended validator service by Code Institute which is [Jigsaw W3C](https://jigsaw.w3.org/css-validator/) was used.


| Validator | Page | Comment | Screenshot |
| --- | --- | --- | --- |
| [Jigsaw W3C](https://jigsaw.w3.org/css-validator/) | style.css | No Errors | ![screenshot](assets/documentation/css-validation.webp) |
---

## Lighthouse Testing

Lighthouse was used to evaluate the website's performance, accessibility and best practices. This testing ensures the site meets modern web standards and provides an optimised user experience accross devices.

| Device | Page | Comment | Screenshot |
| --- | --- | --- | --- |
| Desktop | Home | minor warning | ![HomeDesktop](assets/documentation/home-desktop-lighthouse.png) |
| Mobile | Home | Some warnings cannot be resolved as they involve external libraries. | ![MobileHome](assets/documentation/home-mobile-lighthouse.png) |
| Desktop | Gallery | Some warnings cannot be resolved as they involve external libraries. | ![GalleryDesktop](assets/documentation/gallery-desktop-lighthouse.png) |
| Mobile | Gallery | Some warnings cannot be resolved as they involve external libraries. | ![GalleryMobile](assets/documentation/gallery-mobile-lighthouse.png) |
| Desktop | Book now | minor warnings | ![BookNowDesktop](assets/documentation/book-now-desktop.png) |
| Mobile | Book now | minor warnings | ![BookNowMobile](assets/documentation/book-now-mobile.png) |
---


## Responsiveness

I tested the layout's adaptability to various screen sizes and orientation, ensuring that the users enjoy a consistent and optimised experience, whether they're browsing on mobile, tablet or laltop/desktop. This ensure that all elements, such as images, text and navigation, adapt correctly and maintain usability regardless of the device.

| Device | Comment | Screenshot |
| --- | --- | --- |
| Mobile (Chrome DevTools) | Achieves desired functionality | ![Mobile Device](assets/documentation/mobile-device.png) |
| Tablet (Chrome DevTools) | Achieves desired functionality | ![Tablet Device](assets/documentation/tablet-device.png) |
| Laptop 1024px (Chrome DevTools) | Achieves desired functionality | ![Laptop1024px Device](assets/documentation/laptop-1024px-device.png) |
| Laptop 1440px (Chrome DevTools) | Achieves desired functionality | ![Laptop1440px Device](assets/documentation/laptop-1440px-device.png) |
---

## Browser Compatibility

I have tested the site across major browsers including Chrome, Firefox, MS Edge, Opera, and Safari. Each browser renders the site as intended, ensuring a consistent and seamless user experience.

* **Chrome**

![Chrome](assets/documentation/chrome.webp)

* **Firefox**

![Firefox](assets/documentation/firefox.webp)

* **MS Edge**

![MS Edge](assets/documentation/edge.webp)

* **Opera**

![Opera](assets/documentation/opera.webp)

* **Safari**

![Safari](assets/documentation/safari.png)
---

## bugs

* The header text has visibility issue when the site is viewed on screens 1440px or wider.

![HeaderText](assets/documentation/hero-image.1440px.png)

**_to resolved this, I restyled the header text using CSS, changing the color to white with text-shadows._**


* There is a margin issue with the booking form when viewed on screens 1024px or smaller; the gap is not sufficient.

![bookingForm](assets/documentation/booking-form-1024px.png)

**_to resolved this, I customised it using CSS, setting the margin-top to 40px and margin-bottom to 80px._**

* There is an insufficient gap between the "Contact Us" and "Opening Times" sections when viewed on screens 425px or smaller.

![MobileScreen](assets/documentation/mobile-screen.png)

**_To resolved this, I added Bootstrap utility class mb-5 directly in HTML._**

* Toggler icon is not visible on screens 768px or smaller due to the darker navbar background colour.

![TogglerIcon](assets/documentation/toggler-icon.png)

**_To resolved this, I customised the toggler icon using CSS, setting the toggler to have lighter border-color and backround-color._**

* The book Now button changes position when the site is viewed on screens 1440px or wider.

![BookNowButton](assets/documentation/book-now-button.png)

I tried to customised it using CSS, setting the button to display: block and margin-top: 15px.However, it did not resolved the issue.

![BookNowButton2](assets/documentation/book-now-button2.png)

**_Then, I separate the button into it's own div so, it became a standalone block element._**

* Carousel positiong issue: when viewed on screen of 1024px, the margins are sufficient. However, when viewed on screens smaller than 1024px and wider than 1024px, the carousel does not have enough gap.

![Carousel](assets/documentation/carousel-screen-1440px-768px.png)

**_to resolved this, I added Bootstrap utility classes mt-4 and mb-4 directly in HTML._**