# Irelands Best Escape Rooms

[Link to the live project here](https://breakellrz.github.io/Escape_Room/)

- Irelands Escape Rooms is a website for people of all Escape room experience to check out the best escape rooms in Ireland. (Personal preference) **This website was created for educational purposes.**
- The website has three pages. The home page has a Gencraft AI cyberpunk image as the background, with a header, main content, and footer. The main content on this page is Escape Rooms 101. The second page is the 'Rooms' page. The 'Rooms' page involves the same as the home page but a different Gencraft AI cyberpunk image, and the main content has four amazing Escape Rooms to see. The third and final page again has a different Gencraft AI cyberpunk image with a form that users can fill out and submit questions to be answered.
  
![AMiResponsive picture of the different webpages on different screen sizes ](documentation/am_i_responsive.png)

## Goals of this project

### Site owner goals

- To showcase the best Ireland has to offer in Escape Room games.
- To give basic information to new people who might not be knowledgeable about Escape Rooms and how they work.
- Provide good information through text, an external YouTube video, and answer any questions users may have.

### External User Goals

- To find out what the best Escape room games in Ireland are.
- To gain insightful information on Escape rooms and how they work.
- To get answers to their questions.

## Design of the project

### Strategy plane

The strategy was simple. Here are some of my thoughts and questions to be answered around the strategy --

- Make a functional static website that would showcase Ireland's best Escape Rooms.
- Is the content culturally appropriate? The website is for any age, any race, and any gender.
- Is the content relevant? I wanted to make sure the content was relevant to escape rooms.
- I asked myself, why would a user want this? The answer was for people interested in Escape Rooms looking for more information on Escape Rooms and to find out the best Escape Rooms in Ireland.
- What are we making? Info page on Irelands best Escape Rooms.

### Scope plane

What's on and off the table? What features and content will be used?

- Normal Navigation bar for users to click between the three pages (Home, Rooms, and Contact).
- 'Nav bar' - Burger menu on phone screen sizes. Use a lock instead of the traditional burger menu - Have the lock bounce so users know to click it for a drop-down feature.
- Background image with a transparent Header and normal sticky Footer - both fixed.
- Information on Escape rooms on the 'Home' page.
- Footer with social media links.
- YouTube video on Escape Rooms 101.
- Images and information on my top picks for Irelands best Escape Rooms on the Rooms page.
- Contact section with a form feature to submit questions.
  
### Structure plane

Easy structure - Nav bar with hyperlinks to different pages on the website. Scroll down to see the main content. Easy to see layered content displayed in flex-box in columns on each page with the same layout and structure. It is consistent, predictable, learnable, and visible.

### Skeleton plane

To visualize the website, I used Wireframes for my ideas using Balsamiq. I created them on larger screens with the idea of smaller screens being very similar - just everything wrapped in columns if need be for the smaller screens.

1. **Home page Example.**
   ![Balsamiq Home page example](documentation/home_balsamiq.png)

1. **Rooms page Example.**
   ![Balsamiq Rooms page example](documentation/rooms_balsamiq.png)

1. **Contact page Example.**
   ![Balsamiq Contact page example](documentation/contact_balsamiq.png)

### Surface plane

On the surface plane, the color scheme I went for was 'CyberPunk' - The images I got for my main background on all three pages were from [Gencraft AI](https://gencraft.com/generate) and I used 'CyberPunk' style.
I decided to then go with the CyberPunk color scheme as it matched my Gencraft AI images for the background on the website. These colors consisted of purples, pinks, and white text with a black background. I used the 'Eye Dropper' Chrome extension to give me an idea of that colors to use . I used it on the background images from Gencraft. I manually then changed it to my preferred color. 
![Colors that Eye Dropper found](documentation/color_style.png)

## Features

- **My Header** consisted of a navigation bar for larger screens and a drop-down menu for smaller screens. All screen sizes had a main h1 heading on the top left of the page with the title 'Irelands Best Escape Rooms' so that users knew what the website was. The header was partially transparent and blended in quite nicely with the main hero background image.![Header](documentation/header_feature.png)

- **I used a normal Navigation bar** on screen sizes larger than 768px. It contains three pages named 'Home', 'Rooms', and 'Contact'. All three of these are links to their respective pages. I used 'class="Active"' for each page so that when the user is on each page, it will have an underline under the respective page to tell the user what page they are currently on.
![Navigation bar image](documentation/navbar_feature.png)  

- **I used a drop-down menu** for screen sizes smaller than 768px. I decided to use a lock instead of the normal burger menu, as a lock corresponds more to the Escape Room theme. The lock bounces to tell users that it is clickable.
![Navigation Burger icon but instead it is a lock icon for mobile phones ](documentation/burger_dropdown_feature.png)

- **I used [Gencraft wesbite](https://gencraft.com/generate) for a CyberPunk themed background.** I wanted this to stand out, and be the first thing users see on the Website and make the users feel immersed into the Escape Room world. 
![Main background image with transparent header and normal footer](documentation/home_hero_feature.png)

- **Content of Escape Rooms 101** - This included four card-like sections with a header and information on each card. This was to provide knowledge and insight into Escape Rooms for the user. 
![Home page info section](documentation/info101_feature.png)

- **Footer feature** included icons of 'Facebook', 'Instagram', and 'X'. All three icons are clickable links that will take you to each social media website. The footer was fixed, so it is always showing like the header. The footer has a background color of #771c75; with white social media icons so it stands out. Also included is text with the words 'Find us on:' so it lets users know they can find us on each social media. (This website was created for educational purposes there is no actual social media for this website so the links take the user to just the home pages of the three social media sites.) 
![footer with social media links](documentation/footer_feature.png)

- **I added a YouTube video** of 'Escape Rooms 101' in case users wanted to watch a video format to gain knowledge on Escape Rooms. The video is Scott Nicholson, a game design professor at Wilfrid Laurier University in Brantford, Ontario, for an introductory talk on Escape Rooms! This is at the bottom of the page, under a line break, and above the footer. 
![YouTube video](documentation/youtube_video.png)

- **On the rooms page the website has a main background image** from [Gencraft](https://gencraft.com/generate) with text that says 'Reveal the rooms' and a font awesome hand and finger that points downwards to let the users know to look down to unveil the best rooms.
![Rooms main background image with text](documentation/rooms_hero_feature.png)

- **The main feature on the 'Rooms' page is the four horizontal like-cards with a header, picture, and information of four indivdual escape rooms.** The headers show the name of the escape room, The images show a represetation of each room and the information provides the back story for each room and then the location of the escape room. 
![Images and info on the best escape rooms](documentation/images_for_rooms.png) 

- **Lastly on the 'Contact' page there is a form for users to fill in their 'Name' and 'e-mail' address and to ask a question to be sent to us.** (This is for educational purposes when the user clicks send it brings them to a codeinstitute page acknowleging the user that the question has been sent). The form is slightly transparent with a hint of black in the background. The main background is another image from gencraft.
![Questions Form](documentation/form_feature.png)

## Future Features

I believe I added the necessary Features for this website but I would have liked to have added more, and they will be future features. 
Some of these examples are as shown: 

- If I had more time, I would have liked to add a map section with the exact locations of the Escape Rooms that I referred to on the 'Rooms' page.
- I will add more Escape Rooms and plan on doing so.
- I will add a F.A.Q section of the most common Questions asked.
- I will add an anchor link to 'Irelands Best Escape Rooms' main heading.

## Technologies used

Technologies used in this website were as follows:

- HTML
- CSS
- GIT
- BALSAMIQ WIREFRAMES
- CODEANYHWERE
- GOOGLE DEV TOOLS
- GENCRAFT 
- FONTAWESOME
- GOOGLE FONTS
- IMAGE RESIZER
- W3C HTML Markup Validator
- W3C Jigsaw CSS Validator

## Testing and Validation

### Manual testing
- I tested the live project on Google Chrome, Internet Explorer, and Firefox web browsers.
- I tested the website on iphone, laptop and monitor screen sizes.
- I made sure that the form was working properly on all screen sizes and that the user needs to put in all the details for the form to be sent.
- I checked that the lock icon was working as a dropdown menu for phones and that all anchor links worked for all screen sizes. This includes the navigation bar with the pages 'HOME', 'ROOMS', and 'CONTACT'. This also includes the footer with all three social media apps.
  
### Validation
- I used W3C Markup Validation service to make sure my code had no errors. After some fixes my code came out perfect with no errors found.
![HTML Validator](documentation/html_validator_home.png) 

![HTML Validator for rooms page](documentation/html_validator_rooms.png) 

![HTML Validator for contact page](documentation/html_validator_contact.png) 

- I used the Jigsaw CSS Vlaidator to validate my CSS code.![CSS Validator](documentation/css_validator.png) 

- I used Lighthouse in dev tools to measure the Performance, Accessibility, Best Practices and SEO I had hoped for a better performance I changed images from jpg to webp and made them smaller I will be working on making the performance better in a future update. 

![LIGHTHOUSE testing for home page](documentation/home_lighthouse.png)

![LIGHTHOUSE testing for rooms page](documentation/rooms_lighthouse.png)

![LIGHTHOUSE testing for contact page](documentation/contact_lighthouse.png)


## Challenges/Bug fixes
I had a couple errors and warnings in my HTML code Validator these included a lot of **trailing slashes '/'** that did not need to be in my code - for whatever reason, when I got rid of the unnecessary slashes in my code and clicked save, the slashes would come back into my code. **I also had a couple errors and warnings that needed fixing these included:**

1. 'Trailing slashes.' 
2. 'Attribute required is only allowed when the input type is checkbox, date, datetime-local, email, file, month, number, password, radio, search, tel, text, time, url, or week.'  
3. 'Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections, or else use a div element instead for any cases where no heading is needed.' 
4. 'V=Element legend not allowed as child of element div in this context. (Suppressing further errors from this subtree.)'

 **I fixed these issues by:**
 
1. I found a thread on slack with the same issue and got an answer I went into 'file' then 'preferences' then 'settings' then I turned off 'Format on save' this fixed the problem.
2. Removing 'required' in my input type="submit" as required does not make sense to be used in a submit type. This fixed the error.
3. I added a heading with text, which ultimately made my 'Rooms' page look nicer, and fixed the warning.
4. I took out the 'legend' tag as it was not needed and I put in a H2 tag instead - this fixed the error.

## Deployment

I deployed my website early, as this is recommended. The steps to deploying a website on GitHub pages are:

1. Open the repository and go to the Settings tab.
1. Navigate to the Pages tab in the left menu.
1. Choose Deploy from a branch and select the according branch, main.
1. Click save. Click code The link to the deployed website can be found on the right hand side under 'Deployments' and then under 'active deployments'
   The link to my live site is: [Link to the live project here](https://breakellrz.github.io/Escape_Room/)

## Credit
I would first like to thank my code institute mentor, Brian O'Hare, for guiding me and providing tips and feedback during this project.

- I would like to credit 'Love Running' provided by Code Institute. Love running provided me with inspiration for both the navigation dropdown menu and the footer on my website.
  
- I would like to credit [Gencraft](https://gencraft.com/generate) for providing me with AI generated images which I used for my main background images.

- I would like to credit pexels [Pexels](https://www.pexels.com/) for the images I used for the escape rooms.

- I would like to credit [Fontawesome](https://fontawesome.com/), for the icons used in this project (Facebook, Instagram, X, and the lock icon for my drop-down menu).

- I would like to credit YouTube channel [BGNlab](https://www.youtube.com/watch?v=Tqnw7g5iIFQ) for the YouTube video provided in this project. 
  
- I would like to credit [Inside Escape Rooms Castlebar](https://www.insidecastlebar.ie/), [Ealu Escape rooms Westport](https://ealuescape.com/en/home), and [Great Escape Rooms Galway](https://greatescaperooms.ie/) for providing Ireland with some of the best Escape Rooms in Ireland.