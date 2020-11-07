# Milestone Project One
[Portfolio](assets/readme/preview.jpg)
## Personal Portfolio

    Welcome to my first milestone project! For this project I chose to create a personal portfolio. My 
    reasoning for this selection is based on the fact that I can use this project to come back to as I 
    progress through the [Code Institute](https://codeinstitute.net) and display my work in the "Projects"     
    section of this page.

    After researching full stack developer portfolios online (Google and YouTube), I noticed almost all 
    developers implement a single page design. I personally like this design and chose to follow what 
    seems to be the "norm" in this category.

### Table of contents:
1. [Description](#Description),
2. [UX](#UX)
    1. [Logo](#Logo)
    2. [Wireframes](#Wireframes)
    3. [User Stories](#User-Stories) 
    4. [Information Architectures](#Information-Architectures)
    5. [Responsive](#Responsive)
    6. [Frameworks](#Frameworks)
    7. [Typography](#Typography)
    8. [Colors](#Colors)
    9. [Icons](#Icons)
3. [Features](#Features)
    1. [Existing Features](#Existing-Features)
    2. [Future Features](#Future-Features)
4. [Technologies Used](#Technologies-Used)
5. [Testing](#Testing)
6. [Deployment](#Deployment)
    1. [Local Deployment](#Local-Deployment)
    2. [Remote Deployment](#Remote-Deployment)
7. [Credits](#Credits)
    1. [Media](#Media)
    2. [Content](#Content)
    3. [Acknowledgements](#Acknowledgements)

## Description
    This development is a personal portfolio page. The aim of this project is to convey my experience to a potential 
    recruiter. At this point in time, I have added two "placeholder" projects, which will be replaced by real projects
    as I progress through the course at Code Institute. Ultimately I will add further features to this page in the 
    future, such as pagination style feature for projects. 
    
    I have also added a basic contact me form which at this point in time does not work. A future update will enable
    this feature using an API.
---------------
## UX
    Being a front end development, UX was extremely important. Easy access to information via easy to find 
    links, as well as creating a relaxed, yet professional design was possibly the most important feature 
    of this project. Below I will discuss more in detail about specific UX features and design elements which 
    allowed me to achieve the design I wanted to create.

### Logo
    As branding is such a huge part of sales and promotion, I wanted to create a simple, yet professional
    looking logo to keep this logo specific to this particular page the two forward slashes are the same color 
    as the main theme color (R:240, G:95, B:64).

### Wireframes

    Alternatively you can navigate to the Assets folder, then open the Readme folder for all assets contained
    within this Readme file.

### User Stories
Being **one of**, if not **the most** important features of development is understanding firstly _who_ the user is & then 

_what_ the user wants. In this case the user is likely a recruiter, who is viewing this page looking for further information 

about a potential job applicant. With that in mind I have added some relevent user stories below.

Being a personal portfolio the following user stories apply:
As a user I want to:
* Know who John O'Brien is?
* What experience does John O'Brien have?
* What projects has John O'Brien completed?
* What services can John O'Brien add to our company?
* Download a CV.
* Access social media.
* Contact John O'Brien

### Information Architectures

Located on the top right of the page (on desktops) or underneath the welcome message (for tablets & mobile devices) 

is a button to download my CV. This means this document is immediately available to a potential recruiter. They may simply 

download my CV and leave the website if they wish.

Scrolling down from the welome section a user will encounter a number of sections, I aimed to keep sections short (on 

purpose) to avoid an overload of information. This design concept also allows a user to see clearly that there is another 

section, this allows the page to flow easily from one section to the next, picking up useful 
information along the way.

From anywhere on this portfolio page, you can get to any information in no more than 3 clicks.

### Responsive

    There are a lot of responsive design elements to this project. Firstly the navbar will compress depending on 
    the user device. 

    The button to download my CV contained within the navbar will only appear there on larger screens. On 
    smaller screens this button will be made available within the welcome area in the center of the page.

    All sections are contained in self collapsing bootstrap layouts which will reposition areas within sections 
    as screen size gets smaller.

### Frameworks

    Adding to this project are the frameworks of both Bootstrap and jQuery. These frameworks form the structural
    layout of the page, as well as provide the modal form.

### Typography

    For this project the main typography is Roboto, with a backup typography of Sans Serif.

### Colors
    The main color of this page is rgba(240, 95, 64), this color is used in repetition, it is included in every 
    section of this page and is also contained within the logo.

### Icons
    Logos are placed in multiple locations on this page. They are all supplied via FontAwesome CDN.

--------------------
## Features

### Existing Features

    Currently this project has several features incluing a modal popup, links to download my CV and a lot of 
    interactive features using css hover effects.

### Future Features
    In future this portfolio will include a working form. I will also update the projects section to include 
    future projects and showcase them.
    
------------------
## Technologies Used
    For this project HTML & CSS were used, as well as Bootstrap and jQuery via CDN.
---------------------
## Testing
To test this project I first used [W3C_validator](https://validator.w3.org/) to check all HTML, I then checked all of the CSS via the [W3C_Validation](https://jigsaw.w3.org/css-validator/).

Once these resources confirmed no errors in the code of the project, I then used "lighthouse" in the Google Chrome

dev tools to ensure compliance across all categories.

PLACE AN IMAGE HERE

--------------------
## Deployment
### Local Deployment
To deploy this project on your local system, you can follow these steps:

1. Navigate to my GitHub repository which can be found [here](https://github.com/J-O-B/portfolio).
2. Above the files there is a button with a download symbol and the text "Code"
3. Once you click the button "Code" you will have an option to "Download ZIP"
4. Download the ZIP file and extract the folder on your local computer.
5. Open the index.html to deploy this website locally.
**Please note that all files and folders must be kept in their original locations (folders) for page links (to internal**

**resources such as images) to work. External links to social media etc. will work regardless.**

    
### Remote Deployment
To deploy this project remotely, you can follow these steps:
1. Navigate to my GitHub repository which can be found [here](https://github.com/J-O-B/portfolio).
2. Close to the top of the page there is a navigation bar, the first item here is "<>Code", the last item is "Settings".
3. Click on settings
4. Scroll down the page until you find the section labelled "GitHub Pages"
5. The first item in GitHub Pages is "Source", click the associated dropdown button labelled "None". 
6. You will now have to select "master" as the source.
7. Once you have selected "master" click the "Save" button. 
8. The page should now refresh so you may have to scroll back down to "GitHub Pages".
9. Now you will see a link presented which should look like this https://j-o-b.github.io/portfolio/.
----------------------
## Credits
    Although most of the content and code in this project is my own, I have also used code snippets from bootstrap, 
    for example the modal popup is the standard bootstrap modal which was then changed to hold the "my coding" section.
    
    The narbar is based on the same navbar which was used in Whiskey Drop.
    The footer layout is based on the footer section used in the Resume tutorial.
    The modal feature is based on a code snipped from Bootstrap Documentation.
    The "feature" section of my CSS is original yet based on a tutorial from W3Schools.com
    

### Media
Background Image - [Pixabay Stock & Royalty Free Image](https://pixabay.com)

Whiskey Glass Image - [Pixabay Stock & Royalty Free Image](https://pixabay.com)

Logo Image - [WIX](https://www.wix.com/logo/maker)
### Content
    All of the text content in this project is original content. 

### Acknowledgements
    I would like to acknowledge both my mentor 
