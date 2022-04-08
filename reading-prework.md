# Readings: Introduction to React and Components

## Component-Based Architecture

### What is a “component”?
Components are the building blocks of any React app and a typical React app will have many of these. Simply put, a component is a JavaScript class or function that optionally accepts inputs i.e. properties(props) and returns a React element that describes how a section of the UI (User Interface) should appear.

### What are the characteristics of a component?
Components are independent and reusable bits of code. They serve the same purpose as JavaScript functions, but work in isolation and return HTML. Components come in two types, Class components and Function components, in this tutorial we will concentrate on Function components.

### What are the advantages of using component-based architecture?
Reduced cost − The use of third-party components allows you to spread the cost of development and maintenance. Ease of development − Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.



## What is Props and How to Use it in React

### What is “props” short for?
Props are arguments passed into React components. Props are passed to components via HTML attributes. props stands for properties.

### How are props used in React?
We use props in React to pass data from one component to another (from a parent component to a child component(s)). Props is just a shorter way of saying properties. They are useful when you want the flow of data in your app to be dynamic.

### What is the flow of props?
Adding Flow types to your React components is incredibly powerful. After typing your component, Flow will statically ensure that you are using the component in the way it was designed to be used. There are some Babel plugins which will generate PropTypes from Flow types such as babel-plugin-react-flow-props-to-prop-types if you want both static and runtime checks.



### Reference: 

https://medium.com/the-andela-way/understanding-react-components-37f841c1f3bb#:~:text=Components%20are%20the%20building%20blocks,(User%20Interface)%20should%20appear.

https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm#:~:text=Reduced%20cost%20%E2%88%92%20The%20use%20of,other%20parts%20of%20the%20system.

https://www.w3schools.com/react/react_components.asp#:~:text=Components%20are%20independent%20and%20reusable,will%20concentrate%20on%20Function%20components.

https://www.w3schools.com/react/react_props.asp#:~:text=Props%20are%20arguments%20passed%20into,props%20stands%20for%20properties.