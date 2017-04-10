# Entry 2
## Transitioning to a New Topic
##### Well, in the course of the week I have learned that it was becoming difficult for me to find tutorials for D3.js that I actually understood. I thought that if I had persevered and continued to just read article after article of D3.js then I would slowly begin understanding but no matter how many articles I went through my desire to persevere slowly started to diminish. Thus, I decided to look for other topics that were still non-Ruby and was related to Javascript.

##### Thanks to exploring other blog entries I was able to see different experiences on different topics. With this exploration, I found an interest in React.js mainly because certain blog entries held a lot of helpful links to articles on the basics of React.js. Leaving behind D3.js occurred once I learned that there was a codecademy tutorial for React.js. Therefore, choosing React over D3 because of the opportunity of finding a tutorial that I know I will learn off of.

## What is React.js?
##### React is an efficient and flexible JavaScript library for building user interfaces. When your data changes, React will update and render the components that need to be changed.
##### It was created by Jordan Walke who is a software engineer. He was at the time creating Facebook ads. He was influenced by XHP, which is a PHP-based component system that is still being used at Facebook. He later changed to Product Infra in order to focus on React full-time.

#### A Simple Component
##### React components use a render() method. It takes in input data (in the example below, it takes in the string "Jane") and then returns whatever it is that needs to be displayed (in the example below, the string is replaced for the name under ```this.props.name```, which comes after "Hello ".). 
##### The example given by [React](https://facebook.github.io/react/), uses a syntax called JSX. Any input data that is being passed into the component would be accessed by render() through ```this.props```.
```
class HelloMessage extends React.Component {
  render() {
    return <div>Hello {this.props.name}</div>;
  }
}

ReactDOM.render(<HelloMessage name="Jane" />, mountNode);
```
##### This prints out "Hello Jane"
##### JSX is optional and not required to use React
```
class HelloMessage extends React.Component {
  render() {
    return React.createElement(
      "div",
      null,
      "Hello ",
      this.props.name
    );
  }
}

ReactDOM.render(React.createElement(HelloMessage, { name: "Jane" }), mountNode);
```
##### This will still print out "Hello Jane", however it is the compiled JS version rather than JSX.

#### Takeaways
##### If you find a tutorial that you do not understand no matter how much you continue to look it over, stop wasting time. Find readings and examples that you can actually understand and learn from.
##### Always look for the basics of a new topic before diving into the topic completely.
##### Brainstorm project ideas as you study in order to help invision specific steps/problems that should be explored in the future.





