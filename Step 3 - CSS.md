# STEP 3 - CSS

Okay, So now that we got our website's content there let's add some CSS to it to make it look a lot nicer than what it is.

Let's start with a background on what CSS is:

**From [W3Schools](https://www.w3schools.com/html/html_css.asp)**
*CSS stands for Cascading Style Sheets.
CSS describes how HTML elements are to be displayed on screen, paper, or in other media.
CSS saves a lot of work. It can control the layout of multiple web pages all at once.
CSS can be added to HTML elements in 3 ways:*
- *Inline - by using the style attribute in HTML elements*
- *Internal - by using a <style> element in the <head> section*
- *External - by using an external CSS file*

*The most common way to add CSS, is to keep the styles in separate CSS files. However, here we will use inline and internal styling, because this is easier to demonstrate, and easier for you to try it yourself*

**Lets get back to the Atom Text editor:**
Open back up your "First-Webpage.html" file

The first thing we need to do to get started with CSS is add ```<style></style>``` tags inside our ```<head></head>``` tags

Now that we have the style tags this will let the document know we are trying to add a design to the website. We must now know what we want to target.

Let's say I want the H1 to be a deep sky blue color. I know I want to target to be the h1 header. What I do in the style tags is:
```html
<style>

h1 {
  color: deepskyblue;
}

</style>
```
Furthermore, if I wanted to make the h3 header slategray color I would similarly just add:
```html
h3 {
  color: slategray;
}
```



