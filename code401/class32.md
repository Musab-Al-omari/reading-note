# Read 31: Custom Hooks
## Research:
1. What does a component’s lifecycle refer to?
   - >  Components are created (mounted on the DOM), grow by updating, and then die (unmount on DOM). This is referred to as a component lifecycle.

2. Why do you sometimes need to “wrap” functions in `useCallback` when called from within `useEffect`
 - useCallback will help in avoiding regeneration of functions when the functional component re-renders. 
 - useCallback() often is used in conjunction with useEffect() because it allows you to prevent the re-creation of a function. 
  


3. Why are functional components preferred over class components?
   - Functional component are much easier to read and test because they are plain JavaScript functions without state or lifecycle-hooks. You end up with less code. They help you to use best practices.
   - 
4. What is wrong with the following code?

## Vocabulary Terms:

|  Vocabulary | meaning                          |
|---------|----------------------------------|
| state hook | A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components. |
|effect hook |The Effect Hook lets you perform side effects in function components:|
| reducer hook | An alternative to useState. Accepts a reducer of type (state, action) => newState, and returns the current state paired with a dispatch method. (If you’re familiar with Redux, you already know how this works.) |
