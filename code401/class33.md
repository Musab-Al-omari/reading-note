# Read 33: Custom Hooks
## Research:
1. Describe use cases for useMemo() and useReducer()
   - >  useMemo is a React hook that memorizes the output of a function. That is it. useMemo accepts two arguments: a function and a list of dependencies. useMemo will call the function and return its return value..
   - > useReducer returns an array that holds the current state value and a dispatch function, to which you can pass an action and later invoke. This is similar to the pattern Redux uses but with a few differences. For example, the useReducer function is tightly coupled to a specific reducer.

2. Why do custom hooks need the use prefix?
 - the  name should always start with use so that you can tell react to apply the rules of Hooks on it.
  


3. What do custom hooks usually do?
   -  allow us to have cleaner functional components, remove logic from the UI layer, and prevent code duplication by bringing common use cases to reusable hooks
   - 
4. Describe how a hook that fetches API data might work
we will put all the fetch functionality in side the hook and we will send the 3 argument  the method and url the body if existed . 

## Vocabulary Terms:

|  Vocabulary | meaning                          |
|---------|----------------------------------|
| reducer | function Will always return only one value after take tow , that value can be a number, string, an array, or an object. Great for applying a bit of logic to a group of values and ending up with another single result. Reducers will not mutate your initial value, rather they return something else. |