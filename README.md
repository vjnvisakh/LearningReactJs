# LearningReactJs
Learning React and Redux

ReactJs is a <b>Javascript library</b> that is concerned with making user interfaces.
React makes it easy to make <b>Components</b> which are nothing but reusable html blocks.

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
