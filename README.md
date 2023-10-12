# JavaScript Learning Module

## Adrian's Awesome Explainer for Self Taught Students:  JavaScript

Now that I'm more familiar with JavaScript, it's hard to pinpoint what was initially confusing. All I know is that everything was confusing at first 😵. My first programming language was C++, which didn't baffle me like JavaScript did. I think it's all the period "." joined names. It's tough to discern which words joined by the period are reserved keywords or instructor-made terms. Half the battle with learning JavaScript is the teacher 👩‍🏫. For that reason, I strongly recommend working through a JavaScript book cover-to-cover 📚. Don't listen to anyone else's opinions on JavaScript until you've done this. That's an order! 📣

The confusion around JavaScript often stems from its naming conventions and syntax. It's incredibly flexible and has fewer rules than other languages 🤓. You don't have to declare data types on variables 🤯, and semicolons at the end of each line are optional 🤯 (though still best practice).

When you encounter code like this, you might want to flee 🏃‍♀️:

```javascript

class Emitter {
  constructor(max) {
    this.max = max;
    this.asyncIdx = 0;
  }
  async *[Symbol.asyncIterator]() {
    while (this.asyncIdx < this.max) {
      if (this.asyncIdx < 3) {
        yield this.asyncIdx++;
      } else {
        throw 'Exited loop';
      }  
    }
  }
}
```

This snippet will make sense once you reach that chapter in the book 📖. You might wonder, "Are they just randomly joining two words with a period?" Sadly, it's not that simple. However, comprehensive learning material will demystify JavaScript's syntax.  It is my opinion that the reading material provided forth with in the Learning Material folder will bring clarity and some mastery of JavaScript.

JavaScript doesn't require a compiler and works in any browser, be it Mac, Windows, or Linux 🌐. In the early days of the WWW, companies needed a standard to avoid a "choose your own adventure" scenario, akin to VHS vs. Beta or Blu-Ray vs. HD-DVD 📼. Enter JavaScript. It breaks down all the HTML elements on a webpage into objects, known as the Document Object Model (DOM) 📄.  There was now a way to make the things inside of a \<body> tag or \<h1> or \<div> etc.. do program kinds of things, and change the look and the content displayed without any compiling needed.

But wait, there's more! It also controls browser activities, like pop-up windows or screen size, termed the Browser Object Model (BOM) 🖥️. This led to robust features, making JavaScript a comprehensive language. Innovations like Node.js allow JavaScript to function outside the browser, enabling full client/server programs without requiring compilation and being OS-agnostic 🌟.  You need to buy the book and read every page of everything listed below and complete the activites as part of your own portfolio.

# Learning Material
 
 ### MDN JavaScript Documentation

 - [MDN JavaScript Official Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
 
 ### Book: Eloquent JavaScript: A Modern Introduction to Programming
 ### Third Edition<br>
[PDF](Books/Eloquent_JavaScript.pdf)<br>
[EPUB](Books/Eloquent_JavaScript.epub)<br>

### Learning Objectives

- Values, types, and operators
- Program structure
- Functions
- Data structures, objects, and arrays
- Higher-order functions
- Bugs and errors
- Regular expressions
- Modules
- Asynchronous programming
- The Document Object Model (DOM)
- Handling events
- HTTP and Forms
- Node.js


# JavaScript Learning Exercises and Projects
### Eloquent JavaScript Exercises
Complete the exercises on the following pages:
- Page 37
- Page 55
- Page 79
- Page 95
- Page 115
- Page 126
- Page 165
- Page 178
- Page 201
- Page 214
- Page 241
- Page 259
- Page 282
- Page 306
- Page 328
- Page 348
- Page 367
- Page 387


### Eloquent JavaScript Projects 

- Project: A Robot - Page 117
- Project: A Programming Language - Page 202
- Project: A Platform Game - Page 261
- Project: A Pixel Art Editor - Page 330
- Project: A Skills Sharing Website - Page 369


# Additional Modules

 - Awesome Self-Taught Data Structures Curriculum (pending creation as of 10/8/23)



# Snooze-fest

©️ Adrian Hacker Copyright rights reserved 2023 - 2024<br>
Created under Creative Commons 1.0 universal license, open source, free to modify and distribute.<br>
*A.I. was used for spelling, grammar, and emoji placement only
