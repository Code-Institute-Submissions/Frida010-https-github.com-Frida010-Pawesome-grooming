

# Pawesome Gromming

The Pawesome grooming website is a page for dog owners looking for a place to get their dogs cleaned, trimmed and groomed. 
On this webpage you will be able to find information about the services offerd, and pictures of beautiful grommed dogs. 

Users of this website will be able to find information about the services offerd, an about us section, our services section, adress and contact information. 
The website also have a gallery with beautiful pictures of dogs, and a page to signing up for a grooming of your dog. 





![Screenshot of the website on diffrent screen sizes](https://user-images.githubusercontent.com/129947589/240865624-344c9723-ae7c-4911-a089-73bfa3972592.png)


## Features

#### Navigation
- At the top of the page you have the name of the company: Pawesome Gromming. When the logo is clicked you go back to the homepage.  
- On the right side of the page under the logo you have the navigation links to the Homepage, About us section, Gallery page and to the Book now page.
- The navigation is in a font that looks clean and modern, and have a color that contrasts the background. 
- The navigation tells the user were to find what the user is looking for. 




![Screenshot of the head of the page with the navigation links](https://user-images.githubusercontent.com/129947589/240865730-83475b37-3cff-4d32-9df0-1e6f9de64593.png)
#### The First Section

- The first section contains four images of different dogs and gives the user an extra additional clarification of what the website is for. 
- The images are there to entice the reader to want to know more.
- The images lie horizontally next to each other and have a background color that makes them feel more coherent and connected. 


![Screenshot of the row picture section](https://user-images.githubusercontent.com/129947589/240865800-1733538a-2c3a-4cb0-870d-5fc34f29fb78.png)
#### The Second Section

- The second section contains the information "About us" "Our services" "Adress" and "Contact us"
- The About us divition tells the user about some important criteria that the company is proud to offer its customers. 
- The Our services divition tells the user which services are offered and available.
- The Address divition tells the user where the dog groomers premises are located. 
- The Contact us divition gives the user the contact information to the company. 
- This section is surrounded the same way as the first section to make the website feel coherent. 
- Used icons from Font awesome to make the headings in this section more clear and playful


![Screenshot of the about us, our services, address and contact us](https://user-images.githubusercontent.com/129947589/240256588-26c75357-d96e-4ec0-a9c2-1dd2c5d8ec70.png)
## Footer section
- The footer section have the same background image as the logo to keep the website coherent. 
- The footer contains clickable social media links for the user to find the company on facebook, tiktok, instagram and youtube. 


![Screenshot of the footer section with social media links](https://user-images.githubusercontent.com/129947589/240261458-9d13d883-7322-46eb-9b51-2b1f057c25aa.png)
## Gallery

- The gallery contains images of dogs, some of dogs getting a haircut, some of dogs getting a bath and some of beautiful groomed dogs. 
- Some of the images have a pink background and some have blue details. And this is used to make a pattern and make the gallery more alive. 
- The gallery have the same header and footer as the homepage and the images have the same background color as the first and second section on homepage to make the website coherent. 
- One thing that I would like to fix in the future is to make the gallery look better on different screen sizes. Because I don't think the order of the pictures looks so good on smaller screens. But it is good enough for now. 


![Screenshot of the gallery.html page](https://user-images.githubusercontent.com/129947589/240865838-bf0497f3-8e7c-4467-b7f0-202d6ebc3a82.png)
## Book now 

- The book now page has a form for the customers to fill in and book a grooming for their dog. 
- The form collects the dog owners firstname, lastname, email and what weekday and time the owner will book. 
- The book now page have the same style as the rest of the website, and the header and footer is of course the same as the rest of the pages on this website. 


![Screenshot of the booknow.html page](https://user-images.githubusercontent.com/129947589/240865878-3ee40877-e969-414a-9f19-0789b1211da4.png)
## Testing
- I tested this website in different browsers: Safari, Crome and Firefox and it works. 
- I confirmed that this website looks good on different screen sizes using the devtools device toolbar. 
- I confirmed that this websites navigation, header, sections, gallery and book now page are readable and easy to understand.  
- I have confirmed that the form works on book now page: requiers entries in every field, will only accept email in email field and the submition button works. 

### Bugs
- An bug that I am aware of is that when the user fill in the form and click the "Book now!" button, an error messege will apear "405 Not Allowed". 

### Validator Testing

#### HTML
- Errors returned when passed through the official W3C validator was Error duplicate ID for fname, lname and email.  
- Deleted the id:s for fname, lname and email in label element in booknow.html page to fix the error. 
- After that no errors were found by the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Ffrida010.github.io%2Fhttps-github.com-Frida010-Project-01%2F). 
- However, there is a warning message from the validator about missing headings on the homepage. 

#### CSS
- Errors returned when passing trough the official (Jigsaw) validator was "_Value Error : float center is not a float value : center_" for #services, #address, #contact and #about
- Deleted the float center value in the style.css. 
- After that no errors were returned when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2F8000-frida010-https-githubco-u98cxrzf2k.us2.codeanyapp.com%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

#### Accessibility
- I confirmed that the fonts and colors used on the website are easy to read and accessible by running it through lighthouse in devtools. 


![Screenshot of the lighthouse in devtools](https://user-images.githubusercontent.com/129947589/240895363-6878a763-24ad-493b-98e6-08808cf51bed.png)

### Unfixed bugs

- I have one unfixed bug on this website and that is the one I mentioned earlier in this README file. _"An bug that I am aware of is that when the user fill in the form and click the "Book now!" button, an error messege will apear "405 Not Allowed"."_
- I chose not to fix that bug because Pawesome Gromming doesn't exist as an physical location/business and therefore there is no reason to book an appointment. And because I don't have the knowledge yet to be able to make it work. But maybe in the future when I know how to do that type of code I can fix that problem. 

## Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows:
- In the GitHub repository, navigate to the Settings tab
- From the source section drop-down menu, select the Master Branch
- Once the master branch has been selected, the page provided the link to the completed website.

The live link can be found here - https://frida010.github.io/https-github.com-Frida010-Project-01/

## Credits


### Content
- In the proccess of making this webpage I have used [Code Institute](https://codeinstitute.net/) videos and course material to help me and remind me of how to write some of the code. 
- Used [W3Schools](https://www.w3schools.com/) as my help on how to write the some of the code on this website. 
- The Fonts on the website were taken from [Google fonts](https://fonts.google.com/).
- Used [Codecademy](https://www.codecademy.com/) as help with how to write some of the code on this website. 
- Used [Developer Mozilla](https://developer.mozilla.org/en-US/) as help with how to write some of the code on this website. 
- Introduction on how to insert images to this README file was taken from this youtube video made by [Sean C Davis](https://www.youtube.com/watch?v=Ljj1wGFJqPY&ab_channel=SeanCDavis).
- Used [Stack overflow](https://stackoverflow.com/questions/39217732/is-it-possible-to-change-the-order-of-list-items-using-css3) as help with how to change the order of list items. 
- Used [Stack overflow](https://stackoverflow.com/questions/17687328/getting-a-link-to-go-to-a-specific-section-on-another-page) as help with how to link to a specific section on another page of the website. 
- As inspiration I also looked on [Pinterest](https://www.pinterest.com/). 

### Media
- The icons in the homepage section and the footer were taken from [Font awesome](https://fontawesome.com/)
- All the images on the website are taken from [Pexels](https://www.pexels.com/)
- The colors and background colors on the entire website were picked out from the hero-image by [Imagecolorpicker](https://imagecolorpicker.com/) 

