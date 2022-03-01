# Pawsitively Perfect Pet Care - A Milestone Project

Pawsitively Perfect Pet Care website is a site for pet lovers and owners looking for a professional pet carer and dog walker to look after their pets for a fee. This site offers pet sitting and pet care services, with information on pricing and about the business owner.

Users of the site will be able to find information about Pawsitively Perfect Pet Care: About the business owner, the prices of the services, a contact page and a home page giving a brief description about the business.

This site is targeted towards Dog & Cat owners who may be looking to book time away and want a professional pet carer to look after their pets during this time.

![Responsive view of Pawsitively Perfect Pet Care on all devices](https://raw.githubusercontent.com/LunieLu/PawsPerfect/main/docs/Responsive.PNG "Pawsitively Perfect Pet Care")

## Features ##

- Navigation
    - Featured at the top of the site, the navigation bar shows the logo for the business in the left corner: Pawsitively Perfect Pet Care; which is a link to return to the index.html page
    - The other navigation links to the far right of the nav bar: Home, About, Prices & Contact; these all divert a user to different pages within the site.
    - The navigation also includes a paw print icon in relation to the fact the business is animal based.
    - The fonts used in the Navigation bar are Poppins (For Headings) & Open Sans (For Body)
    - The colours used are taken from the business card, and are the following hex codes:
        - #C39A6B
        - #CFAE89
        - #79492F
        - #fff
        - #F8F1ED

![The Navigation Bar for Pawsitive Perfect Pet Care](https://raw.githubusercontent.com/LunieLu/PawsPerfect/main/docs/navigation.PNG "Navigation")

- The Hero Image
    - The Hero Image used is a photo of Norwood Lakes, an original photo taken by a family member and local to the area that the business is based in.

- The Intro Section
    - The Intro section gives a basic introduction to the business and the services it offers.
    - It explains the locations the business offers its services in, which are: Croydon, Bromley, Lewisham & Clapham.
    - It briefly explains the qualifications of the professional dog walker.
    - It includes logos of qualifications the professional has completed.

![The Intro Section for Pawsitively Perfect Pet Care](https://raw.githubusercontent.com/LunieLu/PawsPerfect/main/docs/intro.PNG "Introduction")

- The Gallery Section
    - Unofficially titled "Our Furry Friends" section
    - Shows photos of pets that have been cared for
        - This is to help personalise the experience for the user, to help them feel connected to the business and its professional staff

![The Gallery](https://raw.githubusercontent.com/LunieLu/PawsPerfect/main/docs/gallery.PNG "Gallery")

- The Footer
    - The footer is minimalistic so not to remove focus from rest of site
    - It includes two Social Links:
        - Facebook
        - Instagram
            - Both Social Links open a new tab when clicked on and take a user to the homepage for each site
    - This helps the user to contact the business on more than one platform

![The Footer with Social Links](https://raw.githubusercontent.com/LunieLu/PawsPerfect/main/docs/footer.PNG "Footer")

- The About Page
    - A text heavy page
    - Goes into detail about the business and the owner who created Pawsitively Perfect Pet Care
    - Page includes 3 images of pets that have been looked after by the professionals who work for the business
    - Adds a personal touch to the business and the website, providing a bit more insight into why it was created

![About Pawsitively Perfect Pet Care](https://raw.githubusercontent.com/LunieLu/PawsPerfect/main/docs/aboutpaws.PNG "About Page")

- Prices Page
    - Minimalistic design
        - Page shows prices of the services offered by the business
            - Dog Walking
            - Home Care (Feeding animals in their own home when owners are away)
    - The Minimalistic design helps make the page easy to read and factual for the users, so they are not scouring through blocks of text for information regarding the services.

![Pawsitively Perfect Pet Care's Services and Prices](https://raw.githubusercontent.com/LunieLu/PawsPerfect/main/docs/Prices.PNG "Prices Page")

- Contact Form
    - A basic form that users can fill out to contact Pawsitively Perfect Pet Care
    - Each section on the form is required before the user can submit it
    - This form can be used to book services, or just to contact the business with any queries

![Contact Pawsitively Perfect Pet Care](https://raw.githubusercontent.com/LunieLu/PawsPerfect/main/docs/Contactform.PNG "Contact Form")

- Thank You Message
    - A small thank you message that pops up for the user when they submit a message through the contact form
    - This informs the user that their message has been sent and that someone from Pawsitively Perfect Pet Care will be in touch with them

![Thank you for submitting a message](https://raw.githubusercontent.com/LunieLu/PawsPerfect/main/docs/thankyou.PNG "Thank you message")

---

## Testing ##

- This site has been tested in Google Chrome and Mozilla Firefox.
- I tested that the site is responsive, looks good and functions well on all standard screen sizes.
- I confirmed that the logo, navigation menu, intro section, gallery section, about us page, prices page, contact form, thank you page and footer all work as intended and are readable for the user.
- I have tested and confirmed that the contact form works and entries are required for every field.
    - The Email input will only accept an email with an @ symbol included
    - The Contact number input will only accept a telephone number
    - The submit button works and diverts the user to a page called 'submit.html' which is a hidden page with a thank you message to inform the user their message has been sent
    - The form does not send any data to the backend of site
- I have tested the social links in the footer and can confirm that they open new tabs to the associated social media site and do not divert the user away from the site

## Bugs ##

**Solved Bugs**

- When the project was first deployed to GitHub pages, the images would not load correctly, I found this was due to a typo in the stylesheet syntax in the head html.
    - I tested the fix for the issue by removing additional / at the beginning of the file path and found that this was inaccurate.

**Unsolved Bugs**

- Whilst reviewing the html syntax through the w3 validator; fixing some of the errors caused the structure and spacing to act strangely on the 'About page'.
    - Despite attempts to fix the positioning of the text vs the images, my knowledge and skills were unable to find a perfect solution to make them sit comfortably on the page.
    - My secondary plan to improve the design and spacing, was to change the text content from 3 div sections, to 2 and move the images from the sides of each text to the middle; breaking up the wall of text which was concerns from early stages of the design.

![Display bug on About Page](https://raw.githubusercontent.com/LunieLu/PawsPerfect/main/docs/aboutpagebug.PNG "Display issues on About Page")

## Validator Testing ##

- HTML
    - When I first ran my HTML code through the official <a href="https://validator.w3.org/#validate_by_input">W3C validator</a>, I encountered 9 red errors.
    - These were fixed within an hour and were due to incorrect section/div placement and lack of headings.

![HTML Validator Errors](https://raw.githubusercontent.com/LunieLu/PawsPerfect/main/docs/ErrorsValidatorHTML.PNG "HTML Errors 1")
![HTML Validator Errors continued](https://raw.githubusercontent.com/LunieLu/PawsPerfect/main/docs/ErrorsValidatorHTML2.PNG "HTML Errors 2")

- CSS
    - No errors were found when passing through the official <a href="https://jigsaw.w3.org/css-validator/#validate_by_input">W3C CSS Validator</a>

- Accessibility
    - I confirmed that the colors and fonts chosen are easy to read and accessible, by running the site through lighthouse in devtools

![Lighthouse report](https://raw.githubusercontent.com/LunieLu/PawsPerfect/main/docs/Lighthouse.PNG "Lighthouse Report")

## Deployment ##

- The site has been deployed to GitHub pages. The steps to deploy are as follows:
    - In the GitHub repository menu for <a href="https://github.com/LunieLu/PawsPerfect">Pawsitively Perfect Pet Care</a>, please navigate to the Settings tab
    - Under the heading 'Code and Automation', click on Pages
    - From the source section drop-down menu, select the Main branch
    - Press the 'Save' button and the site will provide a link to the completed website.

The live link for Pawsitively Perfect Pet Care can be found <a href="https://lunielu.github.io/PawsPerfect/index.html">here</a>


## Credits ##
 
 **Content**
- Icons provided by <a href="https://fontawesome.com/">Font Awesome</a>
- Poppins & Open Sans fonts provided by <a href="https://fonts.google.com/">Google Fonts</a>
- HTML & CSS structure inspired by Code Institute's <a href="https://lunielu.github.io/LoveRunning/">Love Running Walkthrough Project</a>

 **Media**
- Images used on site are all original content
- Text content provided by Anna-Marie Eaton (Student's Family member)
