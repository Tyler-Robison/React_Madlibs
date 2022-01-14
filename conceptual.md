### Conceptual Exercise

Answer the following questions below:

- What is React? When and why would you use it?
React is a front-end framework that helps us organize our JS, HTML and CSS into modular components. In regular JS, the high-level design pattern is to separate JS, CSS and HTML into separate files. React allows us to create components that include all JS/CSS/HTML for the component to work. 

We would use it if we were building a large web app and wanted our code organized this way to promote re-use and speed-up development. It is also easier to understand your components when they are organized this way as opposed to having their logic, html and css scattered across many files. 

- What is Babel?

Babel is an open-course JS transcompiler used to convert ES6+ (2015) into backwards compatible JS that can be run by older browsers. Additionally, Babel can transcompile JSX into JS. 

- What is JSX?

JSX is an extension of the JS language. JSX provides a way to structure component rendering using syntax familiar to many developers because it is similar to HTML. In React, we write our components in JSX.

const App = () => {
   return (
     <div>
       <p>Header</p>
       <p>Content</p>
       <p>Footer</p>
     </div>
   ); 
}

In the above example, there is an App component rendering a div that contains 3 paragraphs. This "HTML-like" JSX will be transcompiled into the correct JS needed to make those HTML elements. 

- How is a Component created in React?

- What are some difference between state and props?

- What does "downward data flow" refer to in React?

- What is a controlled component?

- What is an uncontrolled component?

- What is the purpose of the `key` prop when rendering a list of components?

- Why is using an array index a poor choice for a `key` prop when rendering a list of components?

- Describe useEffect.  What use cases is it used for in React components?

- What does useRef do?  Does a change to a ref value cause a rerender of a component?

- When would you use a ref? When wouldn't you use one?

- What is a custom hook in React? When would you want to write one?
