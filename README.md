<h1 align="center">Yoga Nature</h1>

[View the page here.](https://champion316.github.io/Yoga-Nature/biography.html)

Is a website intended for audiences that are interested in learning body/mind self-improvement techniques through yoga. This will be done by providing an instructor who is certified in yoga and will demonstrate the self-improvement techniques through recorded videos.  

<h2>User Experience (UX)</h2>

* ### User Stories
    * #### First Time Visitor Goals
        a. As a first time visitor I want to know what it is that makes this yoga page different than any other.
        
        b. Who is teaching the material and how much experience do they have.
        
        c. How much does it cost?

    * ### Returning Visitor Goals
        a. Can I contact the instructor if I have any questions?
        
        b. Is the material being updated at least on weekly basis? 
    
    * ### Frequent User Goals 
        a. Material that is really benefiting their overall health.

        b. Newsletter material is constantly providing more resources about yoga.

* ### Design
    * #### Color Scheme
        * I then had a color palette created on (**[coolors](https://coolors.co/)**). This was done by uploading the image and having it choose a palette which I can then adjust to my liking. This is the result I settled with in the end.

        * The colors from left to right in hexadecimal are as follows. 
            1. #aec6de
            2. #a3e3cb
            3. #f7ead7

        <img src="docs/collage.png" width="500" height="300"/>.

    * #### Typgraphy 
        * I used two different fonts for this page. "Mallanna" and "Rajdhani" with sans-serif as the fall back font. My preferred was "Rajdhani" visually it looked elegant with the hero-image.

    * #### Imagery
        * Imagery was important by choosing colors and a feel good image that would construct the rest of the page. It is not only about performing yoga but being in tune with nature as you do it.

* ### Wireframes
    * I did not use any wireframes for "Yoga Nature". I did however use a whiteboard and sketched out the layout as I coded. I find myself constantly changing the layout and felt that my time would of been better spent seeing my mistakes through the learning of code. Though I do kind of regret this approach by realizing the benefits of something like [balsamiq](https://balsamiq.com/) later on during after the inception of my website.

## Features
* Responsive for medium computer screens, this webpage was built using a Surface Pro 6 which has a resolution of (2736 x 1824)
    
* iPhone 5/SE - iPad - iPad Pro

## Technologies Used 

### Language Used 
* HTML5
* CSS3

### Frameworks, Libraries & Programs Used
1.  [Google Fonts](https://fonts.google.com/)
2.  [Font Awesome](https://fontawesome.com/)
3.  [Git](https://git-scm.com/)
4. [Github](https://github.com/)

# Testing
The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.
* [W3C Markup validator](https://validator.w3.org/#validate_by_input)
* [CSS Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)

### Testing User Stories from User Experience (UX) Section
* #### First Time Visitor Goals
    * As a first time visitor I want to know what makes this yoga page different than any other.
        1. Is the person teaching very knowledgable?
        2. Is the material easy to follow?
        3. What is the price for the courses?
    
    * As a first time visitor can I navigate the page?
        1. The nav-bar at the beginning of the page makes it simplistic to find all sections of the website.
        2. Every section of the nav-bar can be found in the index.html page separated by sections that give a small description of the nav-links.

    * As a fist time user I want to know the background of the person teaching
        1. The biography provides great detail into the personal life of the instructor
        2. The videos and the comfort in which the instructor explains her material are representative of her experience

* #### Returning Visitor Goals 
    * Connect with the material being taught.
        1. Great informative material
        2. Modern with the times 
        3. Clear explanation

* #### Frequent User goals 
    * What is the material/courses doing for my health?
        1. Has my health improved?
        2. Does the material expand beyond 2-3 body parts? 

    * Does the material stay true to the theme of body/mind techniques? 
        1. Has my mental health improved?
        2. Has my physical health improved?
        3. Am I better than I was before I started?

### Further Testing 
* The Website was tested on Google Chrome, Microsoft Edge, FireFox, and Safari mobile browsers.
* The website was viewed on a variety of devices such as Laptop, iPhone 5, iPhone SE.
* Testing was done on all the browers listed to ensure all links worked correctly. 

### Known Bugs
* On mobile device I would get white gap on the right side of the page 
    * Issue most likey stemmed from a large hero-image and floating issues on mobile
* One of the biggest issues I encountered later in my development process was text-alignment issues after the menu container.
    * Any section or div that came after the container at the top would push the text away from the left side of the screen and somewhere closer to the middle on the left side upper screen.  
        1. In the beginning I thought it was because I had my container in sticky.
        2. I tried position absolute and the issue still occured.
        3. I settled with position: static, but the issue persisted
        4. Luckily none of my pages required text at the left upper corner after id="container"

* On media devices in videos.html #videos-background has an overflow: auto which causes a thin line to appear when it meets with the footer.
    * Already so late in the development and for the sake of not creating more bugs with the other media devices that were already completed.
        1. I created a class="black-top-border" and used it on all media devices to cover the appearing line when scrolling to the bottom. 

## Deployment 
### GitHub Pages
* The project was deployed to GitHub Pages using the following steps...
    1. Log in to GitHub and locate the [GitHub Repository](https://github.com/CHAMPION316?tab=repositories)
    2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
        * Alternatively Click Here for a GIF demonstrating the process starting from Step 2.
    3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
    4. Under "Source", click the dropdown called "None" and select "Master Branch".
    5. The page will automatically refresh.
    6. Scroll back down through the page to locate the now published site link in the "GitHub Pages" section.

### Forking the Github Repository
* By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...
    1. Log in to GitHub and locate the [GitHub Repository](https://github.com/CHAMPION316?tab=repositories)
    2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
    3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone
1. Log in to GitHub and locate the [GitHub Repository](https://github.com/CHAMPION316?tab=repositories)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link. 
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type ```git clone```, and then paste the URL you copied in Step 3.

        git clone [Royer's Repository](https://github.com/CHAMPION316?tab=repositories)

7. Press Enter. Your local clone will be created.
       
## Credits
### Code
* The hero-image came from [Pexels](https://www.pexels.com/photo/photo-of-blue-sea-1430677/) 
    * They allow the free use of their images

* All the images/videos of the instructor herself were taken by me with her permission. 
    * She is a freelance acrobat as well as a soon to be yoga-instructor. You can find her perosnally webpage over at [Emelie Sandberg](http://www.emeliesandberg.se/)





<!--The title needed to coincide with how in tune yoga makes people feel with nature. I then needed to reflect that right away by having my ([Hero Image](https://www.pexels.com/photo/photo-of-blue-sea-1430677/)) present such an environment. The website is intended for public use so there is no need to **"pay"** a subscription in order to sign up for the courses. Considering the times we are living in where people are working remotely from home and keeping a distance provided a great oppotunity to teach yoga from the comfort of your mobile or laptop device.-->



<!--I have used the website ([Pexels](https://www.pexels.com/)) for all the images on my website except the ones that I own myself which are of the 'yoga instructor' Emelie Sandberg. "Pexels" provides free stock photos and videos for public use. The images of Emelie Sandberg were taken by me personally and the demonstration videos were also recorded by me. I have full rights to use the images and videos from her for this project as she has allowed me. She is also an acrobatic artist who has her own website for bookings at 

([Emelie Sandberg](https://www.emeliesandberg.se/))-->

<!--## Features

### Existing Features

* Navigation bar across all links of the website
* A footer page across all pages that display a sign-up form
<!--Add footer image when completed-->

<!--![](docs/nav-bar.jpg)

## The Landing Page Image 

* ### Logo
    * The landing page I needed to coincide with the logo by connecting yoga to nature. I chose an image of a beach. The colors bring a sense of relaxation and calmness. 

* ### Cover-Text
    * The cover-text is meant to catch the users attention upon arriving to the page and adhere their consciousness as to why this should be their go to yoga page.

![](docs/header-hero-image.jpg)

<!--## Colors

* I then had a color palette created on (**[coolors](https://coolors.co/)**). This was done by uploading the image and having it choose a palette which I can then adjust to my liking. This is the result I settled with in the end.

![](docs/collage.png)

* The colors from left to right in hexadecimal are as follows. 
    1. #aec6de
    2. #a3e3cb
    3. #f7ead7-->

<!--## Logo

* My logo is text based only with the title "Yoga Nature" which is representative by the background image. I chose font-family "Rajdhani" to be the main text for the logo. It is visually pleasing to the eye and I kept it black because no matter the changes the back drop may get the visual of the text remains intact. I also added a rectangler box around the text to add more depth to the lettering.

* It was important that I applied a cover text to the hero-image so that when the user enters the site they will not only see the logo and the backdrop that is warm and welcoming but also understand the purpose of Yoga Nature. My goal with the cover text was to do three very important things that will make the user attract 

![](docs/header-hero-image.jpg)-->

<!--* ## Me Section
    * This section is about the (Yoga Instructor) **Emelie Sandberg**
    * It provides a snippet of information about her with a hyperlink to her biography that can also be find in the navigation bar

![](docs/emelie-me-section.jpg)


* ## Yoga-Course Section
    * This section is a brief intro that connects the user to the video part of the page by providing a small summary of text 
    * The selling point for the audience is that the course vidoes are **free** which is what will grasp their attention the most

![](docs/emelie-videolink-section.jpg)

* ## Footer
    * My current footer page only has a Newsletter sign-up form. The reason for this is because I have my social-media tabs at the top of the page so there was no reason to include them again at the bottom
    *  Since the location functions remotely there was no need to include an address

![](docs/footer-page.jpg)-->














