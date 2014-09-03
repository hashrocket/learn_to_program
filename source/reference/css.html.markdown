#CSS Reference

## Selectors

Select an element by the `id` of `hello`

```html

  <div>
    <h1 id="main">Hello</h1>
    <h1 >Goodbye</h1>
  </div>

```

```html

  h1#main{
    font-weight: bold;
  }

```

---

Select an element by the `class` of `hello`

```html

  <div>
    <h1 class="main">Hello</h1>
    <h1 >Goodbye</h1>
  </div>

```

```html

  h1.main{
    font-weight: bold;
  }

```

Select the body element and make the text _black_

```html

  body{
    color: #000000;
  }

```

## Commonly used styles

```css
  element#id.class.another_class{
    /* this is a comment notice the slash and the star */

    color: #cc9900;
    text-decoration: underline; /* none, line-through, overline */
    font-family: serif; /* sans-serif, monospace */
    font-weight: bold; /* normal, 200, 300, 400 */
    font-size: 12px; /* 16px, 20px, 48px */
    text-align: left; /* center, right justify */
    vertical-align: top; /* middle, bottom */

    background: #ffffff;
    background-color: #ffffff;
    background-image: url('path/to/image.jpg');
    background-repeat: no-repeat; /* repeat-x, repeat-y */
    background-position: 50px 25%;

    height: 10px;
    width: 10px;

    border: solid 1px #000000; /* for all sides */
    /* or specify a side */
    border-top: dashed 2px #ffffff;
    border-right: dashed 2px #aaaaaa;
    border-bottom: dashed 2px #cccccc;
    border-left: dashed 2px #efefef;

    border-radius: 3px;

    padding: 10px;
    padding: 10px 20px 10px 25px;
    /*same as*/
    padding-top: 10px;
    padding-right: 20px;
    padding-bottom: 10px;
    padding-left: 25px;

    margin: 10px;
    margin: 10px 20px 10px 25px;
    /*same as*/
    margin-top: 10px;
    margin-right: 20px;
    margin-bottom: 10px;
    margin-left: 25px;

    float: left; /* right */
    clear: left; /* right, both */

    display: inline; /* inline-block, block, none */
  }
```
