# Welcome to a short front-end exercise

This repository is a static website template meant to introduce students to some HTML and CSS (quickly). If you already know some HTML and CSS, then this exercise shouldn't be too difficult. However, if you're new, we'll learn a bit on how HTML works:

HTML stands for HyperText Markup Language, and it's a language used to structure web pages and its content. It's not a programming language, as it doesn't contain any actual programming logic on its own, but it's a markup language that the internet can use to communicate with its users. HTML works by structuring its content into series of <b>elements</b> that can be organized according to <b>tags</b>. For example:

```html
<p>This is a paragraph tag.</p>
```

Elements can have an opening tag, some content, and a closing tag. Some tags only need an opening tag, like the "img" tag. These tags vary functionality and what content they can store, you can look up what tags are available on the Mozilla Development Docs: <a href="https://developer.mozilla.org/en-US/">Mozilla Developer Docs</a>. Additionally, tags can have attributes. For example, the link I just wrote has an attribute "href" that specifies where the link goes. Attributes can vary, but there are two attributes we should mention: <b>style</b> and <b>class</b>.

The style tag determines what style rules an element must follow. For example:
```html
<p style="color: blue;">This text is blue</p>
```
will appear as <p style="color: blue;">This text is blue</p>

Rather than fill our HTML tags with a bunch of style rules, developers created CSS, or Cascading Style Sheets, so we could define our styles elsewhere. Now, we just need to tell the HTML on which set of styling rules to follow:

```css
/* Our CSS File */
.text-blue {
  color: #0000FF !important;
}
```
```html
<!-- Our HTML File -->
<p class="text-blue">This text is blue</p>
```

With these basics, you can look through the repository and understand a part of what's going on. Here, instead of creating our own CSS file, we're using the Bootstrap-5 CSS library, which also uses some Javascript to work. Bootstrap has its own documentation <a href="https://getbootstrap.com/docs/5.1/getting-started/introduction/">here</a>, but I try to explain some of it in the index file. Note that both html files can be opened in your web browser and even examined with your browser dev tools (Access instructions vary by browser).

The page.html is a blank canvas for you to experiment with. It contains the bare minimum to have a readable HTML web page. I would recommend experimenting with it to practice HTML and perhaps referring to the index.html for ideas.

The index.html is a short web page with basic Bootstrap usage. There's a lot of comments meant to describe each aspect of the HTML, but feel free to delete them if they're in your way. You can look through it and see how an HTML web page might look and maybe take some ideas from it. After looking through it, follow the instructions on Canvas and determine what changes need to be made. This activity doesn't require very many changes to the the actual index.html, but I would recommend spacing out your commits just for practice. Reach out on Slack if you have any questions!

Project Structure: Files of interest
--------

  ```sh
  ├── README.md
  ├── index.html
  ├── page.html
  ├── assets
  │   └── img
  │       └── placeholder-image.png
  └── bootstrap-5.0.2-dist
      ├── css
      │   └── bootstrap.css
      └── js
          └── bootstrap.js
  ```