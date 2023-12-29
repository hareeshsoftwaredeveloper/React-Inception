# What is emmet

It provides auto completion for HTML, CSS code by reducing the need of extra typing.

# Differnece between Framework and Library

Both Framework and Library provide precoded support program to develop software applications.However, library targets a specific functionality , while a framework tries to provide everything required to develop a complex application.

# What is CDN? What is its use?

CDN stands for Content Delivery Network or Content Distrubution Network.
It allows for the quick transfer of assets needed for loading internet content including HTML pages, JavaScript files, stylesheets, images and video.
1.Imporve website loading time.
2.Reduce band width costs.
3.Increase Content availability.
4.Improve website security.

# What is crossorigin in script tag?

It is used inside the script tag in HTML to control how the browser handles requests for the scripts that are loaded from a different domain.

If you are loading a script from the same domain as your web page then we dont need crossorigin.But if you are loading a script from the different domain then we need to have crossorigin in our script tag.

crossorigin="annonymous" : This is the default value. It means the script should be fetched without sending any creditionals(like cookies) to the server. This is suitable for public servers that dont require any authentication.

# Why is React known as React

Because it is meant to help developers UI that are super fast and responsive or react.

# What is the difference between React and ReactDOM

React is the main library for building React Components and managing their behaviour, while ReactDOM is a specific package that handles rendering of react components into the DOM.When we build a react application,you typically use both React and ReactDOM to define your component and render them into the browser.

# What is the difference between react.development.js and react.prodiction.js via CDN

In Production mode , compression and minification of javaScript and other resources happen to reduce the size of the code which is not in the case of development mode. Performance will be much faster in production mode when compared to development mode.

# Difference between async and defer?

Both async and defer allow scripts to be dowloaded without blocking the HTML parsing process.
The main difference is the timing of script execution.
With async the script is executed as soon as its dowloaded, regardless of HTML parsing.
With defer the script is executed in order after HTML parsing.
