# Fases of the Moon

This is an interactive application  made in html and Css. 

<img width="600" alt="image" src="https://user-images.githubusercontent.com/90154152/224174569-df7f06b2-aca4-4e8d-8491-80180b5dbc9f.png">


## Table of content 
   * [Ideas and inspirations](#ideas-and-inspirations)
   * [Process](#process)
   * [Challanges](#challenges)
   * [Failures](#failures)
   * [Lessons](#lessons-learnt)
   * [Wishlist](#what-i-wanted-to-add-to-my-application)
   * [Reflection](#reflection)
   * [Resources](#resources)
   
   ***


## Ideas and inspirations.
 I started this project by looking for inspirations since i had no idea of what i wanted to do or how to start with this project. I then got an idea to 
 do something with the moon and skies. I started searching for examples of the nice illustrations of the skies. 
 
 These are what i found: 
 
 Moon and stars 
 
 <img width="441" alt="image" src= "https://user-images.githubusercontent.com/90154152/224176766-5ecf1c09-48c1-4eb7-b534-037fb15bd1a3.png">
 

 
 Fases of the moon
 
 <img width="441" alt="image" src= "https://user-images.githubusercontent.com/90154152/224176791-a089226a-38fb-42b4-bd85-43504779c31a.png">
 
 <img width="441" alt="image" src= "https://user-images.githubusercontent.com/90154152/224176913-e28eb745-44c7-433b-b1b1-b01470e201b5.png">
 
 <img width="441" alt="image" src= "https://user-images.githubusercontent.com/90154152/224177094-ebb8d8bd-b9f3-4ee7-9289-17f29bc3a855.png">
 
 
 ## Process
 
 Experimenting 
 
 Initially, I began my project by experimenting with gradients in Codepen. Given that I needed to create the different phases of the moon, I realized that using gradients would be crucial in achieving this goal. Fortunately, in the second week of the project, I participated in a workshop that focused on gradients. This workshop was particularly beneficial as it provided me with a deeper understanding of how gradients work and helped me to refine my techniques.



 I made a few notes about it which you can find [here](https://github.com/Whtneyas/css-to-the-rescue-2223/wiki/Gradients)
 
 
 I began experimenting what i learned during the workshop on my project. It took a lot of trials to get the gradients right. I had to combine the radial and linear gradients to get what i wanted. 
 
 
 <img width="382" alt="image" src="https://user-images.githubusercontent.com/90154152/224178305-f1309f4a-d470-4d75-9ba6-91a39990dc5c.png">
 
 
 
 ### Checkboxes 
 
 I am genuinely appreciative of attending the workshop on filters. My primary objective was to implement a filtering functionality in my project using checkboxes to enable users to filter the moon phases. The knowledge and skills I acquired from the workshop proved to be invaluable as I was able to apply what I learned to my project using the "has" selector.

As you may already know, the "has" selector in CSS is used to select elements that have a specific descendant element or set of descendant elements. This selector is incredibly useful as it allows you to style elements based on the presence of other elements within them. Although I recognize that there are numerous ways to utilize the "has" selector, due to time constraints, I chose to keep it simple.

In terms of how I benefited from using the "has" selector, I was able to achieve the following:

-I successfully implemented a filtering functionality that enabled users to filter the moon phases using forms.
-I was able to display the name of the moon phase when a checkbox was clicked, thanks to the "has" selector.

Overall, attending the filter workshop proved to be a critical factor in the success of my project, and I am extremely grateful for the opportunity to have participated.
 
 <img width="200" alt="image" src="https://user-images.githubusercontent.com/90154152/224180257-9a95f015-29ef-4d67-8c5c-32e092348059.png">
 
 **Changing from checkboxes to radio buttons.**
 
 
For my application i wanted to zoom in the moon when the checkboxes are being clicked. I forgot how checkboxes are. Checkboxes are used for selection more that one element while radio buttons are used for selecting one element out of two or more elements. I used checkboxes as a way of selecting the moon. So i needed to change it to make my application logical. 

### This is with checkboxes 

<img width="441" alt="image" src="https://user-images.githubusercontent.com/90154152/223774373-a670a7c9-0e79-494b-9a14-a13fef2b896d.png">


### And this is the code  the html code i used. 

<img width="441" alt="image" src="https://user-images.githubusercontent.com/90154152/223774566-adea69eb-2ae5-4193-8898-f9b77363431b.png">


 
  ***
 
 
 ### Challenges 
 
 
-  Making of the stars 

In my application, I intended to implement a zoom-in functionality for the moon when checkboxes were selected. However, I encountered an issue where I had mistakenly used checkboxes instead of radio buttons. As you may already know, checkboxes are primarily utilized for selecting multiple elements simultaneously, whereas radio buttons are intended for selecting a single option from two or more elements. Given that I required users to select only one option for the moon, it was necessary to alter my approach to ensure logical consistency in my application.

 
 <img width="441" alt="image" src="https://user-images.githubusercontent.com/90154152/224181403-538d4fa7-a90d-4fe6-bd81-65a0bfc023ea.png">
 
 
 
 
 - Changed the figure tag to list items 
 
Upon reflection, I determined that modifying the figure element to list items proved to be a more effective solution as it allowed my application to function precisely as intended. Specifically, I created a list of items within the unordered list (ul) and styled each item individually using the nth-of-type selector. However, as I progressed with this approach, I encountered a significant challenge in that styling each item was increasingly difficult, given that my application consisted of over 100 stars that required individual styling.
 
 - Progress Interview 
 
 After the progress interview with my lecturer Vasilis . He advised me to attend a workshop he is going to give called "Random". I guess you might be wondering what random is. But in this project Vasilis showed us how you can randomly style elements which i needed for making my stars. The work shop was a week ahead so i focused on making the fases of the moon.
 
 
 <img width="441" alt="image" src="https://user-images.githubusercontent.com/90154152/224182032-a7ae2cea-de9c-421f-b9ba-eff6f4318124.png">
 
  ***
  
 ### Failures.
 
 - Position of stars
 
 I wanted the stars to be randomly be positioned and then have this blinking effect but that couldn't work out. So i found a new method. I decided to make  the stars move from up and down and give the stars a different animation delay so that it will look randomly.
 
 
 - Circulating of the moon fases 
   
   I wanted to make the  moon move in a circular motion. I watched a few tutorial on how to make this circulation motion work. I tried animating the             container so that it will automatically affect the moon but it didn't totally as planned. It did circulate but not in the way i wanted.
   
 
  ***
### Lessons learnt

- How to animate using keyframes 
- The has () selector 
- Gradients 
- Color-mix 
- Box shadows 
- Css selectors 
- Styling of checkboxes 

 ***
 
### What i wanted to add to my application 

- Wanted to style the checkboxes 
- Description of the moon in the middle of the moon when the radio buttons  are been clicked.
- Wanted to do more with the backgroud. I was very indecisive whether to make it all black. 

 ***
 
 ### Reflection 
 
 I thoroughly enjoyed working on this project. Throughout the project, I gained a deep understanding of the different CSS selectors and how to use them effectively. The various workshops that were conducted during the project were incredibly helpful in expanding my knowledge and refining my skills.

I was delighted to implement what I learned during the workshops in my project. Initially, I found it challenging to create the stars that I envisioned. However, after attending the Random workshop, I was able to bring the stars to life. I applied the same technique to build the Web app from scratch, and it worked wonders.

Learning about the different types of gradients also proved to be useful. I used this knowledge to create the moon phases, and although it took some time to get the gradients just right, I was ecstatic with the results. Additionally, I discovered that using Codepen to experiment with code was incredibly beneficial before building my project in VSCode.

Overall, I feel that I have learned a great deal in these few weeks. If I had more time, I would have made some modifications to my project and added more functionalities to it. Nevertheless, I am proud of my work, even though it may not be groundbreaking, it still represents my best efforts. 

### Resources 

- https://css-tricks.com/
- Workshop - Gradients 
- Workshop - Random 
- Workshop - Has()
- Workshop - Kleuren
- Workshop - Interactie
- https://www.bing.com/search?q=stack+overflow&cvid=3d42846d09d94f13877ea371d405f754&aqs=edge.0.46j69i57j0l3j46j0l3.2881j0j1&pglt=43&FORM=ANNTA1&PC=HCTS
- https://www.w3schools.com/Js/
- Workshop - Svg filter .











 
 
 

 

 
 
 
 
 
 
 
 

 
 
 






 
 
 
