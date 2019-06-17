# milestone-1-student

This project is only built for my student assignment, 
although its ordered from a real person and company, also planned to fulfill their requirement.

## Deployment
Deployment using git and github hosting, see link below.
Git is used to push files up to github where i store the code for you to see. Wanna se the source code you just click on the file name index.html or style.css<br/>
   https://charlotteaneriksson.github.io/milestone-1-student/

## UX 
  Strategy:<br/>
    This project is made for horselovers, mainly horse buyers but also just them who have an interest. 
    Goals is to sell horses and get customer for upcoming breeding season.
    Want to advertice the breed and tell about the Team Kigers company.
  
  Scope:<br/>
    Gallery, pictures opens in new site when clicked. 
    Scroll-site but also a menu to get to the different sections.
    Social media buttons.
    Collapsed nav for MVP.
  
  Structure:<br/>
    History and facts go together, about the owner and a great picture, for sale and how to buy go together, 
    socail media and other cooperationlinks goes together.
    Grid is used the same on about, history and also for sale.
    
  Sceleton:<br/>
    Great attractive looking pictures are shown in parallax effect on desktop, 
    on smaller devices its just a fixed background that you scroll.
    Who Jessica is, then direclty to the selling part for priority, 
    gallery in the end so that you've seen all info before. 
    Gallery just makes you wanna buy even more strongly.
    
  Surface:<br/>
    Colors goes in blue, yellow, white and beige. 
    Horses are gray and beige and the buttons and links follows the logo color.
    Same hover and link color, consistant all over..

## Tecnologies
  - HTML5
  - CSS3
  - Bootstrap (v4.3.1.) 
  - Git
  - Github
  - VS Code IDE
  - Photoshop
  - Lightroom 
  
## Features
  - For sale block
  - Gallery
  - Collapsed nav
  - Social media icons in collapsed nav
  - Links opens in new tab
  
### Future features
  - Fully working contact form, connected to email.
  - Video section
  - Possibility to choose SV language on a button similar to collapsed manu button 
  
## Testing 
   Tested in Chrome, Chrome Devtools, Firefox, Microsoft Edge, Explorer (not much effects here but looks nice), Huawei and also live deployed in iphone.
   Looked real great. 
Glad I deployed in on github to see on a real mobal device cause Chrome Devtools did not really look the same acually, fixed a few bugs this way.
<br/>
Activated screen reader for Microsoft and tried, was working good.
Tested all links on all devices, works great.

### Bugs & Solutions
  1. Parallax with attachment:fixed; doesnt work on phone.
      - Solution: media queries from 1000px (covers ipad and smaller) attachment:scroll;
  2. Shrink pictures for optimizing loadingtime.
      - Solution: Shrink from 5200px to 1000px, also compressing them with tinypng.com 
  3. Sticky nav doesnt follow/work on mobile.
      - Solution: Used fixed instead;
  4. Horizontoll scroll bug
      - Solution: fixed with overflow-x: hidden;
  5. The logo-links didnt work on mobile, nothing happend while clicking on them.
       - Solution: Put id="destination" on other element then header.
  6. Some effects didnt work browser wide.
       - Solution: Tried adding autoprefixers for all browsers, some helped.
  7. Collapsed menu doesnt go away when clicked on a link, kind of ruining the UX when chosen a link.
       - Solution: https://www.youtube.com/channel/UC9500QCai-WdIiQGrbJ-i_A hade a great codeblock i could use to solve the issue.
       
## Credit

### Text 
The text are taken from the original up and running website, owned by Team Kiger Of Frejes. If not it is mentioned on the page.
Charlotte did the translation and choose the block of text for this deployment.

### Pictures
Owner of all pic used is Jessica Furman Monasdotter who gave me permission for this project and the use of her pictures.
Photoshop was used to shrink them to optimize the website. 
Lightroom was used to put a general filter on all pictures for better UX.
Alt attribute in img tag for screen readers.
Namned pictures after use direction

### Code inspiration 
developer.mozilla.org - bug fixe ideas
w3school.com - how to
getbootstrap.com/docs/4.3/components/navbar/
web-design-weekly.com - inspirations and mobile viewport info 
bootstrap documentaions - information, gallery ideas, nav ideas
css-tricks.com - bug fixer ideas
stackoverflow.com - bug fixer ideas
https://www.youtube.com/watch?v=5y6NFy5M9z8 - bugfixer menu collaps

