# Read 37: Redux - Combined Reducers
## Research:
1. Why choose Redux instead of the Context API for global state?
 - Context API: Resourceful and ideal for small applications where state changes are minimal
- Redux: Perfect for larger applications where there are high-frequency state updates

2. What is the purpose of a reducer?
 - A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change.
  

3. What does an action contain?
   -  It carries a payload of information from your application to store
  
4. Why do we need to copy the state in a reducer?
 - Reducers are not allowed to modify the existing state, instead they must make immutable updates by copying the existing state and making changes to the copied values.


## Vocabulary Terms:

|  Vocabulary | meaning                          |
|---------|----------------------------------|
| immutable state | is an object whose state cannot be modified after it is created. This is in contrast to a mutable object (changeable object), which can be modified after it is created. |
| time travel in redux |redux DevTools records dispatched actions and the state of the Redux store at every point in time, which makes it possible to inspect the state and travel back in time to a previous application state without reloading the page or re-starting the app.  |
| action creator | An action creator is a function that literally creates an action object. In Redux, action creators simply return an action object and pass the argument value if necessary. |
| reducer | A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. .. |
| dispatch | Dispatch is the only software platform to help enterprises successfully unlock the potential of flexible service provider networks to provide world-class customer ... |