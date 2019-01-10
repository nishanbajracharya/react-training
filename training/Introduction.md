# Introduction
React is a javascript library for building component-based user interfaces. It efficiently tracks the changes in the UI state and updates the DOM accordingly. It is actively maintained by Facebook.

## Why React?
React is among the most popular frontend javascript libraries with a massive community following. After five years (as of 2019) of release, the react ecosystem is now very robust and mature with hundreds and thousands of react-based packages available in npm and growing adoption of React for single page application and frontend application development.

So why is React so popular?

1. **Emphasis on reusable components**
   
   In React, we build user interfaces in units called Components which are made with the idea of reusability. Once made, Components can be easily shared and reused as many times as necessary. Well designed Components can also be published as standalone packages for public use.

2. **Reactive updates**
   
   React, as the name suggests, performs UI updates reactively. When the state of a component changes, the UI it represents and subsequently the HTML DOM is updated reactively.

3. **Virtual representation of UI**
   
   React internally maintains a tree based representation of the DOM, called the Virtual DOM. When the component state changes, the nodes of this tree are updated. This process is very efficient and results in updates in only parts of the page where the updates are necessary.