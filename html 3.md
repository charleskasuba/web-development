HTML tags are essential for structuring the content of web pages. They define different elements, which are displayed on a webpage based on the tag’s type. Here's an overview of some basic HTML tags:

### 1. **Heading Tags (`<h1>` to `<h6>`)**
Headings are used to define the titles and subheadings of a webpage. HTML has six levels of headings, with `<h1>` being the highest and `<h6>` the lowest. Each heading adds space before and after the text.

#### Example:
```html
<!DOCTYPE html>
<html>
<head>
   <title>Heading Example</title>
</head>
<body>
   <h1>This is heading 1</h1>
   <h2>This is heading 2</h2>
   <h3>This is heading 3</h3>
   <h4>This is heading 4</h4>
   <h5>This is heading 5</h5>
   <h6>This is heading 6</h6>
</body>
</html>
```

### 2. **Paragraph Tag (`<p>`)**
The `<p>` tag is used to structure text into paragraphs. Each paragraph should be enclosed within the `<p>` and `</p>` tags.

#### Example:
```html
<!DOCTYPE html>
<html>
<head>
   <title>Paragraph Example</title>
</head>
<body>
   <p>This is the first paragraph of text.</p>
   <p>This is the second paragraph of text.</p>
   <p>This is the third paragraph of text.</p>
</body>
</html>
```

### 3. **Line Break Tag (`<br />`)**
The `<br />` tag creates a line break, making the following content appear on a new line. It's an empty tag, meaning it does not have a closing tag.

#### Example:
```html
<!DOCTYPE html>
<html>
<head>
   <title>Line Break Example</title>
</head>
<body>
   <p>Hello<br /> You delivered your assignment on time.<br />
      Thanks<br /> Mahnaz</p>
</body>
</html>
```

### 4. **Center Tag (`<center>`)**
The `<center>` tag aligns the content to the center of the page. However, this tag is deprecated in HTML5, and it's recommended to use CSS for centering content.

#### Example:
```html
<!DOCTYPE html>
<html>
<head>
   <title>Centering Content Example</title>
</head>
<body>
   <p>This text is not centered.</p>
   <center>
      <p>This text is centered.</p>
   </center>
</body>
</html>
```

### 5. **Horizontal Rule Tag (`<hr />`)**
The `<hr />` tag inserts a horizontal line, often used to visually separate sections of content.

#### Example:
```html
<!DOCTYPE html>
<html>
<head>
   <title>Horizontal Line Example</title>
</head>
<body>
   <p>This is paragraph one and should be on top</p>
   <hr />
   <p>This is paragraph two and should be at the bottom</p>
</body>
</html>
```

### 6. **Preserve Formatting Tag (`<pre>`)**
The `<pre>` tag is used to preserve the formatting of text, such as indentation and line breaks. It's often used to display code exactly as it appears in the HTML.

#### Example:
```html
<!DOCTYPE html>
<html>
<head>
   <title>Preserve Formatting Example</title>
</head>
<body>
   <pre>
      function testFunction( strText ){
         alert (strText)
      }
   </pre>
</body>
</html>
```

### 7. **Non-breaking Space (`&nbsp;`)**
The `&nbsp;` entity represents a non-breaking space, meaning that text with `&nbsp;` will not break across lines. This is useful when you want to prevent words from breaking in the middle.

#### Example:
```html
<!DOCTYPE html>
<html>
<head>
   <title>Nonbreaking Spaces Example</title>
</head>
<body>
   <p>Example without non-breaking spaces: 12 Angry Men.</p>
   <p>Example with non-breaking spaces: 12&nbsp;&nbsp;&nbsp;Angry&nbsp;&nbsp;&nbsp;Men.</p>
</body>
</html>
```

### 8. **Listing Tags (`<ul>`, `<ol>`, and `<li>`)**
- The `<ul>` tag creates an unordered list.
- The `<ol>` tag creates an ordered list.
- The `<li>` tag is used to define each list item within both unordered and ordered lists.

#### Example:
```html
<!DOCTYPE html>
<html>
<head>
   <title>Listing Tags Example</title>
</head>
<body>
  <h2>Unordered List</h2>
  <ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
  </ul>
  <h2>Ordered List</h2>
  <ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
  </ol>
</body>
</html>
```

These tags are some of the most commonly used to build basic structures and elements on a webpage. Each tag plays a role in formatting and displaying content, and when combined with other tags and styling techniques (like CSS), HTML allows you to create visually rich and structured webpages.
