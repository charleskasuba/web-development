### HTML Elements

HTML elements are the core building blocks of a webpage. Each HTML element typically consists of three parts: 

1. **Opening Tag**: Indicates the beginning of the element, which may include attributes.
2. **Content**: The actual data, such as text, links, images, etc., that will be displayed on the webpage.
3. **Closing Tag**: Marks the end of the element, ensuring that the content is properly contained.

Here is an example of how these parts fit together:

```html
<p>This is paragraph content.</p>
<h1>This is heading content.</h1>
<div>This is division content.</div>
```

### HTML Element Structure

In an HTML document, each element is represented by an opening tag and a closing tag. The opening tag may include attributes, and the content is placed between the tags. For example:

- `<p>This is paragraph content.</p>`  
  `<p>` is the opening tag, "This is paragraph content." is the content, and `</p>` is the closing tag.

### HTML Elements vs Tags

- **HTML Elements** are created using **HTML Tags**. An element is defined by a pair of opening and closing tags with content between them. 
- **HTML Tags** are the building blocks that help create elements, enclosed in angle brackets `< >`. For example, `<p>` is a tag, and `<p>This is a paragraph</p>` is the element.

### Nested HTML Elements

HTML elements can be nested inside one another, where the parent element contains one or more child elements. This nesting is hierarchical, and multiple levels of nesting can exist. However, some rules must be followed:

- Every opening tag must have a corresponding closing tag.
- The closing tag of the parent element should come after the closing tags of the child elements.
- Nested elements should be valid HTML.

#### Example of Nested Elements:

```html
<!DOCTYPE html>
<html>
<head>
   <title>Nested Elements Example</title>
</head>
<body>
   <h1>This is <i>italic</i> heading</h1>
   <p>This is <u>underlined</u> paragraph</p>
</body>
</html>
```

In the above example:
- The `<i>` tag is nested inside the `<h1>` tag.
- The `<u>` tag is nested inside the `<p>` tag.

### HTML Void Elements

Void elements (also called empty or self-closing elements) do not require closing tags. They cannot have content between their opening and closing tags, and they do not allow nested elements. Examples of void elements include:

- `<img />` – Used to embed images
- `<br />` – Creates a line break
- `<hr />` – Displays a horizontal line
- `<source />` – Used for embedding media like audio or video

#### Example of Void Elements:

```html
<!DOCTYPE html>
<html>
<body>
   <p>This line contains a line break tag, <br /> hence content is visible in two separate lines.</p>
   <p>This line is <hr /> separated by a horizontal rule.</p>
</body>
</html>
```

### Attributes with HTML Elements

Attributes provide additional information about an HTML element and are added within the opening tag. Attributes are written in a name-value pair format, separated by an equals sign `=`.

Example of an image element with attributes:
```html
<img src="logo.jpg" alt="TutorialsPoint Logo" />
```
Here:
- `src` is the attribute name for the image source.
- `alt` is the attribute name for providing an alternative text.

### Mandatory Closing HTML Elements

While void elements like `<img />` and `<br />` don't require closing tags, other elements such as `<p>` and `<h1>` must have corresponding closing tags. Not closing an element can lead to unexpected results, even if it doesn't always break the webpage.

#### Example of Missing Closing Tags:
```html
<!DOCTYPE html>
<html>
<body>
   <p>This line contains a line break tag, <br /> hence content is visible in two separate lines.
   <p>This line is <hr /> separated by a horizontal rule.
</body>
</html>
```

In the above example, the missing closing `</p>` tags may still display content correctly, but it's considered bad practice.

### Are HTML Elements Case-Sensitive?

No, HTML elements are **not case-sensitive**. This means that you can write tag names in uppercase or lowercase, and they will work the same. However, it is **best practice** to use lowercase letters for consistency and readability, as recommended by the W3C.

#### Example of Case Sensitivity:
```html
<!DOCTYPE html>
<HTml>
<BODY>
   <P>HTML is not case sensitive i.e we can use both upper or, lower case letters in the tags.</p>
</BOdy>
</html>
```

Even though we used uppercase for tags like `<HTml>` and `<BODY>`, the browser will render the content correctly. However, lowercase is preferred in modern HTML code.
