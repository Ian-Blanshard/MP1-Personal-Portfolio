# Ian Blanshard Portfolio website

Live version of site hosted on GitPages [here](#link)

---
## Contents

1 [User Experience (UX)](#UX)

  * [Project Goals](#project-goals)
  * [User Stories](#user-stories)
  * [Wireframes](#wireframes)
  * [Colour Scheme and Font](#styles)

2 [Features](#features)

3 [Technologies Used](#technologies-used)

4 [Credits](#credits)

5 [Testing](#testing)

  * [Bugs](#bugs)
  * [Code Validation](#code-validation)

6 [Deployment](#deployment)

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

The portfolio page has a header which is in a seperate container to ensure it's effectively communicated what the page contains. Below this each piece in the portfolio has its own container these are two wide on desktop and tablet displays with one centered below on another line id there are an odd number of pieces currently in the portfolio, this ensures the design can be added to later easily. On mobile the portfolio pieces stack one on top of another.

### Colour Scheme and Font <a name="styles"></a>

![Screenshot of color scheme](/assets/images/color_scheme.jpg)
For the colour scheme I used two different shades of green, the darker one #626A10 for the main background of the site and a lighter shade #A4AC18 for the containers/header/footer. This draws the eye nicely to the content.

For the main bulk of text/information black #000000 is used this has a nice contrast and ensures information is easily readable, then a shade of white #EEE6CD was used to highlight the 
most important information on the site, allowing the user to rapidly focus on the information 
which is of most importance to them.

The font used is Lilita one, with sans-serif as a fall back incase the primary font is not available due to either compatibility or failure of the import.

## Features <a name="features"></a>

Navigation bar created using bootstrap, customised using my own CSS to change font, text-alignment, colors and increased navbar height when viewed on larger devices.

It also contains a title which has the name and title, this is positioned in the top left of
the screen and is present on every page, this is key information, as the purpose of the site
is to communicate who they are and what they do.

The second part of the navigation bar has the name of the other pages so the visitor can immediately see what information is available to them and also where they are on the site is 
highlighted. This allows for easy navigation to key information rapidly.

Responsive design created using bootstrap [grid system](https://getbootstrap.com/docs/4.0/layout/grid/) to allow responsiveness across all screen sizes.

Each page contains a h2 heading which explains the purpose of the page to the user, it is the first piece of content on every page.

Key information is highlighed using a different color throughout the site, this consistency is visualy pleasing and is used for the following:

 * Key pieces of text on the about me page
 * Skills demonstrated by each portfolio piece
 * Job roles on the work experience page
 * Reasons to contact and where to enter your details on the contact page

This allows visitors to the page to quickly engage with and gain the key information needed to convince them to hire/ work with me.

The contents of each page are consistently styled throughout the site.

Footer created using fontawesome icons, aria labels added to provide context of where the links go as icons do not provide this information. CSS used for size/color customisation, responsive spacing of icons and hover effects added using hover pseudoclass.

## Technologies used <a name="technologies-used"></a>

This Project uses the following languages:

* HTML
* CSS

[Bootstrap CSS](https://getbootstrap.com/) framework is utalized to structure the website, allowing me to easily create a responsive website and create a quick and easy to use navigation bar.

[Git](https://git-scm.com/) and [GitHub](https://github.com/) for version control and as a repository.

[FontAwesome](https://fontawesome.com/) was used for the logos of Linkedin, GitHub and Facebook. These logos formed part of the footer 
and were used as links to the sites.

[Google Fonts](https://fonts.google.com/) was used to browse, select and as a source of the font I used on this site.

## Credits <a name="credits"></a>

The [CSS documentation at mdn web docs](https://developer.mozilla.org/en-US/docs/Web/CSS) was used as a reference point during the creation of the website, when creating hovering effects.

The [bootstrap docs](https://getbootstrap.com/docs/5.3/getting-started/introduction/) were used frequently especially when initially trying to get a good understanding of the grid structuring, the [following solution on stackoverflow](https://stackoverflow.com/questions/42523147/place-part-of-form-group-in-different-column-using-bootstrap-grid) in particular was helpful in solving my own problem I was having with my form.

When I wanted to create a fade in effect on my containers I used [this tutorial on geeksforgeeks.org](https://www.geeksforgeeks.org/how-to-create-fade-in-effect-on-page-load-using-css/
) to learn how to do so, I modified the code to achieve the effect I wanted.

When styling my buttons I used [this page on w3schools.com](https://www.w3schools.com/css/css3_buttons.asp) to learn how to achieve the desired effect.

When creating my README I used the website [makeareadme.com](https://www.makeareadme.com/) and the following [markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) from GitHub to assist.

I used the work history timeline idea from the [codeinstitute](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2024_Q1/courseware/616289d66b5641a3808cc43e53842695/a3bcedac97ea4678953a75f07ffd6931/) tutorial and modified it to create my own style of timeline for my work experience page.

I used the code from this site by [samanthaming](https://www.samanthaming.com/tidbits/57-styling-css-placeholder/) to learn how to style parts of my form.

## Testing <a name="testing"></a>

### Code Validation <a name="code-validation"></a>

I used the [W3C Markup validation service](https://validator.w3.org/) to check the validity of my code.
This highlighted a number of errors and warnings.

![Screenshot of errors](/assets/images/code_validation_errors.jpg)

The trailing slash at the end of link to the font awesome stylesheet was removed.

I had also used spacing in the names of two of my HTML files and these were replaced with underscores and the 
links updated across the navigation bar.

![Screenshot of errors](/assets/images/code_validation_errors_2.jpg)

These errors occured as i had missed the closing tag for the anchor elements in the footer, these were added in.

As these elements navigation and footer were present in all pages, the corrections were made for all files and 
following that my code passed the validations and no more errors or warnings were given.

![Screenshot of no errors message](/assets/images/code_validation_corrected.jpg)

My CSS passed validation with no errors found.

![Screenshot of no errors message for CSS](/assets/images/css_validation_no_errors.jpg)

### Bugs <a name="bugs"></a>

 Fixed about me link buttons to have whole button clickable not just text - The 
 anchor element were only around the text of the buttons at the bottom of the index 
 page, I moved them around the div itself so that not only the text was clickable.
 
 The fade in animation for the containers which have the page content in was only 
 targetting the .context-box class and not the project-box class, as the containers 
 on the porfolio page had some different CSS rules to the main ones, this class was
 added to the fadeInAnimation so that all containers had the same effect.

## Deployment <a name="deployment"></a>

This project was developed using Microsoft Visual Studio Code, commited to Git and 
pushed to GitHub using the terminal with in VScode.

I had initially begun using [codeanywhere](https://codeanywhere.com/) which is a cloud
integrated development environment, which runs from a web browser. But after some issues
with long wait times to create the virtual environment and in some instances being unable 
to create one, I moved to using Microsoft Visual Studio Code which I had some experience 
with. This allowed me to work more efficiently and able to work quickly when I had 
limited time.

The final Live version of site is hosted on GitPages [here](#link), instructions on how
to create a site on GitHub pages can be found [here](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)


