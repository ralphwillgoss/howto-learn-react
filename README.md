# learning-react

## Intro
Here are the resources I used in learning React.js  
This is by no means a comprehensive guide and assumes the reader has prior programming knowledge.  
All resources are free at the time of writing.

## Where to start
### The Basics
https://facebook.github.io/react/docs/tutorial.html  
https://egghead.io/courses/react-fundamentals  
https://reactjs.co/#basic-preface  

### Setup your development environment
I went through [js-stack-from-scratch](https://github.com/verekia/js-stack-from-scratch)* to get myself familiar with setting up Node.js, NPM, Yarn, Gulp, Babel and ESLint.  
This tutorial covers many other aspects such as TDD, Redux, however if you do just chapters 1 - 8 it should be a great start.

## Where to next?
Once you have gone through the above tutorials I would assume a good litmus test would be knowledge of the following:
* What is Jsx
* Props vs State
* propTypes
* Components
  * [Lifecycle](https://facebook.github.io/react/docs/react-component.html)

Starter kits provide a great starting point. [Andrew Farmer](http://andrewhfarmer.com) provides a great reference to help narrow down a starter kit for your needs. It can be found at http://andrewhfarmer.com/starter-project  



*The JS Stack from scratch tutorial was developed on Linux, I did it on an Azure Windows 7 VM.  
You may notice that in Chapter 11, fsevent starts to throw some errors due to a package dependency not being available on Windows.  
You can surpress this error by doing the following when adding:  
`yarn add --dev mocha chai --ignore-optional`
