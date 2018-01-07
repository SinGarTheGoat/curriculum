# Stacks

### Projected Time
30-45 minutes

### Prerequisites


### Motivation


### Objective
**Students will be able to** implement a stack.

### Specific Things To Teach
- What is a stack?
- Methods a stack offers.
  - push
  - pop
  - peak
- What makes a stack? 
- When would you use a stack?
- Stacks represented as arrays.

### Materials

- [Great comprenhesive video on stacks](https://www.youtube.com/watch?v=F1F2imiOJfk)
- [A site that goes more into detail and also covers implementation](https://www.geeksforgeeks.org/stack-data-structure/#design)

### Mini Lesson
**Introduction**

Stacks are one of the most basic datastructures in computer science. At it's core a stack is just a list of data or objects arrainged in the order they where inserted.

Stacks are based around the modle of **last in, first out.** this means that anytime somthing is inserted into the stack it is inserted onto the back of the stack, and anytime an object is removed it is removed from the back of the stack. Any other arrangement breaks the stack.

One example of a stack is a out-box of papers on a desk. A person who adds to the stack puts their paper on top of the stack. When somone goes through the stack they take one peice of paper at a time off the stack because that is the easiest one to grab. 

Can you think of another example of a stack in your day to day life? 

**Stack Methods**
Due to stacks being so common in computerscience there are a few methods that just about every stack is designed with.
  - `push()`: This method inserts new objects into the stack.
  - `pop()`: This method removes the last object added to the stack and returns it. 
  - `peek()`: This method returns the last object inserted but does not remove it.
  
Stacks may have other methods and functanoality such as,
  - `isEmpty()`: Boolean method that returns `true` if the stack has no objects.
  - `isFull()`: Boolean method that retuns `true` is a stack cannot accept another object.
  - `getSize()`: Returns an integer number showing how many objects are in the stack.


**What makes a stack?**
A stack is not defined by its implimatation, but rather on its functionality. It does not matter how you get your stack to work, although the efficiency, (speed) of your stack does. Any implimatation that yields a [big-O](https://www.youtube.com/watch?v=MyeV2_tGqvw) of O(1) is sufficant. a big-O of O(1) means an algorithm will always execute in the same time (or space) regardless of the size of the input data set.
the only functionality that must be consistant for a stack is adheareance to the **last in, first out.** rule. As stated above this means that anytime an object is inserted, it is inserted at the back of the stack, and anytime an object is removed, it is from the back of the stack.
[more information on big-O can be found here](https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation/)

//must come back to and give a better explinations of this!!!
one thing to remember is that a stack is not indivudal to anyone language and is what is refeared to as a [abstract data type](https://en.wikipedia.org/wiki/Abstract_data_type)

**When would you use a stack**


Here's text about introducing something and how it works.

Build on the first information. Have students guess things, do an activity, etc.

Make sure to mention these things:
- Things
  - This is a sub-thing
- More things
- Even more things
- Even more things


### Common Mistakes / Misconceptions

This is something that students might not realize or might assume at first.

Make sure they avoid this: thing


### Guided Practice

Have the students work with you as you do something.


### Independent Practice

Class does this thing themselves with specific additional items.


### Challenge

Students can try to do this other thing.


### Check for Understanding

Have students summarize to each other, make a cheat sheet, take a quiz, do an assignment, or something else that helps assess their understanding.
