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
H  color: slategray;
d}
```
Our text's font looks very bland, now to change it for the entire body what we need to do is put:
```html
body {
  font-family: Futura, "Trebuchet MS", Arial, sans-serif;
}
```

This will give us a nicer looking font making our website more appealing.


Lastly let's center our text to the middle of that page. For now, all you should do is copy the code beneath and paste it into your document. There is too much information to explain here that would be better covered later on down your learning.

the code you will need is:
```html
div {
    height: 200px;
    width: 400px;
    text-align: center;

    position: fixed;
    top: 50%;
    left: 50%;
    margin-top: -100px;
    margin-left: -200px;
}
```

Your completed ```<style>/style>``` tags should look like:
```html
<style>

h1 {
  color: deepskyblue;
}

h3 {
  color: slategrey;
}

div {
    height: 200px;
    width: 400px;
    text-align: center;

    position: fixed;
    top: 50%;
    left: 50%;
    margin-top: -100px;
    margin-left: -200px;
}

body {
  font-family: Futura, "Trebuchet MS", Arial, sans-serif;
} 

</style>
```
**Heres what your final site should look like:**
![final website](https://github.com/theonegk/Final-Project/blob/master/website-final.PNG)

# That's it!
Your completed file can be found [here](https://github.com/theonegk/Final-Project/blob/master/First-Webpage.html)




