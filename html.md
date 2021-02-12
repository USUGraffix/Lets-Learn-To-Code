<img alt="HTML5" src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/>

## HTML is the structure of every website! Think of it as the container for all the awesome stuff you are going to put in your website.

### what you'll learn:

1. [The different basic HTML tags](#popular-html-tags)
2. [Audio and video tags](#audio-and-video-tags)
3. [How to structure a web page](#how-to-structure-html)
4. [How to view your web page in browser](#view-webpage)
5. [Using alt tags for accessability](#alt-tags)
6. [Link tag](#linking)
7. [Head tags](#head-tag)
8. [Meta tags](#meta-tags)

```html
<!DOCTYPE html>
<html>
  <!-- <head> tag is where you store the meta tags, title, 
    icons, and linked style sheets for css. 
    Note: you can also add the css in a style 
    tag here but that's not good practice-->
  <head>
    <title>I am the title of your site</title>
  </head>
  <!-- <body> tag is where you will keep your main html for 
    your page, scripts for javascript code -->
  <body>
    <!-- <div> tag is used to divide information whether 
        that be contact info, buttons, side navigation bar,
         etc... -->
    <div>
      <!-- <ul> is short for unordered list, just simply
            used to make bullet points for each <li> tag-->
      <ul>
        <!-- <li> tag can be used on both <ul> or <ol>-->
        <li>list option 1</li>
        <li>list option 2</li>
      </ul>
      <!-- <ol> is short for ordered list. It is used to make the
            <li> tags into numbered lists.-->
      <ol>
        <li>list option</li>
        <li>list option</li>
      </ol>
    </div>
    <button>I am a button</button>
    <>
  </body>
</html>
```

### Linking

When you make an external CSS file, you need a way to connect to that css file with html.

```html
<link rel="stylesheet" href="./home.css" />
```
