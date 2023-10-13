# JavaScript Learning Module

*Quickly establishing a learning plan greatly improves your odds of success in self-learned software engineering.

### How to Use: 
Fork this repo, then simply read all of the things and do all of the things.  Retain your answers to the exercises in "Page_##.js" files in the "Exercises" directory.  Place files for your completed projects in the "Completed Projects" directory and fill out the following information:

Self-Taught Learner's Name: 
<br>
Date Started:
<br>
Date Finished:
<br>
Summarize your learning experience in one to two paragraphs: 
<br>
<br>
What did you enjoy the most in this learning module and why?
<br>
<br>
What did you enjoy the least in this learning module and why? 
<br>
<br>
# Adrian's Awesome Explainer for Self Taught Students:  JavaScript

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
[PDF](Book/Eloquent_JavaScript.pdf)<br>
[EPUB](Book/Eloquent_JavaScript.epub)<br>

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
- [Page 37](Exercises/Page_37.md)
- [Page 55](Exercises/Page_55.md)
- [Page 79](Exercises/Page_79.md)
- [Page 95](Exercises/Page_95.md)
- [Page 115](Exercises/Page_115.md)
- [Page 126](Exercises/Page_126.md)
- [Page 165](Exercises/Page_165.md)
- [Page 178](Exercises/Page_178.md)
- [Page 201](Exercises/Page_201.md)
- [Page 214](Exercises/Page_214.md)
- [Page 241](Exercises/Page_241.md)
- [Page 259](Exercises/Page_259.md)
- [Page 282](Exercises/Page_282.md)
- [Page 306](Exercises/Page_306.md)
- [Page 328](Exercises/Page_328.md)
- [Page 348](Exercises/Page_348.md)
- [Page 367](Exercises/Page_367.md)
- [Page 387](Exercises/Page_387.md)


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
