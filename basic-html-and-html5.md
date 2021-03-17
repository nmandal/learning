# Basic HTML and HTML5

```
<h1>This is a main header</h1>
<h2>This is a sub header</h2>
<p>This is a paragraph</p>
<!-- This is an HTML comment -->
```

HTML5 descriptive tags:
- `main` - helps search engines find the main contents of your page
- `header`
- `footer`
- `nav`
- `video`
- `article`
- `section`

Images: `<img src="https://www.freecatphotoapp.com/your-image.jpg" alt="A business cat wearing a necktie.">`

Links: 

- External: `<a href="https://freecodecamp.org">this links to freecodecamp.org</a>`

- Internal:
```
<a href="#contacts-header">Contacts</a>
...
<h2 id="contacts-header">Contacts</h2>
```

- New page: `target="_blank"`

- Dead link: `href="#"

Lists:

- Bulleted Unordered:
```
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
```
- Numbered Ordered:
```
<ol>
  <li>Garfield</li>
  <li>Sylvester</li>
</ol>
```

Text Field: `<input type="text" placeholder="Text here please" required>`

Form:
```
<form action="/url-where-you-want-to-submit-form-data">
  <input>
  <button type="submit">this button submits the form</button>
</form>
```

Radio buttons: Only one answer out of multiple options:

```
<form action="">
    <input type="text" placeholder="Required text" required>
    <label for="indoor"> 
      <input id="indoor" type="radio" name="indoor-outdoor">Indoor
    </label>
    <label for="outdoor"> 
      <input id="outdoor" type="radio" name="indoor-outdoor">Outdoor
    </label>
    <button type="submit">Submit</button>
  </form>
 ```

 Checkboxes: May have more than one answer
 ```
 <form action="">
    <label for="loving">
      <input id="loving" type="checkbox" name="personality">
      Loving
    </label>
    
    <label for="hairy">
      <input id="hairy" type="checkbox" name="personality">
      Hairy
    </label>
    
    <label for="hungry">
      <input id="hungry" type="checkbox" name="personality"> 
      Hungry
    </label>
    
    <button type="submit">Submit</button>
  </form>
```

- Use value attribute with Radio Buttons and Checkboxes

- Check Radio Buttons and Checkboxes by Default

The `div` element, also known as a division element, is a general purpose container for other elements.

- Define the Head And Body of an HTML Document
```
<!DOCTYPE html>
<!DOCTYPE html>
<html>
  <head>
    <meta />
  </head>
  <body>
    <div>
    </div>
  </body>
</html>
```