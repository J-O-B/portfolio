# Milestone Project One
![Portfolio](assets/readme/Preview.jpg)
## Personal Portfolio

Welcome to my first milestone project! For this project I chose to create a personal portfolio. My 
    reasoning for this selection is based on the fact that I can use this project to come back to as I 
    progress through [Code Institute](https://codeinstitute.net) and display my work in the "Projects"     
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
    5. [Responsive Design](#Responsive-Design)
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

## **Description**
This development is a personal portfolio page. The aim of this project is to convey my experience to a potential 
    recruiter. At this point in time, I have added two "placeholder" projects, which will be replaced by real projects
    as I progress through the course at Code Institute. This project is designed in such a way that the structure can easily be 
    added to, or modified in the future for simplification of future updates.
    
---------------
## **UX**
Being a front end development, UX was extremely important. Easy access to information via easy to find 
    links, as well as creating a relaxed, yet professional design was possibly the most important feature 
    of this project. Below I will discuss more in detail about specific UX features and design elements which 
    allowed me to achieve the design I wanted to create.

### <ins>**_Logo_**</ins>
As branding is such a huge part of sales and promotion, I wanted to create a simple, yet professional
    looking logo. To keep this logo specific to this particular page the two forward slashes are the same color 
    as the main theme color (R:240, G:95, B:64). 

### <ins>**_Wireframes_**</ins>
You can view the wireframe designs [here](assets/readme/wireframe_design.pdf)

Alternatively you can navigate to the Assets folder, then open the Readme folder for all assets contained
    within this Readme file.

### <ins>**_User Stories_**</ins>
Being **one of**, if not **the most** important features of development is understanding firstly _who_ the user is & then 
_what_ the user wants. In this case the user is likely a recruiter, who is viewing this page looking for further information 
about a potential job applicant. With that in mind I have added some relevent user stories below.

Being a personal portfolio the following user stories specific to this project are:
* **As a user I want to:** *Know who John is?*
* **As a user I want to:** *Know what experience John has?*
* **As a user I want to:** *Know what projects John has worked on / completed?*
* **As a user I want to:** *Know what services can John O'Brien add to our company?*
* **As a user I want to:** *Download a CV.*
* **As a user I want to:** *View John's social media.*
* **As a user I want to:** *Contact John.*

### <ins>**_Information Architectures_**</ins>

Located on the top right of the page (on desktops) or underneath the welcome message (for tablets & mobile devices) 
is a button to download my CV. This means this document is immediately available to a potential recruiter. They may simply 
download my CV and leave the website if they wish.

Scrolling down from the welome section a user will encounter a number of sections, I aimed to keep sections short (on 
purpose) to avoid an overload of information. This design concept also allows a user to see clearly that there is another 
section, this allows the page to flow easily from one section to the next, picking up useful 
information along the way.

From anywhere on this portfolio page, you can get to any information in no more than 3 clicks.

### <ins>**_Responsive Design:_**</ins>
Each section of this project is responsive. All sections are contained within collapsable sections to allow a great user experience
regardless of the platform they are using to access the page.

Navbar:
> The navbar area contains a logo, text links & a button on desktops. This becomes a logo and text links on tablet devices. 
Finally this section further collapses into a logo and 'burger' menu icon for mobile devices with a dropdown menu for links.
The button that is available on desktop only will reposition to display under the 'welcome' section on tablet & mobile.

Sections:
> Each section is designed so that the layouts will change depending on device width. This means that a section, such as "projects"
will display as single blocks on mobile, where as on larger screens, the same projects will display in a '2 per line' style.

Social Media Sidebar:
> This section originally appeared on all devices, however after seeing how this displayed on smaller screens, I decided to exclude 
this feature from smaller screens. This was acceptable in my opinion, as social media links are available in other locations too, so 
this does not change the user experience in a detrimental way.

Footer:
> The footer is also fully responsive, showing in a similar fashion on both desktop and tablet. When a user is using a mobile device,
the footer section will automatically switch to a 1 block per line format. This means that across all devices, information is easy to 
view, and for touch screen users, links will be easy to select.

### <ins>**_Frameworks:_**</ins>

Adding to this project are the frameworks of both Bootstrap and jQuery. These frameworks form the structural
    layout of the page, as well as provide the modal form.

### <ins>**_Typography_**</ins>

For this project the main typography is Roboto, with a backup typography of Sans Serif.

### <ins>**_Colors_**</ins>
The main color of this page is rgba(240, 95, 64), this color is used in repetition, it is included in every section of this page and is 
also contained within the logo.

### <ins>**_Icons_**</ins>
Logos are placed in multiple locations on this page. They are all supplied via FontAwesome CDN.

--------------------
## **Features**

### <ins>**_Existing Features_**</ins>

Currently this project has several features incluing a modal popup, links to download my CV and a lot of 
interactive features using css hover effects. 

I have also included features that are layered using Z-Index, this allowed me to include the back to top feature
as well as the social media sidebar.

### <ins>**_Future Features_**</ins>
In future this portfolio will include a working form. I will also update the projects section to include 
future projects and showcase them.
    
------------------
## **Technologies Used**
For this project HTML & CSS were used, as well as Bootstrap and jQuery via CDN.

---------------------
## **Testing**
To test this project I first used [W3C_validator](https://validator.w3.org/) to check all HTML, I then checked all of the CSS via the [W3C_Validation](https://jigsaw.w3.org/css-validator/).

Adding to these tests, I used dev tools in my browser (Chrome) to see specific areas that I wanted to change. As this project is a front end project, the majority of my testing 
was that of design and the use of dev tools to achieve this.

Once these resources confirmed no errors in the code of the project, I then used "lighthouse" in the Google Chrome
dev tools to ensure compliance across all categories. 

![Lighthouse Test](assets/readme/lighthouse.jpg)

Performance:
> To boost my performance score, I have changed all my images to .jpg format, as well as lowered their size, but not to a point that changed their overall quality. This
is why my performance score is 83 and not higher. I was not willing to lower the quality of the design element of my page to improve this score.

Accessibility:
> To achieve this score I have added ALT text to all images, as well as 'screen reader only' notes where needed.

Best Practices:
> Unfortunately this section seemed to pick up that my logo should have been bigger, even though my logo is sized specific to this project and is therefore displayed at
100%. Once again, I chose that the design feature of having my logo was more important than raising this section to 100%.

SEO:
> Being a basic HTML document this project follows the basic SEO principles including a meta description, a favicon and other basic SEO principles.

--------------------
## **Deployment**
### <ins>**_Local Deployment:_**</ins>
To deploy this project on your local system, you can follow these steps:

> 1. Navigate to my GitHub repository which can be found [here](https://github.com/J-O-B/portfolio).
>2. Above the files there is a button with a download symbol and the text "Code"
>3. Once you click the button "Code" you will have an option to "Download ZIP"
>4. Download the ZIP file and extract the folder on your local computer.
>5. Open the index.html to deploy this website locally.

**Please note that all files and folders must be kept in their original locations (folders) for page links (to internal resources such as images) to work. External links to social media etc. will work regardless.**

    
### <ins>**_Remote Deployment:_**</ins>
To deploy this project remotely, you can follow these steps:
>1. Navigate to my GitHub repository which can be found [here](https://github.com/J-O-B/portfolio).
>2. Close to the top of the page there is a navigation bar, the first item here is "<>Code", the last item is "Settings".
>3. Click on settings
>4. Scroll down the page until you find the section labelled "GitHub Pages"
>5. The first item in GitHub Pages is "Source", click the associated dropdown button labelled "None". 
>6. You will now have to select "master" as the source.
>7. Once you have selected "master" click the "Save" button. 
>8. The page should now refresh so you may have to scroll back down to "GitHub Pages".
>9. Now you will see a link presented which should look like this https://j-o-b.github.io/portfolio/.
----------------------
## **Credits**
Although most of the content and code in this project is my own, I have also used code snippets from bootstrap, 
    for example the modal popup is the standard bootstrap modal which was then changed to the specifications I wanted.
    
>* The narbar is based on the same navbar which was used in Whiskey Drop.
>* The footer layout is based on the footer section used in the Resume tutorial.
>* The modal feature is based on a code snipped from [Bootstrap Documentation](https://getbootstrap.com/docs/4.5/components/modal/).
>* The "feature" section of my CSS is original yet based on a tutorial from W3Schools.com
    

### <ins>**_Media:_**</ins>
>Background Image - [Pixabay Stock & Royalty Free Image](https://pixabay.com)
>
>Whiskey Glass Image - [Pixabay Stock & Royalty Free Image](https://pixabay.com)
>
>Full Stack Image - [Pixabay Stock & Royalty Free Image](https://pixabay.com)
>
>Content Writing Image - [Pixabay Stock & Royalty Free Image](https://pixabay.com)
>
>SEO Image - [Pixabay Stock & Royalty Free Image](https://pixabay.com)
>
>Graphic Design Image - [Pixabay Stock & Royalty Free Image](https://pixabay.com)
>
>Logo - [WIX Logo Maker](https://www.wix.com/logo/maker)
### <ins>**_Content:_**</ins>
All of the text content in this project is original content. See above for image credits & acknowledgements.

### <ins>**_Acknowledgements:_**</ins>
I would like to acknowledge both my mentor <ins>Caleb Mbakwe</ins> for his tips during this project. I would also like to thank 
<ins>Matt Rudge</ins> for his tutorial on Bootstrap, which this project is dependent on.
