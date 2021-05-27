# Group_Project_for_Software_Engineering
Web(MERN stack) and Mobile(Flutter ) E commerce Site                                                        
Group Members: Fahmeda Gulzar (153014016)
               Shamia Ferdousy(171014038)
               Fatima- Tuz- Zohora Mithila(172014028)
               Md. Solaiman Sunny (153014008)
               Asif Iqbal (172014009)
               Rahul Roy (172014022)
               Md. Talha Jubayer (172014035)
               Rupom Biswas (172014043)
  
  Project Requirments: Software Requirements Specification
                            Scenario-Based Modeling
                            Data-Based Modeling
                            Class-Based Modeling
                            Object Oriented Analysis and Design
                      Software Test Plans
                            Black-Box Testing
                            White-Box Testing (if needed)
                      Presentable Demo of Software
                            Showcase the first iteration of your software (incremental/evolutionary)
                            
MERNSTACK INTRODUCTION: https://www.mongodb.com/mern-stack 
What is the MERN Stack?
MERN stands for MongoDB, Express, React, Node, after the four key technologies that make up the stack.

MongoDB - document database
Express(.js) - Node.js web framework
React(.js) - a client-side JavaScript framework
Node(.js) - the premier JavaScript web server


MERN is one of several variations of the MEAN stack (MongoDB Express Angular Node), where the traditional Angular.js frontend framework is replaced with React.js. Other variants include MEVN (MongoDB, Express, Vue, Node), and really any frontend JavaScript framework can work.

Express and Node make up the middle (application) tier. Express.js is a server-side web framework, and Node.js the popular and powerful JavaScript server platform. Regardless of which variant you choose, ME(RVA)N is the ideal approach to working with JavaScript and JSON, all the way through.



How does the MERN stack work?
The MERN architecture allows you to easily construct a 3-tier architecture (frontend, backend, database) entirely using JavaScript and JSON.

Mern Stack

React.js Front End
The top tier of the MERN stack is React.js, the declarative JavaScript framework for creating dynamic client-side applications in HTML. React lets you build up complex interfaces through simple Components, connect them to data on your backend server, and render them as HTML.

React’s strong suit is handling stateful, data-driven interfaces with minimal code and minimal pain, and it has all the bells and whistles you’d expect from a modern web framework: great support for forms, error handling, events, lists, and more.

Express.js and Node.js Server Tier
The next level down is the Express.js server-side framework, running inside a Node.js server. Express.js bills itself as a “fast, unopinionated, minimalist web framework for Node.js,” and that is indeed exactly what it is. Express.js has powerful models for URL routing (matching an incoming URL with a server function), and handling HTTP requests and responses.

By making XML HTTP Requests (XHRs) or GETs or POSTs from your React.js front-end, you can connect to Express.js functions that power your application. Those functions in turn use MongoDB’s Node.js drivers, either via callbacks for using Promises, to access and update data in your MongoDB database.

MongoDB Database Tier
If your application stores any data (user profiles, content, comments, uploads, events, etc.), then you’re going to want a database that’s just as easy to work with as React, Express, and Node.

That’s where MongoDB comes in: JSON documents created in your React.js front end can be sent to the Express.js server, where they can be processed and (assuming they’re valid) stored directly in MongoDB for later retrieval. Again, if you’re building in the cloud, you’ll want to look at Atlas. If you’re looking to set up your own MERN stack, read on!



Is MERN a full-stack solution?
Yes, MERN is a full-stack, following the traditional 3-tier architectural pattern, including the front-end display tier (React.js), application tier (Express.js and Node.js), and database tier (MongoDB).



Why choose the MERN stack?
Let’s start with MongoDB, the document database at the root of the MERN stack. MongoDB was designed to store JSON data natively (it technically uses a binary version of JSON called BSON), and everything from its command line interface to its query language (MQL, or MongoDB Query Language) is built on JSON and JavaScript.

MongoDB works extremely well with Node.js, and makes storing, manipulating, and representing JSON data at every tier of your application incredibly easy. For cloud-native applications, MongoDB Atlas makes it even easier, by giving you an auto-scaling MongoDB cluster on the cloud provider of your choice, as easy as a few button clicks.

Express.js (running on Node.js) and React.js make the JavaScript/JSON application MERN full stack, well, full. Express.js is a server-side application framework that wraps HTTP requests and responses, and makes it easy to map URLs to server-side functions. React.js is a frontend JavaScript framework for building interactive user interfaces in HTML, and communicating with a remote server.

The combination means that JSON data flows naturally from front to back, making it fast to build on and reasonably simple to debug. Plus, you only have to know one programming language, and the JSON document structure, to understand the whole system!

MERN is the stack of choice for today’s web developers looking to move quickly, particularly for those with React.js experience.



MERN Use Cases
Like any web stack, you can build whatever you want in MERN - though it’s ideally suited for cases that are JSON-heavy, cloud-native, and that have dynamic web interfaces.

A few examples might be: - Workflow management - News aggregation - Todo apps and Calendars - Interactive forums / social products

And whatever else you can dream up!

FLUTTER INTRODUCTION: https://www.freecodecamp.org/news/what-is-flutter-and-why-you-should-learn-it-in-2020/
                      https://flutter.dev/docs
What is Flutter?
Flutter is a free and open-source mobile UI framework created by Google and released in May 2017. In a few words, it allows you to create a native mobile application with only one codebase. This means that you can use one programming language and one codebase to create two different apps (for iOS and Android).

Flutter consists of two important parts:

An SDK (Software Development Kit): A collection of tools that are going to help you develop your applications. This includes tools to compile your code into native machine code (code for iOS and Android).
A Framework (UI Library based on widgets): A collection of reusable UI elements (buttons, text inputs, sliders, and so on) that you can personalize for your own needs.
To develop with Flutter, you will use a programming language called Dart. The language was created by Google in October 2011, but it has improved a lot over these past years.

Dart focuses on front-end development, and you can use it to create mobile and web applications.

If you know a bit of programming, Dart is a typed object programming language. You can compare Dart's syntax to JavaScript.

“Flutter is Google’s UI toolkit for building beautiful, natively compiled applications for mobile, web, and desktop from a single codebase.” - Google, flutter.dev
Why you should learn Flutter?
I selected some of the reasons why I like Flutter and why I want to use it next year. I will give you details and my feedback below.

Simple to learn and use
Flutter is a modern framework, and you can feel it! It’s way simpler to create mobile applications with it. If you have used Java, Swift, or React Native, you'll notice how Flutter is different.

I personally never liked mobile application development before I started using Flutter.

What I love about Flutter is that you can create a real native application without a bunch of code.

Quick compilation: maximum productivity
Thanks to Flutter, you can change your code and see the results in real-time. It’s called Hot-Reload. It only takes a short amount of time after you save to update the application itself.

Significant modifications force you to reload the app. But if you do work like design, for example, and change the size of an element, it’s in real-time!

Ideal for startup MVPs
If you want to show your product to investors as soon as possible, Flutter is a good choice.

Here are my top 4 reasons to use it for your MVP:

It’s cheaper to develop a mobile application with Flutter because you don’t need to create and maintain two mobile apps (one for iOS and one for Android).
One developer is all you need to create your MVP.
It’s performant – you won't notice the difference between a native application and a Flutter app.
It’s beautiful – you can easily use widgets provided by Flutter and personalize it to create a valuable UI for your customers (you can find examples of applications made with Flutter below).
Good documentation
It’s important for new technology to have good documentation. But it’s not always the case that it has it!

You can learn a lot from Flutter's documentation, and everything is very detailed with easy examples for basic use cases. Each time I’ve had a problem with one of my widgets in my code, I have been able to check the documentation and the answer was there.
