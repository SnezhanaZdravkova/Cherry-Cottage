![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Cherry Cottage
## Site Purpose

The project is a website for `Cherry Cottage` - a rural business providing the following services for visitors:
- Electric car owners how need to charge their batterys (charging point)
- Free hot coffee while they wait
- Free fast wifi is availble
- We are also a poultry farm, where children and parents can visit and see how poultry is raised.

Users of this website will be able to find all the information about Cherry Cottage, where it is located, what services they can find here, information about charging points, and also contact the site owner, through a contact form to reserve a charging point, buy poultry products or visit the farm.

The site owner hopes to increase visitors to the farm, and will use this site to advertise and showcase services and future activites, as well as providing the ability to accept bookings and orders for products.

This website was built using the knowledge gained from the HTML, CSS and User Centric Design modules on the Code Institute Full Stack Software Development programme.

A full list of technologies used can be found in the technologies section of this document.


A live preview of the website can be found [here](https://snezhanazdravkova.github.io/Cherry-Cottage/).

# Cherry Cottage Responsive Website


![Screenshot](/assets/css/images/screenshots/Screenshot%20(2).png)


https://techsini.com/multi-mockup/
The multi device website mockup generator online tool above have been used to render preview images on a selection of Apple devices.

`Cherry Cottage` is a fully responsive website that can be viewed on a range of devices including smartphones, tablets and desktop computers.

# User Experience Design


## Visitor Goals

- As a user, I want to be able to navigate the site to find what I need easily.
- As a user, I want to learn more about the farm.
- As a user, I want to learn about what I can do at the farm and what facilities are avaiable there.
- As a user, I want to view the website and content clearly on a range of devices including mobiles and desktops.
- As a user, I want an easy way to contact the site owner and arrange to use the services avaialble.
- As a user, I want to book a visit to the farm.
- As a user, I want to book a charging point.
- As a user, I want to order poultry products for collection.
- As a user, I want to share the site on Social Media.



## Structure

All Pages will contain a Navigation menu at the top of the Webpage that directs them to a new Page to easily allow users to navigate the site easily.

​The Nav Menu will be collapsable on a Mobile device to make use of space on smaller devices. The purpose of this is to fulfill user story:
​
> - As a user, I want to be able to navigate the site to find what I need easily.
​
The Home Page will contain a small bio about the place. The purpose of this is to fulfill user stories:
​
> - As a user, I want to learn more about the farm.
> - As a user, I want to learn about what I can do at the farm and what facilities are avaiable there.
​
Custom CSS and/or Bootstrap will be used to make the Website responsive by the use of media queries and/or the Boostrap Grid system.
​
All pages will be responsive and the layouts will change dependant on screen size. This is to ensure content flow works, images are displayed properly and that the content is readable. The purpose of this is to fulfill user story:
​
- As a user, I want to view the website and content clearly on a range of devices including mobiles and desktops.


The site will contain a contact form. The purpose of this is to fulfill user stories:

> - As a user, I want an easy way to contact the site owner and arrange to use the services avaialble.
> - As a user, I want to book a visit to the farm.
> - As a user, I want to book a charging point.
> - As a user, I want to order poultry products for collection.
​
The About Page will contain information about the farm and it's owners. Information and images will be updated regularly. This page is to help implement user story:
​
> - As a user, I want to learn more about the farm.
> - As a user, I want to learn about what I can do at the farm and what facilities are avaiable there.
​
The Charging Point page will contain information about the electric car charging point. This page is to help implement user story:
​
> - As a user, I want to learn about what I can do at the farm and what facilities are avaiable there.
> - As a user, I want to book a charging point.
​
All pages will contain a footer containing Social Media icons. The icons are from font-awesome. The aim of the Footer elements are to fulfill user stories:

> - As a user, I want to share the site on Social Media.

## Design

### Colour Scheme

The two main colours used are Green rgba(36, 128, 0, 0.27) and an off-shade of Black rgba(0, 0, 0, .1) as well as black for the text as these colours are similar to the grass colours and the farm. The green and off black shade should compliment each other without being over powering to the eyes.  It provides good contrast which improves the accessibility of the site for visually impraired users.


### Typography

The headers on all pages throughout the Website are using the Oswald font while the main text is using the Lato font.  These are clear, highly readable fonts which make it easy to read for all users on a range of devices.  They are also commonly supported on most browsers.



## Wireframes

Wireframes showing the layout of the various HTML elements to be added here.

## Features


- Navigation bar - allows users to easily navigate the site
- Home Button - return to the home page at any time
- Contact Form - This can be completed on the signup.html page and used for contacting the farm with any queries users may have
- Social sharing icons - share content on popular social media networks


# Technologies
- `HTML`
This project uses HTML as the main language used to complete the structure of the Website.
- `CSS`
This project uses custom written CSS to style the Website.
- `Font Awesome`
Font awesome Icons are used with some of the titles and for the Social media links contained in the in the Footer section of the website.
- `Google Fonts`
Google fonts are used throughout the project to import the Lato and Oswald fonts.
- `GitPod`
GitPod is the Integrated Development Environment used to develop the Website.
- `GitHub`
GithHub is the hosting site used to store the source code for the Website and Git Pages is used for the deployment of the live site.
- `Git`
Git is used as version control software to commit and push code to the GitHub repository where the source code is stored.
- `Google Chrome Developer Tools`
Google chromes built in developer tools are used to inspect page elements and help debug issues with the site layout and test different CSS styles.
- `Balsamiq Wireframes`
This was used to create wireframes for 'The Skeleton Plane' stage of UX design.
MS PAINT

- `Techsini`
tecnisih.com Multi Device Website Mockup Generator was used to create the Mock up image in this README



## Test Strategy
### Summary
Manual and validation testing has been carried out on the Cherry Cottage Website:

- As this project is static and contains no back-end functionality, testing is limited to the visual style and layout of the Website.
​
- Elements should not overlap
​
- All nav links should link to the correct html pages and external links will open in a new broswer tab



The live Project can be found [here](https://snezhanazdravkova.github.io/Cherry-Cottage/).



## Test Results

All Pages were run through the `W3C HTML Validator` and showed no errors.
- [index.html](/assets/css/images/screenshots/index.png)
- [poultry.html](/assets/css/images/screenshots/poultry.png)
- [form.html](/assets/css/images/screenshots/signup.png)

CSS Stylesheet was run through the` W3C CSS Validator` and showed no errors.
- [style.css](/assets/css/images/screenshots/css.png)

Lighthouse Test

![Lighthouse-test](/assets/css/images/screenshots/lighthouse-test.png)

Website was tested by running locally and tested on the deployed version. No differences found.

Elements on the page were tested manually by clicking on each element and verifying that the correct functionality occurred.  Functional tests were tested on Safari, Chrome and Firefox browsers.  No issues were found.


## Deployment

## Project Creation

The project was started by navigating to the CI provided template and clicking 'Use this template'. Under Repository name I input `Cherry Cottage` and checked the Include all branches checkbox. I then navigated to the new repository. I then clicked the Code drop down and selected HTTPS and copied the link to the clipboard.
Opening a bash terminal in Visual studio code I then typed git clone link from clipboard followed by open folder and navigating to the newly created local repository. The following commands were used throughout the project:
​
- `git add filename` - This command was used to add fils to the staging area before commiting.
- `git commit -m commit message explaining the updates` - This command was used to commit changes to the local repository.
- `git push` - This command is used to push all commited changes to the GitHub repository.
- `git status` - This comand is used to check is there any new or modifyed files.

## Using Github Pages
- Navigate to the GitHub Repository:
- Click the 'Settings' Tab.
- Scroll Down to the Git Hub Pages Heading.
- Select 'Main Branch' as the source.
- Click the Save button.
- Click on the link to go to the live deployed page.

## Run Locally
- Navigate to the GitHub Repository:
- Click the Code drop down menu.
- Either Download the ZIP file, or Copy Git URL from the HTTPS dialogue box.
- Open your developement editor of choice and open a terminal window in a directory of your choice.
- Use the `git clone` command in terminal followed by the copied git URL.
- A clone of the project will be created locally on your machine.


## Credits

- Media
- The photos used are taken from [Pexsels](https://www.pexels.com/photo/white-and-brown-house-near-green-grass-field-11495863/)
- The icons are taken [Font-Awesome](script src="https://kit.fontawesome.com/ac5db2b5b6.js" crossorigin="anonymous"></script), according to the terms in their [license](https://www.pexels.com/license/)
- The idea for main image cover text and the Footer is from `Love Running` project

## Acknowledgements

- I would like to thank my mentor Ronan for his guidance throughout my project and his advice.
- I would like to thank Code Institute for giving me chance to learn codding.
- I would like to thank @Daisy-McG as I learned from her how to write good documenation for this project. 
