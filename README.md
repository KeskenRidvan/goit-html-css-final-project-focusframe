# Focus.Frame: A Single-Page Photography Website 📸

This document outlines the core tasks, structure, and technical requirements for the "Focus.Frame" single-page website project. ✨

## Core Features and Requirements

### Layout and Responsiveness 📱💻🖥️

The layout is fully responsive, with specific breakpoints to ensure an optimal user experience across various devices:

* **Mobile:**
    * Fluid layout from 320px.
    * Responsive from 375px.
* **Tablet:**
    * Responsive from 768px.
* **Desktop:**
    * Responsive from 1280px (with an additional responsive layout from 1440px upon request).


### Technical Specifications ⚙️

* **Validation:** The website's layout must pass validation at [https://validator.w3.org/](https://validator.w3.org/) and [https://jigsaw.w3.org/css-validator/](https://jigsaw.w3.org/css-validator/). ✅
* **Semantics:** Semantic compliance with HTML5 standards must be ensured.
* **Fonts:** Fonts must be linked externally. ✒️
* **Image Optimization:**
    * Dimensions for both vector and raster images must be optimized. 📏
    * Image display support for Retina screens must be provided. 💎
    * Image loading must be optimized. ⚡
* **SVG Icons:** All SVG icons must be linked via a sprite. ✨
* **Favicon:** An image for the page's favicon must be added. ❤️


## Project Structure 🏗️

The single-page website is divided into the following sections:

* Header
* Hero
* Advertisement
* About Us
* Our Courses
* Our Mentors
* Sign Up
* Reviews
* Footer


## Detailed Section Breakdown

### Header (Header) 🧭

* Includes a logo, a navigation menu, and a link to the "Sign Up" section. On the mobile version, the link is a camera icon. 📸
* The navigation menu for the mobile version appears as a dropdown sidebar. It is fixed to the viewport height and should include links that navigate to the respective sections of the page.
* The shared background image with the Hero section (a dotted grid) must be applied as a background PNG image to a wrapper that contains both the Header and Hero sections.


### Hero (Hero) 🌟

* The main heading of the website is the text "Discover the magic of photography in our school."
* This section also contains a descriptive part, a block with information about the company's students, and references.
* The text "Our happy students" must be implemented as a link that redirects to the Reviews section. 😊


### Advertisement (Advertisement) 📢

* The heading for this section is the text "Master your photography skills with us!" and should be implemented as a single line.


### About Us (About Us) 📖

* The heading for this section is the text "About us."
* Images should be implemented as content images.
* This section provides detailed information about the school. 🏫


### Our Courses (Our Courses) 📚

* The heading for this section is the text "Our courses."
* This section contains a list of courses offered by the school, which must be implemented as a numbered list using &lt;ol>.
* A course card consists of: a number, a title (the name of the course), a description, and a link icon (⇗).
* Clicking the ⇗ link should take you to the Sign Up section.


### Our Mentors (Our Mentors) 👨‍🏫👩‍🏫

* The heading for this section is the text "Our Mentors."
* This section contains a list of mentors, which must be implemented as an unordered list using &lt;ul>.
* A mentor card consists of: a photograph (a content image), a title (the mentor's name), and a subtitle (the mentor's experience).

### Sign Up (Sign Up) ✍️

* The heading for this section is the text "Sign up."
* The form includes an &lt;input> element (with a pattern attribute for minimum data validation), a &lt;textarea> element, and a "Send" button of type "submit."

### Reviews (Reviews) ⭐

* The heading for this section is the text "Reviews."
* This section contains a list of reviews, which must be implemented as an unordered list using &lt;ul>.
* A review card consists of: a photograph (a content image), the client's name, their status, their feedback, and a rating.

### Footer (Footer) 🦶

* The footer includes the company logo, contact information, a list of social media links, a list of site links, a form with a required &lt;input> element (with a pattern attribute for minimum data validation), and a "Go" button.
* The contact phone number must be implemented using link protocols. 📞
* The list of the company's social media links must be implemented as an unordered list using &lt;ul>. Clicking these links should open the respective GoIT page in a new tab:
    * **Instagram:** [https://www.instagram.com/goit.turkiye/](https://www.instagram.com/goit.turkiye/) 📸
    * **YouTube:** [https://m.youtube.com/@GoITTurkey](https://m.youtube.com/@GoITTurkey) ▶️
    * **Facebook:** [https://www.facebook.com/people/GOIT-T%C3%BCrkiye/61558036560161/](https://www.facebook.com/people/GOIT-T%C3%BCrkiye/61558036560161/) 👍
* The list of anchor links must be implemented as an unordered list using &lt;ul>.
* The dotted grid image must be applied as a background PNG image..
