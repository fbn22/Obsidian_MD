# JSX React

### 📍 Definition 
 _JSX allows us to write HTML elements in JavaScript and place them in the DOM without any `createElement()`  and/or `appendChild()` methods. JSX converts HTML tags into react elements._

### 🔎 Example

**JSX:**
```jsx
const myelement = <h1>I Love JSX!</h1>;

ReactDOM.render(myelement, document.getElementById('root'));
```


**Without JSX:**
```jsx
const myelement = React.createElement('h1', {}, 'I do not use JSX!');

ReactDOM.render(myelement, document.getElementById('root'));
````

### 📝 Notes
- The HTML code must be wrapped in _ONE_ top level element.

So if you like to write _two_ paragraphs, you must put them inside a parent element, like a `div` element.

Wrap two paragraphs inside one DIV element:

```jsx
const myelement = (
  <div>
    <p>I am a paragraph.</p>
    <p>I am a paragraph too.</p>
  </div>
);
``` 

### 📂 Resources
- [React JSX](https://www.w3schools.com/react/react_jsx.asp)


🏷Tags: [[👨‍💻coding]][[javascript]]