# Nan Lieu
# CDA404 Practical Assignment

# Github URL
https://github.com/NanLieu/CDA404-Web-Technologies/tree/master/practical_assessment_1

## Background
For this project, I was looking to add additional communication methods to the Lockheed Martin website. The current website has contact us page, however it only provides phone numbers and email addresses. Therefore, I have created a version of the Lockheed Martin website and added 2 additional web pages that would allow visitors to communicate with Lockheed either through a contacts page or a live chat as an alternative method of making contact. 

## Wire Frames
**index.html**
![index.html wireframe](documentation-images/index-html-wireframe.png)

**products-capabilities.html**
![products-capabilities.html](documentation-images/products-capabilities-html-wireframe.png)

**career.html**
![career.html](documentation-images/career-html-wireframe.png)

**contact-us.html**
![contact-us.html](documentation-images/contact-us-html-wireframe.png)

## Colour Choices
For the colour choices, I kept it simple and tried to use the same colour as the Lockheed Martin's logo to keep in line with the colour scheme. With the contrasting blue and white will allow text to be visible under the nav bar and kept a simple black and white for the text in the background for legibility.

## Accessibility
Once the website was completed, it was checked over using the [Easy Checks – A First Review of Web Accessibility](https://www.w3.org/WAI/test-evaluate/preliminary/) to ensure that the website has high level of accessibility as possible.

### Page Titles
Confirmed that each web pages have been allocated a page title.

### Images
Confirmed pages that contain images have alternative text to convey the purpose of the images.

### Headings
Confirmed each page has at least a h1 heading and any subsequent headings, if any, are implemented in a meaningful hierarchy.

### Contrast Ratio
Confirmed text contrast ratio is sufficient to allow readability for all users.

### Text Resizing
Confirmed texts can be resized without distortion over other objects on the website

### Keyboard Access and Visual Focus
Confirmed that all clickable objects can be selected through the use of tab to allow control via keyboard.

### Forms, Labels, and Errors
Confirmed that all text entry fields have keyboard access, contains labels to identify them and also uses the required attribute to create a pop-up message to notify the user to fill in the field before submitting.

## GDPR
To comply with the GDPR, I have replaced the links on the bottom nav bar, which orignally was used to navigate around the site, to the links of Lockheed Martin's Privacy Notice located on their main headquarter's website which the official UK website also uses. This will provide the visitor up-to-date information regarding Privacy notice, personal information and how this information is handled.

## Distance Selling
As the website does not sell goods or services, the Online and distance selling act does not apply to this website.

## Evaluation
The website initially started off as a mortgage calculator but I unfortunately had to scrap the idea as I couldn't create a theme for the website and what I would create for the other pages as the calculator would have been limited to just 1 page. So I then explored the Lockheed Martin UK website [Lockheed Martin UK](https://www.lockheedmartin.com/en-gb/index.html) and discovered that the website had a contact us page but had only provided two phone numbers. There was no other form of contacting Lockheed Martin so I thought I could create alternative ways of communication such as a contact form, as using lockheed martin emails on public space is not recommended.

I had decided to keep the website simplistic using some similarities found on the Lockheed Martin website and used the colours that would normally be used by Lockheed Martin to keep a sense of unity albeit much more basic in comparison. However, having a basic website allowed the website to be viewed on mobile devices without distortion, as if the website is more complex and contained more objects and elements, they are likely to clash and overlap each other unless the css style sheets adjusted the website when the resolution changees. This had unfortunately happened to me when I created the Live chat button as I wanted to added in an additional complexity to the website. I had the position set as fixed so that the live chat button remained in the same location. However, this proved to be an issue when the page was shrunk to fit a mobile device so I made changes so that it would appear below once the resolution was a specific width. I used Chrome browser's dev tools to view the website under different mobile devices resolution to see how the website was affected and to correct it when required.

Javascript was used on the careers.html page to controlled the function to show and hide the live chat box. I had used [w3schools.com](https://www.w3schools.com/js/default.asp) as a tutorial to assist me through developing the website and the use of the javascript tool. This website has been an invaluable tool to understanding the elements in html and javascript. However, I felt I could have done more with javascript, but as it wasn't one of my strengths, I focused on the html part of the website.

Lastly, I reviewed the website accessiblity using [Easy Checks – A First Review of Web Accessibility](https://www.w3.org/WAI/test-evaluate/preliminary/). I went through each steps to ensure the website complied with the easy checks. Through these checks, I had corrected a few things such as missing headers on certain pages.

In conclusion, this task has given me a valuable insight on the many necessary steps that must be undertaken to develop a website and has allowed to to create a simple website of my own to a reasonable quality which complies to the regulatory standards. However, this website mainly contains the framework and requires further development, such as the Live chat box and the contact form before it is functional.