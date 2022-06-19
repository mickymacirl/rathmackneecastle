# Rathmacknee Castle

Rathmacknee Castle is a website that allows users to have a place to find interesting historical facts surrounding Rathmacknee Castle.

This website will provide information on the castle in the townsland of Rathmacknee in Wexford, Ireland. This site will give the information about the history of the castle, links to social media accounts and a contact form to contact the castle owners.

![Multi Mockup](/docs/multi.jpg)

View the live site: *[here](https://mickymacirl.github.io/rathmackneecastle/)*

## Features of Website

### Header
* Has a Header with the Castle logo centered and it is reponsive on all device sizes.

![Headers](/docs/header.jpg)

### NavBar
* Has links to the Home, History, Contact pages and it is responsive on all device sizes.

![Navbar Readme](/docs/navbar_readme.jpg)

![Navbar Readme Responsive](/docs/navbar_readmesmall.jpg)

* Users will be able to navigate between each page and have the menu the same location on different devices.
### Footer
* Has links to social media websites, and that are set to open in a new tab window.
* Icons will use visually impaired features like aria labels.

![Footer](/docs/footer.jpg)

### 404 page
* A 404 broken page link page will be created and allow the user to easily navigate back to Home page.

![404 Page](/docs/404page.jpg)

### Contact page
* The contact page will provide the user with a contact form to request additional information.
* The contact page will also display the Castles address and other information.

![Contact Us Page](/docs/contactuspage.jpg)

### Landing page
* The landing page will display a picture using method as a hero image.
* The landing page will provide the user information about the Castle.
* Image of Landing page
### History page
* History page will provide the user information about the Castle's history.
* The History page will provide the user links to articles and video's about the Castle's history.
* Image of History page
### Confirm page
 * The Confirm page will provide the user with a message about successful submit.
 * The Confirm page will provide a thanks and a average response time.
 
![Confirm Page](/docs/confirmpage.jpg)

## Design
### Colors
![Colors](/docs/color.jpg)

Using the color palette from the logo, which I generated from an image of the castle using the eye dropper in Adobe Photoshop, the dark green and a lighter brown fit each other well.

The dark green is used as a background and text color which contrasts well with the lighter brown of the navbar and footer. The main background is white, which makes the text content easier to read. 

*#b29e84 light brown* - Color used for navbar background, footer background, navbar hover over text color and font awesome hover over text color.

*#253439 dark green* – Color used for Logo background, navbar hover over, font awesome hover over and main body text color.

*#ffffff white* – Color used for elements of Logo and for main body background color.

### Social Media Icons

The icons for social media are from the Font Awesome library.  Choosing the square option when available. 

![Social Media Icons](/docs/sc1.jpg)

### Fonts

I've made the decision to use the imported *[Montserrat](https://fonts.adobe.com/fonts/montserrat#details-section)* typeface from Google Fonts for the main font of text and menus in the website.

I chose this typeface because, in my opinion, it blends nicely with the website's design and complements the font used in the logo which is *[Anton](https://fonts.adobe.com/fonts/anton)*. 

### Montserrat

![Montserrat Font](/docs/monfont.jpg)

### Anton

![Anton Font](/docs/antfont.jpg)

### Wireframes
#### Landing Page
![Index Page 320](/docs/Index320.jpg)
![Index Page 700](/docs/Index700.jpg)
#### History Page
![History Page 320](/docs/History320.jpg)
![History Page 700](/docs/History700.jpg)
#### Contact Page
![Contact Page 320](/docs/Contact320.jpg)
![Contact Page 700](/docs/Contact700.jpg)
#### 404 Page
![404 Page 320](/docs/404320.jpg)
![404 Page 700](/docs/404700.jpg)
#### Confirm Page
![Confirm Page 320](/docs/Confirm320.jpg)
![Confirm Page 320](/docs/Confirm700.jpg)
## Technology
### HTML
* The main lanuagage of this Website was developed using *[HTML](https://en.wikipedia.org/wiki/HTML)*.
### CSS
* The Website was styled by connecting a custom *[CSS](https://en.wikipedia.org/wiki/CSS)* to an external file.
### Visual Studio Code
* The website was developed using *[Visual Studio](https://visualstudio.microsoft.com/)* Code IDE.
### GitHub
* Source code is hosted on *[GitHub](https://github.com/)* and deployed using *[GitPages](https://pages.github.com/)*.
### Git
* Used *[Git](https://git-scm.com/)* to commit and push code during the development of site.
### Adobe Photoshop
* Used *[Adobe Photoshop](https://www.adobe.com/products/photoshop.html)* for the hero and logo images.
### Adobe Dreamweaver
* The website tested and designed using *[Adobe Dreamweaver](https://www.adobe.com/products/dreamweaver.html)*.
### Google Fonts
* This website uses *[Google Fonts](https://fonts.google.com/)*.
### Font Awesome Icons
* This website uses *[Font Awesome Icons](https://fontawesome.com/)*.
### balsamiq
* Created wireframes for this website using *[balsamiq](https://balsamiq.com/wireframes/desktop/#/)*. 
## Testing
### Responsiveness

Pages were tested on various different screen sizes from 320px on a Samsung fold 2, iPhone 11, Samung Galaxy Tab, Nexus 7 and a wide screen Windows machine.

Pages were tested on most modern browsers including Microsoft Edge, Chrome, Firefox, Opera and Brave.

**Test Steps:**

1.	Open the corresponding browser and open Rathmacknee Castle site.
2.	Open the browser develop tools by hitting the corresponding dev tools short cut.
3.	Resize to the desired width.
4.	Click and drag browser window to lower or higher window size.

**Expected:**

The website is responsive on all sizes and no pixelation is accruing. No overlap of text or images.

**Actual:**

The website behaved as expected, issue with the center of text in the confirm.html page on a larger browser window of 700px. Bug listed in the unfixed bug section.

The website was testing on the following devices, with no resizing issues seen:

* Samsung fold 2
* iPhone 11
* Samsung Galaxy Tab
* Nexus 7 with Kali Linux
* Wide screen 4k monitor

## Accessibility



## Lighthouse Testing



## Functional Testing

### Navigation Links Testing

Testing was done to make sure all navigation links led to the intended pages on their respective pages.

The navigation links on each page were used to do this and were successful.

### Form Testing

The Contact form was tested so that when a user clicks on submit the action directs to the confirm.html web page with a success message.

**Test Steps:** 

1.	Open the corresponding browser and open Rathmacknee Castle site.
2.	Open the browser and navigate to the Contact page.
3.	Enter details in the First Name, Last Name, Email and the Subject fields.
4.	Click the Submit button.
5.  The user should be redirected to the contact.html page with the success message being displayed.

**Expected:**

The user should be redirected to the confirm.html page with the success message being displayed.

**Actual:**

The website redirected the user to the confirm.html page with the success message being displayed.

### Font Awesome Icon Testing

The Font Awesome Icons in the footer were tested to make sure each icon link opened in a new tab and that the color of the hover over matched the color scheme of the website logo and navbar.

When clicked each of the links opened in a new browser and each of the icons color changes happened successfully.

### 404 Page Testing

If the user tries to access a missing or broken link on the site, the 404 page should display offering the user a way to click to return to the home page while maintaining the look and feel of the website.

**Test Steps:**

1. Open a browser and enter the url of the contact page.
2. Modify the url of the page and remove the second t in the contact.html page url, so trying to call the contac.html page.
3. Click the enter button.
4. The user should be redirected to the 404.html page with a link back to the home page while maintaining the look and feel of the webite.

**Expected:**

The user should be redirected to the 404.html page when an incorrect page call is submitted.

**Actual:**

The user is redirected to the 404.html page when an incorrect page call is submitted.

## Validator Testing
### Meta Tags

Validated the correct Meta Data information using *[Meta Tag Analyzer](https://www.internetmarketingninjas.com/tools/webpage-meta-analyzer/)*. 

![Meta Data](/docs/metadata.jpg)

## Deployment
### Version Control
Both Visual Studio code editor and GitPod were used to created this site and then pushed to the GitHub remote repository named ‘rathmackneecastle’.

The following commands were used to push code to the remote repository:

*git add .* was used to stage all files for commit changes

*git commit -m “commit message”* was used to add the changes to the local repository for upload during a push

*git push* was used to push all local changes to the remote repository on GitHub.

### Deployment to GitHub Pages
The site was deployed to **GitHub Pages**.

Below are the steps required:

* In **GitHub**, navigate to your **username.github.io** repository and click **Settings**.
* Within **Settings**, navigate to the **Source** section within the **Github Pages** section. From the dropdown menu, select **master branch** and then click **Save**.
### Deploying New Changes
Once **GitHub Pages** is setup, normal **GithHub** flow updates the live page.

View the live site: *[here](https://mickymacirl.github.io/rathmackneecastle/)*

### Clone the ‘RathmackneeCastle’ GitHub Code Repository locally

* Go to the page of the repository that you want to clone
* Click on **“Code”** menu and copy the URL.

![Clone Repository](/docs/clone.jpg)

![Clone Repository Copied](/docs/copied.jpg)

* Use the **git clone** command along with the copied URL.
* git clone https://github.com/USERNAME/REPOSITORY

## Credits
### Mentor Support
* Mentor support from *[Daisy McGirr](https://github.com/Daisy-McG)*.
### CSS Tricks
* Used *[CSS Tricks](https://css-tricks.com/)* for How's To's on CSS for reference.
### Markdown Language
* Used syntax from *[Markdown Guide](https://www.markdownguide.org/basic-syntax/#headings)* for reference.
### W3C School Flex Box Responsive
* Used *[W3C School Flex Box Reponsive](https://www.w3schools.com/css/css3_flexbox_responsive.asp)* to create flex box responsive pages.
### W3C School Page Regions
* Used *[W3C School Page Regions](https://www.w3.org/WAI/tutorials/page-structure/regions/)* to create page regions.
### W3C School Contact Form
* Used *[W3C School Contact Form](https://www.w3schools.com/howto/howto_css_contact_form.asp)* to create contact form.
### Git and GitHub
* Used *[W3C Git Tutorial](https://www.w3schools.com/git/default.asp?remote=github)* for reference.
* Used *[GitHub Git-Guides](https://github.com/git-guides)* for reference. 
### Multi Device Website Mockup Generator
* Used *[Multi Device Website Mockup Generator](https://techsini.com/multi-mockup/index.php)* to create mutli device mockup.
### Version Control
* Used *[GitHub.io](https://ourcodingclub.github.io/tutorials/git/)* How To's for reference.
### Content
* Logo created using *[Canva](https://www.canva.com/)* and *[Adobe Photoshop](https://www.adobe.com/products/photoshop.html)*.
* Website text content used from *[Wikipedia](https://en.wikipedia.org/wiki/Rathmacknee_Castle)*