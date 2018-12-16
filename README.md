# Glossary

Descriptions of various programming concepts

## Algorithm

A set of instructions that a computer system may go through to solve a problem. Such an algorithm needs to have a well-defined set of inputs and outputs. 

## Debugging

### The Debugging Process

Over the lifetime of a software application various errors may be discovered during production and development; the process of identifying, locating and subsequently dealing with these errors (commonly referred to as bugs) is knows as debugging.

### Debugging Tools and Techniques

Debugging can be quite a tedious task as errors can be quite obscure and difficult to resolve, especially if the problem lies within a system that the software developer has little to no control over. Here are some tools that may be present in an IDE in order to aid with the discovery, isolation and removal of an error:

- Breakpoints: these are lines in source code that have been marked as pause points. Most IDEs have a debugger application that can pause execution of an application; during this pause, a software engineer may analyse the current state of the application and check if it is running as expected. 

- Console: this is a command line interface with two purposes: specific output from an application and referencing parts of the application while it is paused. During development and debugging, a developer may choose to add small messages that are sent to the console during particular moments of execution; for example, an application might output the value of a variable if a specific condition has proven to be true. Further more, some IDEs allow a developer to use the console while the application is stopped; this could be used to check the value of a variable, or to execute and analyse the behaviour of a function.

- Stepping through code: there are a few small tools that can allow a developer to navigate execution:
  - Step into: the application goes through one logical statement, and pause the execution after that statement
  - Step out: the application continues to run code until the current procedure returns, and pause execution after it returned
  - Step over: acts the same as step into, except the application won't pause within a procedure; if a procedure has been reached, execution will stop on the next statement

## Process of Building an Application

When building an application it is advised to use the following steps, in order to create a product that may effectively fulfil the requirements of a customer:

### Obtaining Requirements

The first step of creating a software application, it is vital to contact the client and enquire about what the app is expected to do. After analysing the client's requests, a developer would establish a set of requirements that this software would fulfil; the client's requests alone may be too ambiguous to serve as a set of requirements.

### Design

This step as serves as the planning phase of a project. By this point, a developer has an idea of what they want to achieve; next they need to establish the behaviour of the software and how it interacts with the user.

### Implementation

A developer would use the design documentation produced in the previous step in order to implement a software application. 

### Testing

During this step, a developer may test the functionality of the software application that they are working on. If the developer chose an iterative software development lifecycle model, they may repeat the design, implementation and testing stages of the process until an adequate software application has been created. It should also be noted that some testing will be done during implementation in order to ensure that the software application that is being developed can be tested for issues that may not have been discovered during the design stage or the implementation stage.

### Deployment

At this point, a developer should be able to provide their client with a product that fits the client's expectations.

### Maintenance

Optionally, a developer may choose to support a finished software application for some period of time. This support could be in the form of updates for the application, that should reinforce the software's security and improve its functionality. 

## Programming Paradigms

### Procedural Programming

Procedural programming is a programming paradigm based on the concept of calling procedures (also known as functions or subroutines). Software that follows the procedural programming paradigm is practically a set of procedures operating on some data (such as hard-coded data, user input, file contents, etc.) 

### Object Orientated Programming

In object oriented programming, software applications are composed of objects. Every object is an instance of a class, which contains variables (called properties) and procedures (called methods). Most software in production would include methods specifically for reading from and editing properties. 

### Event Driven Programming

Software applications that use event driven programming rely on events that occur whenever the software is running. The code for such an application assigns some procedures as event listeners/handlers: when the application receives an event, the appropriate procedure would run.

### Comparisons Between Paradigms

Procedural programming languages make use of variables and functions, in order to allow a developer to effectively create a software application. As such, the procedural programming paradigm may be considered to be a precursor to the object orientated programming paradigm, as the latter builds upon procedural programming paradigms by adding concepts related to data encapsulation.

Further more, event driven programming languages build upon procedural programming paradigms by adding the concept of events and how they are handled. 
