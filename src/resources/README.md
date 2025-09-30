## 1. What is JSX, and why is it used?

**What is JSX:**  
JSX (JavaScript XML) is an extension of JavaScript that looks like HTML but is actually JavaScript code. It’s mainly used in React. With JSX, we can easily build User Interfaces (UI). In short, JSX allows React developers to design UI using HTML-like syntax inside JavaScript.  

**Why is it used?**
- Makes UI code easier to write  
- Lets you use JavaScript and HTML together  
- Works smoothly with the React DOM  
- Helps create reusable components  
- Makes the code easier to read  

---

## 2. What is the difference between State and Props?

In React, both **State** and **Props** are used for handling data, but they are not the same.  

- **Props** are used to pass data from one component to another.  
- **State** is used to manage data inside a component itself.  

**Key Differences:**

### Props
- Data is passed from parent to child components  
- Immutable (cannot be changed)  
- Can be used in both functional and class components  
- Read-only  

### State
- Data is managed inside the component  
- Mutable (can be changed)  
- Can be both read and updated  

---

## 3. What is the useState hook, and how does it work?

**What is useState?**  
`useState` is a React Hook that allows you to create and manage state in a functional component.  

**How does it work?**  
It returns an array with two values:  
1. The current state value  
2. A function to update that state  

**Syntax:**
```javascript
const [state, setState] = useState(initialValue);




## 4. How can you share state between components in React?

You can share state between components in two main ways:

### 1. Using Props
- Data is passed from parent to child via props  
- Any type of data (objects, arrays, functions) can be passed  
- Child components can only read props, not modify them  

### 2. Lifting State Up
- Keep the state in a parent component  
- Pass the state and functions down to child components as props  
- This allows child components to update the parent’s state through those functions  

---

##5 How is event handling done in React?

- Event handling in React is similar to HTML but uses **camelCase** syntax (e.g., `onClick` instead of `onclick`)  
- we can pass a function reference as the event handler, not a string  
- React uses its own **SyntheticEvent** system to ensure events work consistently across all browsers  


