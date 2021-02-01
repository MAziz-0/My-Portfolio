# My-Portfolio

A minimalistic approach to introducing myself to a web user and displaying what I can bring to the table.

## Getting Started

This website is functional on all modern browsers and smartphones above a 350 pixel screen size.

## UX
 
### Main intention behind the UX on this website has been the dark theme with a minamalist approach to displaying information.

The ways I approached this:

1. Making sure that the main features used are clear to the eye. Using Parallax scrolling on images and an automatic Carousel left no room for excessive features and creates a responsive and more dynamic website.

2. Sections and Paragraphs are clearly delineated to show the seperate information using images to seperate sections and the use of dark color palletes which guide the user through the site.

3. Using a single scroll page to navigate three seperate pages has allowed maximum efficiency and less room for disruption as users can quickly view all the pages in a single scroll.

4. Images used in the background are relevant to the titles of each section which ties the whole website into a promotional statement.  My intention is to generate appeal so it was important to make sure there is a synergy between the content and my choice of structured styling.

Wireframe:


![My-Portfolio Wireframe](https://user-images.githubusercontent.com/41737293/106295077-e63eaf80-6247-11eb-90ac-93dd1e333c4a.png)

Mockup:

![My-Portfolio mockup](https://user-images.githubusercontent.com/41737293/106295530-7977e500-6248-11eb-8464-bcdbf2adbe84.PNG)

Lighthouse Report:

![Lighthouse](https://user-images.githubusercontent.com/41737293/106296454-995bd880-6249-11eb-80fe-52225549163c.PNG)

## Features

What methods I used to create a responsive and appealing website.
 
### Existing Features
- Feature 1 - The Bootstrap based Navigation toggler was used to ensure a navigation bar that is both stylish and responsive to modern websites and smartphones. When using the website on a low pixel count the toggler uses the three line toggler (also known as the hamburger toggler) to minimise and maximise the menu.
- Feature 2 - Using Parallax scrolling is a feature intended as a design choice to make the website appealing and easy on the eyes. Potential employers or fellow developers are the target audience so I deemed it necessary to create a website that performs well and has aesthetic value.
- Feature 3 - Bootstrap Carousel was used to create a modern and automated approach to displaying information, having a moving slide alongside a parallax scroll feature was used to make the website look more dynamic and animated. This is also necessary to fit more information in a single scrolling page without having to link new pages to target.


## Technologies Used

- [HTML]
    - The project uses **HTML** to create the basic content

- [CSS]
    - The project uses **CSS** to style the HTML

- [Bootstrap]
    - The project uses **Bootstrap Framework** to utilise its highly optimised feature set.


## Testing

1. Navigation Bar:
    1. Hover on navigation bar was tested and is responsive.
    2. Checked each navigation option is connected and linked to relevant sections.
    3. Used appropriate styling such as padding and margin to center align the menu as intended, tested in responsive mode.
    4. Tested at lowest pixel count to check if the Bootstrap hamburger toggler is functional as intended.

2. Background Images / Section Styling:
    1. Tested the website on a lower brightness and found opacity to be too high - lowered opacity to retain image quality.
    2. Originally used a pastelle blue and mint font color for sections but this did not work well with images. Tested darker colors and changed font.
    3. Checked responsiveness and noticed bottom padding would change as text would push sections into other sections. Used media queries to set the text format.
    4. Lowered opactiy on headings and on Title background image for a better user experience, made sure all images are also related to section headings.

3. Bootstrap Carousel Slides with Prev/Next buttons:
    1. Tested the interval speed which was inconsistent, changed each slide transition to 7000ms.
    2. Buttons are working without any issues when tested. Increased size and made responsive to use on smaller screens.
    3. Icon seemed to small, so changed to a larger Bootstrap size.

4. Contact form:
    
    1. Tried and tested all fields to maintain a error message if the form is incorrectly filled in.
    2. Tried to submit without a real email address and received correct error.
    3. Created a confirmation button and tested if error appears if all data is filled in but checkbox is left out.
    4. Tested all form fields with correct information and submitted successfully.

My-Portfolio is a single scrolling page which works well on both Desktop screens, Ipad screens and most smartphones.

There was some issues for phones with a pixel count smaller then 350 pixels but I was unable enforce a media query as the content would be undermined.

## Bugs

1. White space underneath each section. 

    Fix: Set margin and padding to 0, used internal CSS to set max-width and margin size for Paragraphs.

2. Section heading borders overlapping when reducing screen size.

    Fix: Changed sections into fluid containders and utilised m-auto and reduces sizes of borders and text. Changed Section 2 into a span fit larger content.

3. Unable to change padding and margin for background images.

    Fix: Used display: flex instead of Position element to have more room for styling.

4. Excess padding on Navigation bar.

    Fix: used py-0 to reduce padding.

5. Carousel slides changing size based on content.

    Fix: Set an inline fixed height and width to keep the block the same size.

6. Previous/Next button are not aligned in the center of the Carousel:

    Fix: Added a negative top number to push buttons to a new position.

7. Navigation toggler is not collapsing properly.

    Fix: Reduced margin to 0 and changed height of navigation bar toggler to fit content.

## Deployment

1. Create a GitHub account on github.com.
2. Download either GitHub for Mac or GitHub for Windows or use the Browser version, whichever is convenient.
3. Log into Github in app or in browser.
4. "Install Command Line Tools", just in case you want to start using the command line later in life. This is for the app version.
5. Create a new repository in your GitHub application. Name it your-username.github.io. The name is very important. Note the folder that GitHub is saving the repository to. Make sure the "Push to GitHub?" box is checked.
6. Move your website's files into the folder that GitHub just created when you made the repository. You can add this manually or commit through a terminal push. IMPORTANT: Your homepage HTML file must be called "index.html", and it must exist in the top-level directory.
7. You should now see your files in the app or browser. In the app version you can click on commit summary and initial commit and publish repo to deploy.
8. For the browser version you should click on Settings and scroll down to "Github Pages" and change source to main and click save. This should deploy your webpage to Github Pages!


## Credits

Using flex instead of standard Position style

https://css-tricks.com/snippets/css/a-guide-to-flexbox/

Navbar customisation for toggler

https://docs.themeisle.com/article/442-how-to-change-hamburger-menu-color-dropdown-color-on-mobile-in-zerif

Parallax effect:

https://www.w3schools.com/howto/howto_css_parallax.asp

Navigation Bootstrap elements taken from:

https://getbootstrap.com/docs/4.4/components/navs/#horizontal-alignment

Ripple animation:

https://ianlunn.github.io/Hover/

Remove padding:

https://www.webdesignvista.com/how-to-decrease-the-height-of-navbar-on-bootstrap-4/#:~:text=To%20reduce%20height%20you%20need%20to%20remove%20padding%20on%20both.&text=This%20class%20sets%20padding%2Dtop,of%20navbar%20class%20to%200.&text=Thats%20it!

Carousel Bootstrap:

https://getbootstrap.com/docs/4.0/components/carousel/




### Media
Image source:

https://www.pexels.com/

### Acknowledgements

I received inspiration for the layout of my website from Traversy Media (https://www.youtube.com/watch?v=JttTcnidSdQ&ab_channel=TraversyMedia)