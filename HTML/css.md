# Cascading Style Sheets (CSS)

CSS is used to control the visual layout or how a webpage and it's elements look.

<details><summary>Types of CSS</summary>
<p>
  
1. **Inline CSS -** it uses the sytle attribute in any HTML start tag. It is used to apply CSS on a single line or element. For example -
```html
<p style=" color: blue">Hello CSS</p>
```
2. **Embedded or Internal CSS -** it is used to apply CSS on a single page or a class of elements. It is used within the style tag in the head section of a webpage. For example -
```html
!DOCTYPE html>
<html>
<head>
<style>
h1{color:red}
</style></head>
<body>
<h1>The Internal CSS is applied on this heading.</h1>
<p>This won't be affected</p>
</body>
</html>
```
3. **External CSS -** it is generally used when you want to make changes on multiple pages. It can change the look of an entire site by just changing the code of one file. It uses the <link> tag on every page which goes into the <head> section. An external CSS makes use of another file which contains no HTML code and is saved with a .css extension. For example -

**Main file -**
```html
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
<h1>This is a heading</h1>
</body>
</html>
```
  
**style.css -**
```css
h1 { color: navy; margin-left: 20px }
```

</p>
</details>

## Practice Problems

<details><summary>Basic text editing with CSS</summary>
<p>

```diff
+ Write html code to display a text Information Technology having font size 36, apply dotted border to the text and border color effect using CSS.
```
```html
  <p style=" font-size: 36px; border-style: dotted; border-color: green;">Information Technology</p>
```

```diff
+ Write a program using html with following CSS specifications
a) To create a form that should accept name, number of 
present students (compulsory) , time and file to upload from 
the user.
b) Create submit button to send the data.
c) The heading of the form should have border with blank 
space around the content.
```
```html
<h1 style="border: solid 1px; padding: 20px;">Student details</h1>
<form>
Enter Name: <input type="text"><br>
Number of present students: <input type="number" required><br>
Enter Time: <input type="time"><br>
Upload File: <input type="file"><br>
<br>
<input type="submit">
</form>
```
  
</p>
</details>
