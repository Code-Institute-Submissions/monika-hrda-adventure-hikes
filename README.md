# Adventure Hikes
_“And into the forest I go, to lose my mind and find my soul.” - John Muir_

This is a website for a fictional hiking group Adventure Hikes. It primarily aims to inspire users to join the group on their outings. 

It was built as my first milestone project for Code Institute's Full Stack Software Development course, after I completed the HTML, CSS and User Centric Frontend Development modules. The topic for the project was chosen because hiking and adventure have always been close to my heart.

You can view the live website [here](https://monika-hrda.github.io/adventure-hikes/ "Adventure Hikes"). 
***
## User Experience (UX)

### User Stories

* As a new user, I want to easily understand what the purpose of the website is and what the group is about.
* As a new user, I want to be able to navigate the website easily, so that I can find any relevant content. 
* As a user, I want to be able to view the website clearly on my mobile device, so that I can achieve my other goals on the go.
* As a new user, I want to find some information about the group, its history and members, so that I can find out whether I would fit in.
* As a user, I want to be able to find out what new hikes or trips are organised, so that I can decide whether I want to join any of them.
* As a new user, I want to be able to find out how can I join any of the hikes or trips I am interested in.
* As a new user, I want to be able to see pictures from the group's past hikes and trips, so that I can get a feeling for the scenery on the hikes organised. 
* As a returning user, I want to be able to see pictures from the group's past hikes and trips, so that I can relive the ones I joined them on.
* As a user, I want to be able to find the group on social media, so that I can learn more and/or follow them / keep up with their updates.
* As a new user, I want to be able to contact the group, so that I can ask any specific questions and get more information.

### Design

* #### Colour Scheme

  Colours used on the website were chosen to represent nature, and specifically nature of Ireland (shades of green were picked). Emphasis was put on picking colour tones that would ensure a good contrast between text colour and its background. The resulting colour palette was created by Monika Hrda and can be found on the website [coolors.co](https://coolors.co/db6400-fad586-f3fae7-e5f5d7-d6efc7-9ea97c-3c3f26-282c10).

* #### Typography

  Open Sans font has been used as the main font, mostly for its high legibility and "friendly" appearance. In the unlikely case it is not imported into the website correctly, Sans Serif is the fallback font. 
  
  The second font used - for page headings and navbar - is Signika. It is easily readable, which makes it a great choice for use on smartphone screens as well.

* #### Imagery

  Images used on the website were selected with the intention of creating a friendly and welcoming effect (smiling people, a group of people hiking together), as well as showcase the nature of Ireland. The hero image is meant to draw the website visitor in, images in the events section depict the area each planned hike is taking place in, and images on the gallery page are meant to further interest the visitor in joining the group on one of their hikes.

  All of these photographs were taken by Monika Hrda, the website's author. They were optimized - resized and subsequently compressed on TinyJPG website - to not waste storage or bandwidth.

### Wireframes

After identifying high level content for the website (while working with all the user stories listed above), templates were first sketched out on paper. Wireframes were then created in Balsamiq, taking three different screen sizes into consideration - smartphone, tablet, and desktop. (As the desktop and tablet version almost do not differ (except the Gallery page which will see three images used per row in the tablet version, instead of the four used in the desktop version), I opted to leave the tablet one out from the following images in this case.)

Home page
![home page wireframe](wireframes/home.png)

Gallery page
![gallery page wireframe](wireframes/gallery.png)

Contact Us page
![contact us page wireframe](wireframes/contact-us.png)

***
## Features

### Existing Features

* Mobile-first design, with all pages fully responsive on all screen sizes.
* Fully responsive navbar, with menu collapsing on mobile devices and smaller screens.
* Home page with a callout section and a button prompting user to join the hiking group. The button is linked to the event section of the page.
* Event section displays any upcoming hikes the group is organising - currently one due to lockdown - with any relevant information on date, time, and location of the hike, and has a button placed on the event asking the user to contact the group for more information on how to join them. A photograph of the area to be hiked is displayed as well.
* Gallery page shows a number of photographs from previous hikes to tempt the user to join in.
* Contact form allows the user to contact the group with any queries. Name, email, phone and message fields are required to be filled in and the user's input is validated. There is no requirement for a full name to be given. The form is currently not submitting any data - that was not a requirement for this particular project, and can be implemented later on.
* Social media links in the footer redirect the user to the relevant social media pages; these open in a new tab.

### Features Left to Implement

* A login for existing members would allow the user to sign in for an advertised hike without the need to contact the organiser.
* Individual events displayed in the events section would lead to either a new page or an expanded section providing more information on the individual hike, an option to sign up, and details on the meetup location for the logged in user.
* Logged in members would have the option to upload their photographs to the gallery page.

***
## Technologies Used

* HTML
* CSS
* Bootstrap
* Font Awesome
* Google Fonts
* jQuery
* Git
* Github
* Gitpod
* Github Pages
* [Balsamiq](https://balsamiq.com/wireframes/) - to create wireframes for the website
* [TinyJPG](https://tinyjpg.com/) - to optimize JPEG images
* [coolors.co](https://coolors.co/db6400-fad586-f3fae7-e5f5d7-d6efc7-9ea97c-3c3f26-282c10) - to create a colour palette


***
## Testing

Testing of the website has been carried out throughout its development to ensure its proper functioning. The website was also continuously tested for **responsiveness** on varying screen sizes - both physical screens and also with the help of Chrome developer tools to substitute for other devices.

All **links** were checked and are working. Navigation links navigate to correct pages. Links leading to external websites open in a new tab.

**Buttons** invert their colour on hover and perform the appropriate functions.

The contact form is correctly **validating** the user's inputs.

[W3C HTML Validator](https://validator.w3.org/) was used to validate all pages and no errors are present.

[W3C CSS Validator](https://jigsaw.w3.org/css-validator/) was used to validate the project's stylesheet and no errors are present. 

***
## Issues and bugs found and resolved

* Placeholder for the textarea in the contact form was not showing up. After some googling I found out that both the opening and closing tag for 'textarea' need to be on the same line for the placeholder to appear.
* Content and 'Join Us!' button in the callout section was getting hidden on screen resizing / mobile phones in landscape mode. This was solved with two media queries.
* Vertical alignment of content on the event card was an issue. Solved with Bootstrap's grid and a solution found online (accredited in code). 

***
## Deployment

This project can be forked and deployed to GitHub Pages following these steps: 

1. Log in to GitHub and locate this project (you are most likely here). 
2. Locate the Fork button at the top right corner of the page and click it. 
3. In your copy of the project (repository) click on Settings button above the repository. 
4. Scroll down to 'GitHub Pages' section.
5. Click the 'None' button and select the master branch. 
6. Click on the 'Save' button. 
7. Scroll back down to the 'GitHub Pages' section and find the link to your newly publish site.

***
## Credits

### Code

* tutorials from Code Institute's User Centric Frontend Development and CSS modules
* official [Bootstrap](https://getbootstrap.com/docs/4.3/) website
* [W3Schools](https://www.w3schools.com/) website and its examples
* [Bootstrap navbar component](https://getbootstrap.com/docs/4.3/components/navbar/)
* tip on 'orientation: landscape' media query from https://forum.getkirby.com/t/detect-tablet-portrait-landscape/8720/3, and tip on 'hover: none' from https://stackoverflow.com/questions/42025632/how-to-detect-only-with-css-mobile-screens/42025819 and https://stackoverflow.com/questions/12469875/how-to-code-css-media-queries-targeting-all-mobile-devices-and-tablets

### Content

Content written by Monika Hrda.

### Media

All photographs used on the website were taken by Monika Hrda, the website's author.

### Acknowledgements

I would like to thank my mentor Antonio Rodriguez for his advice with the project, and also Mark McGann for his continuous support. Also, what a great resource the Code Institute's Slack channel is! Full of helpful, knowledgeable and friendly coders; thanks to each one of them.