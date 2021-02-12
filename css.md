<img alt="CSS3" src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/>

## CSS is what makes your website look good! This is your websites personality!

### what you'll learn:

1. [How to give your website color](#color-website)
2. [Fonts Fonts Fonts](#fonts)
3. [Hovers](#hover-animations)
4. [Transitions](#transitions)
5. [id](#id)
6. [class](#class)
7. [How to position items on your website](#position-elements)
   a. [Vanilla CSS](#vanilla-css)
   b. [Flex box](#flex-box)
   c. [CSS Grid](#css-grid)
8. [Responsiveness](#responsiveness)
9. [Specificity](#specificity)

### Color Website

```css
body {
  background: lightgray;
  color: black;
}
div {
  background: black;
  color: white;
}
```

### Fonts

If you want to add different fonts to a certain element, you can use the font-family in that element name.

```css
p {
  font-family: comic sans;
}
```

> Note: If you want your whole site to have a font, put the font-family code snippet in your body element.

### Hover Animations

A great way to add a hover effect on any element is to use the :hover on elements you're targeting

```css
div:hover {
  background-color: yellow;
}
```

### Transitions

Animations are great and a one way to animate with time is using`transition`

```css
button {
  width: 100px;
  transition: 2s;
}

button:hover {
  width: 200px;
}
```

### id

There are times when you need to target only `one element` and this is where `id` comes into play
HTML

```html
<div id="idName"></div>
```

> Note: Remember to always give your id and class a purposeful name, meaning you should give your element id or class a name that explains the task of that element. i.e. formContainer

CSS

```css
#idName {
  border: 2px solid red;
  font-family: helvetica;
}
```

### class

Let's say you have a `bunch of elements` and not just one that you want to target

```html
<div class="className"></div>
<div class="className"></div>
<button class="className"></button>
<ol class="className"></ol>
```

> Note: Remember to always give your id and class a purposeful name, meaning you should give your element id or class a name that explains the task of that element. i.e. formContainer

CSS

```css
.className {
  border: 2px solid red;
  font-family: helvetica;
}
```

### Position Elements

##### Vanilla CSS

##### Flex Box

##### CSS Grid

### Responsiveness

### Specificity
