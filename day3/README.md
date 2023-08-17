
web Form--

1--<form>👉🏻 Tag - Defining a Form:
The <form> tag defines an area in which user input is gathered. The action attribute specifies where the form data will be sent once it's submitted.
exp

    <form action="submit_page.php" method="POST">
    <!-- form elements go here -->
    </form>

        
2--<input>👉🏻 Tag - Input Fields:
The <input> tag is used to create various types of input fields. The type attribute determines the type of input field, such as text, password, radio, etc.
exp
       
    <input type="text" name="username" id="username">

3--name Attribute👉🏻 - Identifying Form Data:
The name attribute is used to uniquely identify form elements when the form is submitted. It's crucial for processing user input on the server.

    <input type="text" name="email" id="email">

4--id Attribute👉🏻 - Unique Element Identification:
The id attribute provides a unique identifier for an element. It's often used for targeting elements with CSS or JavaScript.

    <input type="password" name="password" id="password">

5--<fieldset> and <legend> Tags👉🏻 - Grouping Elements:
The <fieldset> tag groups related form elements together, and the <legend> tag provides a caption or title for the group.

    <fieldset>
    <legend>Contact Information</legend>
    <input type="text" name="name" id="name">
    <!-- more form elements -->
    </fieldset>
