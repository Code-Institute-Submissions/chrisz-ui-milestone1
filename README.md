# Milestone1 Chris' Portfolio
Chris' Portfolio is a site meant as a way for me to show my potential to
future employers. This site will be useful as a way to quickly introduce myself
and to get my contact info out there.
![mockup](/assets/img/milestone1.png)

## Wireframes
Read more [here](./assets/milestone1wireframes.pdf)

## Features
- quick introduction of myself
- gallery to show previous projects
- contact form
- links to other forms of contact

### Existing Features
- Navigation band
  - Fixed to the top to make it always possible to know where you are and who's site you're looking at
  - Makes it possible to move between sections without scrolling
- Home page
  - Quick introduction, and links to social and message form
  - Image to accompany introduction and show who I am
- About page
  - A little about me and mission statement
  - An overview of my current skills
- Projects page
  - Gallery to show previous projects
- Contact page
  - includes a form to send me a message
  - repetion of my social links

### Future Features
- download link for CV
- beter gallery

## Testing
- tested responsivenes with chrome developer tools
### Validator Testing
- HTML 
  - no errors were returned when passingg through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fchrisz-ui.github.io%2Fmilestone1%2F)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fchrisz-ui.github.io%2Fmilestone1%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)


## Deployment
The site is deployed to Github Pages using the following process: 
- In the GitHub repository, navigate to the Settings tab
- In the Settings tab go to Pages in the menu
- From the source section drop-down menu, select the Master Branch
- Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://chrisz-ui.github.io/milestone1/

## Credits
### Code
- https://getbootstrap.com/docs/5.0/components/navbar/
  - here I found the basic code for my navbar 
- https://getbootstrap.com/docs/5.0/components/carousel/
  - used the carousel code from bootstrap
- https://getbootstrap.com/docs/5.0/forms/form-control/
  - used the example form from bootstrap
### Media
- stock images used from 
  - https://libreshot.com/it/coffee-and-laptop/
  - https://libreshot.com/it/graphic-designers-desk/
- mockup generated at http://techsini.com/multi-mockup/index.php
### Extra
- This site couldn't have been made without all the people posting guides and anwsers 
- Also thanks to my mentor for staying positive






















## Sources:
* https://getbootstrap.com/docs/5.0/components/navbar/
  - here I found the basic code for my navbar 
    which I edited to put the nav-brand on the left and align the rest of the links on the right
* https://getbootstrap.com/docs/5.0/components/carousel/
  - used the carousel code from bootstrap and edited it to make it look nicer
* https://getbootstrap.com/docs/5.0/forms/form-control/
  - used the example form from bootstrap
- stock images used from 
  - https://libreshot.com/it/coffee-and-laptop/
  - https://libreshot.com/it/graphic-designers-desk/
- 


## Problems  
* can't get the menu to expand and show items inside
  - solution: hadn't yet included the javascript plugin, now I have and the menu works

* activate link in navbar when you reach that point through scrolling (make it bigger)

* change carousel slide indicator into circles
  - I wasn't targeting the css specific enough apparently. I added [data-bs-target] and it worked.
I finally found out about that by inspecting the element in chrome.

* stop the carousel from auto sliding

* the collapsed navbar stays open after clicking
  - I tried adding some data attributes found here https://stackoverflow.com/questions/42401606/how-to-hide-collapsible-bootstrap-navbar-on-click
  and that closed the navbar but also broke the links
  - 
