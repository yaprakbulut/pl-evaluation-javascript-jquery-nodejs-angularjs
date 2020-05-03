# Javascript

![image](https://user-images.githubusercontent.com/36481108/80894405-651bb180-8ce3-11ea-9b2e-c40967adcfca.png)


## What is JavaScript?

JavaScript is a scripting language produced by Netscape company in the early 1990s in order to support HTML language and become more dynamic. The abbreviation is JS. It is not server based; user based. Therefore, they do not tire the servers that provide hosting services.

## History 

Developed by Brendan Eich in conjunction with Netscape Navigator 2.0, formerly Mocha, later called LiveScript, and finally its current name, the JavaScript language was initially just a client-side interpreted language. JavaScript is standardized with ECMAScript specifications.

In December 1995, JavaScript, which we can call C language adapted to browsers, was launched. It is used to provide dynamic content on web pages or to communicate with the user.  It has object oriented, imperative and functional programming principles. Despite the similarity of the name, it is not related to 'Java'. One of common mistakes is defining JavaScript as simplified Java. At first, JavaScript that only works on Netscape browsers is now supported by all common web browsers. Microsoft developed JScript, that is a language similar to JavaScript. While Microsoft Internet Explorer supports both languages, non standard JScript plugins do not work on other browsers.

The syntax of JavaScript is derived from the C and Java programming languages, and also its semantics and design are inspired by the Self and Scheme programming languages. JavaScript is also influenced by various languages, as well helping to develop different languages. Among these; Objective-J, JScript .NET, TIScript languages are included.

JavaScript has been an ECMA standard since 1997 which is originally developed by Brendan Eich at first. Nowadays, it is being developed and maintained by the free software community led by the Mozilla Foundation.

## JavaScript and Java are not the same language

Another concept that beginners in JavaScript frequently encounter in the web environment is the problem of using java expression for javascript briefly. Java and JavaScript languages are very different concepts.

Java is an object-oriented programming language that means it can run independently in a machine environment. It is a reliable language, used to prepare applications for Android devices, software for terminals, and server-side web pages. Java applications need to be compiled to run.

On the other hand, JavaScript is a text-based programming language that will be run as part of a web-based application. When it was first developed, it was intended to be a compliment for Java. However, JavaScript continues as one of the three fundamentals in web development. The others are HTML and CSS languages. JavaScript applications need to be interpreted by browsers to run. After writing the  JavaScript codes, you can open and implement them in any browser.

## Why was it invented?

A web page consists of three basic elements: content, presentation and interaction. The content section represents HTML, the presentation section is CSS, and the interaction section is JavaScript. If we have a project consisting solely of content and presentation, we can describe this website as a static  website. If  we use interaction, namely JavaScript, with use these two elements, we can create a dynamic website. Dynamic sites are interactive and visitors can take part in some activities with the commands they give on the web page. For example; user filled out the contact form; but he forgot to write his e-mail address. Then he pressed the "Submit" button. After pressing the button, a warning window popped up and "You forgot to write your e-mail address!" encountered a warning. The technology that enables this warning window to occur is JavaScript.

Although JavaScript was originally designed for client-side use, it has now started server-side use with NodeJS. More dynamic web interfaces or calculations can be made with JavaScript. We can make simple html pages more interactive and animated.

## When/why shall we use it?

JavaScript has managed to become a popular software language in about 25 years. According to a research in 2016, 90% of today's websites use JavaScript.

Simply, JavaScript is a type of object-oriented programming language. It is designed to make web development easy and more attractive. In most cases, JavaScript is used to apply interactive elements that can react on websites. In this way, expects for increase the user experience. Menus, animations, video players, interactive maps and even simple in-browser games can be created easily and quickly with JavaScript. Besides interactive web elements, JavaScript also allows you to program on the following topics:

### Games
If you are interested in online game player and game development, you can try use JavaScript to create web based games. Although there are some limitations on the complexity of web-based games, JavaScript is as useful as any other programming language in making them.

### Mobile Applications
Although most mobile apps are made with operating system-based programming languages like Swift (iOS) or Java (Android), there is nothing prevents you from implementing with JavaScript. Implementation of frameworks such as Phonegap or React Native paved the way for multiple mobile apps to be created for multiple operating systems. In fact, JavaScript seems to be the future mobile application language.

### Web and Server Applications
As mentioned above, the answer to a frequently asked question such as “What is JavaScript” is “creating interactive web elements”. But it doesn't end with that either. The creation of these new libraries and frameworks gave web developers the opportunity to create a lot of back-end programs with JavaScript. These include things like web application or server application. In fact, JavaScript is quickly becoming indispensable for back-end web developers and front-end developers.

## Advantages of JavaScript

*	One of the most important features is that you can do different operations in independent areas at the same time. This has become even more effective, especially with Vue. This means seriously performance savings.
*	JavaScript has an substructure that can do almost any job with its API, Framework and libraries it provides. 
*	It is easier to learn; It has a more understandable and simple structure compared to other software languages.
*	It simplifies the work of the developer when writing code. It avoids writing code from scratch every time.
*	It has been proven to be faster compared to other software languages. 
*	It is easier to find and debug system errors in the Javascript structure.
*	It can be used to make the static and simple structure of HTML more interactive and dynamic.
*	It makes communication with the user more practical and faster.

## Disadvantages of JavaScript

* The code can be used for malicious purposes in some cases, as it is executed on the users' computer. That's why, some people can choose to disable Javascript.
* JavaScript is sometimes interpreted differently by different browsers. Some older browsers do not support new features. This makes it a bit difficult to write cross-browser code.

## How to setup an environment to use it in different platforms?

JavaScript works right out of the box in every web browser. A JavaScript application works on every device.However, a desktop or mobile application only works on the application it targets (Windows, Mac OSX, Linux, iPhone, Android). This allows you to write cross-platform applications really easily.

## What are development tools? 

Significant tools have developed with Javascript.
   - Web development tools has built into the every major web browsers. And also there are include a JavaScript debugger.
   - ESLint and JSLint, that are static program analysis tools, scan JavaScript code for compatibility with a range of standards and directives.
   - Profiles have built into some browsers. Independent profiling libraries such as Benchmark.js and jsbench have also been created.
   - JavaScript codes can be writen many text editors. And mostly these text editors have support for syntax highlighting.

## Example Codes

Javascript codes are written between <script> </script> tags. Script tags can be written in <head> or <body> tags. In large projects, the file with the extension ".js" is created and written in it, without writing the JavaScript codes directly in the <script> </script> tags. When calling the file, it is called <script src = ”file.js”>.

1. In the example below, it counts the characters entered in the text box and shows how many more characters we can type according to the specified number of characters. As you enter the character in the textarea in this example, the information about how much character is left will be displayed on the screen instantly.
```
<!DOCTYPE html>
<html>
<head>
    <title>example</title>
</head>
<body>
  Comment : <br>
  <textarea rows="20" id="myTextareaId"></textarea>
  <div id="resultId"></div>
<script>
      var myTextareaId =document.querySelector('# myTextareaId ');  
      var resultId=document.querySelector('#resultId');  
    
    myTextareaId.oninput=function(){
       var max=60;
       this.value=this.value.substr(0,max);
       var remaining= max-this.value.length;
       resultId.innerHTML=' Remaining Character : '+remaining;
    }
</script>
    
</body>
</html>
```

2. Refresh the page every 3 seconds with the Arrow function:
```
<script>
setInterval(()=>window.location.reload(false),3000);
</script>
```

3. Refresh the page every 3 seconds with anonymous function:
```
<script>
setInterval(function(){
window.location.reload(false);
},5000);
</script>
```

4. In this example, we will display the x and y coordinate information on the screen by taking the position of the mouse that we moved in the web browser. It will be seen that the coordinate information changes as the mouse moves over the scanner.
```
<script>
// codes that will work as the mouse is moved on the window
window.onmousemove=function(event)
{
// all information about the event that is happening is assigned to the event variable. 
var xposition=event.clientX;
var yposition=event.clientY;
 
//clientX: mouse position on the x-axis
//clientY: mouse position on the y-axis
 
console.log("x Coordinate = " + xposition + "       y Coordinate ="  + yposition) 
} 
</script>
```

5. Validation E-mail address with JavaScript
In the example, there will be an input field for e-mail and will be checked whether the e-mail is valid or not when button is pressed. Since javascript is running client-side, e-mail verification will run after clicking the button.
Take a text input in html and a button input like this 
```
<input type='text' id='emailId'/>
<input type='submit' name='submit' onclick='Javascript:isValid();'/>
```
Now when the button is clicked then the JavaScript function SubmitFunction() will be called. Now write the bellow code in this function.
```
script language="javascript">

    function isValid() {

    var email = document.getElementById('emailId');
    var filter = /^([a-zA-Z0-9_\.\-])+\@(([a-zA-Z0-9\-])+\.)+([a-zA-Z0-9]{2,4})+$/;

    if (!filter.test(email.value)) {
    alert('Please provide a valid email address');
    email.focus;
    return false;
    }}
</script>
```

## How do browsers interpret JavaScript?

JavaScript is designed as a scripting language in terms of design. As the host environment, it works mostly within the structure we call browsers. However, JavaScript can run in any environment where is an interpreted language and interpreter.

As developers, we run JavaScript most on the browser. Of course, some interpreters are required for this language to run. Nowadays, applications such as Chrome, Firefox, Safari, Internet Explorer, Opera, which come to mind when it comes to browsers, use tools called Engine to interpret JavaScript.

In fact, the name of the V8 Engine, which is the JavaScript interpreter of Chrome, was designed as V and was inspired by an 8 cylinder engine type. This type of engine is known for its good performance and very fuel burning.

JavaScript engines used by browsers;
* Chrome - V8
* Firefox - SpiderMonkey
* IE - Chakra
* Safari – JavaScriptCore

SpiderMonkey was developed as the first JavaScript engine and was written in C by the inventor of the JavaScript language, Brendan Eich. So it was working in Netscape before Firefox.

## Which Libraries and Framework can be used?

JavaScript is one of the technologies that form the core of web application development.

*	jQuery is a library that aims to provide a cross-browser API that allows for “write less, do more”.
*	Angular is a JavaScript framework that aims to facilitate configuring single-page applications.
*	Backbone aims to provide structure for web applications with the use of models, collections and views.
*	Ember.js is a different library for “building passionate web applications”.
*	React.js is not exactly a framework, but a JavaScript library that makes it easy for developers to create dynamic user interfaces.
*	And more.

## Things that are specific to this language?

JavaScript is an interpreted programming language. In other words, a JavaSript code you write is not compiled before execution, it is interpreted at run time. Today, it is used in mobile application development, web server authoring, desktop application development, and even Arduino programming.

It should be noted that JavaScript has nothing to do with the Java programming language in any way.The  "Java" prefix has been used  to take advantage of the popularity of the Java language at that time. The correct spelling is actually "JavaScript" because of its prefix.

The biggest factor in the development of JavaScript so much is that its writing is as easy as Python language, and its speed is much higher than other peers (Ruby, Python, Php ...).

Today, many applications have started using JavaScript on the mobile side. Native Applications which are of great benefit in developing two different applications, especially for iOS and Android (Generally, most of applications written outside the platform's original language, Java for Android, Objective-C, or Swift for iOS) have become quite common. Many companies such as Instagram and Facebook use React Native on the mobile side.

According to both the Developer Survey conducted by Stack Overflow and the survey by GitHub, JavaScript ranks first among the most used languages.

![image](https://user-images.githubusercontent.com/36481108/80894428-88def780-8ce3-11ea-9f6f-6cc436b113c8.png)
 
One of the problems that arise when you come up with a mobile application or website idea is that you have to use different languages in the web server, mobile application, website and desktop application. At least it used to be. But thanks to JavaScript, you can use a single language in all of them. This will both increase your productivity and reduce confusion.

* NodeJS for Server
* jQuery, React, Vue, Angular for website
* React Native or NativeScript for mobile
* You can learn Electron for desktop applications.

## Conclusion

Although JS is a small language, it is very flexible and the developers have developed a lot of tools on this language. Thanks to these improvements, it is possible to solve many problems in a short time. As the canvas that comes with HTML5 slowly outstrips Adobe Flash, which is used to make more interactive sites, and also the development of Cloud technologies and in these technologies as well, JS has become an indispensable language, programmers started to focus more on JavaScript. Now, almost anything that comes to mind with JS can be done. These include 2D and 3D games and applications that use databases. It is still indispensable that for JS developers to providing indispensable programming freedom , especially the ability to can be made dynamic text and events on web pages, to read the values entered by the user and to ensure that the page reacts accordingly, to use the offline features that come with cookies and HTML5 and many other features.



History of the Jquery.
jQuery is one of the most widely used JavaScript library in the coding world. jQuery is developed by John Resig and he release initial version in 2006. On January 16th, 2006 he gave a talk at the BarCampNYC event about his new library. John was only college student when he created jQuery.  He has an own write on original jQuery’s website:
“jQuery is a Javascript library that takes this motto to heart: Writing Javascript code should be fun. jQuery achieves this goal by taking common, repetitive tasks, stripping out all the unnecessary mark-up, and leaving them short, smart and understandable.”
Finally, jQuery initial version is published on August 26th, 2006. At the end of 2006, jQuery licenced with MIT and GPL. At now, stabil version is released April 10, 2020 and version name is 3.5.0.

Why was jQuery invented
The first purpose is making codes ergonomic. Pure JavaScript long codes are becoming smaller with jQuery. As the slogan for jQuerty “Write less, do more!” jQuery aims make JavaScript codes smaller than before.  For example:
JavaScript
1.	document.getElementsByClassName("className");  
jQuery
2.	$('className') 
When/why shall we use jQuery?
We can handle this topic one by one. And we explain this with examples.
a-	HTML/DOM manipulation. 
This is jQuery’s one of the most important task. Dom elements, as like we show on top and following exampe, can manipulate with jQuery easier.
1.	$("#myElementId").remove();
b-	CSS manipulation.
When used with CSS programs, it works flawlessly and does not allow any problems. Even in CSS, jQuery makes your work easier. Following code makes background colour blue for element whose id is myArea.
1.	$("#myArea").css("background-color" : “blue” , “weight” : “100px”);
c-	 Animations and Effects.
It enables animations developed in HTML to progress more easily. In the following example When the button is clicked, the element whose id is "myDiv" is shifted 250px to the right.
1.	$(document).ready(function(){
2.	  $("#myButton").click(function(){
3.	    $("#myDiv").animate({right: '250px'});
4.	  });
5.	});

d-	 Creating and Manipulating Event
In jQuery, there is an equivalent jQuery method for many DOM events. For example, it can be used to assign a click event to all “a” tags on a page.
1.	$("a").click(function(){
2.	  //there will be action for the click event for “a” tags.
3.	});
e-	  Ajax Operations
jQuery supports AJAX and offers solutions for vulnerabilities.
1.	$.ajax({url: '/api.json',
2.	type: 'GET'
3.	success: (data) => {
4.	console.log(data)
5.	}
6.	})
How to Setup an Environment to Use jQuery in Different Platforms?
jquery runs in browsers just like javascript. So, if you loading website has jQuery in your browser everything goes automatically but, developer must initialize jQuery into website. There is a very simple way like implementing other libraries. That way contains Google CDN or Microsoft CDN and it works quite fast: 
1.	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script> 
 Or you can download in webserver and run jQuery files from device.
1.	<script src="jquery-3.4.1.min.js"></script>
 

Things That Are Specific to jQuery?
We can talk about few important things for this topic. Learning to use the jquery library is very easy. People with little knowledge of HTML, CSS and JavaScript will immediately grasp the use of Jquery. People who do not have any knowledge about JavaScript can also easily grasp Jquery.
One of the largest sites in the world, applications such as Google, Facebook and Microsoft IBM all prefer the Jquery library during software development.
As it is constantly developing, it becomes a faster and more comprehensive library with new versions.
And finally, as shown on examples and When/Why topic reasons, jQuery does runs and make their job.


				NODE.JS
History of The Node.js
Node.js has developed by Ryan Dahl and others from Joyent in 2009 with Joyent company supports. First release was supporting from only Linux and MacOS. All creating and development managed by Ryan Dahl and then sponsored by Joyent.
Node.js Package Manager (NPM) is presented in January 2010. NPM made easyer installing and uploading libraries, packages and frameworks. 
After two years from first version of Node.js in June 2011, Joyent and Microsoft created Node.js version for Microsoft. 
By June 2015, communities of Node.js and io.js started work together under Node.js Foundation.
Node.js Foundation education community manager Tracy Hinds says:
The Node.js Foundation, with help from incredible community members and core experts, is creating a comprehensive certification program that broadens the funnel of skilled Node.js expertise available. Whether working in enterprise environments or as individual consultants, those who become Node.js Certified Developers will be well-positioned to hit the ground running as a Node.js developer, possessing skills that are in high demand,”
Also , to access Ryan Dahl’s in 2009 original Node.js presentation use following link:
https://www.youtube.com/watch?v=ztspvPYybIY




Why Was Node.js Invented

It was developed to run JavaScript on the server side by making various additions to the V8 JavaScript engine that the Google Chrome browser uses to run JavaScript commands. V8 engine is an intermediate software used to translate JavaScript commands developed with C / C ++ into machine language. Converting commands to machine code makes JavaScript commands run faster and more efficiently.

When/why Shall we use Node.js
The reason for using Node.js is that it is fast and performance, as well as the flexibility of JavaScript commands, the processing of commands without blocking and event-based operation, as well as the need for an additional web server (Apache HTTP, IIS, Nginx etc.) like other server-side programming languages.
Applications written in other server-side programming languages (PHP, ASP.NET etc.) need additional software that establishes the connection between the client and the server called web server (Apache HTTP, IIS, Nginx etc.).
Requests to the web server are then forwarded to the server-side programming languages and the desired commands are executed.
Thanks to the kernel modules that come in Node.js, it enables commands to be run without the need for an additional web server.
Thanks to the Node.js modular structure and the NPM package manager, it allows you to easily add modules prepared by other developers to your project and develop faster applications.
For example; You can easily develop applications that use database systems such as MySQL, SQLite, MongoDB, PostgreSQL by including the modules created to connect to the database in your project.

How to Setup an Environment to Use Node.js in different Platforms

To quickly mention the node.js installation process;
To download the installation package, log in to the Node.js Downloads page, download and install the installation file for your operating system (this will be the Windows Installer button for Windows).
After installation, login to the console screen and enter node -v command to run it. If you see the version number on the screen, it means that node.js setup is complete.
When you install Node.js, the npm application will be installed with it. You can check if it is installed on your computer via the npm -v command and see the currently installed version of npm. When we run this line, it will output a version as in node.js.

			Example Codes With Node.js
Module Example
Calc.js
1.	// Plus x and y and return result
2.	exports.plus = function (x, y) {
3.	    return x+y;
4.	}; 
5.	 
6.	// minus y from x and return result
7.	exports.minus = function (x, y) {
8.	    return x-y;
9.	}; 
10.	 
11.	// divide x with y and return result
12.	exports.div = function (x, y) {
13.	    return x/y;
14.	}; 
15.	
16.	// product x and y and return result
17.	exports.mult = function (x, y) {
18.	    return x*y;
19.	}; 
 
getModule.js
1.	var calc = require('./calc);
2.	var x=15, y=3;
3.	console.log("Plus ; "+ calc.plus(x,y));
4.	console.log("Minus ; "+ calc.minus(x,y));
5.	console.log("Divide ; "+ calc.div(x,y));
6.	console.log("Product ; "+ calc.mult(x,y));
HTTP Server Example
The codes below manage the localhost 8090 port and write "Hello World!"  top of the page.
1.	 var http = require('http');
2.	 
3.	http.createServer(function (req, res) {
4.	    res.writeHead(200, {'Content-Type': 'text/plain'});
5.	    res.end('Hello World!');
6.	}).listen(8090);
 		

Things That Are Specific to Node.js?

When any user requests to other server-side programming languages, the server only responds to that request and other requests are queued.
It takes a long time for a request to affect other users, but since Node.js handles commands without blocking it, the long-running command does not slow down the system, and Node.js responds to other users.
Node.js different from conventional languages and based on asynchrony.
The best example of asynchronous is the food ordering system.
When the traditional server-sided programming languages arrive when a food order arrives, other customers who wait in line wait for the order to be prepared.
Node.js, on the other hand, reports the order to the back and takes notes when any food order arrives and then takes the order of the next customer.
Which of the given food orders is prepared before, it responds to the food order.
Thus, the customer does not wait extra for a meal to be prepared quickly before.
Thanks to this structure, real-time applications such as instant messaging and gaming systems are made easily and at less cost.

			ANGULAR.JS
History of the Angular.js
Basically, AngularJS is a MVVM (Model-VIEW-VIEWMODEL) and MVC (Model-View-Controller) based JavaScript framework running on the client side. In 2009, Misko Hevery and his friend Adam Abrons (they are developers in Google) starts developing Angular.js personally. In 2010, Angular was published for the first time under the name AngularJS on the internet address https://angularjs.org. With this success Google supported Angular.js.
 
Angular, which is much loved by the developers, comes with a radical change in 2016, and the development language changes from JavaScript to TypeScript, and support and development for the old version AngularJS is stopped. Even after this radical change, the website https://angularjs.org is replaced with https://angular.io/. Angular is now made workable on popular internet browsers and cross-platforms. However, Angular still supports JavaScript.
The first announcement came in January 2018, later reiterated at NG Conf in Salt Lake City, that the final release of AngularJS would be 1.7 and would enter Long Term Support (LTS) through June 30, 2021. After that time, Google won't longer maintain the library.



Why Was Angular Invented
Angular.js’s first mission was supporting Google’s one page application and making efficient results on this. In Angular’s official web site (https://angular.io/docs) they write for Angular:
“Angular is an application design framework and development platform for creating efficient and sophisticated single-page apps.”


When/why shall we use Angular.js
Some features I will explain below may also be in other libraries. But it's all in Angular. We will focus more on architectural aspects.
a. Opinionated Approach
b. Explicitness
c. Isolation
d. Modularity
e. Extending HTML
f. Dependency Injection







a. Opinionated Approach
Angular is a framework has opinionated approach. So, what is opinionated approach? An opinionated system tells you how to design it. Instead of defining what is what and where as a .json, an .xml, or any file, you follow the architectural tradition expected of you. 
In this way, Angular, with its approach, provides orientation to the architecture overlooking the domain without getting tired.

b. Explicitness

Angular expects you to clearly define what is what and by whom. This means you will be faced with less surprises. This openness will be very useful when reading code or writing your own static code analysis tools in the future.

c. Isolation
Being able to isolate the structures that make up the system easily and quickly is one of the strongest aspects of Angular. Everything from CSS files to JS codes can be isolated from other parts. Unlike JS modules, it also provides another isolation between its structures with its own "NgModules".

d. Modularity
Angular made proper isolation design with NgModule structures. Everything is controlled. Everything happens in NgModule, from what you export to the outside and from what you import. It defines the modules you want and you can work there safely without fear of breaking other modules.

e. Extending HTML

It is possible to extend your HTML files in Angular. The structures you use to achieve this are called Directives. So instead of writing the things to be done one by one, you just define them, like saying “<br/>”: This means adding a line. Look, you didn't say how the line should be added. You just said what should be added. Currently, Angular comes with some very useful directives. Perhaps you will not even have to define your own guidelines most of the time.

f. Dependency Injection
Dependency Injection is mainly used for the control and management of dependencies. Basically, that tells you that if you are going to use the object of another class in a class you will create, you should not create it with the keyword "new". It emphasizes that the required object should be taken as a parameter either from the Constructor or by the Setter method. Thus, he argues that we have isolated the two classes from each other. Dependency Injection liberates your code and minimizes the bond between classes.

How to Setup an Environment to Use Angular.js in different Platforms
All popular web browsers are can use for to view Angular based web site.
If you want to be Angular developer need to follow following steps. Those steps are from Angular’s official website. 
1-	Use npm to install Angular’s commend line interface (CLI)
npm install -g @angular/cli
2-	Run the following code to create a workspace and initial application.
ng new my-app
3-	Finally go to initialized folder and lunch server using following CLI command 
cd my-app
 ng serve –open
 


Example codes

 EX-1
When web page load, Angular.js starts automatically.
“np-app” directive shows Angular.js element belongs to <div> element.
“bg-model” directive binds the value of the input field to the application variable name.
“ng-bind” directive binds the contents of <p> to the name of the application variable.

 

EX-2
“ng-init” instruction initializes AngularJS variables.
  
Things That Are Specific to Node.js?

AngularJs is one of the first effective example of one-page web application. With this it is became very popular and took Google’s support.
Besides being easy to learn and applicable, AngularJS, which is behind a giant like Google with many advantages, is becoming more and more common day by day. It's a technology that Javascript software developers and client-side developers should focus on.


