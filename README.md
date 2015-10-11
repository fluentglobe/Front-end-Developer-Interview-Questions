#Front-end Job Interview Questions

Please realise that we value good people over particular skills. It is however important
for us to figure out your strenghts and weaknesses. And of course your passions, they
are the most important. So please go through this questionaire as you would approach
normal development. Go ahead and look up details that have slipped your mind, but
please consider that you are expected to live up to the skill level reflected in your
answers.

Please send your answers to:

henrik@fluentglobe.com

along with,

* GitHub username
* Skype username
* Time of day we can call you
* A brief introduction to a mobile HTML5 game(or similar) you have built and how

Next up will be a coding challenge.


#### General Questions:

* What did you learn yesterday/this week?
* What excites or interests you about coding?
* Name 3 ways to decrease game load (perceived or actual load time).
* If you could master one technology this year, what would it be?
* What OS do you normally develop on?
* What mobile devices do you have access to for testing?
* Are you a morning or evening person?
* How do you prefer to chat? IRC/iMessage/Slack/Skype/HipChat

#### HTML Questions:

* Have you used different HTML templating languages before?
* What is progressive rendering?
* What are the options for mobile page sizing with meta tag?

#### CSS Questions:

* Have you played around with the new CSS Flexbox or Grid specs?
* How is responsive design different from adaptive design?
* Have you ever worked with retina graphics? If so, when and what techniques did you use?
* Is there any reason you'd want to use `translate()` instead of *absolute positioning*, or vice-versa? And why?

#### JS Questions:

* Explain how `this` works in JavaScript
* Explain how prototypal inheritance works
* Explain why the following doesn't work as an IIFE: `function foo(){ }();`.
  * What needs to be changed to properly make it an IIFE?
* What's the difference between a variable that is: `null`, `undefined` or undeclared?
  * How would you go about checking for any of these states?
* What's the difference between `.call` and `.apply`?
* Explain `Function.prototype.bind`.
* What sort of programming style does ES5 enable?
* What are the pros and cons of using Promises instead of callbacks?
* Do you have a preference between Web Pack and Browserify?
* Do you have a preference between npm and bower?

#### Other Questions:

* What are some advantages/disadvantages to testing your code?
* What's a cool project that you've recently worked on?
* Do you have an interest in European languages? Or other ones?
* Tea or Coffee?
* Cats or Dogs?
* Activity Holiday or Party Holiday?


#### Quiz

Write a function that flattens a nested object into URLs, so that:

    {
      'index': {
        'about': {
          'team': true,
          'company': ['Jim', 'Barry']
        }
      }
    }

Is transformed into:

    {
      'index/about/team': true,
      'index/about/company': ['Jim', 'Barry']
    }
