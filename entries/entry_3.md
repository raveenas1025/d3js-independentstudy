# Entry 3:
## Tic Tac Toe with React.js
One thing that I did know about React.js was that there is a codecademy tutorial on the topic. However, I chose not to directly dive into that tutorial as I had found a tutorial on creating a Tic Tac Toe game using React.js. This tutorial would illustrate the interactive aspect of React and the previous knowledge that I have of HTML and Javascript. The tutorial is provided by [React](https://facebook.github.io/react/tutorial/tutorial.html) and was truly helpful in beginning my journey in React.js as I was in the learning zone through out the process of creating the game.

The tutorial had already provided me with the shell of the code, which is seen here at: [Nakagawa's Code ](https://codepen.io/ericnakagawa/pen/vXpjwZ?editors=0010). In this code pen, the style of the game is already written, therefore, all that was left is to type out the Javscript.

Most of what was being coded were within the three components, the Square, Board and Game. Each component renders different amount of data. The Square component renders a ```<button>```, the Board component renders nine squares and the Game renders placeholders wihtin the board.

One of the key things that I have learned of React is the value of ```this.props```. This one line is what allows data to be passed from one component to the next. In the [final result](https://codepen.io/ericnakagawa/pen/ALxakj), it will display how ```this.props ``` is used multiple times in order to pass data from the Square, Board and Game.

An example of ```this.props```, using the [starting code](https://codepen.io/ericnakagawa/pen/vXpjwZ?editors=0010), is changing ```renderSquare``` method within the Board component to return ```<Square value={i} />```. Then within the the Square component's render method, replace ```{/* TODO */}``` with ```{this.props.value}```.
This will change the empty Square component to consist of numbers passed from the Board component. As shown below:


<img src="../imgs/tictac-empty.png"/>
<img src="../imgs/tictac-numbers.png"/>

Most of the week consisted of working and understanding the Tic Tac Toe game as I coded it along with the steps provided. Similar to rspec in Ruby, it felt nice being able to watch red errors pop up and dissappear as I attempted to fix them. Error messages in the code pen were helpful as they pointed at specific line errors and this code pen allowed the ability to go backwards to when the code did not have the error.

### Takeaways
Save your code! A mistake I did twice this week was forgetting to save my code. Twice in a week I had to recode what I had already coded due to forgetting to save.

Read everything. I found myself falling into a habit of skimming informative sections of the tutorial as I simply searched for where it directly told me to type in code. However, when I did stop to read things that I had skimmed, I came to a realization that every sentence of that tutorial is important.

Don't fear errors. The errors that popped out in the code pen I used were a striking red color and it annoyed, and scared me at first. However, it really helped in understanding each line of code I had. Most of my errors were syntax errors involving too many parenthesises and/or brackets. It is frustrating at first, but when you are able to get rid of the red errors by yourself, it is a great feeling of accomplishment.