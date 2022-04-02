<h1>Dublin Book Club</h1>

[View the live project here.](https://stephhjar.github.io/dublin-book-club/)

This is the home page for the Dublin Book Club, a fiction book club for adults of all ages based in Dublin. The goal of the website is to provide the user with information about the club, including when it was founded, previous books, a photo gallery, testimonials from current members, and form to register your attendance at the next meeting. 

## User Experience (UX)

-   ### User stories

    -   #### First Time Visitor Goals

        1. As a First Time Visitor, I want to understand what the Dublin Book Club is, and the purpose of the website.
        2. As a First Time Visitor, I want to understand how to navigate the site to find content and information easily.
        3. As a First Time Visitor, I want to find out what happens at book club meetings, and how they are organized. I want to see photos from previous events and hear from members. 

    -   #### Returning Visitor Goals

        1. As a Returning Visitor, I want to find out the date and time of the next meeting. 
        2. As a Returning Visitor, I want to find out what the next book selection is. 
        3. As a Returning Visitor, I want to register my attendance/RSVP to the next meeting.

    -   #### Frequent User Goals
        1. As a Frequent User, I want to see new photos and updated testimonials from recent book club meetings.
        2. As a Frequent User, I want to see what previous book selections were that I may have missed, and purchase previous and upcoming books.

-   ### Design
    -   #### Colour Scheme
        -   
    -   #### Typography
        -   
    -   #### Imagery
        -   

*   ### Wireframes

    -   Desktop Wireframe - [View](assets/readme/desktop.pdf)

    -   Tablet Wireframe - [View](assets/readme/tablet.pdf)

    -   Mobile Wireframe - [View](assets/readme/mobile.pdf)

## Features

-   Responsive on all device sizes

-   Interactive elements

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [wireframes](https://github.com/) during the design process.
1. [EightShapes Contrast Grid:](https://contrast-grid.eightshapes.com/)
    - EightShapes was used to ensure color contrast for accessibility.
1. [Coolors.co:](https://coolors.co/)
    - Coolors was used to generate a color palette.
1. [Unsplash] (https://unsplash.com/)
    - Unsplash was used for images (hero image and gallery images).
1. [Pexels] (https://www.pexels.com/)
    - Pexels was used for gallery images.
1. [Favicon] (https://favicon.io/)
    - Favicon was used to generate a logo and favicon.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results]()
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results]()

### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

    1. As a First Time Visitor, I want to understand what the Dublin Book Club is, and the purpose of the website
 
    2. As a First Time Visitor, I want to understand how to navigate the site to find content and information easily.
 
    3. As a First Time Visitor, I want to find out what happens at book club meetings, and how they are organized. I want to see photos from previous events and hear from members.

-   #### Returning Visitor Goals

    1. As a Returning Visitor, I want to find out the date and time of the next meeting. 

    2. As a Returning Visitor, I want to find out what the next book selection is. 

    3. As a Returning Visitor, I want to register my attendance/RSVP to the next meeting.

-   #### Frequent User Goals

    1. As a Frequent User, I want to see new photos and updated testimonials from recent book club meetings.

    2. As a Frequent User, I want to see what previous book selections were that I may have missed, and purchase previous and upcoming books.

### Further Testing

### Known Bugs

    1. 'font-weight: bold' was not working in the "next meeting section". Determined this is because the font chosen from Google Fonts did not have a bold weight. Imported a bold version of the font, this solved the bug.

    2. Could not vertically align the "Submit" text in the submit button. The padding was equal on all sides, but it looks like the font itself has space built in underneath the letters. Adjusted the padding to compensate for this. The downside here is that the text will not appear centred if the custom font is not available or does not load.

    3. There was a large gap between the "about us" section and the "next up" section due to a fixed height assigned to the div. Removed the height from the CSS code so that the sections stay close together.

    4. Used the "next-book" ID twice in the "up next" section, corrected this to be a class.

    5. Header div does not fit content at larger screen sizes, so couldn't vertically center the logo and the nav bar. Adjusted height of header to fit content. Nav bar width was also set to 100%, which prevented it from sitting next to the logo. Set the width to 40%, which allowed them to align next to each other at medium and large screen sizes. 

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Main Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

-   Footer with social media links used code from the Love Running walkthrough

-   [Goodreads] (https://www.goodreads.com/) for book covers and synopses

-   [TinyPNG] (https://tinypng.com/) to compress image sizes

### Code

### Content

-   All content was written by the developer.

-   Psychological properties of colours text in the README.md was found [here](http://www.colour-affects.co.uk/psychological-properties-of-colours)

### Media

-   All Images were created by the developer.

### Acknowledgements

-   My Mentor for continuous helpful feedback.

-   Tutor support at Code Institute for their support.