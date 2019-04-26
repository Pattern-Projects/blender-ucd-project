# Blender Enthusiast

An information website for Blender software. 
It gives a quality overview of the open source software.
Users can learn how to use Blender, see example uses and get involved in developing the software.
They can also download the software.

Hosted on [GitHub Pages](https://pattern-projects.github.io/blender-ucd-project/index.html)
Repository on [GitHub](https://github.com/Pattern-Projects/blender-ucd-project)

## UX
![Responsive Views of Home Page](documentation/responsiveness.png)

### Users 
Expected users of the website include 3D artists, educators, software developers and students of all kinds. 
They come to the website with questions in need of answering.

### User Stories
1. A student user wants to learn more about the blender software
2. A 3D artist user wants to download the latest version of blender
3. A technology enthusiast user wants a prerelease version of the software
4. A law student user wants to learn about the open software licence structure
5. An education professional user wants learn about the research process if blender
6. A 3D artist user wants to learn the software
7. A 3D artist user wants to improve their skills
8. An education professional user wants to share learning material with their students
9. A developer user wants to become involved in the developing of blender software

### Design
![Custom blender enthusiast logo](documentation/logo.png)
- Colour scheme made taken from blender logo colors
    - blender-orange:   ![#EA7600](https://placehold.it/15/EA7600/000000?text=+) `#EA7600`
    - blender-blue:     ![#0E548B](https://placehold.it/15/0E548B/000000?text=+) `#0E548B`
- [Custom designed logo](documentation/logo-no-text.png) using base shapes of the [blender logo](documentation/blender-logo.png)
- Profile style image box for the About page gives a personality to the software
- roboto font used throughout the website
    - font-family: 'Roboto', 'helvetica' sans-serif;

### Mockups

- [Home](https://www.figma.com/file/BAEdmRXdAFKWjGLucREMVBd0/Blender-Enthusiast?node-id=0%3A1)  
- [About](https://www.figma.com/file/BAEdmRXdAFKWjGLucREMVBd0/Blender-Enthusiast?node-id=4%3A83)  
- [Help Out](https://www.figma.com/file/BAEdmRXdAFKWjGLucREMVBd0/Blender-Enthusiast?node-id=4%3A21)  
- [In Use](https://www.figma.com/file/BAEdmRXdAFKWjGLucREMVBd0/Blender-Enthusiast?node-id=6%3A97)  
- [Learn](https://www.figma.com/file/BAEdmRXdAFKWjGLucREMVBd0/Blender-Enthusiast?node-id=6%3A173)  
 
## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
### Planned Features
- Documentation - ReadMe File & Mockups
- Bootstrap - HTML, CSS Framework
    - Grid System - Columns and Rows
    - Cards
    - Icons
- Responsive design - Mobile First
- UX elements
    - User Flow
    - Animations
    - Transitions
    - Smooth Scrolling
- Accesibility
- Large Landing Page - Full screen landing image
- Semantic HTML - nav, article, etc
- Call to Action - Download Button
- Alert - Open Movie Call Out
- Social Buttons - Twitter, Discord, Linkedin
- Feedback Form
- Colour Scheme
- Custom Logo
- Favicon
- Testing
- Git - Version Control System
- GitHub - Remote Repository
- Deployed - Hosted on Github Pages

### Existing Features
- Documentation - ReadMe File & Mockups
- Bootstrap - HTML, CSS Framework
    - Grid System - Columns and Rows
    - Cards
    - Icons
- Responsive design - Mobile First
- UX elements
    - User Flow
    - Transitions
    - Smooth Scrolling
- Accesibility
- Large Landing Page - Full screen landing image
- Semantic HTML - nav, article, etc
- Call to Action - Download Button
- Alert - Open Movie Call Out
- Social Buttons - Twitter, Facebook, Slack, YouTube
- Colour Scheme
- Custom Logo
- Favicon
- Git - Version Control System
- GitHub - Remote Repository
- Deployed - Hosted on Github Pages

### Features Left to Implement
These features may be added at a later time.
- Video backgrounds
- Full page image background
- Resizible sections
- Auto-update software version downloads
- Animations
- Feedback Form
- Live feed

## Technologies Used

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
    - HTML for strucutre
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
    - CSS for Styling
- [Figma](https://www.figma.com)
    - Development made use of **figma** for creating mockups.
- [Inkscape](https://inkscape.org)
    - Custom logo created using **Inkscape**.
- [Bootstrap](https://getbootstrap.com/)
    - HTML and CSS Framework from **Bootstrap**
- [Font Awesome](https://fontawesome.com/)
    - Icons used are sourced from **Font Awesome**
- [Cloud9](https://c9.io/)
    - This project was built using the **Cloud9** IDE
- [Github](https://github.com/)
    - Repository hosted on **Github**
- [Github Pages](https://pattern-projects.github.io/blender-ucd-project/in-use.html)
    - Website hosted on **Github Pages**
- [Colour Scheme Designer](https://colorschemedesigner.com/csd-3.5/)
    - Colour scheme developed using **Colour Scheme Designer**
- [Google PageSpeed Insight](https://developers.google.com/speed/pagespeed/insights/)
    - Used to test the websites performance efficiency
- [Nu HTML checker](https://validator.w3.org/nu/)
    - Used to test the website for errors

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

### HTML Check

Using W3's [Nu HTML Checker](https://validator.w3.org/nu/)
![Warning: The document is not mappable to XML 1.0 due to two consecutive hyphens in a comment.](documentation/comment-issue.png)

### Performance

Using Google's [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) the website was tested for network performance.
The results were:
- Desktop:  100%
- Mobile:   99%

Suggestions provided to improve mobile performance include:
- Serve images in next-gen formats
- Eliminate render-blocking resources

### Bugs
1. Home screen - large image fit changes by screen
    ![Mobile view with and without browser bar](/documentation/format-mobile.png)
    - On mobile the browser bar pushes down the webpage.
    - Bottom of the page is off screen
2. Irregular image error on firefox.
    - [Image corrupt or truncated.]
    - [This StackOverflow link refers to JQuery as the source of the issue](https://stackoverflow.com/questions/32459621/how-to-handle-image-corrupt-or-truncated-in-firefox)
    - Bootstrap jquey links added to the bottom of the pages are the likely culprit
    - Further investigation required

### Bug Fixes
1. test-file.txt not downloading after dialog box
    - The file was not stored in assets folder so that addresses were incorrect
    - Moved test-file.txt to the assets folder
    - Issue resolved
2. Cannot move navbar items to the right
    - navbar div had a mr-auto class holding it in place
    - Changed it to ml-auto
    - Issue resolved

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

The project is hosted on [GitHub Pages](https://pattern-projects.github.io/blender-ucd-project/index.html)

The process involved:
- Host a git repository on GitHub. Explained [here](https://help.github.com/en/articles/create-a-repo).
- root folder contains README.md and index.html files
- On GitHub repository settings page move to GitHub Pages section
- Change source to master branch. (Or any desired brance)
- Provided link will be your projects home (index) page.

The benefits of hosting your website on GitHub pages is that any pushed changes to your project will automatically update the website. Development branches can be created and merged to the master when complete.

It may take a moment for changes to appear on the hosted website.

During development the site is hosted using cloud9's local server feature. It runs in the browser.

## Credits

### Content
Some of the text on the website has been copied from:  
- [blender.org](https://www.blender.org/)

### Media
The images for the website are taken from:
- [blender.org](https://www.blender.org/)
- [Manuel Peter](https://www.artstation.com/manuel-peter)
- [Matuesz Wielgus](https://www.artstation.com/mateusz_wielgus)
- [Guilherme Henrique](https://www.artstation.com/sepultura)
- [Lukas Walzer](https://www.artstation.com/lukas_walzer)
- [Rico Cilliers](https://www.artstation.com/ricocilliers)
- [Lester Banks](https://lesterbanks.com/2014/10/demolishing-building-blender/)
- [LinkedIn Learning](https://www.linkedin.com/learning/sculpting-a-game-asset-in-blender)
- [Udemy](https://www.udemy.com/character-animation-for-beginners/)
- [User Elbrujodelatribu - Stack Exchange](https://blender.stackexchange.com/questions/5593/any-good-free-materials-libraries-online)

### Acknowledgements

Thank you to the following for inspiration, motivation and the direction I needed:

- Andrew Price
- Grant Abbitt
- Ton Roosendaal
- Blender Institute

- [CSS-Tricks](https://css-tricks.com/)


- Seun Owonikoko
- Code Institute