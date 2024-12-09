# TESTING

## Code Validation


To validate all HTML files, the recommended validator service by Code Institute which is [HTML W3C](https://validator.w3.org/) was used.


| Validator | Page | Comment | Screenshot |
| --- | --- | --- | --- |
| [W3C](https://validator.w3.org/) | Home | No Errors | ![screenshoot](screenshots/htmlHome.webp) |
| [W3C](https://validator.w3.org/) | Gallery | No Errors | ![screenshoot](screenshots/htmlAbouta.webp) |
| [W3C](https://validator.w3.org/) | Book Now | No Errors | ![screenshoot](screenshots/htmlBookingForm.webp) |

---

To validate the CSS file, the recommended validator service by Code Institute which is [Jigsaw W3C](https://jigsaw.w3.org/css-validator/) was used.


| Validator | Page | Comment | Screenshot |
| --- | --- | --- | --- |
| [Jigsaw W3C](https://jigsaw.w3.org/css-validator/) | style.css | No Errors | ![screenshot](screenshots/CSS.webp) |
---

## Lighthouse Testing

Lighthouse was used to evaluate the website's performance, accessibility and best practices. This testing ensures the site meets modern web standards and provides an optimised user experience accross devices.

| Device | Page | Comment | Screenshot |
| --- | --- | --- | --- |
| Desktop | Home | minor warning | ![HomeDesktop](screenshots/HomeDesktop.png) |
| Mobile | Home | Some warnings cannot be resolved as they involve external libraries. | ![MobileHome](screenshots/HomeMobile.png) |
| Desktop | Gallery | Some warnings cannot be resolved as they involve external libraries. | ![GalleryDesktop](screenshots/GalleryDesktop.png) |
| Mobile | Gallery | Some warnings cannot be resolved as they involve external libraries. | ![GalleryMobile](screenshots/GalleryMobile.png) |
| Desktop | Book now | minor warnings | ![BookNowDesktop](screenshots/BookNowDesktop.png) |
| Mobile | Book now | minor warnings | ![BookNowMobile](screenshots/BookNowMobile.png) |
---


## Responsiveness

I tested the layout's adaptability to various screen sizes and orientation, ensuring that the users enjoy a consistent and optimised experience, whether they're browsing on mobile, tablet or laltop/desktop. This ensure that all elements, such as images, text and navigation, adapt correctly and maintain usability regardless of the device.

| Device | Comment | Screenshot |
| --- | --- | --- |
| Mobile (Chrome DevTools) | Achieves desired functionality | ![Mobile Device](screenshots/MobileDevice.png) |
| Tablet (Chrome DevTools) | Achieves desired functionality | ![Tablet Device](screenshots/TabletDevice.png) |
| Laptop 1024px (Chrome DevTools) | Achieves desired functionality | ![Laptop1024px Device](screenshots/Laptop1024pxDevice.png) |
| Laptop 1440px (Chrome DevTools) | Achieves desired functionality | ![Laptop1440px Device](screenshots/Laptop1440pxDevice.png) |
---

## Browser Compatibility

I have tested the site across major browsers including Chrome, Firefox, MS Edge, and Opera. Each browser renders the site as intended, ensuring a consistent and seamless user experience.

* **Chrome**

![Chrome](screenshots/Chrome.webp)

* **Firefox**

![Firefox](screenshots/Firefox.webp)

* **MS Edge**

![MS Edge](screenshots/MS%20Edge.webp)

* **Opera**

![Opera](screenshots/Opera.webp)
---

## bugs

* The header text has visibility issue when the site is viewed on screens 1440px or wider.

![HeaderText](screenshots/heroImage.1440px.png)

**_to resolved this, I restyled the header text using CSS, changing the color to white with text-shadows._**


* There is a margin issue with the booking form when viewed on screens 1024px or smaller; the gap is not sufficient.

![bookingForm](screenshots/bookingForm.1024px.png)

**_to resolved this, I customised it using CSS, setting the margin-top to 40px and margin-bottom to 80px._**

* There is an insufficient gap between the "Contact Us" and "Opening Times" sections when viewed on screens 425px or smaller.

![MobileScreen](screenshots/mobileScreen.png)

**_To resolved this, I added Bootstrap utility class mb-5 directly in HTML._**

* Toggler icon is not visible on screens 768px or smaller due to the darker navbar background colour.

![TogglerIcon](screenshots/togglerIcon.png)

**_To resolved this, I customised the toggler icon using CSS, setting the toggler to have lighter border-color and backround-color._**

* The book Now button changes position when the site is viewed on screens 1440px or wider.

![BookNowButton](screenshots/BookNowbutton.png)

I tried to customised it using CSS, setting the button to display: block and margin-top: 15px.However, it did not resolved the issue.

![BookNowButton2](screenshots/BookNowbutton2.png)

**_Then, I separate the button into it's own div so, it became a standalone block element._**

* Carousel positiong issue: when viewed on screen of 1024px, the margins are sufficient. However, when viewed on screens smaller than 1024px and wider than 1024px, the carousel does not have enough gap.

![Carousel](screenshots/CarouselScreen1440px.768px.png)

**_to resolved this, I added Bootstrap utility classes mt-4 and mb-4 directly in HTML._**