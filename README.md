# Web-designing---

day1 

#-------------Day1-------------

1--Document Type Declaration: <!DOCTYPE html> indicates that the document is written in HTML5.

    2--<html> Tag: The root element of the HTML document.
3--<head> Section: Contains metadata about the document, such as the character encoding, viewport settings, and the title of the webpage.

    4--<body> Section: Contains the visible content of the webpage.
5--Headings: Various heading levels , h1 & h2  are used to define hierarchical headings.

    6--Horizontal Line: The <hr> tag adds a horizontal line for visual separation.
7--Paragraph with Formatting: The <p> tag defines a paragraph. Within the paragraph, various tags like <b>, <i>, <small>, <sup>, and <sub> are used to format text.

    8--Unordered List: The <ul> tag creates an unordered (bullet) list. Nested lists are also used within list items.
9--Ordered List: The =ol tag creates an ordered (numbered) list. The type="A" attribute is used to change the numbering style to uppercase letters.

    10--Hyperlink: The <a> tag creates a hyperlink. It links to a YouTube video and is placed within a paragraph. A separate <h1> heading is added.



-------------Day2--------------

Links (<a>): 

    --These links direct users to different pages and external websites. The target="_blank" attribute in the Google Maps link opens the link in a new tab.
------------->


Images (<img>):

    --Images are displayed using the <img> tag. The src attribute specifies the image file, the alt attribute provides alternative text, and the width attribute controls the display width.
---------------->


Videos (<video>): 

    --Videos are embedded using the <video> tag. The src attribute specifies the video file, and the controls attribute adds video controls. The loop attribute makes the video loop, and the poster attribute provides an image that is displayed before the video is played.
----------------->


<iframe> Tags: 

    --The <iframe> tags are used to embed external content. One embeds a YouTube video, and the other embeds a GitHub page.
-------------------->

  
Tables 

    --(<table>, <thead>, <tbody>, <tfoot>, <th>, <td>): A table is created with headers (<th>), data cells (<td>), and footer cells (<tfoot>). The colspan attribute in the footer cell merges columns.>



---------------------Day3------------------



web Form--

👉1--<form> Tag - Defining a Form:
The <form> tag defines an area in which user input is gathered. The action attribute specifies where the form data will be sent once it's submitted.
exp

    <form action="submit_page.php" method="POST">
    <!-- form elements go here -->
    </form>


        
👉2--<input> Tag - Input Fields:
The <input> tag is used to create various types of input fields. The type attribute determines the type of input field, such as text, password, radio, etc.
exp
       
    <input type="text" name="username" id="username">

👉3--name Attribute - Identifying Form Data:
The name attribute is used to uniquely identify form elements when the form is submitted. It's crucial for processing user input on the server.

    <input type="text" name="email" id="email">

👉4--id Attribute - Unique Element Identification:
The id attribute provides a unique identifier for an element. It's often used for targeting elements with CSS or JavaScript.

    <input type="password" name="password" id="password">

👉5--<fieldset> and <legend> Tags - Grouping Elements:
The <fieldset> tag groups related form elements together, and the <legend> tag provides a caption or title for the group.

    <fieldset>
    <legend>Contact Information</legend>
    <input type="text" name="name" id="name">
    <!-- more form elements -->
    </fieldset>

👉6--required Attribute - Making Fields Mandatory:
The required attribute makes a form field mandatory. Users must fill out this field before they can submit the form.
   
    <input type="text" name="name" id="name" required>

👉--Text Area - Multi-line Input:
The <textarea> tag creates a multi-line text input area. The cols and rows attributes define its dimensions.

    <textarea name="address" id="address" cols="30" rows="4"></textarea>
    
👉8--Email Input - Validating Email:
The type="email" attribute in an <input> tag helps browsers validate the entered text as an email address.

    <input type="email" name="email" id="email">
    
👉9--Number Input - Numeric Input:
The type="number" attribute creates an input field for numeric values. It may include additional attributes like min and max.

    <input type="number" name="age" id="age" min="0" max="120">
    
👉10--Dropdown Select - Selecting Options:
The <select> tag creates a dropdown menu. Each option is defined with an <option> tag. The value attribute specifies the value sent to the server.

    <select name="country" id="country">
    <option value="USA">United States</option>
    <option value="UK">United Kingdom</option>
    </select>

👉11--Date Input - Selecting Dates:
The type="date" attribute in an <input> tag provides a date picker for selecting dates.

    <input type="date" name="birthdate" id="birthdate">
    
👉12--Password Input - Secure Text Input:
The type="password" attribute in an <input> tag masks the entered text for security (e.g., passwords).

    <input type="password" name="password" id="password">

👉13--Submit Button - Form Submission:
The <input> tag with type="submit" creates a button that submits the form data to the server.

    <input type="submit" value="Submit">






