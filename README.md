# Readme Milestone1

## Sources:
* https://getbootstrap.com/docs/5.0/components/navbar/
  - here I found the basic code for my navbar 
    which I edited to put the nav-brand on the left and align the rest of the links on the right
* https://getbootstrap.com/docs/5.0/components/carousel/
  - used the carousel code from bootstrap and edited it to make it look nicer
* https://getbootstrap.com/docs/5.0/forms/form-control/
  - used the example form from bootstrap

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
