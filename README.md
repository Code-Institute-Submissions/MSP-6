# Personal Website
The purpose of Milestone Project 1 is to create a personal portfolio for Courtney Marshall.

# Project Summary

The Project will enable a user to view:
-	Employment history
-	Education/certificates
-	Projects/skills
-	Affiliations
-	Contact

It will be user friendly across multiple devices.

![Multi Device Preview](https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/final/multipc.PNG)


## Benefits and Rational

Such a website will:
-	enable recruiters / potential employers to view Courtney Marshall details in a single location,
-	provide simple ability for users to validate certificates obtained by Courtney Marshall
-	provide a centralised location for all publicly available coding examples

## User Stories

Below is a high-level list of User Stories for the purposes of development, testing and delivery.

Business Case User stories:
-	As a User I want to easily determine Courtney’s Work History
-	As a User I want to easily determine Courtney’s Educational achievements
-	As a User I want to easily view Courtney’s Portfolio
-	As a User I want to easily determine what groups Courtney is affiliated with
-	As a User I want to easily determine where content has been obtained from (if from, or maintained on, external sources)
-	As a User I want to easily identify which page of the site I am on at any given time
-	As a User I want to easily be able to contact Courtney.
-	As a User I want to easily verify the validity of Courtney’s listed certifications

Functional User stories:
-	As a User I want all external links to open in a new browser tab
-	As a Visually impaired user I want to know that all non-text elements have planned alt text equivalents
-	As a User I want to ensure the website HTML code passes through the official W3C validator without faults
-	As a User I want to ensure the website CSS code passes through the official (Jigsaw) validator without faults
-	As a User I want to ensure that images are displayed without pixelization irrespective of screen size
-	As a User I want to ensure there are screen captures of the finished project within the README document
-	As a User I want to be able to easily deploy this site to the cloud.
*Interpreted from the Assignment document*



# Functional Requirements Scope

## Design Consistancies
The following are a list of design aspects that must be maintained throughout the site. 

Header will consist of:
  - Background colour/image different to the body, but matching the footer.
  - Professional photo to the left.
  - Name, current job title, quote to the right of the photo on three lines.
  - Quote contents will change per page.

Table of Contents / Navigation bar.
  - Horizontally displayed, directly under the header.
  - Each Option will be a different (light colour).
  - Each option will appear darker when user is on that page (or hovers mouse over).
  - Box Shaped.

Body of page
  - Will be a lighter/simple background to enable easy reading of content.
  - Will appear directly under the Table of Contents/Navigation bar
  - Contents is detailed in the following sections

Footer
  - Will appear at the base and remain static across all pages
  - Will contain the following info:
  - Github and linkedin links
  - ©CourtneyMarshall2021


## Home Page

The About Me page is the first page a user will land on. This page will provide an image and a basic summary.

Key features:
-	Header should be different background/colour to the body of the page
-	Body of page will be paragraph (2-3 lines) about me, goals etc (summary)

Below is the initial wire frame:

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/concepts/aboutwf.png" alt-text="about page wireframe" width="200" height="300" />
</p>


## Work Experience/History

This page will detail the employment history. 
Side toggle tab for each role/company

Key features:
-	Each Role will display the applicable company logo and will contain a link to the company’s website
-	The responsibilities will be contained within a collapsible section (so as to not overwhelm the user)
-	Information for these roles will be the same as created on linkedin, this will be noted at the base

Below is the initial wire frame:

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/concepts/experiencewf.png" alt-text="experience page wireframe" width="200" height="300" />
</p>


## Certification/Education

This page will detail the current certificates, including courses and badges. 

Key features:
-	Each major Certificate will display the applicable company/provider and will contain a link to the company/providers website
-	The qualification name will be a link to the certification verification site
-	Minor Badges will be displayed as a table. 
- Each Badge logo will redirect the verification site (ie acclaim)
- Each Provider Name will redirect to the course site.

Below is the initial wire frame:

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/concepts/certwf.png" alt-text="certificate page wireframe" width="200" height="300" />
</p>


## Affiliations/Groups

This page will detail the various Groups where membership is held.

Key features:
-	Each group will contain a link to the groups website or meetup page
-	Each group will be accompanied by a brief description (obtained from their site and properly cited)

Below is the initial wire frame:

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/concepts/afillwf.png" alt-text="affiliations page wireframe" width="200" height="300" />
</p>


## Portfolio/Skills

This page will detail the available Projects and a description of skills. This page is not positioned more predominately on the site (ie after the “About Me” page due to the limited content available at this time). Potential for this page to be promoted once more content becomes available

Key features:
-	When listing software – a link will be provided to the software’s own website.
-	When listing skills (ie testing specific) links will be provided to a description page (ie QA site)

Below is the initial wire frame:

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/concepts/portwf.png" alt-text="portfolio page wireframe" width="200" height="300" />
</p>


## Contact

This page will enable to User to contact me directly.

Key Features:
-	Ability to send me an email using a contact form on the page
-	Contact information including email, telephone, linkedin etc

Below is the initial wire frame:

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/concepts/contactwf.png" alt-text="contact page wireframe" width="200" height="300" />
</p>


# Final/Existing Feature Outcomes

![Multi Device Preview](https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/final/multipc.PNG)


- __Header Panel__

  - Featured on all six pages, containing a profile (cartoon) image to the left. On the right will be my name, along with a quote that is unique for each page.

__Desktop__
<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/final/headerdesktop.PNG" alt-text="desktop header" width="200" height="300" />
</p>

__Tablet__
<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/final/headermax1000.PNG" alt-text="tablet header" width="150" height="200" />
</p>

__Mobile__
<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/final/headermobile.PNG" alt-text="tablet header" width="100" height="150" />
</p>


- __Navigation Bar__

  - Featured on all six pages, the full responsive navigation bar includes links to the About, Experience, Certifications, Affiliations, Portfolio, Contact pages. It will appear identical on each page. The active page for the User will have an underline to indicate the Users current location.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

__Desktop__
<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/final/navdesktop.PNG" alt-text="desktop nav bar" width="300" height="100" />
</p>

__Tablet__
<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/final/navbartablet.PNG" alt-text="tablet nav bar" width="150" height="200" />
</p>

__Mobile__
<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/final/navbarmobile.PNG" alt-text="tablet nav bar" width="100" height="150" />
</p>


- __Footer__

  - Featured on all six pages, the footer will contain links to the Linked in page and GitHub repositories for Courtney Marshall. Along with a copyright reference.
  - These links will open in a new browser tab to allow the user to view the media pages without leaving the site.

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/final/footer.PNG" alt-text="footer bar" width="300" height="100" />
</p>


- __About Page__

  - This page is the main landing page for the website
  - The body of this page provides high level information about Courtney Marshall
  - The information is static and brief

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/final/desktopabout.PNG" alt-text="about page" width="200" height="300" />
</p>


- __Experience Page__

  - The body of this page provides details of the employment history of Courtney Marshall
  - The roles are first presented as closed according text so to not overwhelm the User with information.
  - Each block will initially show the "Title" = Company Name and the Role Name
  - Once selected the according text will expand to show the company logo to the left of the page, with a hyper link to the company's webpage, this link will open in a new tab. Next to this image will be a list of responsibilities undertaken during the contract.
  - Clicking on the "Title" again will close the accordion text
  - All content can also be found on the LinkedIn page for Courtney Marshall

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/final/desktopexperience.PNG" alt-text="experience page" width="200" height="300" />
</p>


- __Certificates Page__

  - The body of this page details the Certificates obtain by Courtney Marshall
  - Each entry contains the following:
  - Logo of the course provider with a hyperlink to their website (opens in a new tab)
  - Name of the course, with a link to the certificate validation website (via an icon on the page, opens in a new tab), <s> and a popup text box (appearing when user hovers the curser over the text) explaining same.</s>
  - Name of the course provider, with a link to the specific course website (via an icon on the page, opens in a new tab), <s> and a popup text box (appearing when user hovers the curser over the text) explaining same.</s>

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/final/desktopcert.PNG" alt-text="certification page" width="200" height="300" />
</p>


- __Affiliations Page__

  - The body of this page provides details of the main groups that Courtney Marshall if affiliated with.
  - The groups are first presented as closed according text so to not overwhelm the User with information.
  - Each block will initially show the "Title" = Group Name
  - Once selected the according text will expand to show the Groups logo to the left of the page, with a hyper link to the Groups website, this link will open in a new tab. Next to this image will be details of each group, this information is extracted directly from the Groups website.
  - Clicking on the "Title" again will close the accordion text

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/final/desktopaffil.PNG" alt-text="affiliations page" width="200" height="300" />
</p>


- __Portfolio Page__

  - The body of this page currently displays an under construction sign. This page will be further developed as more publicly available projects are created.

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/final/desktopport.PNG" alt-text="portfolio page" width="200" height="300" />
</p>


- __Contact Page__

  - The body of this page provides a form by which the User can send a message to Courtney Marshall.
  - The form will enable to User to include their name, email, phone number, a preferred contain method and a message.

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/final/desktopcontact.PNG" alt-text="contact page" width="200" height="300" />
</p>


# Features to be Implemented
- Further develop the Portfolio Page as new projects become available


# Testing 

The subsections detail the proposed approach for testing of the final product. Due to the size and nature of this project, a full V-Style testing approach will not be required. Instead, a simplified version of agile will be adopted.

## Unit Testing
 
A formal round of unit testing will not be scripted/conducted for this project. Instead, there will be a form of self-peer review whereby code writing will occur on day one and code review and refactoring will occur on the following day.
This will reduce the effect of; reading what should be there instead of what is actually there.

A once a working prototype for each page is developed, the code will be validated via both W3C html validator and the CSS jigsaw.
At regular intervals (upon significant updates) this validation will occur.

## Functionality

This website has been developed with the following compatibility in mind: 
- Desktop browsers (Chrome, firefox, edge), 
- Enterprise tablet sizes (max width 1200), 
- Standard generic tablet sizes (max width 1000px), 
- Common mobile size (max width 700px).

__Compatability testing:__

__iphone6/7/8 plus:__

Device width: 414px

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/aboutiphone6.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/experienceiphone6.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/certificationiphone6.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/afilliphone6.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/portfolioiphone6.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/contactiphone6.gif" width="100" height="200" />
</p>

__samsung galaxy s5:__

Device width 360px

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/aboutsgs5.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/expersgs5.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/certsgs5.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/afillsgs5.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/portsgs5.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/contactsgs5.gif" width="100" height="200" />
</p>

__Moto G4:__

Device width 360px

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/aboutmotog4.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/experiencemotog4.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/certmotog4.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/affilmotog4.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/portmtotg4.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/contactmotog4.gif" width="100" height="200" />
</p>

__Pixel 2:__

Device width 411px

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/aboutpixel2.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/experpixel2.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/certpixel2.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/afillpixel2.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/portpixel2.gif" width="100" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/contactpixel2.gif" width="100" height="200" />
</p>

__iPad Pro:__

Device width 1024px

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/aboutipadpro.gif" width="150" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/experipadpro.gif" width="150" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/certipadpro.gif" width="150" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/affilipadpro.gif" width="150" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/portipadpro.gif" width="150" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/contactipadpro.gif" width="150" height="200" />
</p>

__Surface Duo:__

Device width 540px

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/aboutsurfaceduo.gif" width="125" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/expersurfaceduo.gif" width="125" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/certsurfaceduo.gif" width="125" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/affilsurfaceduo.gif" width="125" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/portsurfaceduo.gif" width="125" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/contactsurface%20duo.gif" width="125" height="200" />
</p>

__Desktop Chrome:__

Device width 1024px

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/chromeabout.gif" width="300" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/chromeexper.gif" width="300" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/chromecert.gif" width="300" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/chromeaffil.gif" width="300" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/chromeport.gif" width="300" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/chromeport.gif" width="300" height="200" />
</p>

__Desktop Firefox:__
Device width 1024px

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/firefoxabout.gif" width="300" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/firefoxexper.gif" width="300" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/firefoxcert.gif" width="300" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/firefoxaffil.gif" width="300" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/firefoxport.gif" width="300" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/firefoxcontact.gif" width="300" height="200" />
</p>

__Desktop Edge:__
Device width 1024px

<p float="left">
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/edgeabout.gif" width="300" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/edgeexper.gif" width="300" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/edgecert.gif" width="300" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/edgeaffil.gif" width="300" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/edgeport.gif" width="300" height="200" />
<img src="https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/testing/edgecontact.gif" width="300" height="200" />
</p>

## User Functionality
 
User acceptance testing will be conducted on an ongoing basis. Prior to each git push, an exploratory testing session will occur.

Once a working prototype is available, third-party individuals will review the website as an independent user with no prior knowledge of its purpose (or project criteria). Feedback from this session will be used to further develop and/or amend the site.

## Production Shakedown

Once the site has been deployed the HTML code will be passed throught the official W3C validator for the HTML portions:

![w3cvalidatorindex]()
![w3cvalidatorexperience]()
![w3cvalidatorcertificates]()
![w3cvalidatoraffiliations]()
![w3cvalidatorportfolio]()
![w3cvalidatorcontact]()

Once the site has been deployed the CSS code will be passed throught the official Jigsaw validator for the CSS portions:

![jigsawvalidator]()

### Unfixed bugs

- When using the browser "autofill" option the background of the form field will revert to white instead of retaining its current background image. This appears to be due to the implementation of autofill and would require Javascript to resolve in the future.

- Random occurance: On occasion when accessing the website on a mobile device (primarily a phone) a white border appears on the right side of the screen. Upon navigating to a different page within the site, this bar will disappear.

- Linked to the previous issue, there is an over flow in the site that courses a white border to appear, this is not instantly visible, but appears on mobile/tablet devices when the user attempts to navigate horizontally



# Deployment Process

## Direct Deployment

The site was deployed to GitHub pages. The repository link can be found here - https://github.com/Sphere42/MSP-1

The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab

![Repo](https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/deploy/deploy1.PNG)

  - Scroll down to the GitHub Pages section, The latest GitHub version now maintains the GitHub Pages in a new page, click the "Check it out here!" page to be redirected. 

![githubpages](https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/deploy/deploy2.PNG)

  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, click the Save button

![deploysave](https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/deploy/deploy3.PNG)

  - The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 
    Note: It takes time to build the site, please wait 5-10 mins before clicking on the link to access the deployed site.

![finallink](https://github.com/Sphere42/MSP-1/blob/main/assets/images/readme/deploy/deploy4.PNG)


# Credits 
This project could not have been created without the following:

## Code 

- The basis for the accordion text was learned from [Code Institute](https://codeconvey.com/responsive-accordion-pure-css/)
- <s>The basis for the Tooltips hover text was learned from [Log Rocket Blog](https://blog.logrocket.com/creating-beautiful-tooltips-with-only-css/)</s>
            - After User testing, it has been determined that including hover message boxes in the certificate page is over engineering the development of the page. They are not beneficial for the user. Instead Icon links will be utilised for the validation and course links.
- The basis for the form was learned from the Love Running Project from Code Institute
- The icons across the site were taken from [Font Awesome](https://fontawesome.com/)

## Media

- The background patterns/photos used on the home and sign up page are from This Open Source site
[HIP wall paper](https://hipwallpaper.com/best-webpage-backgrounds/)
- All logo images are obtained from the respective company/group website. The link where they are obtained is the link built into each image on the site.
- The under construction image on the portfolio page is from:
[wallpaperup](https://www.wallpaperup.com/uploads/wallpapers/2014/09/25/455952/8d9dee7d6978d6dda0a1ee308ec01187-700.jpg)

## Tools
- https://gtmetrix.com - speed testing the loading times for the website
- https://tinypng.com - to reduce image file size without removing quality
- https://gitpod.io - IDE tool preferred by Code Institute
- https://validator.w3.org/#validate_by_input - HTML validator
- https://jigsaw.w3.org/css-validator/#validate_by_input - CSS validator


## Additional Thanks

Independant Reviewers: Tom Walsh, Daragh Curtis.

Code Institute (https://codeinstitute.net/)

Mentor: Felipe Souza Alarcon
 