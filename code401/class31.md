# Read 31: Hooks API
## Research:
1. Why do we not need more .html pages in a multi-page React app?
   - > Using the **react-router-dom** package, we can implement multiple routes in a React application. A user browsing this app feels each route is each page. So in React, multiple routes are considered as multiple pages.

2. If we wanted a component to show up on every page, where would we put it and why?
 - Outside the` <BrowserRouter/>`
 - Inside the `<BrowserRouter />`, outside a `<Route />`
 - Inside a` <Route />`
The answer would be `**Inside the <BrowserRouter />, outside a <Route />**`.

3. What does props.children contain?
   - `props.children` it displays whatever you include between the opening and closing tags 

## Vocabulary Terms:

|  Vocabulary | meaning                          |
|---------|----------------------------------|
| Composition | It is a pattern that can be used to break a complex component down to smaller components, and then composing those smaller components to structure and complete your application |
| Children / Child Components | is a more specific part inside a parent component. |
| Hash Routing | is using the anchor part of the URL to simulate different content. |
| Link Routing | It is a dynamic routing algorithm in which each router shares knowledge of its neighbors with every other router in the network. |


## Review 
### React Hooks:
* It was  introduced in the React 16.8 version.
* In case we have complex components that are not divisible by simpler component.
* Hooks comes to "organize the logic inside a component into reusable isolated units".
* It is done inside a component.
* It allows you to use state and other React features without writing a class.

### Hooks Examples:
*  `setState `: alters the state and causes rerendering.
*  `useEffect`: used to tell React that a component needs to do something after render. 
*  `useContext`: used to create common data that can be accessed throughout the component hierarchy without passing the props down manually to each level.

![](https://i.stack.imgur.com/lQQX7.png)

### Hook Definition:
* According to the [React Document](https://reactjs.org/docs/hooks-state.html):
* >  A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components


### Rules of Hooks:
* Only Call Hooks at the Top Level
* Only Call Hooks from React Functions
* Don’t call Hooks from regular JavaScript functions
* `eslint-plugin-react-hooks` plugin uses these roles.

## References:
* [Create A Multi-Page Website With React](https://www.techomoro.com/how-to-create-a-multi-page-website-with-react-in-5-minutes/)