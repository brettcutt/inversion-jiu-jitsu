 # Front End milestone project
 
 ## The Idea
 For my front end project I decided to build a Jiu-Jitsu academy site. I thought this would be a great idea because I'm a student of
 the martial art, I have good knowledge in it, I believe I know what visitors would be looking for before deciding to join and
 I can use the facility I train at to take pictures and limit the amount I take off the web.
 View the site here https://brettcutt.github.io/inversion-jiu-jitsu/
 
 ## Technologies used:
 ### HTML5
 
 ### CSS3
 
 ### JS
 - The photo gallery uses java script code from the wc3schools website.
 - The FAQ accordion also uses javascript from the wc3schools website.
 
 ### Jquerie
 -The click function of the mobile device menu uses Jquery.
 
 ### Bootstrap
 -I used the bootstrap grid layout to positon most elements, then customized it from that.
 
 
 ## Strategy Plane
 
 ### Business objectives
 Who are your target audience?
 - Martial art enthusiasts.
 - People with an interest in learning self defence.
 - People looking to improve their fitness.
 
 ### What is compelling visitors to your site?
 - People searching for a reputable or closely located Jiu-Jitsu academy.
 
 ### Why is this site different from your competitors?
 - It provides a different location from other Jiu-Jitsu academies which may be closer for possible recruits.
 - Its team has the reputation of performing well at the national competitions.
 
 ### Baseline business objectives
 -Increasing the number of Jiu-Jitsu practitioners for the academy.
 
 
 ## Scope Plane
 
 ### What features will be in the first release?
 - Home Page.
 - About: Jiu-Jitsu/ The academy/ The instructor.
 - Schedule/ class times.
 - photo gallery.
 - FAQ.
 - Pricing.
 - Contact.
  -Footer.
 
 ### What features will be released in the future?
 
 - Testimonials
 - rules/ etiquette.
 - News/ highlights/ seminars.
 
 ### Scenario
 1. Person decides they want to start a martial art or sport.
 2. Research of different martial arts.
 3. Picks Jiujitsu.
 4. Research of different academies and finds the closest.
 5. Finds your website.
 6. Gathers contact information.
 
 
 ## Structure
 
 - This project will be a single scroll webpage.
 
 ### Navigation Bar
 - There will be a navigation bar located at the top of the page at all times with a fixed position. The mobile responsive part 
 will have a menu button with a drop down menu.
 
 ### Homepage
 - The homepage will host the academy name and a background picture of the academy, which i will take pictures of the academy
 I train at. It will feature a second headline tempting visitors to continue either by scrolling down or pressing the "read more"
 button.
 
 ### About
 - This section will feature information about the martial art, academy and the instructor. For people with little knowledge
 about jiu-jitsu, this will give a brief explaination about jiu-jitsu, how it started and how it functions. About the 
 academy will give you an idea of what to expect from an academy. Because vsitors would like to know "what makes this person 
 a better teacher than the other academies instructor, located 2 minutes closer?", "About the instructor" will explain and show who 
 is teaching, and list some of their achievements.
 
 ### Schedule
 - Visitors would like the know the different sessions and session times that are running during the week. I will describe the 
 different classes and display a time table as a visual showing the class times. 
 
 ### Photo Gallery
 - A window with a sliding function. Pictures will display Jiu-jitsu practitioners rolling at the academy.
 
 ### FAQ
 - People have questions, Hopefully this section will answer some of them before making a decision.
 
 ### Pricing
 - There will be different options of how many lessons you can do during the week, depending on the plan chosen. This section will be 
 close to the bottom of the page to encourage visitors to view the other page content first, before making a decision.
 
 ### Contact
 - This will contain the address, phone number and the email address, as well as a google map image.
 
 ### Footer
 - This will have the social media links to their various sites.
 
 ## Skeleton
 
 ### Wire frame:
 
+- ![home section](assets/wire-frames/index.png)
+- ![about section](assets/wire-frames/about.png)
+- ![schedule section](assets/wire-frames/schedule.png)
+- ![gallery section](assets/wire-frames/gallery.png)
+- ![faq section](assets/wire-frames/faq.png)
+- ![pricing section](assets/wire-frames/pricing.png)
+- ![contact section](assets/wire-frames/contact.png)
 
 
 ## Testing
 
 - To make sure the coding was correctly made, I used w3c validator to check both the html 5 and css. These returned no errors.
 While writing the code I always had a live preview running on a second monitor.
 
 - To test the functionality of the website I mostly used Chromes developer tools and the different responsive device modes.
 Additionally I also downloaded Firefox, Safari and Opera on my laptop, and already had Edge installed. I tested my website on each of
 these browsers. I couldn't test on Safari because the cloud 9 log in did not work.
 
 - As apart of this project, where I could, I tried everything myself first before using third party sources. I built the time table
 schedule and had to figure out the best way to make it mobile responsive which was making its overflow hidden and adding a 
 scroll bar.
 
 - I originally made up a good desktop responsive photo gallery, however it wasn't so much in the tablet and mobile device modes.
 I chose to go for a sliding gallery from w3schools in the end.

- I built the navigation bar myself making it responsive on all devices, however the hover function didn't seem to be the appropriate action to
deploy the drop down menu on mobile devices. I ended up getting a jquery code from w3c schools for a click to show and hide function.
One problem I came across with this was, if I clicked to show the menu on mobile then clicked again to hide the menu, and then switched to a landscape
mobile position, tablet device or desktop mode, the navigation bar was hidden. To combat this I copied and pasted the
navigation menu with all its content to create a second one. I than changed that menu to hidden on sm, md and lg and changed the original navigation
menu to hidden xs and deleted the id linking it to the jquery code.

- I also noticed that when I clicked the drop down list item, the menu stayed showing. I got another jquery code for this to hide the menu on a clicked
list item.
 
 ### Edge: 
 
 -The first problem I encounted with edge was that my paralax background started to jump as I scrolled down the page.
 I did research into this and found out it's a bug in the edge/ internet explorer programming and it has no current solution
 as many forums described. I later checked edge again for a further test and the flickering had stopped. 
 
 -When the schedule timetable enters the mobile responsive mode and the scrollbar becomes active, the default scroll bar is 
 semi transparent. It can be difficult to see especially since it was too close to the border of the time table. I found the 
 code to change the appearance but it's not compatible on edge. I ended up moving the scroll bar slighly down so it is a bit
 more destinguishable.
 
 ## Final Test
 
 ### On all devices and on browsers (Chrome, opera, firefox, edge)
 
 - The Navigation menu testing works 
 - The logo redirects to the home page.
 - The "Find out more" button directs the page to the "about us" section.
 - The "about us" section has the pictures stacked under or over its related "p" element in different device modes.
 - The schedule class descriptions stacks appropriately to the different device modes.
 - The schedule time table resizes in the tablet mode and goes into a horizontal scrolling element in the mobile mode.
 - The gallery resizes appropriately.
 - FAQ resizes and stacks appropriately.
 - Pricing resizes and stacks appropriately.
 - The contact section resizes and stacks appropriately. Input fields all work however they intentionally don't direct anywhere.
 - The social media links only direct back to the homepage, being intentional since there are no real social media accounts linked to the site.
 
 ### Conclusion
 
 - Everything is user friendly and responsive.
 
## Deployment
- The project and coding was all done on cloud 9. Everything was committed and pushed to my github repository at https://github.com/brettcutt/inversion-jiu-jitsu and has been published on github pages at
https://brettcutt.github.io/inversion-jiu-jitsu/. Due to an error when deleting a non related repository, I accidently deleted my project off of cloud 9. So to get my project back this was cloned from my Github.

 ## References
 
 #### Jiu-Jitsu logo:
 - https://cdn.pixabay.com/photo/2012/04/24/18/15/judo-40769_960_720.png
 
 #### Fonts from Google fonts:
 - link href="https://fonts.googleapis.com/css?family=Raleway" rel="stylesheet">
 - link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">
 
 - The click function of the mobile device menu:
 https://www.w3schools.com/jquery/tryit.asp?filename=tryjquery_toggle
 
 #### All the icons are from font awesome:
 - https://fontawesome.com/icons?d=gallery&m=free
 
 The box shadow css codes
 - https://www.cssmatic.com/box-shadow
 - webkit-box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
 - moz-box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
 - box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
 
 #### The slide show gallery
 - https://www.w3schools.com/howto/howto_js_slideshow_gallery.asp
 
 #### This is for the accordion in the faq section
 - <https://www.w3schools.com/howto/tryit.asp?filename=tryhow_js_accordion
 
 #### Google map location
 - iframe class="map" src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d3273.4360947450377!2d138.63722329258113!3d-34.87039399773799!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sen!2sau!4v1531043627247" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe 
 
 
 #### The description of jiu-jitsu is from:
 - https://en.wikipedia.org/wiki/Brazilian_jiu-jitsu
 
 #### The description of the academy and instructor is based from:
 - http://www.sabjj.com.au/index.php/27-top-blocks/20-popularizing-and-developing-traditional-karate
 
 #### This is for the schedule table when the overflow hidden is active and the scrollbar appears.
 - https://css-tricks.com/almanac/properties/s/scrollbar/