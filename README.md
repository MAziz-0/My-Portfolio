<h1 align="center">My-Portfolio</h1>

A minimalistic approach to introducing who I am to a potential employer and displaying what I can bring to the table.

View the live project here: https://maziz-0.github.io/My-Portfolio/

## Getting Started

I have created the My-Portfolio website to showcase my experience in Frontend development. Using the Bootstrap framework alongside HTML and CSS, I made a minimalist and clean single scrolling web page that uses a dark theme. 
This website represents my new skillset and aesthetic choices, as I am a fool for the dark theme in all applications if the option exists. I have created a simple summary, and some Carousel slides to display what I have learnt. Some of the languages listed are what I intend to learn in due time.
Hopefully, this is one of the many projects I will undertake to create and add to the developer space.

<h2 align="center"><img src="https://user-images.githubusercontent.com/41737293/106295530-7977e500-6248-11eb-8464-bcdbf2adbe84.PNG"></h2>

## UX
 
### The main intention behind the user experience on this website is to appeal to potential employers who will need a Portfolio that is easily accessible and is intuitive in it's approach to promoting my soft/technical skills.

The ways I approached this:

1. Making sure that the main features used simple and intuitive. This has been achieved by using Parallax scrolling and Bootstap Carousel making a more responsive and dynamic website.

2. Sections and Paragraphs are delineated to show information easily. The use of dark backgrounds allows the text to pop and works with overall tone of the website.

3. Using a single scroll page to navigate three separate pages has allowed maximum efficiency and allows the user to stay on one page. Users can quickly view all the pages in a single scroll. Modern resumes tend to be short and concise; this inspired the website's design as this may be a potential selling point for an employer.

4. Images used in the background are relevant to each section's titles, which ties the whole website into a promotional statement.  I intend to generate appeal, so it was essential to making sure there is a synergy between the content and my design choices.

## Design
#### Colour Scheme
- The two main colours used are Black and Dark Turquoise.
#### Typography
- The Titillium Web font is the main font used throughout most of the website. Navigation and titles also utilise the Lato font.
#### Imagery
- Imagery is essential to this project. The extensive background hero images are designed to be striking and catch the user's attention and are relevant to each section. It also has a modern, chic aesthetic.

## User Stories

Target audience: Potential employer

#### I would like to get more information on who this person is.

The information displayed using the Carousel and Sections presents a short introduction on what type of employee I can expect and the developer's skills.

#### I would like to see there work history.

- A CV link has been added to the Navigation bar, which allows me to download a CV containing all the relevant information pertaining to work history.

#### Where can I find this person on other platforms to see what type of person they are.

- Provided multiple social links in the footer, which allows me to view the developer's profile on other platforms and, most importantly, their Github, which would display projects.

#### I want to work with this person; what is the best way to start working with them?

- A contact form has been provided so I can easily send in a project request or a job specification; alternatively, I can find the developer on other platforms via the social links provided.


## Wireframe:


![My-Portfolio Wireframe](https://user-images.githubusercontent.com/41737293/106295077-e63eaf80-6247-11eb-90ac-93dd1e333c4a.png)

### Lighthouse Report:

![Lighthouse](https://user-images.githubusercontent.com/41737293/106616454-7d1bac80-6565-11eb-88d9-ab1cf62bb9c1.PNG)

## Features

What methods I used to create a responsive and appealing website.
 
### Existing Features

- Feature 1 - The Bootstrap-based Navigation toggler utilised to ensure a navigation bar that is both stylish and responsive to modern websites and smartphones. When using the website on a low pixel count, the toggler uses the three-line toggle (also known as the hamburger toggler) to minimise the menu.
- Feature 2 - Using Parallax scrolling is a feature intended as a design choice to make the website appealing and easy on the eyes. Potential employers or fellow developers are the target audience, so I deemed it necessary to create a website that performs well and has aesthetic value.
- Feature 3 - Bootstrap Carousel was applied to create a modern and automated approach to displaying information; having a moving slide alongside a parallax scroll feature was used to make the website look more dynamic and animated and made it necessary to fit more information in a single scrolling page without having to link new pages.

## Technologies Used

- [HTML]
    - The project uses **HTML** to create the basic content

- [CSS]
    - The project uses **CSS** to style the HTML

- [Bootstrap]
    - The project uses **Bootstrap Framework** to utilise its highly optimised and customisable feature sets such as the Carousel.


- [GitHub]
    - GitHub is used to store the code of the project after being pushed from Git.

- [Balsamiq]
    - Balsamiq was used to create the wireframes during the design process.

- [Google Fonts]
    - Google fonts were used to import the 'Titillium Web' font into the style.css file, used on all pages throughout the project.



## Testing

1. Navigation Bar:
    1. Hover on navigation bar was tested and is responsive.
    2. Checked each navigation option is connected and linked to relevant sections.
    3. Used appropriate styling such as padding and margin to centre align the menu as intended, tested in responsive mode.
    4. Tested at lowest pixel count to check if the Bootstrap hamburger toggler is functioning as intended.

2. Background Images / Section Styling:
    1. Tested the website on a lower brightness and found opacity to be too high - lowered opacity to retain image quality.
    2. Originally used a pastel blue and mint font colour for sections, but this did not work well with images. Tested darker colours and changed the font.
    3. Checked responsiveness and noticed bottom padding would change as text would push sections into other sections. Used media queries to set the text format.
    4. Lowered opacity on headings, and the Title background image for a better user experience ensured all assets are also related to section headings.
    5. Added media query to disable parallax on mobile screen sizes as they do not work correctly.

3. Bootstrap Carousel Slides with Prev/Next buttons:
    1. Tested the inconsistent interval speed on each slide, changed each transition to 7000ms.
    2. Buttons are working without any issues when tested. Increased size and made responsive to use on smaller screens.
    3. Icon seemed too small, so I changed to a larger Bootstrap size.

4. Contact form:
    
    1. Tried and tested all fields to maintain an error message when incorrect details are provided.
    2. Tried to submit without an actual email address and received an error.
    4. Tested all form fields with correct information and submitted them successfully.

    ## Bugs

- White space underneath each section. 

   - Fix: Set margin and padding to 0, used internal CSS to set max-width and margin size for Paragraphs.

- Section heading borders overlapping when reducing screen size.

   - Fix: Changed sections into fluid containers and utilised m-auto and reduces sizes of borders and text. Section 2 changed into a span to fit more extensive content.

- Unable to change padding and margin for background images.

   - Fix: Used display: flex instead of Position element to have more room for styling.

- Excess padding on the Navigation bar.

   - Fix: used py-0 to reduce padding.

- Carousel slides changing size based on content.

   - Fix: Set an inline fixed height and width to keep the block the same size.

- Previous/Next button unaligned in the centre of the Carousel:

   - Fix: Added a negative top number to push buttons to a new position.

- Navigation toggler is not collapsing correctly.

   -  Fix: Reduced margin to 0 and changed the height of navigation bar toggle to fit the content.

- Parallax feature does not work well on mobile devices.

   -  Fix: Added a media query to disable the feature on mobile screen sizes.


 
## Validator Tools

 This website tested using HTML/CSS validator tools:

https://validator.w3.org/

https://jigsaw.w3.org/css-validator/

HTML/CSS formatted: 

https://webformatter.com/




## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps.

1. Log in to GitHub and locate the relevant Repository.
2. At the top of the Repository (not top of page), find the "Settings" button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository, we make a copy of the original Repository on our GitHub account to view and/or make changes without affecting the original Repository by using the following steps.

1. Log in to GitHub and locate the relevant Repository.
2. At the top of the Repository (not top of page), just above the "Settings" button on the menu, locate the "Fork" button.
3. You should now have a copy of the original Repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the relevant Repository.
2. Under the repository name, click "Clone or download".
3. To clone the Repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

## Credits

Using flex instead of standard Position style

https://css-tricks.com/snippets/css/a-guide-to-flexbox/

Navbar customisation for toggler

https://docs.themeisle.com/article/442-how-to-change-hamburger-menu-color-dropdown-color-on-mobile-in-zerif

Parallax effect:

https://www.w3schools.com/howto/howto_css_parallax.asp

Navigation Bootstrap elements are sourced from:

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