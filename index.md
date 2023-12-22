# HTML Tutorial

In this tutorial you will learn all the basics of html that you need to know to start programming in html

## Basic Boilerplate

Open up your text editor and paste the following code in there.

```html
<html>
<head>
  <title>Web Development Tutorial</title>
</head>
<body>
<!--All HTML Body here-->
</body>
</html>
```

Now save the file by name `index.html` in any folder of your choice.

The html body is wrapped between `<body>` and `</body>`.

## Headings

So to make a heading for the webpage, in the `<body>` section, add following code.

```html
<h1>Heading Level 1</h1>
<h2>Heading Level 2</h2>
<h3>Heading Level 3</h3>
<h4>Heading Level 4</h4>
<h5>Heading Level 5</h5>
<h6>Heading Level 6</h6>
```

So there are 6 heading levels, in the order of biggest to smallest.

Now I want you to try out this webpage by opening this html file in the browser of your choice. Everytime you make a change and save file, reload the webpage to see the difference.

## Paragraphs

Now these are the most important of all, the paragraphs. They take up a big chunk of the websites content.

So to create a paragraph, in the `<body>` section below the `<h6>` you just wrote, paste the following code.

```html
<p>This is a paragraph</p>
```

## Horizontal rules

Horizontal rules are just normal horizontal lines which help in dividing sections. So to create one simply add an `<hr>` tag where you want to make the divider. Like this:

```html
<h3>Section 1</h3>
<p>So this is some dummy text to cover up section 1's content.</p>
<hr>
<h3>Section 2</h3>
<p>This is some more dummy text to cover up section 2's content.</p>
```

And now with all this learnt, I want you to make a basic webpage about any topic you want. This is just for you to get your hands dirty in these basic html tags.

## Links

Links are extremely important when you want your user to navigate from one page to another. So to do that is as easy as follows:

```html
<p>Navigate to the website of <a href="www.google.com">google</a>.
```

## Images

Images can easily be added with the `<img>` tag as follows:

```html
<img src="image_url/or/path/to/the/file" height="100px" width="100px"></img>
```

We can even make a link image by containing `<img>` tag in the `<a>` tag.

## Tables

Making tables is a bit more complicated, but here is how we can do it.

```html
<table border=1>
  <thead>
    <tr>
      <th>Col 1</th>
      <th>Col 2</th>
      <th>Col 3</th>
    </tr>
  </thead>
  <tr>
    <td>Just some dummy</td>
    <td>Just some dummy</td>
    <td>Just some dummy</td>
  </tr>
  <tr>
    <td>text in col 1</td>
    <td>text in col 2</td>
    <td>text in col 3</td>
  </tr>
</table>
```

It is kind of complicated, but try it out, it is a good way to show data, and also you can use it as layout manager.

With all this learnt, now I again want you to try building a website about any topic you want.
