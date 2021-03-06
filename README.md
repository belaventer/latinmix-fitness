# LatinMix Fitness

![LatinMix Fitness Mockup](https://github.com/belaventer/latinmix-fitness/blob/master/screenshots/mockup-screenshot.png "LatinMix Fitness Mockup")

[Demo of Website](https://belaventer.github.io/latinmix-fitness/).

An intuitive website for LatinMix Fitness, a new dance academy focused on Latin rhythms with a fitness twist.
The website showcases the offered classes and its respective timetable, membership options, contact and directions information.
The main goal of the website is to attract new customers.

Business goals includes:
- Increase the number of registered clients.
- Establish brand awareness.
- Showcase offered services effectively.
- Display contact and directions information.

Customers goals includes:
- Find fun and compelling exercise classes information.
- Clear access to membership plans and how to pay instructions.
- Easily find contact information and directions of dance academy.

## UX
### User stories
1.	As a new visitor to the website, I want to easily navigate throughout all pages of the website.
2.	As a new visitor to the website, I want to clearly identify what classes that are being offered.
3.	As a potential client, I want to learn more about each individual class.
4.	As a potential client, I want to easily find the directions to the facility as the business contact information.
5.	As a potential client, I want to find clear pricing and payment instructions.
6.	As an existing client, I want to be on top of all updates on classes and offers.

### Strategy 
The website must display the product offered clearly and have all contact information and direction presented to the user.
As Latin rhythms can look challenging for new learners, it is interesting to detail each class and showcase a small video in a fun and inviting way.
It is also of interest to display a gallery and the business history; however, the content is not currently available as LatinMix Fitness is a new facility.

### Scope
It was deemed of most importance to present the classes and contact / directions to the potential client.
Clear pricing is an important aspect of B2C design and easy to implement, so it should be included on the first website release.
About page and Gallery page are not feasible for the current website release, as resource is not available. 

### Structure
The website is design so the user can get all the required information to book a class from the main Home page.
The information is structured to answer the following questions in descending order “What is this business?”, “What are the classes offered and time?”, “How much it costs?”.
Also, from the Home page the user can access further information on each section.
The structure for every remaining page will be user friendly and expand on the Home page information on small units of details.

### Skeleton
- [Home Page](https://github.com/belaventer/latinmix-fitness/blob/master/wireframes/home-wireframe.pdf)
- [Classes Page](https://github.com/belaventer/latinmix-fitness/blob/master/wireframes/classes-wireframe.pdf)
- [Plans Page](https://github.com/belaventer/latinmix-fitness/blob/master/wireframes/plans-wireframe.pdf)
- [Contact Page](https://github.com/belaventer/latinmix-fitness/blob/master/wireframes/contact-wireframe.pdf)

#### Deviations from planed wireframes
- Footer information for mobile screens was stacked instead of shown inline as the content would not fit.
- Plans will not have the images with the option as initially planned and the mobile view will not be restrained at 1 view height, as content would be too small.

### Surface
#### Colour
The website will use vibrant colour palette to evoke fun and exciting feelings.
The colour palette used is extracted from the hero image and have tones of green (eggshell) and vibrant pinks.

#### Typography
Headings will follow the logo font-family “Abhaya Libre” with slight increased letter spacing for better readability.
All other text will be set to font-family “Open Sans”.
Default fallback font-family: "sans-Serif".

## Features
On **every page** there is a Navigation Bar at the top of the page. 

On **every page** there is a Footer at the very bottom of the content.

On the **Home** page:
- At the top, full width hero image and inviting text.
- Below the hero image, a small compelling "About Us" section.
- Below the "About Us", there is the “Our classes” section. Four images spaced evenly on the page representing each style.
- Below the “Our classes” section, there is the “Find your Plan” call to action. This will link to the Plans page.
- Below "Find your Plan", a small gallery to reinforce business credibility.
- The last section of the Home page is the “Join Us” with the business address.

On each **Class** page:
- There will be an embedded video player showing the dance.
- Bellow video player there is a short description on the dance style.
- The class timetable is further detailed with the class time.
- Lastly a button to "Contact Us" and book a class.
- The entire page should fit the screen height to follow approach of small unit of information.

On the **Plans** page:
- The three plans options will be displayed.
- The flow of information will fall right to left and back to right to be dynamic.
- Brief text to explain payment methods at the bottom.
- Lastly a button to "Contact Us" and book a class.

On the **Contact** page:
- The user has two options of contact: sending a query via form or contacting directly from details provided.
- Users will also be presented with option to register for the business newsletter. 
- On mobile the options will be displayed in block (vertically).
- On table and desktop, two options will be displayed in line (horizontally).


### Existing Features
- **Navigation Bar** feature: on the left side, there is the **Header Logo** linking back to the **Home** page.
- **Navigation Bar** feature: on the right side, there are links to **Home**, **Classes**, **Plans** and **Contact** pages. **Classes** pages are under a dropdown menu expandable when clicking.
On **Mobile** all links are collapsed into the Hamburger Symbol.

- **Footer** feature: on the left side, there is the Business contact information.
- **Footer** feature: on the right side, there is the social media icons links (Facebook, Instagram and LinkedIn).
- **Footer** feature: items on footer are responsive. On **Mobile**, they are shown stacked. On medium to larger screens, information is shown inline.

- **Hero-image** feature: when the home page is loaded, the hero-image is displayed below the **Navigation Bar** and the inviting text moves left to right to catch attention.

- **About Us** feature: below the hero-image, the **LatinMix Logo** is visible with a short description text enforcing the business idea.

- **Classes** Home page feature: 4 images are displayed to link to the Class page.
   On mobile they are stacked with the text and button visible.
   On tablet they are 2 side by side with the text and button visible.
   On web they are displayed 4 in line and text is invisible. On hover, the text and button become visible.

- **Plans** Home page feature: blinking affordable price, small assuring paragraph for the customers and a call to action button linking to the **Plans** page.

- **Gallery** Home page feature: small gallery with five pictures thumbnail that can be clicked, and full size is shown on modal. Modal also allows for sliding through the images.
   On mobile, the images are stacked.
   On tablet, the images are on 2 or 3 rows. 
   On desktop, the images are in line.

- **Contact** Home page and Contact page feature: small section with business address and embedded Google Maps.

- **Contact Forms** Contact page feature: two forms are available on the contact page. One is for miscellaneous queries and the second is an option to subscribe for the Newsletter.
All fields are required on both forms.

- **Plan Options** Plans page feature: the three available options will appear one after another once the page is loaded.
The button at the bottom of the page will re-direct to the "Contact" page.

- **Video** Classes page feature: the embedded Youtube video is available on each Class page which the user can interact as wishes.

### Features left to implement
Currently the business does not have a YouTube Channel, but it plans to create one in the future.
Once the channel is created, the Footer of every page must be updated with the YouTube account and link.

Currently the business owner could not provide enough media resource for a full Gallery page.
Once more photos and videos of the classes are taken, a Gallery page must be developed, following the same design used on the website.
The Navigation of all pages will be updated to include Gallery link. Gallery section on Home page to be update on call to action button "Show me more".

The business owner wishes to include an full About Us page on the first-year anniversary of the business.
The owner must return with content to be included on page for the history and team of the LatinMix Fitness.
An About Us page must be developed, following the same design used on the website. The Navigation of all pages will be updated to include About Us link.

The business owner wishes to create an application for booking the classes online, where users can pick dates and time of the classes after log-in on the website.
If a class is fully-booked classes, users would be able to join a waitlist in case of cancelations.
The current budget, time constraint and developer knowledge does not allow for this feature.

## Technologies used
### Languages
- HTML | HTML5
- CSS | CSS3

### Libraries, Frameworks & Programs
- [Gitpod](https://gitpod.io/workspaces/):

    The developer used Gitpod as the IDE for building the website.
- [Bootstrap v4.5](https://getbootstrap.com/):

   Used for Navigation Bar, grid layout, modal and carrousel of Gallery.
- [Google Fonts](https://fonts.google.com/):
   
   Used to import “Abhaya Libre” and “Open Sans” fonts.
- [Fonts Awesome v5.15](https://fontawesome.com/):

   Used to include Social Media Icons on the footer, pointer at "Find your plan" button and camera at gallery.
- [Hover.css](https://ianlunn.github.io/Hover/):

   Used for hover effect on classes cards and "Find your plan" button on Home page.
- [Clip Studio Paint](https://www.clipstudio.net/en/):

   Used for images resizing and colour adjustments.
- [AutoPrefixer](https://autoprefixer.github.io):

   Used on CSS to ensure functionality accross browsers.

## Testing
Refer to [TESTING.md](https://github.com/belaventer/latinmix-fitness/blob/master/TESTING.md) file for testing details.

## Deployment
This project was developed using the Gitpod IDE, committed to git and pushed to GitHub.

### Deploy to GitHub Pages from GitHub Repository:
- Login to GitHub.
- Search for the repository belaventer/latimix-fitness and select it.
- Select Settings on the Menu under the Reposity name.
- Under "GitHub Pages", use Branch drop-down menu and select Master Branch as the publishing source.
- The page will be refreshed and the website is deployed. Return to GitHub Pages section to view the link to the deployed website.

At the moment of submitting this Milestone project the Development Branch and Master Branch are identical.

### Run the project locally:
- Ensure you have Gipod Browser Extention for Chrome and you are logged in Gipod with your GitHub account. 
- Login to GitHub.
- Search and select the GitHub repository belaventer/latinmix-fitness.
- Click the green "Gitpod" button in the top right corner of the respository.
- A new Gitpod workspace will be created from the repo in GitHub and you can start working locally.

### Dowload project to local IDE:
- Login to GitHub.
- Search for the repository belaventer/latimix-fitness and select it.
- Under the repository name, click on Code.
- In the Clone with HTTPs section, copy the clone URL for the repository.
- In your local IDE open the terminal.
- Change the current working directory to the desired cloned location.
- From the terminal run git clone with the copied URL.
- Your local clone will be created and you can start working locally.

## Credit
### Content
Salsa page content taken from [Wikipedia](https://en.wikipedia.org/wiki/Salsa_(dance)).

Samba page content taken from [Wikipedia](https://en.wikipedia.org/wiki/Samba_(Brazilian_dance)).

Zumba page content taken from [Wikipedia](https://en.wikipedia.org/wiki/Zumba).

Forró page content taken from [Wikipedia](https://en.wikipedia.org/wiki/Forr%C3%B3).

All other content was written by the developer.

### Media
Hero image photograph by Isaiah McClean “Welcome to Burlesque” obtained from [Unplash](https://unsplash.com/photos/j9PpIy_x4EE). The image resizing and hue adjustments performed by the developer with [Clip Studio Paint](https://www.clipstudio.net/en/).

Logo image created by the developer using [Canva Logo Generator](https://www.canva.com/).

Salsa thumbnail picture "Man and Woman Dancing" by Pixabay obtained from [Pexel](https://www.pexels.com/photo/active-dance-dancer-dancing-270789/).

Samba thumbnail picture "Woman in Brazilian Samba Carnival Costume with Colorful Feathers Plumage" by Max4e obtained from [Canva](https://www.canva.com/photos/MAEJYoFHZ2A-woman-in-brazilian-samba-carnival-costume-with-colorful-feathers-plumage/).

Forró thumbnail picture "Positive ethnic couple in elegant wear dancing on pavement" by Kamille Sampaio obtained from [Canva](https://www.canva.com/photos/MAEGL6Rh1w0-positive-ethnic-couple-in-elegant-wear-dancing-on-pavement/).

Zumba thumbnail and Gallery picture two "Group of Women Doing Exercise Inside The Building" by Andrea Piacquadio obtained from [Pexel](https://www.pexels.com/photo/group-of-women-doing-exercise-inside-the-building-3775566/)

Gallery picture one "Young Adult Man Exercising at Dance Class" by Iakov Filimonov obtained from [Canva](https://www.canva.com/photos/MAEN1dkzhHM-young-adult-man-exercising-at-dance-class/)

Gallery picture three "Grayscale Photography of Man Lifting Woman" by Norexy art obtained from [Pexel](https://www.pexels.com/photo/grayscale-photography-of-man-lifting-woman-3034188/).

Gallery picture four "Smiling Latina Enjoying Slow Foxtrot with African American Partner" by Iakov Filimonov obtained from [Canva](https://www.canva.com/photos/MAEN1d6mKSk-smiling-latina-enjoying-slow-foxtrot-with-african-american-partner/)

Gallery picture five "Young Adult Man Exercising at Dance Class" by Iakov Filimonov obtained from [Canva](https://www.canva.com/photos/MAEN1GKfVjg-young-adult-man-exercising-at-dance-class/).

Salsa video by Plesni Centar Mimbao on [Youtube](https://www.youtube.com/watch?v=tBEc9Kni6I0&feature=emb_title).

Samba video by Vanesca Pascaleon on [Youtube](https://8000-e79d1313-f9ce-4d13-98bd-0b202ed2904c.ws-eu01.gitpod.io/samba.html).

Zumba video by Don Omar on [Youtube](https://www.youtube.com/watch?v=8HpG0l9cLos&feature=emb_title).

Forró video by Bailando Escola de Dança de Salão - Fortaleza on [Youtube](https://www.youtube.com/watch?v=rkJ0Xn5U5Go).

### Code
Favicon added as per ["Add A Favicon to A Website in HTML | Learn HTML and CSS | HTML Tutorial | HTML for Beginners"](https://www.youtube.com/watch?v=kEf1xSwX5D8) by Dani Krossing

Navigation Bar inspiration from [Code Institute](https://codeinstitute.net/) Full Stack Development Course Boostrap Basecamp lesson.

Use of span class sr-only for screen headers on Social Links taken from [Code Institute](https://codeinstitute.net/) Full Stack Development Course Resume Mini-project lesson.

Use of animation for hero image text inspired by [Code Institute](https://codeinstitute.net/) Full Stack Development Course Resume HTML/CSS Love Running Project lesson.

[Bootstrap Documentation](https://getbootstrap.com/) was constantly referred to for the correct use of Bootstrap components and grid.

[W3Schools](https://www.w3schools.com/) referred to for general HTML and CSS syntax.

[Hover.css](https://ianlunn.github.io/Hover/) used for the Home page classes card hover effect with few modifications. Classes feature inspired by feature on [Sporty - WordPress Gym Theme](https://www.awwwards.com/sites/sporty-wordpress-gym-theme)
    
[Hover.css](https://ianlunn.github.io/Hover/) used for the "Find your plan" button hover effect with few modifications.

How to justify flex-item learned from [StackOverflow Post](https://stackoverflow.com/questions/32551291/in-css-flexbox-why-are-there-no-justify-items-and-justify-self-properties).

Source with API key for Google Maps iframe [MAPS.ie](https://www.maps.ie/create-google-map/).

Use of :focus:active for click and hold mouse button from [StackOverflow Post](https://stackoverflow.com/questions/16715274/what-is-the-mouse-down-selector-in-css).

Keeping the footer at the botoom solution found in [DEV post](https://dev.to/domysee/keeping-the-footer-at-the-bottom-with-css-flexbox-5h5f).

Embedded video steps from [Youtube Support](https://support.google.com/youtube/answer/171780?hl=en).

### Acknowledgment
I'd like to thank my mentor Ignatius Ukwuoma for the valuable feedback and advises.

I'd also like to thanks Anna Greaves and Jim Morel for the helpful talks on MS1 planning and README file writing.

## Disclaimer
This project purpose is only educational and the gym "LatinMix Fitness" portraited is a fictional business.

## Notes on Commits
Initially I had understood each new file required its own "Initial Commit", for that reason there are multiple "Initial Commits" on the revision history.
My Mentor has explained each project, conventionally, only have one "Initial Commit". This is a lesson learned to be applied for future projects.