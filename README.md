# Aleksandra Kula - The story of space 
Code Institute, User - Centric frontent development 2019
# Project purpose

This is educational project for elementary school students. They come to the website with questions in need of answering and learn about our Solar System. The purposes of this project are to promote STEM subjects in elementary schools. 
while learning how to build good looking responsive websites by just using CSS3.

## Demo 

Live demo can be found here: https://olaqla.github.io/First-Milestones-Project/

![](gallery_img/DEMO.png)

## UX 
- In my design of user experience I chose to use rather dark theme that would be consistent with 
the main topic of the website:

    - ![#515a5f](https://placehold.it/15/515a5f/000000?text=+) `#515a5f`

    - ![#05122e](https://placehold.it/15/05122e/000000?text=+) `#05122e`
    
- Roboto font used throughout the website for paragraphs font-family: 'Roboto', sans-serif;
- Exo font used throughout the website for headings font-family: 'Exo', sans-serif;

As one of the main purposes of this website is  learning CSS3 I chose to use different layouts on the pages to make sure that I cover using the latest layout techniques as grid and flex as well as traditional methods using floats, all in responsive fashion.


## Features:

* Front page including model of Solar System with true scaled time flow
* Big bang page with timeline
* Sun page with float based layouts
* Main planets page with Grid based layout
* Individual planet pages with flex based layouts
* Discoveries page with events and linked videos using flex layout
* Gallery laid out on a grid layout
* Responsive top menu that changes into hamburger menu on devices with small screen resolutions
* All pages responsive and designed using mobile first principles 
* Footer with social media buttons
* Hosting and deployment
* Site is made crispier using animations and transitions
* Documentation - ReadMe File
* Code is version controlled
* Manual testing

### Main menu

Main menu on top of the page is responsive. It is a page-wide stripe of horizontally laid out buttons on bigger screens and turns into a hamburger menu on mobile devices and small screens. 
In order to provide smoother user experience buttons are animated when the page is loaded and also provide a visual feedback effect by getting slighty bigger and changing text color when hovered over. 
Planets dropdown is built using relative positioning of elements and is available as a static page on smaller screens. 
Each of the menu options opens a subsection covering a specific topic. 

### Planet pages

Main planets page is built with CSS grid and each of the images link to a page about specific planet. 
All planet pages use the same layout with a single relevant image and a text that describes it. 

### Gallery page

Gallery page was built using CSS grid and flex to provide interesting layout of images. The layout changes to a scrolable list on small devices. 

### Footer

Footer contains few social media buttons that link to important pages where users can find more up to date information. 

## Technologies

1. HTML 5 
   - HTML for document structure
2. CSS3 (Selectors, Grid, Flex, Floats, Positioning, Transitions, Media Queries) 
   - CSS for document Styling
3. JavaScrit
   - Minimal javascript to open/close hamburger menu
4. Google Chrome
   - Used for browsing, testing and a debugging and development tool
5. Bootstrap
   - Minimized bootstrap library for icon support
6. Git used for Version Control
7. GitHub
   - Repository hosted on GitHub
8. Github Pages
   - Website hosted on Github Pages
9. Am I Responsive
   - Testing responsiveness of the website
   
## Testing 

- Website was tested manually using multiple browsers
- Each html file was tested in multiple screen resolution and in mobile device modes, available in browsers developer tools. 
- All links have been manually tested to ensure that they are pointing to the correct destination. 
- Checked if all alt attributes are add on any img tag on website and if it describes what’s on it. Screen readers for the blind and visually impaired will read out this text and therefore make image accessible.
- All pages were tested for HTML validity 
- All pages were tested for CSS validity

Browsers used for testing: 

| Browser name        |
| ------------- |
| Google Chrome |
| Microsoft Edge |
| Opera |
| Mozilla Firefox |

Browser test results: 

| Browser name        | Page name | Test result | Fixed |
| ------------- | ------ | ----- | ------ |
| Google Chrome | Homepage | OK :heavy_check_mark:|| 
| Microsoft Edge | Homepage | OK :heavy_check_mark:||
| Opera |Homepage |OK :heavy_check_mark:||
| Mozilla Firefox |Homepage |OK :heavy_check_mark:||
| Google Chrome | Big bang | OK :heavy_check_mark:| |
| Microsoft Edge | Big bang |OK :heavy_check_mark:||
| Opera | Big bang |OK :heavy_check_mark:||
| Mozilla Firefox |Big bang |OK :heavy_check_mark:||
| Google Chrome | Sun | OK :heavy_check_mark:| |
| Microsoft Edge | Sun | OK :heavy_check_mark:||
| Opera |Sun |OK :heavy_check_mark:||
| Mozilla Firefox |Sun | OK :heavy_check_mark:||
| Google Chrome | Planets main |OK :heavy_check_mark:|| 
| Microsoft Edge | Planets main | rgb background didn't work|Fixed :heavy_check_mark:|
| Opera |Planets main | OK :heavy_check_mark:||
| Mozilla Firefox |Planets main | OK :heavy_check_mark:||
| Google Chrome | Planets individual | OK :heavy_check_mark:|| 
| Microsoft Edge | Planets individual | rgb background didn't work| Fixed :heavy_check_mark:|
| Opera |Planets individual | OK :heavy_check_mark:||
| Mozilla Firefox |Planets individual | OK :heavy_check_mark:||
| Google Chrome | Moon | OK :heavy_check_mark:| |
| Microsoft Edge | Moon | OK :heavy_check_mark:||
| Opera |Moon | OK :heavy_check_mark:||
| Mozilla Firefox |Moon | OK :heavy_check_mark:||
| Google Chrome | Discoveries | OK :heavy_check_mark:|| 
| Microsoft Edge | Discoveries | Frame was moved| Fixed :heavy_check_mark:|
| Opera |Discoveries | OK :heavy_check_mark:||
| Mozilla Firefox |Discoveries | OK :heavy_check_mark:||
| Google Chrome | Gallery | OK :heavy_check_mark:| |
| Microsoft Edge | Gallery | OK :heavy_check_mark:||
| Opera |Gallery | OK :heavy_check_mark:||
| Mozilla Firefox |Gallery | OK :heavy_check_mark:||

Brosers and virtual devices used for responsiveness testing: 

| Device name    |
| ------------- |
| Galaxy S5 |
| Pixel 2 |
| iPhone 5/SE |
| iPad |
| iPad Pro |


Responsiveness test results: 

| Device name        | Page name | Test result | Fixed |
| ------------- | ------ | ----- | ------ |
| Galaxy S5 |Homepage | OK :heavy_check_mark:||
| Pixel 2 |Homepage | OK :heavy_check_mark:||
| iPhone 5/SE |Homepage | OK :heavy_check_mark:||
| iPad |Homepage | OK :heavy_check_mark:||
| iPad Pro |Homepage | footer was positioned incorrectly|Fixed :heavy_check_mark:|
| Galaxy S5 |Sun | OK :heavy_check_mark:||
| Pixel 2 |Sun | OK :heavy_check_mark:||
| iPhone 5/SE |Sun | OK :heavy_check_mark:||
| iPad |Sun | OK :heavy_check_mark:||
| iPad Pro |Sun | footer was positioned incorrectly|Fixed :heavy_check_mark:|
| Galaxy S5 |Big bang | OK :heavy_check_mark:||
| Pixel 2 |Big bang | OK :heavy_check_mark:||
| iPhone 5/SE |Big bang | OK :heavy_check_mark:||
| iPad |Big bang | OK :heavy_check_mark:||
| iPad Pro |Planets main | footer was positioned incorrectly|Fixed :heavy_check_mark:|
| Galaxy S5 |Planets main  | OK :heavy_check_mark:||
| Pixel 2 |Planets main  | OK :heavy_check_mark:||
| iPhone 5/SE |Planets main  | OK :heavy_check_mark:||
| iPad |Planets main  | OK :heavy_check_mark:||
| iPad Pro |Planets main  | footer was positioned incorrectly|Fixed :heavy_check_mark:|
| Galaxy S5 |Planets individual  | OK :heavy_check_mark:||
| Pixel 2 |Planets individual  | OK :heavy_check_mark:||
| iPhone 5/SE |Planets individual  | OK :heavy_check_mark:||
| iPad |Planets individual  | OK :heavy_check_mark:||
| iPad Pro |Planets individual  | footer was positioned incorrectly|Fixed :heavy_check_mark:|
| Galaxy S5 |Moon  | OK :heavy_check_mark:||
| Pixel 2 |Moon   | OK :heavy_check_mark:||
| iPhone 5/SE |Moon   | OK :heavy_check_mark:||
| iPad |Moon   | OK :heavy_check_mark:||
| iPad Pro |Moon   | footer was positioned incorrectly|Fixed :heavy_check_mark:|
| Galaxy S5 |Discoveries  | OK :heavy_check_mark: ||
| Pixel 2 |Discoveries    | OK :heavy_check_mark:||
| iPhone 5/SE |Discoveries   | OK :heavy_check_mark:||
| iPad |Discoveries   | OK :heavy_check_mark:||
| iPad Pro |Discoveries  | footer was positioned incorrectly|Fixed :heavy_check_mark:|
| Galaxy S5 |Gallery  | OK :heavy_check_mark:||
| Pixel 2 |Gallery     | OK :heavy_check_mark:||
| iPhone 5/SE |Gallery    | OK :heavy_check_mark:||
| iPad |Gallery  | OK :heavy_check_mark:||
| iPad Pro |Gallery   | footer was positioned incorrectly|Fixed :heavy_check_mark:|

## Deployment / Hosting

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.
No deployment process other than configuring repository were necessary.

Deployment process involved:

- Create Git repository on GitHub
- Commit code and code updates to Git repository on GitHub
- Enable hosting setting on GitHub pages
- GitHub pages pointed to host master branch
- Ensure root folder contains README.md and index.html files

To deploy your own version of the website:

- Have git installed
- Visit the repository
- Click 'Clone or download' and copy the code for http
- Open your chosen IDE (Cloud9, VS Code, etc.)
- Open a terminal in your code root directory
- Type 'git clone ' followed by the code taken from github repository
  (git clone https://github.com/OlaQla/First-Milestones-Project.git)
- When this completes you have your own version of the website (You can make any changes to it)
- The website can be run by opening one of the HTML files in a web browser
- Saved changes to the website will appear locally after refreshing the page

## Credits

### Media

All the images are linked to images found in google search results.
The pictures in gallery were downloaded from google result links and scaled down.
Videos are linked to youtube.

### Acknowledgements

- Styles used to build solar system model were crafted manually, following inspiration from: https://codepen.io/kowlor/pen/ZYYQoy
- https://www.nasa.gov
- https://kids.nationalgeographic.com
- https://www.wikipedia.org
- "Outer Space" By Ruht Martin, Templar publishing 2006, ISBN 978-1-78370-249-7

** Purpose of this project is educaional **
