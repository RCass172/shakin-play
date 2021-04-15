<h1 align="center"><b>Shakin'play Website</b></h1>

![webpage layout on devices](assets/images/device-layout.png)

[Click Here To View Live Project](https://rcass172.github.io/shakin-play/)

---

## UX

### Project Goals
The primary goal of this website is to give all the relevant information to a user in an appealing and simple way. The site is designed 
to be as clear and easy to use while also looking professional to help stand out from other competitors.

### User Goals

* Easy to use on mobile, tablet and desktop
* Visually appealing
* Relevant content
* Easy to navigate to seperate sections
* Contact details easy to find
* Testimonials and information to showcase what they offer

### Business Goals

* Stand out from other competitors
* Showcase what they can provide
* Professional looking website
* Increase bookings

### User stories

As a user I would like:

1. To see testimonials of what other people thought about their service
2. To be able to navigate easily from each page
3. Visual icons easy to understand and recognise
4. An easy to use yet visually appealing website
5. The website to look good regardless of what device I use
6. To feel like the business is professional by the look and feel of website
7. The feeling that this business is better than other competitors to help decide on booking
8. Social media links present so I can investigate further if needed
9. Any links I click on to open in a new tab
10. Information to show what they can do
11. To be able to easily contact the business
12. To learn more about their history

### Design

* Two colors were used for the background in the project. A type of corral and off white which matched the hero image background to help the page flow. Bright colors used to make it look clean and enticing to the user.
* A large Hero image used to help get attention of user and showcase a modern look of the band to help stand out from competitors.
* The band logo was created on the website [Free Logo Design](https://www.freelogodesign.org/)

### Wireframes

Balsamiq was used to showcase the initial wireframe of website on mobile, tablet and desktop - [View Here](https://github.com/RCass172/shakin-play/blob/master/wireframe/wireframe.pdf)

---

## Features

* Responsive on all different device sizes
* Call to action buttons used to help increase bookings
* Iframe used to showcase the bands performance
* Upcoming showcase with modal to register
* Social media links in footer for users to investigate further


---

## Technologies Used

### Languages

* [HTML](https://en.wikipedia.org/wiki/HTML)
* [CSS](https://en.wikipedia.org/wiki/CSS)
* [JavaScript](https://en.wikipedia.org/wiki/JavaScript) (via Bootstrap)

### Frameworks/Libraries/Programs

* [Bootstrap 4.3.1](https://getbootstrap.com/docs/4.3/getting-started/introduction/) - used for responsive pages 
* [Fontawesome](https://fontawesome.com/)- used for aesthetics 
* [TinyPNG](https://tinypng.com/) - used to compress images for better performance
* [Google Fonts](https://fonts.google.com/) - roboto font used throughout all pages with poppins font used on headings, imported to the style.css file
* [Git](https://git-scm.com/) - used for version control
* [Gitpod](https://www.gitpod.io/) - used to write code before pushing to GitHub for storage

---

## Testing

I used the W3C [markup](https://validator.w3.org/#validate_by_input) and [CSS](https://jigsaw.w3.org/css-validator/#validate_by_input) validation services to make sure there were no errors on all html pages and css stylesheet

### Testing User Stories

* To see testimonials of what other people thought about their service 
  * I placed the testimonial section on the first page as these rank highly for a user when searching for any service. Once the user scrolls past a little about the band they are met with these testimonials plus the footer just below with social media links where they can find more reviews if needed.

* To be able to navigate easily from each page
  * Navigation is key for any website which is why I have a clear and simple navigation bar at the top of each page. A hamburger navigation bar is used in mobile devices to avoid a mess and look more clean. As a user scrolls down the home page I have a find out more button to easily navigate to next page and again on the about-us page a contact us button to easily navigate to contact-us page to help the whole website flow. The website logo when clicked will always bring the user back to the homepage.

* Visual icons easy to understand and recognise
  * I used FontAwesome icons on section headings to help create a more recognisable feeling for what each section was as they scroll through. I also used icons in the why pick us section to for each reason, to look aesthetically pleasing and help the user understand each point more easily.

* An easy to use yet visually appealing website
  * I used a hero image to capture the users attention and tied in the navigation bar color and hero image background colour to match the section colors for a nice flow when scrolling down. By doing this is also makes it easier for user to see what section they are currently reading.

* The website to look good regardless of what device I use
  * I used the Bootstrap container layout to give the best responsive webpage layout. Using this I was able to easily have each section take up 100% width on mobile devices so content was still readable and looks good.

* To feel like the business is professional by the look and feel of website
  * Content is easy to read with contrast colors checked and the layout looks good and not messy in any way. Relevant information is given on page with call to action buttons given to find out more as too much info would distract user initially. Navigation bars and footer with social media links and contact present as expected from any website.

* The feeling that this business is better than other competitors to help decide on booking
  * With the professional look as previous, plus on the homepage I have the band YouTube video to show users exactly what they are like with testimonials just under this and social media links in the footer. These all tie in together to show user what they provide, what other people thought and links to provide more ways to invesigate if needed before booking. An upcoming showcase is also added to show users they are still active and relevant with a call to action button to register for this.

* Social media links present so I can investigate further if needed
  * I have added the bands social links in the footer so can be found easily on all pages.

* Any links I click on to open in a new tab
  * I have all the external links i.e the social media links in footer and the YouTube link under video to all open in a new browser tab so user won't lose focus of website and get distracted elsewhere.

* Information to show what they can do
  * I have basic information about the band and video to show what they can do on the homepage, the call to action button to find out more then brings user to second page where it goes into more detail about the band and the services they provide which all leads the user to the contact page and potential bookings.

* To be able to easily contact the business
  * I have the band email address on the footer of all pages for users to easily find. I also have a seperate contact-us page for users to fill in their details and contact the band.

* To learn more about their history
  * I created an about us section on the second webpage to go into more detail about the band and their history to help users learn more about them.

### Further Testing

* I tested the website on different browsers such as Google Chrome, Firefox, Internet Explorer and Microsoft Edge to make sure all pages worked okay.
* All buttons and links were checked to make sure none were broken and all leaded to relevant page.
* Form inputs were checked that relevant input fields were marked as required before user submitted and page refreshed on submission.
* Modal checked and worked as required, easily exited if needed, input fields marked as required and page refreshed on submission.
* All pages checked using DevTools to make sure layout was correct on all different sized devices.
* DevTool Lighthouse was used to check the quality and performance of each page on both website and mobile.
* Friends and family reviewed website and asked for feedback if any broken links, user experience issues or bugs experienced.

### Bugs

* I had the band image on the why pick us section as an ``<img>`` tag in the HTML page, however on testing on different device sizes it wasn't as resposive as I liked. 
  * I changed this to use of the background-image property in my css stylesheet which made the image much more responsive across all device sizes.

* On testing with Lighthouse using the DevTools, the contrast colors were not enough with the corral color.
  * I changed the corral color to a lighter shade to help with contrast and make content easier to read for the user.

* When testing with Lighthouse the hero image was showing as loading too slow which leads to bad user experience.
  * I used the website TinyPNG to compress all my images to a smaller size to help with the loading times and performance of website.

---

## Deployment

This project was deployed to GitHub pages by executing the following steps:

1. Open GitHub and find relevant [repository](https://github.com/RCass172/shakin-play).
2. Navigate to the <b>settings</b> tab and scroll down to <b>pages</b>.
3. Under <b>source</b> heading click the none dropdown and select <b>master branch</b> and save.
4. When page refreshes the website is now live and found when you click <b>settings</b> > <b>pages</b> > <b>Your site is published at </b>[link](https://rcass172.github.io/shakin-play/)

To run project locally:

1. Open GitHub and find relevant [repository](https://github.com/RCass172/shakin-play).
2. Click the download code dropdown.
3. Using the clone HTTPS option copy the link provided.
4. Open Git Bash and change working directory to location where you want cloned directory to go.
5. Type <b>git clone</b> command and paste the clone link you had copied.

---

## Credits

### Content

* Inspiration was taken from these two websites [The Brian McDermott Band](https://thebrianmcdermottband.ie/) and [Blacktye](https://blacktye.net/)
* Images were taken from website [Pexels](https://www.pexels.com/)

### Acknowledgements

I would like to firstly thank my mentor Victor Miclovich who guided me throughout this project and helped point me in the right direction making it a great learning experience. His opinions were always greatly appreciated.

To my family and friends who helped provide great and honest feedback throughout the project.

And finally thanks to the slack community for whenever i got stuck on a problem, research always pointed me in the right direction.

