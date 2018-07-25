# Step 2 - HTML

Before we dive into coding away our first website we must first understand what HTML is.

**From [W3Schools](https://www.w3schools.com/html/html_intro.asp)**
- *HTML is the standard markup language for creating Web pages.*
- *HTML stands for Hyper Text Markup Language*
- *HTML describes the structure of Web pages using markup*
- *HTML elements are the building blocks of HTML pages*
- *HTML elements are represented by tags*
- *HTML tags label pieces of content such as "heading", "paragraph", "table", and so on*
- *Browsers do not display the HTML tags, but use them to render the content of the page*

Now that we have a basic understanding of what HTML is, let's dive into the coding aspect of it.
`
Open up Atom and click **File -> New File**
![Atom New File](https://github.com/theonegk/Final-Project/blob/master/new-file-atom.png)

Afterwords, click **File -> Save As**
Let's save the file as "First-Webpage.html"

What you should do now is copy and paste the next lines of code into your Atom window:
```html

<!DOCTYPE html>
<html>
<head>
<title></title>
</head>
<body>


</body>
</html>
```

This is known as the skeleton for HTML files. All HTML files will include this.

The next step we're going to want to do is fill in the blanks with our personal information.
We are going to put the website name in the ```html <title></title``` part of the code. Let's just put ```html <title>My First Webpage```

Okay now that we got that ready Let's add two lines of Code to our Body.
We are going to be adding an H1 and H3 header. These are just different sizes of the headers (with 1 being the biggest)
It is good practice to always put content in a container <div>. The <div> tag just defines a division or a section in an HTML document.
  
So what we wanna do now is put this next block of code **INSIDE** our <body> </body> tags:
```html
<div>

<h1>Hello World!</h1>
<h3>This Is My First Website</h3>

</div>
```
Then click Save!

As you can probably tell, what ever text that goes in between these tags will be the content displayed

Your complete html file will look like:
```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>
<div>

<h1>Hello World!</h1>
<h3>This Is My First Website</h3>

</div>

</body>
</html>
```

# That's it!
[Click here for the next step]

