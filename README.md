This repo contains my portfolio which was created with HTML and CSS. It is lightweight, fully responsive, and loaded with Awesome Font. The site was built as modular as possible to make shifting around styles and content easy. 
To view a live demo https://micheal13195.github.io/MickayPortfolio/

Content:
General
Images
Header Section
Lead Section
About Section
Experience Section
Education Section
Projects Section
Skills Section
Contact Section
Footer Section
Optional Sections


Images

By default, the site comes with several images, which are downloaded from the web.

Main background (images/lead-bg.jpg) - this is the main background image provided via Unsplash. Background size of at least 1920x1080
Favicon (/favicon.ico) - this is the favicon used for the page. Similar to the main bag, this can be kept or changed easily by replacing the favicon.ico with your new one.
Project image - these are the images associated with the projects under the project section. These are simply placeholders.

Header Section
The header section can be found within the <header> tag and simply contains an unordered list of anchors to different sections of the page. If you add a new section and want to be able to quickly navigate to it from the top, simply add another list element with an anchor that has the href of the ID of the section.

Lead Section

The Lead section is pretty straightforward, it contains an h1 for your name and an h2 for your title. It also contains a link that can be used to link to your resume should you wish to add it as well. 
The href attribute points to where my resume is stored and the download attribute is what triggers the download / provides the name of the file that will be downloaded when the user clicks the button (In this case, it will download as resume.pdf).

About Section

The About section contains concise information about me. 

Experience Section

The experience section creates a vertical timeline with all your relevant experience. 
The data attribute data-date is what is used to add a date to the associated timeline point. All that is required is a wrapping div (i.e. #experience-timeline) and nested divs to build the timeline. The h3, h4, and p tags are optional and the contents of the div can be styled however you wish.

Education Section

The Education section is a series of (.education-block) classes with some details associated with them. By default, it shows the school name, date, degree, and some additional details.

Projects Section

The Project section contains several .project elements that represent each of your projects. By default, it contains a 300x300 image under .project-image and relevant project information under .project-info.
This will add a link that says "View More Projects" under the current projects and when clicked, all projects in the "More-projects" div will be shown.

Skills Section

The Skills section is simply an unordered list that spits out a "Skill Cloud" with all the skills listed. 

Contact Section

Since the page is static, I opted to use the awesome Formspree to allow for a contact form without the need for anything else. To use it, you must have the page hosted on a server (loading a basic HTML page won't work) where a referrer header is generated. Also, simply add the email to the action.

Footer Section

The Footer contains an optional copyright where you can place your name as well as an unordered list of all of your social or coding-related profiles. By default, it contains Github, Stack Overflow, Facebook, Twitter, and Google Plus. You can add or remove them easily and simply use the Font Awesome icon associated with the social profile you wish to use. For a list of all icons,

