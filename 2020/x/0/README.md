# Project 0

Web Programming with Python and JavaScript
"# project0" 


For Project0, I have created a website for an imaginary "Chemistry Classes" and the use of any names, marks, grades, numbers, images or addresses has no real-life relevance to any person.

The project consists of four .html files, 1 .css file and 1.scss file and few images. Every page has made use of the general bootstrap queries to display the main image on top of the page
with the page title "CHEMISTRY CLASSES" and to display the dropdown navigation tab at the top of each page to ease the user switch between different pages.
The first page has title- "Chemistry Classes".
The second page has title- "Page 2".
The third page has title- "Project Page 3".
The fourth page has title- "Project Page4".



"Page1.html" as the first page which contains a brief introduction about the classes and the director of the class.

	It uses multiple classes where the main- "CONTAINER" class has sub-class "ROW" which further has two sub-classes "col-sm" describing the column width required by the two headings
	"ABOUT US" and "DIRECTOR's DESK". They are referenced via their ids under the "nav" tab. There are general stylings used under the <style> tab as well.

	

"Page2.html" describes about the awards and achievements received by the director of the classes and lists some of the shining stars(students) selected into some of the top universities or
working with some of the top companies across the globe, along with their year of selection.

	It uses similar class structure where the main- "CONTAINER" class has sub-class "ROW" which has sub-sub-classes - "col".
	The <img> tag uses class "img-fluid" to make the images flexible and page responsive. 
	Two of the three "col pt-4" classes  make use of paragraph <p> in both and ordered and unordered list <ul>, <ol> and <li> tags.
	The third class makes use of <table> tag with <th> for table headings, <tr> for table rows and <td> for table data tags.
	The .pt-4 makes sure of the padding-top spacing. The .w-100 classes make sure of the spaces in between two different headings/paragraphs. 
	It links "page2style.css" sheet which basically provides styling for <table>, <th>, <td>, <p>, class- .pt-4, id- #navbarDropdown.
	The #navbarDropdown ensures that non of the text within the Dropdown is underlined, unlike in other pages.
	The "p::after" selector in the CSS styling uses unicode for the "star" being added after every paragraph. While the "*" selector, makes sure that all the text within the page is 
	center-aligned.
	It also makes use of five different CSS Properties and five different CSS Selectors. Majority of the page styling and screen responsiveness is due to bootstrap code used.



"Page3.html" has semi-blurred images of handwritten and printed notes as well as question-papers provided to students in the classes.

	It uses similar class structure where the main- "CONTAINER" class has sub-class "ROW" which has two sub-sub-classes- "col".
	The <img> tag uses class "img-fluid" to make the images flexible and page responsive. 
	The .pt-4 makes sure of the padding-top spacing. The .w-100 classes make sure of the spaces in between two different headings/paragraphs.
	To further enhance the styling and provide an individual heading to notes and questions, <h2> heading tag is used along with the styling options to make it bold.
	Each sub-sub-class has a paragrapah at the end of the image and a <button> tag with text "Contact Us" re-directing the user to "Page4.html"
	The first sub-sub-class also has blank heading tag <h3> denoting the use of mobile-responsive text; the styling for which is given under the <style> tag
	The button tag uses bootstrap class-"btn btn-primary btn-lg" within the anchor tag along with other bootstrap stylings.
	Other than the normal stylings being used in other pages too for the same classes, this page uses styling for button and button:hover.
	Also, the mobile-responsive @media query makes sure that none of the images are printed and also the "@media (min-width and max-width)" ensure that the text within them is displayed
	on the page only when the page has certain width, otherwise the text changes.
	
	



"Page4.html" gives the contact details- mobile and landline numbers with the address of classes and google map location.

	It uses similar class structure where the main- "CONTAINER" class has sub-class "ROW" which has two sub-sub-classes- "col".
	The <img> tag uses class "img-fluid" to make the images flexible and page responsive. 
	The .pt-4 makes sure of the padding-top spacing. The .w-100 classes make sure of the spaces in between two different headings/paragraphs.
	Each sub-sub-class have paragrapahs
	The first sub-sub-class makes use of unordered and ordered <ul> and <ol> tags where the <ul> tag has <img> image tag in betweent the text- denoting the use of images in between.
	While the <ol> tag is just a rough text to depict the SCSS styling.
	Both sub-sub-classes have a button tag directing the user to the "Home" page- "Page1.html". The main purpose of the button is shown the "pagefourstyle.scss" style sheet linked
	in the beginning, which shows the SCSS nesting and inheritence with the use of  "@extend".
	The second sub-sub-class makes use of Google map location for the address. It uses the id- "map-container-google-1 for the class- "z-depth-1-half map-container".

For the all the .html pages, the <nav> tag with class- "navbar navbar-expand-lg fixed-top navbar-dark bg-dark" ends after the end of all the division <div> tags, right before the end of 
body </body> tag.
