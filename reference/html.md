# HTML Reference

##Sample HTML page

```html
<!DOCTYPE htmll>
<html>
  <head>
    <title>Title in here</title>
  </head>
  <body>
    Body Content here
  </body>
</html>
```

## How to use an Anchor (link) `<a>`

### Link to a page within my own site

__Typing this:__

```html
  <a href="/about">
    About Us
  </a>
```

__Results in the following:__

<a href="/about">
  About Us
</a>

### Link to another website

__Typing this:__

```html
  <a href="http://google.com">
    Take me to Google
  </a>
```

__Results in this:__

<a href="http://google.com">
  Take me to Google
</a>

## How do use a Unordered List `<ul>`

__Typing this:__

```html
<ul>
  <li>first item</li>
  <li>second item</li>
  <li>third item</li>
  <li>
    <ul>
      <li>first item in the fourth item</li>
      <li>second item in the fourth item</li>
      <li>third item in the fourth item</li>
    </ul>
  </li>
</ul>
```

__Results in this:__

<ul>
  <li>first item</li>
  <li>second item</li>
  <li>third item</li>
  <li>
    <ul>
      <li>first item in the fourth item</li>
      <li>second item in the fourth item</li>
      <li>third item in the fourth item</li>
    </ul>
  </li>
</ul>

## How to use a Table `<table>`

__Typing this:__

```html
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

__Results in this:__

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
