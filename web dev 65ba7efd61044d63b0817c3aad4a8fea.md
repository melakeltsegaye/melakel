# web dev

Web development involves designing, building, and maintaining websites and web applications. It encompasses various technologies and skills, including HTML, CSS, JavaScript, and server-side programming languages.

Web developers use these tools to create interactive and user-friendly websites that provide a seamless experience for users. They work on both the front-end and back-end aspects of a website, ensuring that it functions properly and delivers the intended content.

Front-end development focuses on the visual and interactive elements of a website, such as layout, design, and user interface. Back-end development involves handling server-side processes, databases, and ensuring the website's functionality.

Web developers also need to consider factors like responsiveness, accessibility, and security when building websites. They often collaborate with designers, content creators, and other professionals to create websites that meet the needs of businesses and users.

Overall, web development is an exciting field that constantly evolves with new technologies and trends, offering endless opportunities for creativity and innovation.

IDE(integrated developer environment)

Here is a list of some commonly used HTML tags:

- `<html>`: Defines an HTML document
- `<head>`: Contains metadata about the document
- `<title>`: Defines the title of the document
- `<body>`: Contains the visible content of the document
- `<h1>` to `<h6>`: Defines headings of different levels
- `<p>`: Defines a paragraph
- `<a>`: Defines a hyperlink
- `<img>`: Defines an image
- `<ul>`: Defines an unordered list
- `<ol>`: Defines an ordered list
- `<li>`: Defines a list item
- `<div>`: Defines a division or section
- `<span>`: Defines a section in a document
- `<table>`: Defines a table
- `<tr>`: Defines a table row
- `<td>`: Defines a table cell
- `<form>`: An HTML form is used to collect user input. The user input is most often sent to a server for processing.

### Form Attributes

1. The `action` attribute defines the action to be performed when the form is submitted.
2. The `target` attribute specifies where to display the response that is received after submitting the form.
3. The `method` attribute specifies the HTTP method to be used when submitting the form data.
4. The `<input type="radio">` defines a radio button.
5. The `<input type="checkbox">` defines a **checkbox**.
6. The `<input type="submit">` defines a button for submitting the form data to a form-handler.

The form-handler is typically a file on the server with a script for processing input data.

The form-handler is specified in the form's `action` attribute.

Checkboxes let a user select ZERO or MORE options of a limited number of choices.

Radio buttons let a user select ONE of a limited number of choices.

### Form Element

1. The `<input>` element can be displayed in several ways, depending on the `type` attribute.
2. The `<label>` element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.
3. The `<select>` element defines a drop-down list:
4. The `<option>` element defines an option that can be selected. By default, the first item in the drop-down list is selected.

To define a pre-selected option, add the `selected` attribute to the option.

- `<input>`: Defines an input field
- `<aside>`: The  tag is used to describe the main object of the web page in a shorter way like a highlighter.
- `<base href = ” “>`: The HTML base tag is used to specify a base URI, or URL, for relative links. This URL will be the base URL for every link on the page.
- `<bdi>`: The bdi tag refers to Bi-Directional Isolation. It differentiates a text from other text that may be formatted in a different direction.
- `<iframe>`: The iframe tag defines a rectangular region within the document in which the browser can display a separate document.
- `<fgcaption>`: The figurecaption tag in HTML is used to set a caption to the figure element in a document. This tag is new in HTML5.
- `<figure>`: The figure tag in HTML is used to add self-contained content like illustrations, diagrams, photos, or codes listed in a document.
- `<isindex>`: The index tag is used to query any document through a text field.

These are just a few examples, and there are many more HTML tags available for different purposes.

```jsx
<html>
<head>

<title>Web dev</title>
<isindex prompt="Search" />
</head>

<body>

<aside>
        <h1>This is heading text in aside Tag</h1>
        <p>This is paragraph text in aside Tag</p>
    </aside>

<iframe width="560" height="315" src="https://www.youtube.com/embed/bho8Eo-J8ds?si=UdpwhupT4w1jGcvU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    
    <acronym title="GeeksforGeeks">GFG</acronym>
    <br>
    <acronym title="Operating System">OS</acronym>

<ul>
        <li><bdi class="name">Himanshu Jha</bdi>: indian name</li>
        <li><bdi class="name">الرجل القوي إيان</bdi>: arabic name</li>
    </ul>

<figure>
        <img src="https://media.geeksforgeeks.org/wp-content/uploads/geeks-25.png" alt="gfglogo" style="width:50%">
        <!--HTML figcaption tag starts here-->
        <figcaption>
            GeeksforGeeks Logo
        </figcaption>
        <!--HTML figcaption tag ends here-->
    </figure>

<form action="/action_page.php" target="_blank" method="get">
<option value="fiat" selected>Fiat</option>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
<label for="cars">Choose a car:</label>
<select id="cars" name="cars">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>
</form>

</body>

</html>

```