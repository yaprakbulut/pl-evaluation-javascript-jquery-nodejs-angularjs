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


