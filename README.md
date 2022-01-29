# The Box Hub

## Hello and welcome to my very first Portfolio Project for my Diploma in Software Development (E-commerce Applications). 

For my first project, I have created a website for a fictional boxing gym based in South London. The aim of my site is to encourage individuals of all ages and abilities to come and give boxing a go. Their motivation could be to increase their fitness, hone their boxing skills, be more confident, self-defence, or just a bit of fun! 

Users of this website will be able to get all the information they for the following main points:

- WHO it caters for
- WHAT services the club offers
- WHEN you can attend the different classes
- HOW people can get in touch to get involved

You can see my website here: [The Box Hub](https://jakepennell.github.io/the-box-hub/)

![Am I Responsive Image](https://github.com/JakePennell/the-box-hub/blob/main/assets/images/am-i-responsive-readme.png)

## User Experience (UX)

### User Stories

#### First Time Visitors
- As a First Time Visitor, I want it to be easy to understand who the business are, what they do and what they can offer me.
- As a First Time Visitor, I to be able to find my around the website easily using simple Navigation.
- As a First Time Visitor, I want to know how to contact them should I wish to. Including on Social Media.
- As a First Time Visitor, I want to get a feel of what other customers experience through images.

#### Returning Visitor Goals
- As a Returning Visitor, I want to find information on which classes are available and when. 
- As a Returning Visitor, I want to find out how to initiate the process of joining a class or signing up for future contact.

#### Frequent User Goals
- As a Frequent User, I want to check if there has been any changes to timetables or added classes.
- As a Frequent User, I want feel part of the community with updated pictures with myself included.

## Design

#### Colour Scheme
- To maintain a strong, bold feel to the website, in keeping with the theme of Boxing, I have chosen a distinctive colour scheme. 
- The dark grey and black backgrounds are contrasted by an off-white, almost Ivory shade of white. 
- To add a pop of colour, I have used a neon purple in places. I have kept this to a minimal to ensure it stands out.
### Typography
- The two fonts used are Oxygen & Heebo with Sans Serif acting as a fallback if the fonts aren't imported correctly. 
- Oxygen & Heebo compliment the Colour Scheme and general theme as they are strong and bold in style. 
### Imagery
- I have used very bold, striking images throughout the website. Capturing the community spirit of hard-working individuals.

## Existing Features

### Logo
- The Logo I created is a strong, bold logo that sets the theme for the whole project. 
- It acts as an anchor to bring the user back to the home page when clicked. 

### Navigation
- The Navigation Bar is a clear and concise directory with fully working links to the Home, Gallery and Contact Us pages. 
- It is style with an underline for the active page and when hovered over, it changes colour to the neon purple that appears subtly throughout the website.

![Logo and Nav Bar Screenshot](https://github.com/JakePennell/the-box-hub/blob/main/assets/images/logo-nav-readme.png)

### Hero Image
- The Hero Image is a powerful image that draws the viewers attention to the fact this website is designed with boxing in mind. 
- The animation used to slowly zoom out gives it added visual appeal.
- The overlying text states in clear and simple terms what the business is and where it is based. 

![Hero image with text overlay Screenshot](https://github.com/JakePennell/the-box-hub/blob/main/assets/images/hero-image-readme.png)

### About Us Bio
- The About Us section is a basic 'bio' of the business.
- It is designed to portray the message that this club is accessible to all ages and skill levels. 
- The styling is in keeping with the general them.
- I have included a call to action by signing up for a free class. This is delivered via a working link to the contact us page. Highlighted by bold and colourful text.

### About Us Image 
- This black and white image of a man boxing serves to break up the about us section and the timetable. Without this, the home page would be too wordy and not visually appealing.  

![About Us Screenshot](https://github.com/JakePennell/the-box-hub/blob/main/assets/images/about-us-readme.png)

### Timetable
- The simple box method works really well to show the viewer what classes are available and when. 
- The icons are an added bit of visuals to make the section more interesting viewing. 

![Timetable Screenshot](https://github.com/JakePennell/the-box-hub/blob/main/assets/images/timetable-readme.png)

### Contact Us
- The Contact Us section provides the businesses address and contact details, making it easy for the viewer to make contact. 

### Footer
- The footer is a simple but effective selection of fully working social media links, displayed as icons.
- The icons are style similarly to the Nav options, in that they highlight in purple when hovered over. 

![Contact Us and Footer Screenshot](https://github.com/JakePennell/the-box-hub/blob/main/assets/images/contact-us-footer-readme.png)

## Gallery 

- The Gallery page is used to show the viewer what they can expect at one of the classes. 
- The styling is simple but effective with a tiled effect, images separated by a thin white border. 

![Gallery Page Screenhot](https://github.com/JakePennell/the-box-hub/blob/main/assets/images/gallery-readme.png)

## Contact Us Page

- As mentioned in the About Us section, the website offers the viewer the chance to claim a free class. 
- This is achieved by completing the contact form and selecting the desired goal. Fitness, Boxing Skills or Self-defence. 
- I have used the https://formdump.codeinstitute.net as the destination for the submitted data as it is just a 'dummy' form.

![Contact Us Page Screenhot](https://github.com/JakePennell/the-box-hub/blob/main/assets/images/contact-us-readme.png)

## Future Features

To further improve my website, I would like to add additional features in the future These include:
1. A map of where the gym can be found.
2. A 'meet the team' page with a personal bio of the gym trainers.
3. Videos of classes in session as part of the Gallery page.

## Testing

Testing was a crucial part of my process to ensure my website performed as well as possible. Below I have detailed the steps I took to test my site comprehensively. I successfully tested my website in the following browsers: Chrome, Safari & Firefox. All the Navigation, Social Media and Internal links work as designed. As well as the contact us / sign up page.

### Validation
- HTML: No errors were returned when passing through the official W3C validator.
- CSS: No errors were found when passing through the official W3C validator.

### Lighthouse
- My lighthouse scores are very strong. Particularly the accessibility score which is 96. 

![Lighthouse](https://github.com/JakePennell/the-box-hub/blob/main/assets/images/lighthouse-readme.png)

## Bugs

I encountered several bugs along my journey. The main issues were around content display and responsiveness.
- Section Heights: I had originally given each section of a defined height. This meant that although they looked fine on my desktop, they would not respond to my effort to make the website responsive on different devises. This was resolved by removing the height value on various sections. 
- My navigation links overlapped on smaller devices. My initial solution was to reduce the text size but that negatively affected the aesthetics of the site. Therefore, to fix this I used the display: flex function to re-order the Nav links. 
- My Social Media links were also problematic as they were stacking on smaller devices. This was due to unnecessarily large border and margins. When these were reduced, the links lined up a behaved how I intended. 

## Unfixed Bugs

I have no unfixed bugs. 

## Deployment 

This website was deployed to GitHub pages. The steps to deploy are as follows:

1. In the GitHub repository, navigate to settings tab.
2. From the source section drop-down menu, select the Master Branch.
3. Once the Master Branch has been selected, the page provided the link to the completed website.

- Here is the link to the repository: [My Repository](https://github.com/JakePennell/the-box-hub)
- Here is the link to the live website: [The Box Hub](https://jakepennell.github.io/the-box-hub/)

## Credits

### Content
- The Slack Community were amazing and helped me fix bugs and improve my designs throughout my project.
- My mentor Jack gave me numerous suggestions on layout and section sizing to make my website more visually appealing. 
- I used W3C regularly for bug fixes and suggested features.
- The code in the CI Love Running Project served as inspiration for my website within many places. No coded directly used but used as inspiration to create my own.

### Media
- All my images are from: [Pexels](https://www.pexels.com/)
- All my Icons are from : [Font Awesome](https://fontawesome.com/)





