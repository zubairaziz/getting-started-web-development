# Getting Started With Web Development

This repo is to help anyone get started with their web development journey. Currently a work in progress. PRs welcome.

---

## Prerequisites

- <details>
  <summary>git</summary>
  <p>Git is a version-control system for tracking changes in source code during software development.</p>
  <p>First, you want to get git installed on your system. Here's how to do it for different platforms:</p>
  <ul>
    <li><strong>Mac:</strong> <code>brew install git</code></li>
    <li><strong>PC:</strong> <a href="https://gitforwindows.org/" target="_blank">gitforwindows.org</a></li>
    <li><strong>Linux:</strong> You know what to do</li>
  </ul>
  <p>Then, let's set up your git credentials so your commits can be tied to your account and have it saved on your machine.</p>
  <pre>
  $ git config --global user.email "yourgithubemail"
  $ git config --global user.name "yourfullname"
  $ git config --global credential.helper cache --timeout=31536000  // sets timeout to 1 year
  </pre>
</details>

- <details>
  <summary>text editor</summary>
  <p>A text editor or your internal development environment (IDE) is where you'll spend most of your time in as a developer. You'll be using it to edit all the files that you'll be working with for all your projects.</p>
  <p>I would highly recommend Visual Studio Code, a free and open-source code editor made by Microsoft for Windows, Linux and macOS. Features include support for debugging, syntax highlighting, intelligent code completion, snippets, code refactoring, and embedded Git. I will also list out other text editors that you might want to try out.</p>
  <ul>
    <li><a href="https://code.visualstudio.com/">VS Code</a></li>
    <li><a href="https://atom.io/">Atom</a></li>
    <li><a href="https://www.sublimetext.com/">Sublime Text</a></li>
    <li><a href="https://notepad-plus-plus.org/"></a>Notepad++</li>
  </ul>
</details>

- [Web Development explained](https://www.youtube.com/watch?v=5YDVJaItmaY) (A good intro to all facets of web development)

---

## Beginners Front-End

### HTML

HTML stands for Hyper Text Markup Language. It defines the content and structure of a web page. HTML is the fundamental technology used to define the structure of a webpage. HTML is used to specify whether your web content should be recognized as a paragraph, list, heading, link, image, multimedia player, form, or one of many other available elements or even a new element that you define.

#### What to know?

- Overall structure of a web page including high-level tags like <html>, <head>, <body> and their importance.
- HTML tags and their uses
- Semantic markup
- Accessibility on the web

#### Useful Resources

- [MDN Web Docs: Learn HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)
- [W3Schools: HTML](https://www.w3schools.com/html/default.asp)

#### Great Tutorials

- [Traversy Media: HTML Crash Course For Absolute Beginners](https://www.youtube.com/watch?v=UB1O30fR-EE)
- [freeCodeCamp.org: HTML Full Course - Build a Website Tutorial](https://www.youtube.com/watch?v=pQN-pnXPaVg)

---

### CSS

CSS stands for Cascading Style Sheet. CSS is the first thing you should learn after HTML. While HTML is used to define the structure and semantics of your content, CSS is used to style it and lay it out. For example, you can use CSS to alter the font, color, size, and spacing of your content, split it into multiple columns, or add animations and other decorative features.

#### What to know?

- Different ways of defining styles and best practices around them.
- How are different types of selectors defined in CSS?
- What is specificity?
- What are some of the commonly used CSS properties?
- Cross browser support for modern CSS features
- Knowing how to inspect the styles on a browser.

#### Useful Resources

- [MDN Web Docs: Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)
- [W3Schools: CSS](https://www.w3schools.com/css/default.asp)
- [CSS Tricks](https://css-tricks.com/)

#### Great Tutorials

- [Traversy Media: CSS Crash Course For Absolute Beginners](https://www.youtube.com/watch?v=yfoY53QXEnI)
- [Web Dev Simplified: Learn CSS in 20 Minutes](https://www.youtube.com/watch?v=1PnVor36_40)

---

### JavaScript

JavaScript is a programming language that allows you to implement complex things on web pages. Every time a web page does more than just sit there and display static information for you to look at—displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, or more—you can bet that JavaScript is probably involved.

#### What to know?

- Understanding fundamentals of the language
- Getting familiar with ES6 features
- Getting comfortable with debugging in JavaScript through Browser's developer console.

#### Useful Resources

- [MDN Web Docs: Learn JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
- [The Odin Project: JavaScript](https://www.theodinproject.com/courses/javascript)

#### Great Tutorials

- [Traversy Media: JavaScript Crash Course For Beginners](https://www.youtube.com/watch?v=hdI2bqOjy3c)
- [JavaScript Explained](https://www.youtube.com/watch?v=c-I5S_zTwAc) (5 minute video)