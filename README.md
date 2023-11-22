# Meow Counter

A Pen created on CodePen.io. Original URL: [https://codepen.io/Nalini1998/pen/XWyvBPZ/a8970c3f37de544a52f8a64d0452f758](https://codepen.io/Nalini1998/pen/XWyvBPZ/a8970c3f37de544a52f8a64d0452f758).

# Counter Component

The `Counter` component is a simple React component that allows you to increment and decrement a counter. It also features a GIF animation that loops continuously.

## Props

The `Counter` component does not accept any props.

## Usage

To use the `Counter` component, you can import it and render it within your React application:

```jsx
import React from 'react';
import ReactDOM from 'react-dom';
import Counter from './Counter';

ReactDOM.render(<Counter />, document.getElementById('app'));
```

The `Counter` component will be rendered within the element with the `app` id.

## Example

```jsx
import React from 'react';
import ReactDOM from 'react-dom';
import Counter from './Counter';

const App = () => {
  return (
    <div>
      <h1>Counter App</h1>
      <Counter />
    </div>
  );
};

ReactDOM.render(<App />, document.getElementById('app'));