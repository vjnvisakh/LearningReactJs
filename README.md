# LearningReactJs
Learning React and Redux

ReactJs is a <b>Javascript library</b> that is concerned with making user interfaces.
React makes it easy to make <b>Components</b> which are nothing but reusable html blocks.

<h2>History of React</h2>

React was developed by Jordan Walke, a software Engineer at Facebook. He was inspired by XHP, which is an HTML component framework for PHP.

<h2>Virtual DOM</h2>

The browser follows something called a Document Object Model(DOM) to update the elements or to form an HTML page.
Whenever the HTML reaches the client side from the server side, the browser uses this model to form the tree like structure which you are able to see when you open the developer console and go to elements. 

Anytime you make a change to an element, maybe you are removing something or adding a new list item, there are browser APIs which do all the work for you. We use JQuery to update our DOM easily and hence we never have got into those complexities. 

However React says, that there is a much better way to do it.

React has something called <b>states</b> which are responsible to update every component that you make.

And it does all this in a very efficient way. How you ask?

The virtual DOM is a in-memory DOM which the browser uses to update the componet. It is just a copy of the DOM and not the actual DOM.
Everytime an update is made to a component, React compares the old Virtual DOM with new Virtual DOM and identifies the minimum changes to be made to the actual DOM and does it. 

Thus it's one step ahead in making changes and is quite fast too.


<h2>JSX</h2>

JSX is a markup introduced by React which combines the best of HTML and JS together. By using JSX you can write HTML inside JS and you can easily operate JS using {} expressions. However since JSX is not valid JavaScript it has to be converted into JS using a transpiler - <b>Babel</b>.


<h2>Installing React</h2>

React is available as a node module via the <b>create-react-app</b> package that the React team has made available to us.

Follow these steps to set up React on your system.

<ul>
    <li>1. Choose an editor. I'm using Visual Studio Code.</li>
    <li>2. Create an empty directory in one of your drives.</li>
    <li>3. Open VSCode and go to the Terminal (Ctrl + `).</li>
    <li>4. First you will have to initialize npm in the directory. Run <code>npm init</code> command and follow the default instructions.
    <li>5. Then to install React you need another package called <b>create-react-app</b>. Run this command <code>npm install create-react-app --save</code>.</li>
    <li>6. To setup React run the command <code>create-react-app <app_name></code>. This will install react and the basic scaffolding you need for React. You will be able to see a directory structure appear.</li>
    <li>7. Once that is done run <code>npm start</code>. This will start React in your local browser and you will be able to see a text saying <i>You can now view <app_name> in the browser</i>. Hurray! we are done.</li>
</ul>



<b>Open App.js</b>

<b style='color:red'>Delete Everything in it.</b>

Then start writing this.

<code>import React, { Component } from 'react';</code>

<b>React</b> is module(ES6 part), which is what makes render() and other functions recognizable.
<b>Component</b> is a module which allows to extend or which allows to create a new component in React.

<code>
class App extends Component
{
    render()
    {
        return (

        );
    }
}

export default App;

</code>

This is what a component should be.

1. It should extend Component class.
2. It should have a render method.
3. It should return something. Though this is not mandatory. We will see later on.
4. export default is what makes your component available to globally.

