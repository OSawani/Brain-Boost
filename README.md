# Brain Boost - Lifehacks for Optimizing Brain Health
![Brain Boost Logo](./assets/images/logo-1.png)
Recent advancements in neuroscience illuminate the brain's incredible capacity for change, growth, and resilience. Discover how you can tap into these insights and optimize your cognitive prowess.

## Code Institute - First Milestone Project: User Centric Frontend Development



# Table of Contents
- [Brain Boost - Lifehacks for Optimizing Brain Health](#brain-boost---lifehacks-for-optimizing-brain-health)
  - [Code Institute - First Milestone Project: User Centric Frontend Development](#code-institute---first-milestone-project-user-centric-frontend-development)
- [Table of Contents](#table-of-contents)
  - [Inspiration](#inspiration)
  - [Motivation](#motivation)
  - [Demo](#demo)
    - [The website is hosted using github pages and can be found here](#the-website-is-hosted-using-github-pages-and-can-be-found-here)
  - [UX - Experience Planes](#ux---experience-planes)
    - [Strategy](#strategy)
      - [User Needs](#user-needs)
      - [Business Needs](#business-needs)
    - [Scope](#scope)
      - [Functional Specifications](#functional-specifications)
      - [Content Requirements](#content-requirements)
    - [Structure](#structure)
    - [Skeleton](#skeleton)
    - [Surface](#surface)
  - [Technologies](#technologies)
  - [Features](#features)
    - [MVP Features](#mvp-features)
    - [Features To Be Develped](#features-to-be-develped)
  - [Testing](#testing)
    - [Validator Testing](#validator-testing)
    - [Bugs](#bugs)
  - [Deployment](#deployment)
  - [Credits](#credits)
    - [Content](#content)
    - [Media](#media)
    - [Acknowledgements](#acknowledgements)

## Inspiration
hbrekbekbv

## Motivation
ejrghekjgvre

## Demo

![Website look on mobile & desktop](./assets/images/demo/Laptop2.png ./assets/images/demo/Laptop.png ./assets/images/demo/Mobile.png ./assets/images/demo/Mobile2.png)

### The website is hosted using github pages and can be found [here](https://osawani.github.io/Brain-Boost/)

## UX - Experience Planes
ergerg

### Strategy
kjebvger

#### User Needs
egrerge

#### Business Needs
egre

### Scope
ergergrg

#### Functional Specifications
efreregr

#### Content Requirements
regergerg

### Structure
erbfkerfv

### Skeleton
regerger

### Surface
ergergerf

## Technologies

1. Wireframing was done using Figma & Balsamiq.
2. HTML5 was utilised to place structural elements that are semantically sound alongside attributes for SEO & accessibility
3. Vanilla CSS was used to create a minimalistic style for the html elements

## Features

### MVP Features

* **Navigation Bar**
  - The navigation bar is at the top of the page, and it is fixed to the top. The logo is in the left-hand corner of the navigation, and it links to the index.html page.
  - The other navigation links on the website are to the right. Home, Experience, Education, Skills, and Contact connect to different sections of the same page. Download CV is a link embedded in a pdf that will download the traditional CV to the device on which the website is open.
  - The font color is in contrast with the navigation background color. The hover effect is used for navigation, so the user can know which page they are on.
  - The different sections of the navigation are under the same heading as a traditional CV. Users can easily understand what information is contained in different sections.


- **Home**
  - As the background image, an image of me (Anjalee Kulasinghe) has been used. On top of the image, I have used a flat color overlay with opacity.
  - There is a brief introduction to Anjalee Kulasinghe (me) with a simple animation used to give a welcome to the site.
  


- **Brain Lifehacks - Brain Food**
  - In the 

- **Brain Lifehacks - Brain Fitness**
  - In the E

- **Brain Lifehacks - Brain Building**
  - In this section, 

- **Contact**
  - In the Contact 


- **Footer**
  - This section includes the social media links 

### Features To Be Develped

In the future,
- I would like to add 

## Testing

* I tested the site, and it works in different web browsers: Chrome, Firefox, and Microsoft Edge.
- On mobile devices, I tested the my site on a Samsung Galaxy S23 Ultra with the Samsung browser and an iPhone SE with the Safari browser.
- I confirmed that the site is responsive and functions on different screen sizes using the devtools device toolbar.
- I confirmed that the navigation and the sections Home, Experience, Education, Skills, and Contact are readable and easy to understand.
- I confirmed that the form works: it requires entries in every field, only accepts an email in the email field, and both the submit and reset buttons work.
- I confirmed that the Download CV link will download the pdf copy of the traditional CV to the device on which the site is open.

### Validator Testing

* **HTML**
  No errors were returned when passing through the official [W3C validator](./assets/readme-assets/validator_result_html.PNG)

- **CSS**
  No errors were found when passing through the official [(Jigsaw) validator](./assets/readme-assets/css-validator_result.PNG)
  
- **Accessibility**
  I confirmed that the colors and fonts chosen are easy to read and accessible by running it through [Lighthouse DevTools](./assets/readme-assets/site_accessibility.PNG)

### Bugs

* **Solved bugs**
  - When I deployed my project to GitHub pages, I found that my project was broken; the links to the other files (CSS and images) did not work.
  - My mentor showed me this had happened since I have used the file paths in the following way:
        `<link rel="stylesheet" href="/assets/css/style.css">`
  - Adding a '.' to the start of the file path fixed the problem.
        `<link rel="stylesheet" href="./assets/css/style.css">`

  - When I was fixing my site to be responsive, I found out that in the 'Contact Me' section, the contact form does not go below the screen when the screen is small.
  - This has happened since I have used `<display: flex;>`.
  - Changing flex to block fixed the problem `<display: block;>`.
  
- **Unfixed Bugs**

When I checked my site on a Samsung Galaxy S23 Ultra with the Samsung browser, I found out that the navigation was not responsive properly. Even though the navigation is fixed to the top, it is sometimes hidden in the address bar. I have to pull it down when I need to use the navigation bar.

## Deployment

* The site was deployed to Git Hub pages using the following steps:
  - In the Github repository, the Stetting tab.
  - Under General, navigate to Code and Automation and select 'Pages'.
  - In the Build and Deployment section for Source, select 'Deploy from a branch' from the drop-down list.
  - For Branch, select 'main' from the drop-down list and Save.
  - On the top of the page, the link to the complete website is provided.
  
  - The deployed site will update automatically upon new commits to the master branch.

## Credits

### Content

* Icons were taken from flaticon:
* - 
* - 
* - 
* - 
* -
* -
* -



### Media

- Icons were taken from flaticon:
  * -
  * -
  * -
  * -
  * -
  * -
  * -

### Acknowledgements

* Ideas were taken from the Code Institute's Coffee House and Love Running projects.
- My mentor, Medale Oluwafemi, for his guidance.
