# Irelands Best Escape Rooms

[Link to live project here](https://breakellrz.github.io/Escape_Room/)

- Irelands Escape Rooms is a website for people of all Escape room experience to check out the best escape rooms in Ireland. (Personal preference) This website was created for educational purposes.
- The website has three pages. The home page has a Gencraft ai cyberpunk image as the background with a header main content and footer. The main content in this page is Escape Rooms 101. The second page is the Rooms page. The rooms page involves the same as the home page but a different Gencraft ai cyberpunk image and the main content has four amazing Escape Rooms to see. The third and final page again has a different Gencraft ai cyberpunk image with a form that users can fill out and submit questions to be answered below the form is a F.A.Q section.

![Hero Image on home screen of website](documentation/mainreadme.png)

## Goals of this project

### Site owners goals

- To showcase the best Ireland has to offer in Escape Room games.
- To give basic information for new people who might not be knowledgeable on Escape Rooms and how they work.
- Provide good information through text, an external YouTube video and answer any questions users may have.

### External Users goals

- To find out what the best Escape room games in Ireland are.
- To gain insightful information on Escape rooms and how they work.
- To get answers for there questions.

## Design of project

### Strategy plane

The strategy was simple here is some of my thoughts and questions to be answered around the strategy --

- Make a functional static website that would showcase Ireland's best Escape Rooms.
- Is the content culturally appropriate ? The website is for any age, any race, any gender.
- Is the content relevant ? I wanted to make sure the content was relevant to escape rooms.
- I asked my self why would a user want this? The answer was for people interested in Escape Rooms looking for more information on Escape Rooms and to find out the best Escape rooms in Ireland.
- What are we making? Info page on Irelands best Escape Rooms.

### Scope plane

What's on and off the table? What features and content will be used ?

- Normal Navigation Bar for users to click between the three pages(Home, Rooms, Contact) [Navigation bar image](documentation/navbar.png)
- Nav bar -- Burger menu on phone screen sizes (Use a lock instead of traditional burger menu -- Have the lock bounce so users know to click it for a dropdown feature) [Navigation Burger icon but instead it is a lock icon for mobile phones ](documentation/burger.png)
- background Image with a transparent Header and normal sticky footer - both fixed [Main background image with transparent header and normal footer](documentation/heroreadme.png)
- Information on Escape rooms on the Home page [Home page info section](documentation/info101.png)
- Footer with Social media links [footer with social media links](documentation/footer.png)
- YouTube video on Escape Rooms 101 [YouTube video](documentation/youtubevideo.png)
- Images and information on my top picks for Irelands best Escape Rooms on the Rooms page [Images and info on the best escape rooms](documentation/imagesonrooms.png)
- Contact section with a form feature to submit questions [Questions Form](documentation/formreadme.png)

### Structure plane

Easy structure -- Nav bar with hyperlinks to different pages on website. Scroll down to see main content easy to see layered content displayed in flexbox in columns on each page same layout and structure. It is consistent, predictable, learnable, and visible.

### Skeleton plane

To visualise the website I used Wireframes for my ideas using Balsamiq. I created them on larger screens with the idea of smaller screens being very similar just everything wrapped in columns if need be for the smaller screens.

1. **Home page Example.**
   ![Balsamiq Home page example](documentation/home.png)

1. **Rooms page Example.**
   ![Balsamiq Rooms page example](documentation/rooms.png)

1. **Contact page Example.**
   ![Balsamiq Contact page example](documentation/contact.png)

### Surface plane

On the surface plane the color scheme I went for was 'CyberPunk' - The images I got for my main background on all three pages were from gencraft ai [Gencraft wesbite](https://gencraft.com/generate)and I used 'CyberPunk' style.
I decided to then go with the CyberPunk color scheme as it matched my Gencraft ai images for the background on the website. These colors consisted of purples pinks white text with black background. I used 'Eye Dropper' Chrome extension to give me an idea of that colors to use . I used it on the background images from Gencraft. I manually then changed it to my exact prefered color. ![Colors that Eye Dropper found](documentation/color.png)

## Future Features

I believe I added the necessary Features for this website but I would have liked to have added more and they will be future features some of these examples are as shown: 

1. If I had more time I would have liked to add in a map section with the exact locations of the Escape Rooms that I referred to on the 'Rooms' page.
2. I would have like to have added more Escape Rooms and plan on doing so.
3. I will add a F.A.Q section of the most common Questions asked.

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
- IMAGE RESIZER
- W3C HTML Markup Validator
- W3C Jigsaw CSS Validator

## Testing and Validation

### Manual testing
- I tested the live project on Google Chrome, Internet explorer and firefox web browsers.
- I tested the website on iphone, laptop and monitor screen sizes.
- I made sure that the form was working properly on all screen sizes and that the user needs to put in all details for the form to be sent.
- I checked that the lock icon was working as a dropdown menu for phones and that all anchor links worked for all screen sizes. This includes the navigation bar with the pages 'HOME' 'ROOMS' & 'CONTACT'. This also includes the footer with all three social media apps.
  
### Validation
I used W3C Markup Validation service to make sure my code was perfect. ![HTML Validator]()

I used the Jigsaw CSS Vlaidator to vlidate my CSS code.  ![CSS Validator](documentation/css_validator.png)

I used Lighthouse in dev tools to measure the Performance, Accessibility, Best Practices and SEO. ![LIGHTHOUSE TESTING]()


## Challenges/Bug fixes
I had a couple errors and warnings in my HTML code Validator these included a lot of **trailing slashes '/'** that did not need to be in my code - for whatever reason when I got rid of the unneccesay slashes in my code and clicked save the slashes would come back into my code. I also had a couple errors and warnings that needed fixing these included: 1. **'Attribute required is only allowed when the input type is checkbox, date, datetime-local, email, file, month, number, password, radio, search, tel, text, time, url, or week.'**  2. **' Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections, or else use a div element instead for any cases where no heading is needed.'** & 3. **V=Element legend not allowed as child of element div in this context. (Suppressing further errors from this subtree.)**
 I fixed these issues by:
 
1. removing 'required' in my input type="submit" as required does not make sense to be used in a submit type. 
2. 

## Deployment

I deployed my website early as this is recommended. The steps to deploying a website on GitHub pages are:

1. Open the repository and go to the Settings tab.
1. Navigate to the Pages tab in the left menu.
1. Choose Deploy from a branch and select the according branch, main.
1. Click save. Click code The link to the deployed website can be found on the right hand side under 'Deployments' and then under 'active deployments'
   The link to my live site is: [Link to live project here](https://breakellrz.github.io/Escape_Room/)

## Credit

Gencraft for background images
Love running for nav bar and burger dropdown
pexels for images
font awesome for lock icon
YouTube BGNlab for video
Ealu escape rooms
inside escape rooms
Great Escape rooms
Mentor Brian O'Hare
