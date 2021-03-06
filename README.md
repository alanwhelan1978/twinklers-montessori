[CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png) 

[Link to Live Website](https://alanwhelan1978.github.io/twinklers-montessori/)

[GitHub Repo](https://github.com/alanwhelan1978/twinklers-montessori)

*** 

## About  

Twinklers Montessori is a website created for my PP1 project with Code Institute.
 
   
Twinklers Montessori is a business dedicated to the education of children aged from 2.5 years to school going age. This is owned by my sister in-law and the website will be used for the business. The client had full input in the design.

Twinklers Montessori needs to have a website to tell users a little bit about the business, show potential clients what services they offer.
***

## User Experience (UX)


## Strategy
### User Stories  

#### Reasons a user may visit the website
* A user looking for childcare and montessori schools in the area.
* A user who wants to get in contact.
* A user doing research on what we offer.

#### Reasons for the website
* Increase clients
* Showcase work
* Provide a way for new and existing clients to contact us.  

## Scope
#### What a user may expect
* Easy to navigate website 
* Good presentation and visually appealing regardless of screen size.
* Links and functions work as expected.
* Information about what Twinklers Montessori does.
* A way to get in contact with Twinklers Montessori.

#### What a user may want 
* To be able to find links to social media pages.
* To see examples of what the school does.
* Check availability of class places


#### As a developer / business I expect
* To provide information about Twinklers Montessori.
* To provide an easy way for new and existing clients to contact us.
* To provide an easy to navigate website with links that work as expected.
* To encourage clients to contact us for a more information. 
* Note that not all -What the user may wants- will be implamentedat this step in the business. Additional features may be added as the scope mandate changes and the buisness grows.

## Structure
The website will consist of 3 separate pages
* A home page with ???About???. 
* A ???Your Journey??? page with information on what your school time offers and what we do.  
* A page with a form to contact the business. 

## Home
![Home Page](/readme-files/home2.png)
* The home page gives a breif indroduction to the business
* Allows the user to navigate the rest of the site
* Provides information to the user as to what the site is for.

## Your Journey
![Your Journey](/readme-files/Journey2.png)
* The your journey page gives the user information on the Montessori experience
* Allows the user to see more of what the business offers
* Allows the user to navigate the rest of the site

## Contact Us
![Contact us](/readme-files/Contact2.png)
* The contact page allows the user to contact the business using a contact form
* It allows the user to see social media feed and like and meesage the sociall media page
* Allows the user to navigate the rest of the site

#### Colour

I have used blues as my main colour theme for the website. These are colors that the client selected as they use them in their other marketing collateral. Light blue for background and dark blue for text. This will help with Accessibility for visually impaired users.

#### Typography 

I have used https://fonts.google.com/ for my fonts.  I have chosen to use Roboto and Noto Sans JP as my main font throughout the website.  This is a fairly modern style that is easy to read at various sizes.

I imported the following code into the top of my style.css file

        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP&family=Roboto&display=swap');

#### Call to Action

I made all my call to actions as easy to see as possible. 

* The links in the Nav/Logo are highlighted using a underline when the mouse is hovered over them.
* Contact us form is simple and easy to us and makes it easy to get in touch and ask your question
### Imagery   

Due to the business being a school I had no images to use from the company as parental permission would of had to os been given. I looked for simple and eye-catching designs that showcased the fun behind learning.

***

### Wireframes

  -   #### Main Page Mockup

![Home](/readme-files/hpmockup.png)

  -   #### Your Journey Mockup

![Journey](/readme-files/yjmockup.png)

  -   #### Contact Page Mockup

![Contact](/readme-files/cpmockup.png)


## Features

#### Universal Features Across the Site

###### Logo and Navigation Bar
The Navigation Bar is at the top of the right of webpage. The nav links all underline when hovered over. The nav links direct the user to the correct page of the website. When the logo is clicked on it will take the user to the home page. When on smaller devices the nav goes underneath the logo and it is centred


###### Responsiveness

The page is scaled up and down for different screen resolutions to help the content stay neat. This has been done using media queries.
![Mockup](/readme-files/Responsive.png)


###### Accessibility

All images and navigations have an alt attributes or aria-label. This is to make the site easier to use for people with visual impairments by allowing them to navigate the site easily. There is high contrast used throughout the design. Header elements have been used in sequence so that the site makes semantic sense to screen readers. Links are consistent when hovered over. I have also set the font to rem so that if someone has their font settings higher for visibility the font size will increase accordingly.
![Mockup](/readme-files/Accessibility.png)

###### Footer 

The footer is split into 3 sections:. ???Opening Hours???, ???Contact Info??? and ???Social???. These scale up and down depending on device size.
 

##### Meta data


I have included descriptions, author, and keywords into the head element to increase traffic to the website. I have also labelled each page differently so that if the user has multiple tabs open it is easy to recognise each tab.
## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

-   [Google Fonts:](https://fonts.google.com/) was used to import the 'Roboto' and 'Noto-Sans-JP' fonts into the style.css file which are used on all pages of the project.
-   [Git:](https://git-scm.com/) was used for version control by utilising the Gitpod terminal to commit to Git and Push to GitHub.
-   [GitHub:](https://github.com/) is used as the respository for the projects code after being pushed from Git.

## Testing

### Validator Testing
The error showing on the contact page is from the facebook plugin

- [HTML Validator](https://validator.w3.org/)

    - result for index.html
      ![HTML results index](/readme-files/HTML-Home.png)
    - result for menu.html
      ![HTML results your-journey](/readme-files/HTML-Journey.png)
    - result for contact.html
      ![HTML results contact](/readme-files/HTML-Contact.png)

    - result for css
      ![CSS Validator](https://jigsaw.w3.org/css-validator/)


- result for style.css
      ![CSS results](/readme-files/CSS.png)

### Browser Compatibility

- Testing has been carried out on the following browsers :
    - Chrome
    - Firefox
    - Edge
    - Safari   

## Deployment

### How this site was deployed

- In the GitHub repository, navigate to the Settings tab, then choose Pages from the left hand menu 
- From the source section drop-down menu, select the Master Branch
- Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment
- Any changes pushed to the master branch will take effect on the live project

### How to clone the repository

- Go to the https://github.com/alanwhelan1978/twinklers-montessori repository on GitHub 
- Click the "Code" button to the right of the screen, click HTTPs and copy the link there
- Open a GitBash terminal and navigate to the directory where you want to locate the clone
- On the command line, type "git clone" then paste in the copied url and press the Enter key to begin the clone process

## Known Bugs 
* BUG -The code for the facebook plugin is showing up as an error on the html checker. 
 

## Acknowledgements

### Credit

* Brian Macharia- Mentor support, guidance, tips, and key things to look out for throughout the project. Helping me to check for errors and looking at my code. 
 

* [Code Institute SampleREADME](https://github.com/Code-Institute-Solutions/SampleREADME)
* [Code Institute README Template](https://github.com/Code-Institute-Solutions/readme-template)
* [W3schools](https://www.w3schools.com/) - for various code information and trouble shooting.
* [Google fonts](https://fonts.google.com/) - CDN for the fonts were used in the project.
* [Pexel](https://pexels.com/) All site images taken from Pexels -
* [HTML Validator](https://validator.w3.org/) - Testing validity of HTML.
* [CSS Validator](https://validator.w3.org/) -Testing validity of CSS.
* [Am I Responsive](http://ami.responsivedesign.is/#) - Checking the responsive nature.
* [Beautifer](https://beautifier.io/) - Allowing me beautify my code.
* [Facebook](https://facebook.com/) - for facebook plugin


*** 

### Code:

*  Facebook devolopers tools was used to get plugin for contact page.
<iframe src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FTwinklersMontessoriSchool&tabs=timeline&width=500&height=500&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true&appId" width="500" height="500" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"></iframe>
