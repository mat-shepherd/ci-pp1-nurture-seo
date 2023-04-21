# Nurture SEO
(Developer: Matthew Shepherd)

![Mockup image](docs/responsive-device-screenshots.webp)

[Live webpage](https://mat-shepherd.github.io/ci-pp1-nurture-seo/)

## Table of Content

1. [Project Goals](#project-goals)
    1. [User Goals](#user-goals)
    2. [Site Owner Goals](#site-owner-goals)
2. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [User Requrements and Expectations](#user-requrements-and-expectations)
    3. [User Stories](#user-stories)
3. [Design](#design)
    1. [Design Choices](#design-choices)
    2. [Colour](#colours)
    3. [Fonts](#fonts)
    4. [Structure](#structure)
    5. [Wireframes](#wireframes)
4. [Technologies Used](#technologies-used)
    1. [Languages](#languages)
    2. [Frameworks & Tools](#frameworks-&-tools)
5. [Features](#features)
6. [Testing](#validation)
    1. [HTML Validation](#HTML-validation)
    2. [CSS Validation](#CSS-validation)
    3. [Accessibility](#accessibility)
    4. [Performance](#performance)
    5. [Device testing](#performing-tests-on-various-devices)
    6. [Browser compatibility](#browser-compatability)
    7. [Testing user stories](#testing-user-stories)
8. [Bugs](#Bugs)
9. [Deployment](#deployment)
10. [Credits](#credits)
11. [Acknowledgements](#acknowledgements)

## Project Goals 
The goals of this website include:

### Business Goals
- Increase brand awareness
- Convey the expertise, capabilities, and track record of the consultant to build trust in the brand
- Increase qualified leads for the consultant's services
- Build an SEO-optimised website with a great user experience to increase our search engine visibility and showcase the quality of the consultant's work

### User Goals
- Find a consultant that provides SEO services that align with their business goals and budget
- Understand the services provided by the consultant
- Find proof of work that the consultant can deliver the results desired
- Contact the consultant to request more details on the services provided and request a proposal

## User Experience

### Target Audience
- Medium to large-sized business owners in the UK, Ireland and North America
- Marketing managers of medium to large-sized businesses in the UK, Ireland and North America
- Sales managers of medium to large-sized businesses in the UK, Ireland and North America

### User Requirements and Expectations
- An intuitive and easy to locate navigation system regardless of screen size
- Ability to quickly find relevant information on the business and its services
- Quick and easy ways to contact the business
- A visually appealing and instuitively structured website that works well and is easy to read on all screen sizes
- Informative and relevant content that is easy to locate and read
- A website that loads quickly on all devices and connections
- A website that is accessible to all users 

### User Stories
I have divided my user stories into prospective customers, existing customers, and site owners, as each of these users will have a distinct set of needs and goals.

#### Prospective Customers
1. As a prospective customer, I want to see a list of the services offered by the consultant so that I can understand if the consultant can provide the solution my business is seeking.
2. As a prospective customer, I want to see a description of each service so I can understand the services provided.
3. As a prospective customer, I want to see details of the consultant's experience, past customers, and examples of their work or results so that I can feel confident the consultant can deliver the results my business expects.
4. As a prospective customer, I want to see details of the consultant's work experience and expertise to understand if they have the expertise required to handle my project.
5. As a prospective customer, I want to submit questions or details of my project through the website so I can connect with the consultant to discuss my project and receive answers, set up, a call or receive a project proposal.
6. As a prospective customer, I want to locate the consultant's contact details so I can see where they are located and phone or email them about my project and any questions I may have.
7. As a prospective customer, I want to locate the consultant's social media details so I can see if they are thought leaders in the space, learn from their content, and see what other social media users say about them.


#### Existing Customers
8. As an existing customer, I want to locate the consultant's contact details or reach out to them directly through the website so I can request assistance or enquire about additional services.
9. As an existing customer, I want to locate the consultant's social media details so I can follow them and learn about SEO industry trends and tips and tricks to improve my site's performance.

#### Site Owner 
10. As a site owner, I want to be able to quickly update the service and testimonial sections of the site so I can showcase our newest services and most recent reviews to help convert more prospective customers.
11. As a site owner, I want to be able to receive timely notifications of forms submitted through the website so I can quickly respond to prospective and existing customers.

## Design

### Design Choices
I researched other digital marketing agency websites to find a bright, clean, and simple layout that fit my desired content and that was also responsive. I based my site design on the layout of [Workhu's](https://workhu.com/) website.

Imagery used on the site was chosen to convey growth and as such are primarily images of nature. The hero iamge was chosen to covney the digital mrketing services provided.

### Colour
As the agency focuses on growth through SEO and is called Nurture SEO I chose elemental (earth, water, sun, air) and organic (plants) colours to convey organic growth. Colors were adapted from palettes generated using [Venngage's Accessible color palette generator](https://venngage.com/tools/accessible-color-palette-generator).

Primary Colours - White / Green

Secondary Colours - Yellow / Blue

To remain WCAG AAA compliant, I chose dark colour variants for background colours behind white text to mantain maximum contrast. Colour contrast compliance was tested using [WebAIM's Contrast Checker tool](https://webaim.org/resources/contrastchecker/). Brighter green, yellow, and blue colours used in gradients in the services containers were pruposefully not placed behind text to avoid poor contrast and accessibility issues.
<br>

![Colour scheme](docs/features/colour-palette.webp)


### Fonts
Oswald and Noto Serif fonts were selected with the help of the [21 Google Fonts Combinations For Websites & Brands](https://www.garett.co/21-google-fonts-combinations-for-websites-brands) article by [Garett Southerton](https://www.garett.co/about). The article noted that these fonts are "...perfect for brands that are sleek, impactful, or need to build trust with their audience."

Oswald font is used for site headings and Noto Serif for the main body text. Both fonts use a sans serif fallback.

Fonts are imported using the [Google Fonts](https://fonts.google.com/) library.

The logo image uses Nunito Sans Bold as this was the closest complimentary font available in the [HubSpot Brand Kit Generator](https://www.hubspot.com/brand-kit-generator/) tool.

### Structure
The page is structured in an easy to navigate z-shaped pattern allowing visitors to quickly consume key information while scanning the page from left to right. Starting at the the top left of the page the visitor will notice the site logo followed by the navigation menu and a Get a Quote call to action button. This allow them to quickly understand the name of the business, how to navigate the site, and how to get in touch with site owner to get a quote.

For simplicity the site consists of one primary page (plus a 404 page) and contains 10 distinct sections:
- A header section containing the business logo, a responsive navigation menu and call to action button
- A hero section containing a concise description and image to convey the the business's purpose and value proposition and call to action button
- A client logos section to showcase the consultant's existing clients and build trust with the visitor
- A parallax section to provide a visual break in the content that displays imagery related to growth
- A services section to provide brief descriptions of the services the consultant provides
- A client testimonials section
- Another parallax section to provide a further visual break in the content that displays imagery related to growth
- An About me section to provide details of the consultant's work experience and expertise as well as a headshot image to build trust with the visitor
- A contact section which provides a contact form to allow the visitor to contact the consultat with question or to request a quote and a Google map displaying the consultant's location
- A footer section which displays the business logo, business tagline, navigation menu, call to action button, navigation links, contact information, social media links, the site owners name and copyright notice, and a linkt ot he site owner's GitHub page.

### Wireframes

### Index
<details><summary>iPhone SE</summary>
<img src="docs/wireframes/iphone-se-wireframe.webp">
</details>

<details><summary>iPad Mini</summary>
<img src="docs/wireframes/ipad-mini-wireframe.webp">
</details>

<details><summary>Desktop</summary>
<img src="docs/wireframes/desktop-wireframe.webp">
</details>


## Technologies Used

### Languages
- HTML
- CSS
- JavaScript

### Frameworks & Tools
- [Git](https://git-scm.com/)
- [GitHub](https://github.com/)
- [Gitpod - Cloud IDE](https://www.gitpod.io/)
- [CodeAnywhere - Cloud IDE](https://codeanywhere.com/)
- [GIMP - iamge editor](https://www.gimp.org/)
- [Figma - wireframing tool](https://www.figma.com/files/recent?fuid=1219987136949485526)
- [Google Fonts](https://fonts.google.com/)
- [Font Awesome](https://fontawesome.com/)
- [Favicon.io - favicon generator](https://favicon.io/)
- [Google Maps](https://www.google.com/maps)
- [Placehold - placeholder image generator](https://placehold.co/)
- [Responsive Image Breakpoints Generator v2.0](https://www.responsivebreakpoints.com/) tool by [Cloudinary](https://cloudinary.com/)
- [Venngage's Accessible color palette generator](https://venngage.com/tools/accessible-color-palette-generator)
- CSS Gradient tool at [cssgradient.io](https://cssgradient.io/)
- [W3C Markup Validation Service](https://validator.w3.org/)
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)
- [WAVE web accessibility evaluation tool](https://wave.webaim.org/)
- [Google Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/)


## Features
The website consists of two pages in total, an index page and 404 page. The index page contains 12 distinct features:

### Logo and Navigation Bar
- containing the business logo, a responsive navigation menu and call to action button

![Logo and navbar]()

### Hero Section
- containing a concise description and image to convey the the business's purpose and value proposition and call to action button

![Feature 2]()

### Client Logos
- to showcase the consultant's existing clients and build trust with the visitor

### First Parallax Section 
- to provide a visual break in the content that displays imagery related to growth

### Services Section
- to provide brief descriptions of the services the consultant provides

### Client Testimonials

### Second Parallax Section 
- to provide a further visual break in the content that displays imagery related to growth

### About Me 
- section to provide details of the consultant's work experience and expertise as well as a headshot image to build trust with the visitor

### Contact Form 
- a contact form to allow the visitor to contact the consultat with questions or to request a quote

### Google map 
- a Google map displaying the consultant's location allowing the visitor to get the consultant's address, view a map of the location and directions to their location

### Footer
- which displays the business logo, business tagline, navigation menu, call to action button, navigation links, contact information, social media links, the site owners name and copyright notice, and a linkt ot he site owner's GitHub page.

## Validation

### HTML Validation
The W3C Markup Validation Service was used to validate the HTML of the website. All pages pass with no errors no warnings to show.

index.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmat-shepherd.github.io%2Fci-pp1-nurture-seo%2F)
404.html results [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmat-shepherd.github.io%2Fci-pp1-nurture-seo%2F404.html)

### CSS Validation
The W3C Jigsaw CSS Validation Service was used to validate the CSS of the website.

styles.css [results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fmat-shepherd.github.io%2Fci-pp1-nurture-seo%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Accessibility
The WAVE WebAIM web accessibility evaluation tool was used to ensure the website met high accessibility standards. All pages pass with 0 errors.

index.html [results](https://wave.webaim.org/report#/https://mat-shepherd.github.io/ci-pp1-nurture-seo/)
404.html results [results](https://wave.webaim.org/report#/https://mat-shepherd.github.io/ci-pp1-nurture-seo/404.html)

### Performance 
Google Lighthouse in Google Chrome Developer Tools was used to test the performance of the website. All elements perfomed well.

### Index 
<details><summary>Mobile</summary>
<img src="docs/lighthouse/index-lighthouse-mobile.webp">
</details>
<details><summary>Desktop</summary>
<img src="docs/lighthouse/index-lighthouse-desktop.webp">
</details>

### 404 
<details><summary>Mobile</summary>
<img src="docs/lighthouse/404-lighthouse-mobile.webp">
</details>
<details><summary>Desktop</summary>
<img src="docs/lighthouse/404-lighthouse-desktop.webp">
</details>


### Performing tests on various devices 
The website was tested on the following devices:


In addition, the website was tested using Google Chrome Developer Tools Device Toggling option for all available device options.

### Browser compatability
The website was tested on the following browsers:
- Google Chrome
- Mozilla Firefox
- Microsoft Egde

### Testing user stories
#### Prospective Customers
1. As a prospective customer, I want to see a list of the services offered by the consultant so that I can understand if the consultant can provide the solution my business is seeking. 

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| | | |
| | | |
| | | |

<details><summary>Screenshots</summary>

</details>

2. As a prospective customer, I want to see a description of each service so I can understand the services provided.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| | | |
| | | |
| | | |


<details><summary>Screenshots</summary>

</details>

3. As a prospective customer, I want to see details of the consultant's experience, past customers, and examples of their work or results so that I can feel confident the consultant can deliver the results my business expects.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| | | |
| | | |
| | | |

<details><summary>Screenshots</summary>

</details>

4. As a prospective customer, I want to see details of the consultant's work experience and expertise to understand if they have the expertise required to handle my project.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| | | |
| | | |
| | | |


<details><summary>Screenshots</summary>

</details>

5. As a prospective customer, I want to submit questions or details of my project through the website so I can connect with the consultant to discuss my project and receive answers, set up, a call or receive a project proposal.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| | | |
| | | |
| | | |


<details><summary>Screenshots</summary>

</details>

6. As a prospective customer, I want to locate the consultant's contact details so I can see where they are located and phone or email them about my project and any questions I may have.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| | | |
| | | |
| | | |


<details><summary>Screenshots</summary>

</details>

7. As a prospective customer, I want to locate the consultant's social media details so I can see if they are thought leaders in the space, learn from their content, and see what other social media users say about them.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| | | |
| | | |
| | | |

<details><summary>Screenshots</summary>

</details>

#### Existing Customers
8. As an existing customer, I want to locate the consultant's contact details or reach out to them directly through the website so I can request assistance or enquire about additional services.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| | | |
| | | |
| | | |


<details><summary>Screenshots</summary>

</details>

9. As an existing customer, I want to locate the consultant's social media details so I can follow them and learn about SEO industry trends and tips and tricks to improve my site's performance.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| | | |
| | | |
| | | |


<details><summary>Screenshots</summary>

</details>

#### Site Owner 
10. As a site owner, I want to be able to quickly update the service and testimonial sections of the site so I can showcase our newest services and most recent reviews to help convert more prospective customers.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| | | |
| | | |
| | | |

<details><summary>Screenshots</summary>

</details>

11. As a site owner, I want to be able to receive timely notifications of forms submitted through the website so I can quickly respond to prospective and existing customers.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| | | |
| | | |
| | | |


<details><summary>Screenshots</summary>

</details>

## Bugs

| **Bug** | **Fix** |
| ----------- | ----------- |
| | |
| | |
| | |
| | |

## Deployment
The website was deployed using GitHub Pages by following these steps:
1. In the GitHub repository navigate to the Settings tab
2. On the left-hand menu select Pages
3. For the source select Branch: master
4. After the webpage refreshes automatically you will see a ribbon on the top saying: Your site is live at https://mat-shepherd.github.io/ci-pp1-nurture-seo/

You can for fork the repository by following these steps:
1. Go to the GitHub repository
2. Click on Fork button in upper right-hand corner

You can clone the repository by following these steps:
1. Go to the GitHub repository 
2. Locate the Code button above the list of files and click it 
3. Select if you prefer to clone using HTTPS, SSH, or Github CLI and click the copy button to copy the URL to your clipboard
4. Open Git Bash
5. Change the current working directory to the one where you want the cloned directory
6. Type git clone and paste the URL from the clipboard ($ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY)
7. Press Enter to create your local clone.


## Credits
Images and logos not referenced below are owned or created by the developer.

### Media
In order of appearance:

### Wireframes
- [Figma Wireframing Kit](https://www.figma.com/community/file/1088059168988686975) by [Tiago Gonçalves](https://www.figma.com/community/file/1088059168988686975)
    <details><summary>Image Placeholders</summary>
    <img src="docs/wireframes/desktop-wireframe.webp">
    </details>
- [Website Wireframes UI Kit](https://www.figma.com/community/file/1212997233512196965) by [UI-UX Expert](https://www.figma.com/@uiux_expert)
    <details><summary>Button, Menu and Form Elements</summary>
    <img src="docs/wireframes/desktop-wireframe.webp">
    </details>    
- [placehold.co](https://placehold.co/)
    <details><summary>Placeholder Images</summary>
    <img src="https://placehold.co/600x400">
    </details>
- [HubSpot Brand Kit Generator](https://www.hubspot.com/brand-kit-generator/) by [HubSpot](https://www.hubspot.com/)
    <details><summary>Logo</summary>
    <img src="docs/credits/logo-variations.webp">
    </details>
- Font Awesome Icons by [Font Awesome](https://fontawesome.com/)
    <details><summary>Service Section [Font Awesome Icons](https://fontawesome.com/icons)</summary>
    <img src="docs/credits/service-fontawesome-icons.webp">
    </details>    
- [Social icons](https://pixabay.com/vectors/social-media-icon-set-facebook-6261537/) by [goddessSue13](https://pixabay.com/users/goddesssue13-615343/)
    <details><summary>Social icons</summary>
    <img src="docs/credits/social-media-6261537_1920.webp">
    </details>

### Index Page
- [HubSpot Brand Kit Generator](https://www.hubspot.com/brand-kit-generator/) by [HubSpot](https://www.hubspot.com/)
    <details><summary>Logo</summary>
    <img src="docs/credits/logo-variations.webp">
    </details>   
- Purchased under subscription from [iStock Photos](https://www.istockphoto.com/) by [Mykyta Dolmatov](https://www.istockphoto.com/portfolio/VectorKnight?mediatype=illustration)
    <details><summary>Hero Image</summary>
    <img src="docs/credits/istock-1053519140.webp">
    </details>
- Roadtrips Logo used with permission of former client [Roadtrips](https://www.roadtrips.com/)
    <details><summary>Client Logo: Roadtrips</summary>
    <img src="docs/credits/roadtrips-logo.webp">
    </details>
- iQmetrix Logo used with permission of former client [iQmterix](https://www.iqmetrix.com/)
    <details><summary>Client Logo: iQmetrix</summary>
    <img src="docs/credits/iqmetrix-black-logo.webp">
    </details>
- Scootaround Logo used with permission of former client [Scootaround](https://scootaround.com/en)
    <details><summary>Client Logo: Scootaround</summary>
    <img src="docs/credits/scootaround-logo.webp">
    </details>
- IP Telecom Logo used with permission of former client [IP Telecom](https://www.iptelecom.ie/)
    <details><summary>Client Logo: IP Telecom</summary>
    <img src="docs/credits/ip-telecom-logo536x97.webp">
    </details>
- Purchased under subscription from [iStock Photos](https://www.istockphoto.com/) by [amenic181](https://www.istockphoto.com/portfolio/amenic181?mediatype=photography)
    <details><summary>First Parallax Image: Young plant stock photo</summary>
    <img src="docs/credits/istock-533007815.webp">
    </details>
- Font Awesome Icons by [Font Awesome](https://fontawesome.com/)
    <details><summary>Service Section [Font Awesome Icons](https://fontawesome.com/icons)</summary>
    <img src="docs/credits/service-fontawesome-icons.webp">
    </details>
- Purchased under subscription from [iStock Photos](https://www.istockphoto.com/) by [Photodjo](https://www.istockphoto.com/portfolio/Photodjo?mediatype=photography)
    <details><summary>Second Parallax Image: Agriculture stock photo</summary>
    <img src="docs/credits/istock-1453737875.webp">
    </details>    
- [goddessSue13](https://pixabay.com/users/goddesssue13-615343/)
    <details><summary>[Social icons](https://pixabay.com/vectors/social-media-icon-set-facebook-6261537/)</summary>
    <img src="docs/credits/social-media-6261537_1920.webp">
    </details>

### 404 Page
- Purchased under subscription from [iStock Photos](https://www.istockphoto.com/) by [ilyakalinin](https://www.istockphoto.com/portfolio/ilyakalinin?mediatype=illustration)
    <details><summary>Missile crashed Page not found error 404</summary>
    <img src="docs/credits/istock-1324403502.webp">
    </details>  

### Code
In order of appearance:

- The layout of the site was inspired by (but no code was copied from) [Workhu's website](https://workhu.com/)
- Font selections were inspired by the [21 Google Fonts Combinations For Websites & Brands](https://www.garett.co/21-google-fonts-combinations-for-websites-brands) article by [Garett Southerton](https://www.garett.co/about)
- The markdown structure of this readme and the deployment steps were based on the structure and content of the following readme.md files from other Code Institute student projects:
    - https://github.com/4n4ru/CI_MS1_BodelschwingherHof
    - https://github.com/jamie2210/CI_MS1_TBC
- The HTML and CSS code for the mobile hamburger menu was copied and modified from the [Pure CSS responsive menu](https://codepen.io/alvarotrigo/pen/MWEJEWG) example by [Álvaro](https://codepen.io/alvarotrigo)
- The accessibility bug where the label element used in the mobile menu required text was overcome using the code from [this Stack Overflow answer](https://stackoverflow.com/a/71369523/21643967) by [GrahamTheDev](https://stackoverflow.com/users/2702894/grahamthedev)
- Flexbox methods used throughout the site were learned from [W3C Schools](https://www.w3schools.com/css/css3_flexbox_container.asp) and the amazing [Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) by [Chris Coyier at CSS Tricks](https://css-tricks.com/author/chriscoyier/)
- The method for providing alternate text for background images was adapted from the [Alternate text for background images](http://www.davidmacd.com/blog/alternate-text-for-css-background-images.html) by [David MacDonald](https://www.davidmacd.com/david_macdonald_bio.html)
- img srcset methods used to display different images at various breakpoints were learned from the [Responsive images with srcset and sizes](https://medium.com/@woutervanderzee/responsive-images-with-srcset-and-sizes-fc434845e948) by [Wouter van der Zee](Wouter van der Zee) and breakpoints were chosen with the help of the [Responsive Image Breakpoints Generator v2.0](https://www.responsivebreakpoints.com/) tool by [Cloudinary](https://cloudinary.com/)
- The flexbox method to achieve equal height columns for the index page's service containers was learned from the [Same Columns Height](https://flexbox.ninja/demos/same-height-columns/) article by [Geoffrey Crofte at Flexbox Ninja](https://flexbox.ninja/about/) and the [CSS equal height columns](https://daily-dev-tips.com/posts/css-equal-height-columns/) article by [Chris Bongers at Daily Dev Tips](https://daily-dev-tips.com/about/)
- CSS Gradients in the service containers of the index page were achieved using the code output from the CSS Gradient tool at [cssgradient.io](https://cssgradient.io/)
- The method to achieve a circular frame around the index page's headshot image was adapated from the [Code Institute's Love Running Project](https://github.com/Code-Institute-Org/love-running-2.0).
- CSS commenting styles were based on the [Principles of writing consistent, idiomatic CSS readme](https://github.com/necolas/idiomatic-css) by [Nicolas Gallagher](https://github.com/necolas)



## Acknowledgements
I would like to thank the following people for their contributions in creating this projecT:
- My mentor Mo Shami for your support, guidance, and encouragement 
- Alan Bushell and the February 2023 Student Cohort for their knowledge sharing, advice, and camaraderie during our weekly standup calls and in Slack
- The Code Institute team for an excellent experience and great support leading leading up to this first project
- My wife for her patience and support while I sit in front of the computer for hours on end
- My boys William and Oliver for helping me test the site and spot bugs!
