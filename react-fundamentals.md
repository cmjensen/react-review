### Remember

Answer these on your own, then compare answers as a group

1.  What is React?
      JS library, highly optimized, for building user interfaces
      Prioritizes component-based architecture and utilizes unidirectional data flow

2.  What is create-react-app?
      // me > CLI command for creating a new react app from scratch
      Package that creates a default boiler plate React application


3.  What is Component Based Architecture?
      set-up where the tasks are broken down into smaller components which are reusable and can be passed around
      Sections of code are broken into different components to keep code cleaner, reusable, and easy to debug

4.  What is JSX?
      Allows you to write HTML in React

5.  What is the virtual DOM?
      Light-weight copy of DOM stored in memory, synced with the "real" DOM through a process called reconciliation

6.  What is unidirectional (one-way) data flow?
      Describes how data flows in React, from parent to child or from top to bottom in component tree

### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `npx create-react-app my-app`
      Build a basic react application so you can get started on a new react project quickly

8.  Summarize the steps for forking and cloning a repo with an existing React app. How does this process differ from the process of creating a new React app on your laptop?
    - fork the repo
    - clone
    - cd into the repo
    - npm i

9.  Explain what this code does:

```jsx
import React from "react";

const Mentor = props => (
  <div className="mentor-container">
    <h1 className={props.title === "Lead Mentor" ? "lead" : ""}>Tim Biles</h1>
    <ul>
      <li>Fort Worth, TX</li>
      <li>My email address is timbilestimbiles@gmail.com</li>
    </ul>
  </div>
);

export default Mentor;
```

10.  Explain how data is passed from a parent component to a child component.
      Through props!

### Apply

Try these on your own, but work together if you start to get stuck.

11.  Use `create-react-app` to create a new React application called `student-directory`

12.  Use the code from `Mentor` above to create a new functional, stateless component called `User` with a list of friends. Hard code the list of friends, do not use state or props.

### Analyze, Evaluate, Create

Discuss these questions as a group

13. What are the benefits and drawbacks of using a tool like create-react-app?

14. Compare and contrast JSX with other templating options, such as those used in Angular or Vue

15. Compare and contrast one-way data flow with two-way data binding.
