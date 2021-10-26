# State and Props

## React Lifecycle

**Based on the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**

- Render comes first

- render > React updates DOM abd refs > componentDidMount

**What is the very first thing to happen in the lifecycle of React?**

- constructor function.

**Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates**

- constructor -> render -> react updates -> componentDidMount -> componentWillUnMount

**What does componentDidMount do?**

- is invoked after a component is mounted. loads network requests or start the DOM.

## React State Vs Props

**What types of things can you pass in the props?**

- arguments, displayed information like titles and subtitles,

**What is the big difference between props and state?**

-props you pass into a component handling them from the outside, while the state is inside a component and handled inside.

**When do we re-render our application?**

- when we want to change information that was already displayed, so when we change the state stored information the application will rerender.

**What are some examples of things that we could store in the state?**

- counters, fill forms,

Blankenship, Joshua. "What is “React: Component Lifecycle Events" medium, 9 Jul 2018, <https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093>

"React State Vs Props" YouTube, uploaded by Web Dev Simplified, 27 Aug 2019, www.youtube.com/watch?v=IYvD9oBCuJI.

All definitions and information came from the above-listed publication(s).

[<===Back>](README.md)
