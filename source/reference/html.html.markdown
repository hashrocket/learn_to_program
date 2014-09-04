# HTML Reference

Sample HTML page

```html

<!DOCTYPE html>
<html>
  <head>
    <title>
      Title in here
    </title>
  </head>
  <body>
    <header>
      <h1>
        Main Header
      </h1>
    </header>
    <section id="main">
      Main Content in here ...
    <section>
    <footer>
      Footer Content here ...
    </footer>
  </body>
</html>
```

---

Commonly used elements

```html

  <html>    - every html page starts with this
  <head>    - everthing inside here loads first
  <title>   - text that shows up in the browser's tab
  <body>    - where all the content goes
  <header>  - for the top of a section, or body, or article
  <footer>  - for the bottom of a section, or body, or article
  <ul>      - create an unordered list
  <ol>      - create an ordered list
  <li>      - used inside a list (ordered/unordered) for each item
  <table>   - create a table
  <tr>      - table row
  <td>      - table cell/column
  <p>       - paragraph
  <a>       - anchor A.K.A. a link

  <img src="image/path" />    - image (notice the "/". This is a self closing tag)
  <input type="text" />       - field. Used in forms to enter information

```

---

How to use an Anchor (link) `<a>` within my own site

```

  <a href="/about">
    About Us
  </a>

```

<a href="/about">
  About Us
</a>

---

How to use an Anchor (link) `<a>` to another website

```

  <a href="http://google.com">
    Take me to Google
  </a>

```
<a href="http://google.com">
  Take me to Google
</a>

---

How do use a Unordered List `<ul>`

```

  <ul>
    <li>first item</li>
    <li>second item</li>
    <li>third item</li>
    <li>
      fourth item
      <ul>
        <li>first sub item</li>
        <li>second sub item</li>
        <li>third sub item</li>
      </ul>
    </li>
  </ul>

```

<ul>
  <li>first item</li>
  <li>second item</li>
  <li>third item</li>
  <li>
    fourth item
    <ul>
      <li>first sub item</li>
      <li>second sub item</li>
      <li>third sub item</li>
    </ul>
  </li>
</ul>

---

How do use a Ordered List `<ol>`

```

  <ol>
    <li>first item</li>
    <li>second item</li>
    <li>third item</li>
    <li>
      fourth item
      <ol>
        <li>first sub item</li>
        <li>second sub item</li>
        <li>third sub item</li>
      </ol>
    </li>
  </ol>

```
<ol>
  <li>first item</li>
  <li>second item</li>
  <li>third item</li>
  <li>
    fourth item
    <ol>
      <li>first sub item</li>
      <li>second sub item</li>
      <li>third sub item</li>
    </ol>
  </li>
</ol>

---

How to use a Table `<table>`

```

  <table>
    <thead>
      <th>Name</th>
      <th>Email</th>
      <th>Phone</th>
    </thead>
    <tbody>
      <tr>
        <td>Micah Example</td>
        <td>micah@example.com</td>
        <td>1-800-111-2222</td>
      </tr>
      <tr>
        <td>Hashrocket developer</td>
        <td>dev@eample.com</td>
        <td>1-800-111-3333</td>
      </tr>
      <tr>
        <td>Student Developer</td>
        <td>student@example.com.com</td>
        <td>1-800-111-4444</td>
      </tr>
    </tbody>
  </table>

```

<table>
  <thead>
    <th>Name</th>
    <th>Email</th>
    <th>Phone</th>
  </thead>
  <tbody>
    <tr>
      <td>Micah Example</td>
      <td>micah@example.com</td>
      <td>1-800-111-2222</td>
    </tr>
    <tr>
      <td>Hashrocket developer</td>
      <td>dev@eample.com</td>
      <td>1-800-111-3333</td>
    </tr>
    <tr>
      <td>Student Developer</td>
      <td>student@example.com.com</td>
      <td>1-800-111-4444</td>
    </tr>
  </tbody>
</table>
