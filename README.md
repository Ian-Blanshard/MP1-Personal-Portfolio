# Ian Blanshard Portfolio website

My name is Ian Blanshard and I am developing my skills as a software engineer, this site is a place for me to practice my HTML and CSS skills. Whilst offering an opportunity to demonstrate skills I have, which make me employable.

The website is designed to attract work opportunities through communicating information about me, skills, work experience and providing a way for people visiting  to initiate contact with me.

Live version of site hosted on GitPages [here](https://ian-blanshard.github.io/MP1-Personal-Portfolio/)

![Screenshot of page on different devices](/assets/images/responsive_design_image.jpg)
---
## Contents

1 [User Experience (UX)](#UX)

  * [Project Goals](#project-goals)
  * [User Stories](#user-stories)
  * [Wireframes](#wireframes)
  * [Colour Scheme and Font](#styles)

2 [Features](#features)

  * [Navigation Bar](#navigation-bar)
  * [Timeline](#timeline)
  * [Contact Form](#contact-form)
  * [Portfolio Cards](#portfolio-cards)
  * [Footer](#footer)
  * [Overall Site Features](#overall-features)

3 [Technologies Used](#technologies-used)

4 [Credits](#credits)

5 [Testing](#testing)

  * [Bugs](#bugs)
  * [Code Validation](#code-validation)
  * [Lighthouse Testing](#lighthouse-testing)
  * [Manual Testing](#manual-testing)
  * [Testing Stories](#testing-stories)
  * [Device and Browser Testing](#testing-devices-browsers)

6 [Deployment](#deployment)

7 [Finished Site](#finished-site)

 * [About Me Page](#about-me-page)
 * [Portfolio Page](#portfolio-page)
 * [Work Experience Page](#work-experience-page)
 * [Contact Me Page](#contact-me-page)
 

## User Experience (UX) <a name="UX"></a>
### Project Goals <a name="project-goals"></a>
This project is for a personal portfolio website designed to:

* Show potential employers what skills I have
* Show potential employers what work experience I have
* Provide ways for people to contact me
* Share information about me

### User stories <a name="user-stories"></a>

Users of this site may be:

1 A recruiter looking for suitable employee to fit a role they have, they want:

  * To be able to quickly see what skills I have
  * To be able to access a copy of a CV which they could download
  * Know how to contact me
  * See what work experience I have

2 A Employer who is coming to this site after I have applied to their job listing, they want:
 
  * To learn more about me 
  * Know my employment history
  * See examples of my previous work 

3 Somebody who would like to collaborate on a project with me, they want:

  * To see if my skills are suitable to their idea
  * find out how to contact me 

### Wireframes <a name="wireframes"></a>
I used [figma](www.figma.com) to create wireframes for my project to get some of the ideas for layouts designed prior to starting to code them.

![Screenshot of wireframes](/assets/images/figma_basic_page_layout.jpg)

For the index page and work experience page the layout consists of a header containing the navigation which will always be present at the top of the page, The footer containing links 
to external sites which will also always be present and the main container which will be scrollable depending on the size of the content contained in it. The header and footer being 
visible at all times allows for easy navigation for the user who will be interested in the 
information contained in them. For example external links to GitHub and other pages on the site
such as CV, work experience and a contact form. All these are crucial in obtaining employment from the site.

![Screenshot of wireframes](/assets/images/figma_contact_page_layout.jpg)

The contact form site layout has the important feature discussed above but when being view on a mobile device this layout wouldn't be visually pleasing so the text and the form will be split and displayed text above the form, this ensures the explanatory text is read before the form.
Highlighting of key words is used to draw attention the most important messages being communicated.

![Screenshot of wireframes](/assets/images/figma_porfolio_page_layout.jpg)

The portfolio page has a header which is in a separate container to ensure it's effectively communicated what the page contains. Below this each piece in the portfolio has its own container these are two wide on desktop and tablet displays with one centered below on another line id there are an odd number of pieces currently in the portfolio, this ensures the design can be added to later easily. On mobile the portfolio pieces stack one on top of another.

### Colour Scheme and Font <a name="styles"></a>

![Screenshot of color scheme](/assets/images/color_scheme.jpg)

For the colour scheme I used two different shades of blue, the lighter one #2bb2f6 for the main background of the site and a darker shade #003753 for the containers/header/footer. This draws the eye nicely to the content.

For the main bulk of text/information the lighter blue #2bb2f6 is used this has a nice contrast with the containers and ensures information is easily readable, then white #fafafa was used to highlight the most important information on the site, allowing the user to rapidly focus on the information 
which is of most importance to them. Black #000000 was used in the tiles on the portfolio page and the placeholder text on the form. I had an earlier design using a different colour scheme but during testing it came to my attention that these combinations did not score well for accessibility so was changed, this is discussed in detail in the [testing section](#lighthouse-testing)

The font used is Lilita one, with sans-serif as a fall back incase the primary font is not available due to either compatibility or failure of the import.

## Features <a name="features"></a>

### Navigation Bar <a name="navigation-bar"></a>

The navigation bar was created using bootstrap, customized using my own CSS to change font, text-alignment, colors, hover over effects and responsive navbar height.

![Screenshot of navigation bar](/assets/images/navigation_bar.jpg)

The navbar contains a title which has the name and title, this is positioned in the top left of the screen and is present on every page, this is key information, as the purpose of the site is to communicate who they are and what they do, it also functions as a link to return to the index/about me page.

The second part of the navigation bar has the name of the other pages so the visitor can immediately see what information is available to them and also where they are on the site is highlighted. This allows for easy navigation to key information rapidly.

### Timeline <a name="timeline"></a>

![Screenshot of timeline feature](/assets/images/timeline.jpg)

The timeline feature communicates the work history in chronological order, it has the key information of employer and job role highlighted and then includes a list of further information about the role.

### Contact Form <a name="contact-form"></a>

![Screenshot of contact form](/assets/images/contact_form.jpg)

The contact form allows visitors to the site to get in contact with me, it has some text describing reasons to use the form to encourage use. It has areas to allow name and email to be entered which ensures they can be responded to and a box for a message to be entered. All of these have placeholder text to make the form more user friendly and also aria labels for accessibility.

### Portfolio Cards <a name="portfolio-cards"></a>

![Screenshot of portfolio card](/assets/images/portfolio_card.jpg)

The portfolio cards are places to display project that demonstrate skills, they contain images of the projects and tiles which highlight the demonstrated skills, a link is also included which opens on a seperate tab, taking them to the GitHub page for the projects to look in more detail.

### Footer <a name="footer"></a>

![Screenshot of footer](/assets/images/footer.jpg)

The footer displays links to social media sites to encourage making contact.

The footer was created using fontawesome icons, aria labels added to provide context of where the links go as icons do not provide this information. CSS used for size/color customization, responsive spacing of icons and hover effects added using hover pseudoclass.

### Overall site features <a name="overall-features">

Responsive design created using bootstrap [grid system](https://getbootstrap.com/docs/4.0/layout/grid/) to allow responsiveness across all screen sizes.

Each page contains a heading which explains the purpose of the page to the user, it is the first piece of content on every page and attention is drawn to this by creating a typing animation that runs on page load.

Key information is highlighted using a different color throughout the site, this consistency is visually pleasing and is used for the following:

 * Key pieces of text on the about me page
 * Skills demonstrated by each portfolio piece
 * Job roles on the work experience page
 * Reasons to contact and where to enter your details on the contact page

This allows visitors to the page to quickly engage with and gain the key information needed to convince them to hire/ work with me.

The contents of each page are consistently styled throughout the site.


## Technologies used <a name="technologies-used"></a>

This Project uses the following languages:

* HTML
* CSS

[Bootstrap CSS](https://getbootstrap.com/) framework is utilized to structure the website, allowing me to easily create a responsive website and create a quick and easy to use navigation bar.

[Git](https://git-scm.com/) and [GitHub](https://github.com/) for version control and as a repository.

[FontAwesome](https://fontawesome.com/) was used for the logos of Linkedin, GitHub and Facebook. These logos formed part of the footer 
and were used as links to the sites.

[Google Fonts](https://fonts.google.com/) was used to browse, select and as a source of the font I used on this site.

I had initially begun using [codeanywhere](https://codeanywhere.com/) which is a cloud
integrated development environment, which runs from a web browser. But after some issues with long wait times to create the virtual environment and in some instances being unable to create one, I moved to using Microsoft Visual Studio Code which I had some experience with. This allowed me to work more efficiently and able to work quickly when I had limited time.

## Credits <a name="credits"></a>

The [CSS documentation at mdn web docs](https://developer.mozilla.org/en-US/docs/Web/CSS) was used as a reference point during the creation of the website and when creating hovering effects.

The [bootstrap docs](https://getbootstrap.com/docs/5.3/getting-started/introduction/) were used frequently, especially when initially trying to get a good understanding of the grid structuring, the [following solution on stackoverflow](https://stackoverflow.com/questions/42523147/place-part-of-form-group-in-different-column-using-bootstrap-grid) in particular was helpful in solving my own problem I was having with my form.

When I wanted to create a fade in effect on my containers I used [this tutorial on geeksforgeeks.org](https://www.geeksforgeeks.org/how-to-create-fade-in-effect-on-page-load-using-css/
) to learn how to do so, I modified the code to achieve the effect I wanted.

When styling my buttons I used [this page on w3schools.com](https://www.w3schools.com/css/css3_buttons.asp) to learn how to achieve the desired effect.

When creating my README I used the website [makeareadme.com](https://www.makeareadme.com/) and the following [markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) from GitHub to assist.

I used the work history timeline idea from the [codeinstitute](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2024_Q1/courseware/616289d66b5641a3808cc43e53842695/a3bcedac97ea4678953a75f07ffd6931/) tutorial and modified it to create my own style of timeline for my work experience page.

I used the code from this site by [samanthaming](https://www.samanthaming.com/tidbits/57-styling-css-placeholder/) to learn how to style parts of my form.

I used [this tutorial/blog](https://blog.hubspot.com/website/typing-animation-css) to learn how to create a typing animation and edited the code to change timings and remove the cursor once the typing animation had run.

## Testing  <a name="testing"></a>

### Testing across different devices and browsers  <a name="testing-devices-browsers"></a>

I used the developer tools in chrome browser to test the responsiveness of the site on screen sizes from a variety of mobile devices, this highlighted a couple of issues.

On mobile screen size I modified the margins on the content containers to make the design more visually pleasing and fixed an issue with the bottom of the content not displaying correctly above the footer.

I added a media query to change the font size of the navbar brand to ensure the icon for the collapsible element of the navbar didn't overspill onto a new line on certain screen sizes.

I tested the site on Microsoft Edge, Google chrome and Mozilla Firefox browsers. 


### Code Validation <a name="code-validation"></a>

I used the [W3C Markup validation service](https://validator.w3.org/) to check the validity of my code.
This highlighted a number of errors and warnings.

![Screenshot of errors](/assets/images/code_validation_errors.jpg)

The trailing slash at the end of link to the font awesome stylesheet was removed.

I had also used spacing in the names of two of my HTML files and these were replaced with underscores and the 
links updated across the navigation bar.

![Screenshot of errors](/assets/images/code_validation_errors_2.jpg)

These errors occurred as i had missed the closing tag for the anchor elements in the footer, these were added in.

As these elements navigation and footer were present in all pages, the corrections were made for all files and 
following that my code passed the validations and no more errors or warnings were given.

![Screenshot of no errors message](/assets/images/code_validation_corrected.jpg)

My CSS passed validation with no errors found.

![Screenshot of no errors message for CSS](/assets/images/css_validation_no_errors.jpg)

### Lighthouse testing <a name="lighthouse-testing"></a>

During testing it became clear that the white text on a green background made for poor accessibility as can be 
seen below by a reduced lighthouse score for this using chromes web developer tools.
![Screenshot of poor lighthouse score](/assets/images/poor_accessibility_score.jpg)

Although I liked how the design looked, pictured below, this led me to explore other colour schemes.

![Screenshot of site using original design](/assets/images/original_color_scheme.jpg)

![Screenshot of site using original design](/assets/images/original_color_scheme_1.jpg)

I visited a site called [venngage](https://venngage.com/tools/accessible-color-palette-generator#colorGenerator), 
which helped me better understand this score and colour schemes which are better for accessibility, then changed 
my colour scheme and achieved an improved score, seen below, this is  fop the final colour scheme in the published site.

![Screenshot of improved lighthouse score](/assets/images/improved_accessibility_score.jpg)

### Manual testing <a name="manual-testing"></a>

#### Tested Navigation bar

 * clicked portfolio link
 * expected it to take me to portfolio page
 * took me to portfolio page, page loaded correctly

 <br>

 * clicked work experience link
 * expected it to take me to work experience page
 * took me to work experience page, page loaded correctly

 <br>

 * clicked contact me link
 * expected it to take me to contact me page
 * took me to contact me page, page loaded correctly

 <br>

 * clicked about me link
 * expected it to take me to about me page
 * took me to about me page, page loaded correctly

 <br>

 * clicked download cv link
 * expected it to open new tab containing CV
 * opened new tab containing CV, page loaded correctly

<br>

#### Tested Footer 

 * clicked LinkedIn logo
 * expected it to open new tab with LinkedIn
 * opened new tab to LinkedIn page

<br>

 * clicked GitHub logo
 * expected it to open new tab with my GitHub
 * opened new tab to my GitHub page

<br>

 * clicked Facebook logo
 * expected it to open new tab with Facebook site
 * opened new tab to Facebook site

<br>

#### Tested About Me page

 * loaded about me page
 * expected page to display about me text and header animation to run
 * page loaded correctly, text displayed correctly and animation ran successfully 

<br>

 * clicked portfolio link button at bottom of page
 * expected to be taken to portfolio page
 * portfolio page loaded correctly

<br>

 * clicked CV link button at bottom of page
 * expected new tab to open displaying CV
 * new tab opened correctly with CV displayed correctly

<br>

 * clicked message link button at bottom of page
 * expected to be taken to contact me page containing form
 * contact me page loaded correctly

<br>

#### Tested Portfolio page

 * loaded portfolio page
 * expected page to display portfolio cards and header animation to run
 * page loaded correctly, portfolio cards and animation ran successfully, could       scroll  down and view all available cards 

<br>

 * clicked GitHub links on portfolio cards
 * expected hover over effect to change colour hovering over button
 * hover over effect worked colour changed
 * when clicked expected new tab to open to GitHub
 * new tab opened correctly with GitHub 

<br>

#### Tested Work Experience page

 * loaded work experience page
 * expected page to display timeline of work experience which was scrollable and header animation to run
 * page loaded correctly, timeline displayed correctly, was scrollable and animation ran successfully 

<br>

#### Tested Contact page

 * loaded contact page
 * expected page to display contact me form and header animation to run
 * page loaded correctly, form displayed correctly and animation ran successfully 

<br>

 * attempted to submit form with no details
 * expected form to not be able to submit and details to show required fields which had no details entered
 * form did not submit and required fields were highlighted to user

<br>

 * attempted to submit form with incorrectly formatted email address
 * expected form to not be able to submit and details to show user problem with email format
 * form did not submit and email address issues were highlighted to user

<br>

 * attempted to submit form with all field filled correctly
 * expected form to submit and information collected correctly
 * form submitted correctly

### Testing user stories  <a name="testing-stories"></a>

1 A recruiter looking for suitable employee to fit a role they have:
 * I could immediately see links to download a CV and Work Experience
 both links work correctly, on the work experience page I could see well organized information regarding skills used in previous jobs.
 * The link to contact me page was constantly visible on the navigation and took me to a form which functioned correctly in which I could write a message to make contact.

2 A Employer who is coming to this site after I have applied to their job listing:
 * On the first page I could see information about the applicant, key bit of information were highlighted effectively.
  * I could see a link on the navigation bar to a portfolio page, the link worked correctly and took me to a page which had summaries of previous work I had completed, Key languages and skills used were highlighted, links were present to GitHub to see the projects in more detail.

3 Somebody who would like to collaborate on a project with me:
 * I could quickly navigate to a portfolio page containing examples of work which allowed me to decide if the skills there were a good match for my project.
  * There was an easily visible link to a contact me page present on the portfolio page, the link worked correctly and took me to a form which I could send a message from.
    

### Bugs <a name="bugs"></a>

During testing of the site I came across a few bugs, this is a list of them and how they were resolved.

 Fixed about me link buttons to have whole button clickable not just text - The 
 anchor element were only around the text of the buttons at the bottom of the index 
 page, I moved them around the div so that not only the text was clickable.
 
 The fade in animation for the containers which have the page content in was only 
 targeting the .context-box class and not the project-box class, as the containers 
 on the portfolio page had some different CSS rules to the main ones, this class was
 added to the fadeInAnimation so that all containers had the same effect.

 Fixed a bug in which images on the portfolio page spilled out of their containers
 at certain screen widths.

## Deployment <a name="deployment"></a>

This project was developed using Microsoft Visual Studio Code, committed to Git and 
pushed to GitHub using the terminal with in VScode.

The final Live version of site is hosted on GitPages [here](https://ian-blanshard.github.io/MP1-Personal-Portfolio/) 

This is achieved by:

 1. logging into GitHub
 2. navigating to the repository you would like to create a site for
 3. at the top of the repository clicking the settings icon
 4. on the left hand side of the settings page click the pages section
 5. under source click the dropdown and select master branch
 6. once the page refreshes there will be a link to your site, click this


Detailed instructions on how to create a site on GitHub pages can be found [here](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)


## Finished site  <a name="finished-site"></a>

### About me page <a name="about-me-page"></a>

![about me page screenshot](/assets/images/about-me-page.jpg)

### Portfolio page <a name="portfolio-page"></a>

![portfolio page screenshot](/assets/images/portfolio-page.jpg)

### Work experience page <a name="work-experience page"></a>

![work experience page screenshot](/assets/images/work-experience-page.jpg)


### Contact me page <a name="contact-me-page"></a>

![contact me page screenshot](/assets/images/contact-me-page.jpg)


