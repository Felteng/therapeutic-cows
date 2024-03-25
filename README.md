# Thereapeutic Cows
The Theraputic Cows website is place for anyone who might be looking for a natural substitute to therpay, be it coping of grief, stress release, or to simply experience some serenity. It's also for anyone who takes a liking to being around cows. We want more connection to nature!

The user will be presented with information as to why the activity could be of consideration and what benefits it may present. It should also give a brief overview as to what one could expect from it.

![Capture of the homepage on different devices and screen sizes](assets/images/am-i-responsive.png "Website homepage")

## Features
- **Color and contrast**
    - The site uses a contrast of a very light grey and a soothing green color to give a feeling of mindfullness and serenity while making the content very visible to the reader.

- **Navigation and header**
    - Conventionally featured at the top of the page with the name of the site and will *stay* at the top if the user scrolls downwards.
    - Navigation to all 3 pages can be found at the navigation bar, clearly indicated with highlight while hovering on computer devices, and with different icons.
    ![Capture of the header on large screen](assets/images/header-capture.png "Website header")
    - For *smaller* width devices it features a toggleable navigation bar to free up space.
    ![Capture of the header on small width display](assets/images/mobile-header.png "Website header on a mobile device")

- **Landing page hero image**
    - The landing section features a warm photograph with a slightly see through text-overlay that briefly tells the user what to expect and the relevant location.
    - The user should feel encouraged to scroll down and find out more.
    ![Capture of the hero section](assets/images/hero-capture.png "Website hero section")

- **The activity essence section**
    - This section aims to tell the user the benefits and the hows of cow therapy and why it may be a good idea to give it a try.
    ![Capture of the reasons to try section](assets/images/reasons-capture.png "The reasons to try cow therapy")

- **Footer**
    - The footer features our 4 social media links which open in a new tab when clicked to avoid creating a nuisance.
    - It's a valuable aspect to encourage visitors to stay connected without specifically visiting our web page.
    ![Capture of the footer and the social media links](assets/images/footer-capture.png "Footer with social media links")

- **The Gallery**
    - The gallery will display images of all our *fluffy staff* to give an idea as to what to expect.
    - It provides value and should further encourage the user to explore what cow therapy has to offer them.
    ![Capture of the gallery page](assets/images/gallery-capture.png "Capture of the gallery and some of its images")

- **The Booking Page**
    - This page is here to allow the user to sign themselves up for the upcoming cow cuddling and therapy sessions. 
    - The sign up will ask the user to supply their full name, email address, and phone number. It will also ask the user their preferred way of getting contacted.
     ![Capture of the booking page and form](assets/images/booking-capture.png "Capture of the booking page and its form")

- **Features to implement in the future**
    - Automatic confirmation message for sign ups.
    - Lay groundwork for implementation of a payment system in case it'd be necessary to change that model. 

## Testing
- I have validated the website works on various browsers, such as Chrome, Edge, Firefox, and Safari.
- I have tested the project's responsiveness and fucntions across all standard screen sizes and breakpoints using Chromes devtools.
- Additionally I have tested the website on a different computer than this one, 2 different mobile devices, and on 1 tablet device.
- I have confirmed and adjusted text sizes and positioning based on size breakpoints to assure that the text remains readable and easy to understand.
-I have made sure that the form requires a proper email format, input for the full name and phone number, and that an option for preferred contact method is selcted before submission.

## Bugs

### Current bugs
- None known

### Solved bugs
- I noticed that on very low-height displays the Booking form would displace itself and sit up to the right of the form, off the screen.
    - I troubleshot using devtools and discovered that it was the "height: 100vh" on the form element making it unable to handle overflow.
    ![Image of overflow bug in booking form](assets/images/booking-bug.png "Image of the bug on the form")
    - Nesting the form inside a div for the background image and changing the height property to "min-height: 100vh" fixed the bug.


## Credits
https://pexels.com | Stjin Dijkstra, Vlad Bagacian\
https://unsplash.com | Charlie Firth, Eilis Garvey, Coralie Meurice, Brian Taylor