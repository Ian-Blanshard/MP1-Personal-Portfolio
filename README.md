# Ian Blanshard Portfolio website

Live version of site hosted on GitPages [here](#link)

---
## Contents

1 [User Experience (UX)](#UX)

  * [Project Goals](#project-goals)
  * [User Stories](#user-stories)
  * [Wireframes](#wireframes)

2 [Features](#features)

3 [Technologies Used](#technologies-used)

4 [Credits](#credits)

5 [Testing](#testing)

  * [Bugs](#bugs)
  * [Code Validation](#code-validation)

6 [Deployment](#deployment)

## User Experience (UX) <a name="UX"></a>
### Project Goals <a name="project-goals"></a>
### User stories <a name="user-stories"></a>
### Wireframes <a name="wireframes"></a>
I used [figma](www.figma.com) to create wireframes for my project to get some of the ideas for layouts designed prior to starting to code them.

![Screenshot of wireframes](/assets/images/figma_basic_page_layout.jpg)

![Screenshot of wireframes](/assets/images/figma_contact_page_layout.jpg)

![Screenshot of wireframes](/assets/images/figma_porfolio_page_layout.jpg)

![Screenshot of color scheme](/assets/images/color_scheme.jpg)

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

[Bootstrap CSS](https://getbootstrap.com/) framework is utalized to structure the website, allowing me to easily create a responsive website
and create a quick and easy to use navigation bar.

[Git](https://git-scm.com/) and [GitHub](https://github.com/) for version control and as a repository.

[FontAwesome](https://fontawesome.com/) was used for the logos of Linkedin, GitHub and Facebook. These logos formed part of the footer 
and were used as links to the sites.

[Google Fonts](https://fonts.google.com/) was used to browse, select and as a source of the font I used on this site.

## Credits <a name="credits"></a>

https://developer.mozilla.org/en-US/docs/Web/CSS

https://getbootstrap.com/docs/5.3/getting-started/introduction/

https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

https://www.geeksforgeeks.org/how-to-create-fade-in-effect-on-page-load-using-css/

https://www.makeareadme.com/

https://stackoverflow.com/questions/42523147/place-part-of-form-group-in-different-column-using-bootstrap-grid

https://www.w3schools.com/css/css3_buttons.asp

https://www.youtube.com/watch?v=R3UGK1RhY6I

https://blog.hubspot.com/website/typing-animation-css

https://pokemonpalette.com/


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


