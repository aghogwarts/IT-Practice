# The use of Audio and Video Tags

HTML5 includes special elements (tags) allowing to include video and audio and to define controls as below

<details><summary>Audio Tag</summary>
<p>
  
**\<audio> -** The \<audio> tag allows you to embed/add audio files on Webpages
  - **Attributes of \<audio> Tag -**
  
  | Attribute | Values | Description |
  | --- | --- | --- |
  | autoplay | NA | autoplay on site load |
  | controls | NA | show audio controls |
  | loop | Value | start over again after end | 
  | muted | NA | specifies that the output be muted |
  | src | URL | URL of audio file to use |
     
<p>
</details>
<details><summary>Video Tag</summary>
<p>  
    
**\<video> -** The \<video> tag is used to embed video into your web page
  - **Attributes of \<audio> Tag -**
  
  | Attribute | Values | Description |
  | --- | --- | --- |
  | src | URL | URL of video file to embed |
  | autoplay | NA | autoplay on site load |
  | controls | NA | show video controls |
  | height | pixels | sets the height of the embed |
  | width  | pixels | sets the width of the embed |
  | loop | Value | start over again after end | 
  | muted | NA | specifies that the output be muted |
  | poster | URL | URL of the image to be set as the default cover image |
  | preload | auto, metadate, none | how to load the video when the webpage loads |
  
</p>    
</details>
  
## Some important points to remember

## Practice problem statements
  
<details><summary>Use of Audio on web pages using HTML5</summary>
<p>

```diff
- Question - 
  
+ Create a webpage to set up an audio file with controls. The file should play on browser load and again as soon as it ends.
+ Create another webpage to set up multiple file formats for the same audio file. It should play automatically with controls. Browser must display the appropriate message when a specific file isn't supported.
```
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Inserting Audio</title>
    </head>
    <body>
        <h1>Inserting Single Audio Source</h1>
        <audio controls autoplay loop src="\\C:\Users\Admin\Documents\test\stay.mp3">
            Not Supported
        </audio>
    </body>
</html>
```
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Inserting Audio</title>
    </head>
    <body>
        <h1>Inserting Multiple Audio Source</h1>
        <audio controls autoplay>
            <source src="\\C:\Users\Admin\Documents\test\stay.mp3">
            <source src="\\C:\Users\Admin\Documents\test\stay.ogg">
            Not Supported
        </audio>
    </body>
</html>
```
  
</p>
</details>
<details><summary>Use of Video on web pages using HTML5</summary>
<p>

```diff
- Question - 
  
+ Create a webpage to display a video file on a web page and plays automatically with controls. It's dimensions should be 150*150 px.
+ Create another webpage to set up multiple file formats for the same video file. It should play automatically with controls. Dimensions should be 100*100 px. Browser must display the appropriate message when a specific file isn't supported.
```
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Inserting Video</title>
    </head>
    <body>
        <h1>Inserting Single Video Source</h1>
        <video height="150" width="150" controls autoplay src="\\C:\Users\Admin\Documents\test\stay.mp4">
            Not Supported
        </video>
    </body>
</html>
```
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Inserting Video</title>
    </head>
    <body>
        <h1>Inserting Multiple Video Source</h1>
        <video height="100" width="100" controls autoplay>
            <source src="\\C:\Users\Admin\Documents\test\stay.mp4">
            <source src="\\C:\Users\Admin\Documents\test\stay.ogg">
            Not Supported
        </video>
    </body>
</html>
```
  
</p>
</details>  
