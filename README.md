# useReducer Hook in React Explained with Simple Examples

## What is useReducer()?
useReducer(reducer, initialState) follows the reducer pattern found in JavaScript. The reducer function defines how state should be updated based on the dispatched action. The hook then returns an array of 2 items: the current state and the dispatch function.

You can run with below command:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

In the example above, the `Counter` component uses the `useReducer` hook to manage the count state. The reducer function defines how the state should be updated based on the dispatched actions (`INCREMENT` and `DECREMENT`). The state is initialized with an initial value of `{ count: 0 }`, and the dispatch function is used to trigger state updates by dispatching the corresponding actions.

You can check detail explaination in https://www.kushalstudy.com/blog/usereducer-hook-in-react-explained-with-simple-examples/
