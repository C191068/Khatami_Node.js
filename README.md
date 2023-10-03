# Khatami_Node.js

### Introduction

Node js is an environment to run java script outside of the browser .<br>

Node.js was created in 2009 and built on chrome v8 javascript emgine <br>

Every browser has an engine a toll that compiles our code <br>

down to machine code and chrome uses one by the name of v8 <br>

In extremely simple terms the creator of node Ryan dahl <br>
 ripped the v8 engine and build node on top of it <br>

 Since the moment it was created the node has evoved tremendously <br>

 and where there are many things to like about node <br>

 I particularly enjoy large community around node sinec that tremendously save3s time <br>

 on feature development as well as the fact withe help of node it is never been easier <br>

 to build full stack apps since both front end and bacxk end are essentially built  <br>

 in the same language and that language is our beloved javascript <br>

![image](https://github.com/C191068/Khatami_Node.js/assets/89090776/109abdd4-62bc-422a-8908-f4ad77da3b6c)

 
while working with node js we have no access to browser apis , since well they don't simply <br>
\
exits in node , there is no browser , there is no DOM ( Document Object Model)  <br>

Document Object Model is a representation of the elements and data within a web document.<br>
It encompasses the structure and content of the document on the web. The Document Object Model (DOM) serves as a programming interface designed for web documents <br>
 
there is no geo location, no fetch and all the other cool browser goodies   <br>

Unlike browser apps that are interactive for example user clicks the button <br>

or toggles the nav and that sort of things with node we built server side app <br>

our node app wil only consit of pure logic without graphical interface <br>
 In browsser app we use a bunch of cool things available on the window object  <br>
but it si not avilabe at node <br>

Unlike browser we can access file system <br>

Info about our operating sytem respond to network quest just to name a few <br>

Another major fact about node it is based on version <br>

unlike browser app which depend on user browser <br>

our node app depends only on node js version it was built in  <br>

if we built a browser app and if our user's browser does not support it <br>

it is our responsibility to fix it otherwise our app might have bugs  <br>

but when we build our node app there is no rule that we have to upgrade <br>

to a newer node js version and possibly break our app  <br>

we can simply running our node app in the version it was built in and without any worries  <br>

Unlike browsers where module are optional in node js we have access to module by default <br>

and it is hard to imagine a node app without them <br>

Node js uses common js library for the module 

the general idea is exactly the same as ES6 module <br>

that we use browser syntax is a bit different <br>

![image](https://github.com/C191068/Khatami_Node.js/assets/89090776/0ee4033d-55de-4abf-ad95-e09564c5a470)

there are two option to download one is 18LTS another is 20 current <br>

For production app LTS is suggested which stands for Long term support <br>


How do we get node ? <br>

For that we have two options <br>

1. REPL = Read Eval Print Loop <br>

2.CLI executable = which means running our app code in node <br>

If i have to be perfectly honest REPL is for playing around <br>

CLI is for everything else <br>

![n1](https://github.com/C191068/Khatami_Node.js/assets/89090776/a3d393ad-e734-4cd4-8d09-57474fdd1df4)

for REPL we do the above <br>

in the above the angle bracket means that we are in the REPL <br>

![n2](https://github.com/C191068/Khatami_Node.js/assets/89090776/32a87137-9e12-42c8-9029-bdff4ce623dd)

the first REPL things we have done is that we input our name and output it <br>

so we can see we not  gonna write anything serious in here <br>

when it comes with serous application we need CLI executable 

![n3](https://github.com/C191068/Khatami_Node.js/assets/89090776/77c830a2-cc86-49c9-86dd-b2f9941be5ee)

to exit the REPL we typed the above <br>

Now how do we get node to evaluate our code <br>

![n4](https://github.com/C191068/Khatami_Node.js/assets/89090776/f02cbe4a-8691-4d72-a25f-7c43b8e2452e)

for that we have created the above file and folder <br>

![n5](https://github.com/C191068/Khatami_Node.js/assets/89090776/7361f0e0-35d4-4d6b-84df-010e632270d1)

for output we will do the above <br>

![n6](https://github.com/C191068/Khatami_Node.js/assets/89090776/8248f7c5-e269-4794-86e3-c6eb876e2df5)

change the number and again output <br>


source: https://johnsmilga.com/ <br>


![n7](https://github.com/C191068/Khatami_Node.js/assets/89090776/fc4c4f45-da6a-4e65-bf24-c33e7b0ca617)

to keep in memory we ill create file in the above way <br>


working with vanilla js application one has acces to window object <br>


In the window object we can get a bunch of useful things <br>

for example we can get a query selector so we can select a node <br>
and can get built in fetch <br>

but in node js there is no window because there is no browser <br>


If we try to access window , node will split backthe error <br>

and mostl likly our app will crash <br>

there is a concept of global variables <br>

global variables maeans anywhre in our application we can access them <br>

no matter how complex my application gets or whatever i wil have acces to those variables <br>


```

console.log(__dirname);

```


when we give the above code we get the following output to get the current directory <br>


![n8](https://github.com/C191068/Khatami_Node.js/assets/89090776/d0990c21-8b3f-4e65-ad19-309079b50980)



```
setInterval(() => {
  console.log("My name is Khatami");
});

```



when we type the above code we will get the following output about getting at every second continuosly <br>

![n9](https://github.com/C191068/Khatami_Node.js/assets/89090776/0f09d719-5a04-4536-aeda-de1a48bdff89)

























 



 


