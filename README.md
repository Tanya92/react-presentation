React presentation

**Slide 1: Greeting**

Hello! My name is Tanya. I know that one of the most popular JS libraries nowadays is React. It became interesting for me. That’s why I’ve chosen this presentation topic. 

**Slide 2: What is React?**
React is a JavaScript library for building user interfaces. It’s maintained by Facebook and a community of individual developers and companies.

**Slide 3:  History of creation**
Let’s look at a few facts about history of creation

**Slide 4: 2011 – FaxJS**
More and more functions were added to Facebook Ads app and the team needed more people. A large number of team members slowed their development as a company. 
Jordan Walke created FaxJS, the early prototype of React.

**Slide 5: 2012 – Instagram & Facebook**
Instagram was bought by a Facebook in April 2012.
Instagram wanted to adopt new Facebook technology. Facebook sought to separate React from Facebook and to make it open-sourced. 

**Slide 6: May 2013 – JS ConfUS**
Jordan Walk introduced React on JS ConfUS. React became open-sourced.
Many people thought that React is a big step back because there were early followers here and not innovators. Creators realized it in time and were going to support React tour in summer 2013. React was finally recognized as a success.

**Slide 7: 2019 – The highest popularity**
Nowadays React  is one the most popular JS libraries. 

**Slide 8: Let’s look at the React in more details.** 
React has very small API, and you basically need to understand 4 concepts to get started: JSX, Components, State, Props

**Slide 9: JSX**

**Slide 10: Let’s look to the next code:**
This syntax is not a string and not an HTML code. It’s syntactic sugar for JS is called JSX. React creators recommend us to use JSX and React together as it shows us the most clear appearance and at the same time contains all the power of JavaScript.
Actually you can write JavaScript directly within JSX. To do this, you simply include the code you want to be treated as JavaScript within curly braces: 

**Slide 11: (image jsx_example)**
If and for statements are not expressions in JavaScript and they can’t be used in JSX  
So you can use it only in surrounding code. 

**Slide 12: Components**
React greatly simplifies the creation of interfaces by splitting each page into small fragments. They are called components

**Slide 13: (Image google elements)**
This is example where every page part  is a component . And what is a component for developers ?

**Slide 14: (image cake)**
Each component is a JavaScript function that returns a piece of code representing a page fragment.

**Slide 15: (Image two ways to create components)**
There are two ways to create a React component. 
The first way is to use a JavaScript function. Defining a component in this way creates a stateless functional component. To create a component with a function, you simply write a JavaScript function that returns either JSX or null. One important thing to note is that React requires your function name to begin with a capital letter. 
The other way to define a React component is using the ES6 class syntax and render method. Render () returns a description of what you want React to show on the page. 

**Slide 16: State**
Class-based components can store information about the current situation. This information is called state. It’s stored in a JS object.

**Slide 17: Image state_example & image state_example2**
We can see object and  key “isMusicPlaying” with false value. This object is assigned to this.state in the constructor method.
So, what should we do with this “state”? Why is it invented?
State is a tool to update the user interface based on events. Here we will use the state to change the appearance of the music playback button, based on a click on it.  Button can be displayed in one of two options . The first indicates the possibility of starting playback, the second - that the music is playing, and this process can be suspended. When a user clicks a button, the state changes and then the user interface is updated.
Word Class in JS is reserved, JSX – is a combination JS and HTML, and we will use word className to define class to html tag. 
After header definition we see a string  like a tag, but tag name is a Component name. It means that string calls playButton component and render it. In the tag brackets  the name of component must be followed by a space and then a slash.

**Slide 18: UNIDIRECTIONAL DATA FLOW**
State is always belong to one component. Any data that affects this state can affect only the following components, that are children.
Changing the state of a component will never affect its parents or siblings or any other component in the application: only descendants.

**Slide 19: Virtual DOM**
React uses virtual DOM. React creates a cache structure in memory that allows you to calculate the difference between the previous and current interface states for optimal updating of the browser DOM. To change the state, use the setState () method. The developer can work with the page, considering that it is updated all, but the library independently decides which components of the page need to be updated.

**Slide 20: Props**
Passing props to child components is a great way to transfer values across the entire application. A component can both store data (having a state) and receive it through its props.
Props (or «properties») and state – are objects in JavaScript. Although each of them contains information that affects the result of the component's rendering, there is an important difference between them: props is passed to the component (similar to the function parameters), while state is controlled inside the component (like variables declared inside the function).

**Slide 21 : Thanks for watching!**
I hope you got a brief idea of such a library as a react. Thanks for watching.


