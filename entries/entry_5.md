# Entry 5
# Just A Little More On JSX

This week consisted of more codecademy learning. Specifically, I learned more on JSX expressions and ways that they are actually similar and different from HTML. It was kind of annoying seeing the many similarities between them as I felt that React wasn't going to be any different from what I already know. I felt like I was relearning past code rather than new ones. However, I learned to look past this as I began to see that it was useful seeing the similarities. Similarities kept me from ending up in the panic zone for React.

#### Things I've Learned:

- In order for code to be read as Javascript instead of JSX inside of JSX expressions, add curly brackets around that code. 

    - ```<h1>2 + 3</h1>``` vs ```<h1>{2 + 3}</h1>```

        - In this example, rather than printing out "2 + 3", it will actually do the math and print out "5".
- ```var React = require('react')``` saves a JavaScript object into your file. It has methods that are needed to make React itself work, Some examples methods being: ```React.createElement``` and ```React.createClass```.
- ```var ReactDOM = require('react-dom')``` also saves other JavaScript objects into your file. It revolves around mainly DOM interaction. The mainly used one being ```ReactDOM.render```.
- As previously shown, ```React.createClass``` returns a new component class. A component class isthe class that actually produces components, thus it is not just a component. The important thing about this line of code is that every component must come from a component class.
    - Calling ```React.createClass``` saves the returned component class in a variable. As a reminder to me, this variable is written in UpperCamelCase.
- ```React.createClass``` takes one argument. That argument has to be a JavaScript object. This object explains to the component classthe steps required in order to build a React component.
#### Just a Little Helpful Code: This prints out "Hello World"
```
var React = require('react');
var ReactDOM = require('react-dom');

var MyComponentClass = React.createClass({
  render: function () {
    return <h1>Hello world</h1>;
  }
});
```
```
ReactDOM.render(
	<MyComponentClass />, 
	document.getElementById('app')
);
```
### Takeaways

Don't rely on one tutorial. Codecademy was helpful in learning to code simple components but sometimes it helped to look at React's Facebook tutorial as there were many helpful tips and notes that allowed me to understand React classes easier.

The least you could do it print "Hello World". If what you're learning allows it, print "Hello World". It'll truly show that you understand the basics and can print something out.