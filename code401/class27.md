# Read27: Props and State

## Research:
1. Does a deployed React application require a server?
   No, It doesn't as it is a front end UI
2. Why do we prefer to test a React application at the behavior rather than the unit level?
   According to the react doc: "With components, the distinction between a “unit” and “integration” test can be blurry. If you’re testing a form, should its test also test the buttons inside of it? Or should a button component have its own test suite? Should refactoring a button ever break the form test?"
3. What does npm run build do?
   > npm run build runs the script "build" and created a script which runs your application.
4. Describe the actual composition / architecture of a React application
   Every React app has a root component of a tree of components. Some of these components are static and some have a state that could change.
## Vocabulary Terms:

|  Vocabulary | meaning                          |
|---------|----------------------------------|
| BDD | Behavior-driven development, we use it to test a react app |
| Acceptance Tests | they are tests that are used to make sure the code is working with various scenarios and have no issue|
| mounting |In react, it is the process of outputting the virtual representation of a component into the final UI representation  |
| build | In react, it is preparing the code for production |



## Review 
### React Concepts:
* `setState()`: used to change the state of the component as we can't modify directly the start property because it is mutable. used with stateful components.
* Handling Events: 
  - `onClick={functionName}`
  - `onChange={functionName}`
  - `onSubmit={functionName}`

#### State and Lifecycle:

![](https://2.bp.blogspot.com/-hG_eQYv5-Fo/WCGvwiJSLFI/AAAAAAAABzU/Gu832Gwzi_UjVIE73g9ISQ94mAHGLSYEQCLcB/w1200-h630-p-k-no-nu/reactjs_component_lifecycle_status.png)

#### Components and Props in react js:

![](https://s1.o7planning.com/en/12125/images/25128970.png)

## References:
* [React Doc](https://reactjs.org/docs/handling-events.html)