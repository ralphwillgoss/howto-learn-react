# learning-react

## Intro
Here are the resources I used to learn the basics of `React.js`  
This is by no means a comprehensive guide and assumes the reader has prior programming knowledge.  
All resources are free at the time of writing. 

As a .Net developer new to the JS ecosystem, the number of choices can cause analysis paralysis.  
I thought I would document how I previously skilled up on `React.js`.  
You should be able to complete the content below in one afternoon and evening sitting.  
The sooner you feel you have the basics down, you can start making something of value to yourself.

## Setup your development environment
This is not necessary to learn React.js, but as a precursor to the tutorials I found it very useful.  
All tutorials I've listed below will take you through any necessary installations, as needed.  
I went through [js-stack-from-scratch](https://github.com/verekia/js-stack-from-scratch)* to get myself familiar with setting up `Node.js`, `NPM`, `Yarn`, `Gulp`, `Babel` and `ESLint`.  

## Where to start
I would go through the following tutorials in order.  
https://facebook.github.io/react/docs/tutorial.html  
https://egghead.io/courses/react-fundamentals  
https://reactjs.co/#basic-preface  
https://github.com/facebookincubator/create-react-app

## Where to next?
Once you have gone through the above tutorials I would assume a good litmus test would be knowledge of the following:
* What is Jsx
* Props vs State
* propTypes
* Components
  * [Lifecycle](https://facebook.github.io/react/docs/react-component.html)

### Starter Kits
[Andrew Farmer](http://andrewhfarmer.com) provides a great reference to help narrow down a starter kit for your needs.   
It can be found at http://andrewhfarmer.com/starter-project.  
Now that you have a basic knowledge of the ecosystem, the starter kits and their choice of packages will make more sense and will allow you to quickly get up and running.  


*The JS Stack from scratch tutorial was developed on Linux, I did it on a Windows 7 VM.  
You may notice that in Chapter 11, `fsevent` starts to throw some errors due to a package dependency not being available on Windows. I've submitted a [PR](https://github.com/verekia/js-stack-from-scratch/pull/126) for this, you can surpress this error by doing the following when adding:  
`yarn add --dev mocha chai --ignore-optional`
