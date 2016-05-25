#Introduction to React.js

React is a JavaScript library for creating user interfaces ny Facebook and Instagram. It's usefulness is usually in solving the one problem building large applications with data that changes over time. Simply express how your application should look and React.js will automatically update UI changes based on your data changing.

React.js is conceptually about resuable components. The only thing you really need to do is build the components and React will handle the rest.

##Working with the DOM

React.js provides abstractions that keeps you away from manipulating the acutal DOM in most cases, unless you need to access the underlying API to work with a 3rd part library for example. It achieves this because it never talks to the DOM directly. React.js maintains a fast in memory copy of the DOM. Rendering methods acutally return a description of the DOM, and React.js can compare this description with the in-memory representation to compute the fastest way to update the browser.

##DOM and Component Lifecycle
	Components have three main parts to their lifecycle:
		*Mounting: component is being inserted into the DOM.
		*Updating: component is being re-rendered to determine if the DOM should be updated.
		*Unmounting: A component is being removed from the DOM.
React.js provides lifecycle methods that you can specify to hook into this process.

#How Extensive is React.js? 
	Let's look into tools able to be integrated such as:
		
		*Language Tools
		*Package Management
		*Server-side Environments
