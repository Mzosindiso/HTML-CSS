# React
<p>React is a popular library used to create user interfaces. React components use Pascal case (or upper camel case) variable names</p>
<p>Component: is an independent, reusable code block which divides the UI into smaller pieces.</p>
<ul>
    <li>Functional component - is basically a JavaScript/ES6 function that returns a React element (JSX)</br>
    
```html
    <script>
        function Welcome(props) {
              return <h1>Hello, {props.name}</h1>;
        }
    </script>
```
</li>
    <li>Class-based component - are ES6 classes that return JSX, must have an additional render( ) method for returning JSX.<br>

```html
    <script>
    class Welcome extends React.Component {
      render() {
        return <h1>Hello, {this.props.name}</h1>;
      }
    }
    </script>
```
</li>
    
    <li>Presentational component - </li>
    <li>Container components - </li>
</ul>
<p>JSX is a combination of JavaScript and the X from XML. It is a JavaScript extension that allows us to define React elements using a tag-based syntax directly within our JavaScript code.</p>
<ol>
    <li>Props - are used to pass data from component to component</li>
    <li>State - it's what makes your application grow beyond static content being displayed on a website, because a user can interact with it</li>
    <ul>
        <li>Props are used to pass information down the component tree, state is used to alter information over time.</li>
    </ul>
</ol>

### Hooks <br>

<p>Hooks works similarly with JavaScript variables (store data and later perform operations on that data), but they are designed to manage state in functional components</p>

```html
<script>
import { useState } from 'react';

export default function MyInput() {
  const [text, setText] = useState('hello');

  function handleChange(changeText) {
    setText(changeText.target.value);
  }

  return (
    <>
      <input value={text} onChange={handleChange} />
      <p>You typed: {text}</p>
      <button onClick={() => setText('hello')}>
        Reset
      </button>
    </>
  );
}
</script>
```


