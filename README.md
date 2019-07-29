-----------------------
First Milestone Project
-----------------------
This is my first milestone project that I'll be completing as part of my Fullstack Developer course with Code Institute.  
The brief is to create a static (front-end only) website for a band, specifically for the Monkees, an American pop rock band that rose to fame in the 60s.


-----------------------
UX
-----------------------
The brief for this project is to create a site to showcase music and video clips of the band's back catalog.
As well as to publicise the band's availability to perform at events like weddings, or Christmas parties.

User Stories:-  
* As a fan I want short bios of the band so that I can learn more about its members.  
* As a fan of 60s music I want audio clips of the band's back catalog so that I can find out if I like their music.  
* As someone with an upcoming wedding I want to contact the band so that I can ask more about bookings.  
* As a new fan I want links to the band's social media accounts so that I can engage with more of their content.

Wireframes:-  
Macro concept of layout:
![alt text](/assets/images/wireframes-macro.jpg)
- On the left is a singular scrolling page, whereas the mock-ups on the right represent the same sections but given each to their own page.  
- I opted for the singular scrolling look as I liked the sense of flow I got from seeing other similar projects.

More detailed depiction for each individual section:
![alt text](/assets/images/wireframes-more-detail.jpg)
- The simple home page of a single image was something I found used again and again on other bands' websites.  
- In fact many of them opened with a full-viewport auto-playing file of their latest video. But because I ran into problems with file sizes with my featured video, I decided to opt for the image.  
- I particularly liked the landing image I used as the grayscale felt neat, its showed the band performing, and it even had the band name already displayed in its center.  
- As such, I reviewed my other media and implemented the grayscale theme to create a more consistent consistent look. I didn't completely eliminate colored images, in order to provide some visual variety.  
- I quickly learned that my plans for the gallery section would require the use of javascript, which I didn't want to get too heavily into as I'd neither started the associated fundamentals course, nor was the assessment based on my JavaScript skills.  
- Yet, despite scaling my plans back to a modal, I still had to borrow some JS code from elsewhere.  
- I later renamed the "Gallery" section to an "About" section, after adding more textual elements. This created some unfortunate issues around class-naming conventions, and was a good lesson in being careful about naming conventions in general.  
- Placing the About section after the Video section was a two-fold decision, as I felt the background image effect I had better suited the cards of the About section, and the Video was probably the best conveyed the essence of the band.  
- As with the About/Gallery section, the plans for my video section turned out to be too ambitious, requiring more JS than its worth, and as such became a single video hosted from the official Monkees YouTube page.  
- The Audio section turned out almost exactly as sketched out, but with an additional audio clip, which helped to vary the layout of the sections, with a 3-way rather than a 2-way split.  

-----------------------
Features
-----------------------
The features I've implemented include:  
* A single, scrolling page with distinct sections.  
* A Navigation bar that remains fixed to the top of the webpage's viewport.  
* Social Media links embedded in the navbar.  
* A Landing section to both ease the viewer into the website, while also making clear what it is about.  
* A Video section to showcase the band performing.  
* A Gallery/About section that provides further details about the band members.  
* A modal to offer an expanded view of the images found in the gallery.  
* An Audio section to showcase even more audio samples from the band's catalog.  
* A Contact form for bookings or other queries. This form is for demonstration purposes and is not connected to any external databases or email accounts.
* Clickable elements are reactive and further draw attention to themselves to convey interactability.  
* A font inspired by the 60s.  
* Background images that showcase more of the band.  

Another feature idea:
* Fictional Tour Dates

-----------------------
Technologies Used
-----------------------
This project used HTML5 and CSS3 languages.  
I also borrowed a snippet of JavaScript for my modal from w3schools:  
https://www.w3schools.com/howto/howto_js_lightbox.asp  
I also used the Bootstrap framework to simplify the layout of the website:  
https://getbootstrap.com/

-----------------------
Testing
-----------------------
Compatibility:
Testing was carried out on Google Chrome, Mozilla Firefox, Microsoft Edge, and Opera browsers.
Devices tested on included a Microsoft Surface Book 2 (Windows 10 OS), desktop and tablet mode, a Sony Xperia phone (Android 7 OS), and an Amazon fire 5 tablet.
Testing on these platforms involved checking that layout did not become warped, links still worked, audio clips still functioned, etc.
The only found iisue was that the smoot scrolling efect was not compatible with Microsoft Edge.

Resolved Issues:  
* Discovered that landing background image was not working correctly as the style.css file was improperly referenced in the index.html file.  
* Video player no longer breaks alignment at smaller resolutions.  
* video from repository exceeded 8MB in size preventing its rendering; opted to use a link to a corresponding youtube video.  
* Images in modal no longer extend past edge of screen.  
* Thumbnails in modal no longer overlap.  
* Navbar no longer occludes headings after clicking associated link, I achieved this by adding an additional row at the end of each section and creating a paragraph of transparent text. This not only solved the navbar issue but added additional padding between sections, to give the viewers eyes a bit more of a break.

Known Bugs:  
all bugs currently resolved

-----------------------
Deployment
-----------------------
This project has been deployed at:  
https://brendanmolloy.github.io/milestone1/

-----------------------
Credits
-----------------------
Much of the media for this project has been taken from the respository of aaronsnig501, found on GitHub.
Other content was sourced from:  
www.wikipedia.org  
www.8notes.com  
www.yahoo.com  
www.biography.com  
www.pinterest.com  
www.purpleclover.littlethings.com

I'd also like to thank my mentor, Aaron Sinnott, for all of his assistance and recommendations for this project.

