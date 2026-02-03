# JS_LLD
Low level design practice with JS

## DOM
Dom is a tree structure in which every HTML element is arranged in heirarchical order.

## Events
In JavaScript, **an event is a signal that something has happened in the web page or application**. 
This could be user interactions like clicks, key presses, or page loading.

## Event handling
Event handling in JavaScript refers to the **process of writing code to respond to events**. This involves attaching event listeners to specific elements in the DOM (Document Object Model) and defining functions that are executed when the specified event occurs. Event handling allows developers to create interactive and dynamic web experiences.

## Debouncing
Debouncing is a technique that **delays the execution of a function** until the user stops performing a certain action for a specified amount of time.
In debouncing, the function is only executed after a specific delay since the last event's occurrence.

## Throttling
Throttling is a technique that **limits the execution of a function** to once in every specified time interval. 
In throttling, the function is executed at a fixed interval. Even if the triggering event occurs more frequently, the function is invoked according to the defined interval.

## Reconciliation
In React, reconciliation is the internal process of updating the actual Browser DOM to match the latest Virtual DOM tree.
How the Process Works
When a component’s state or props change, React triggers a three-step cycle: 
1. Render: React creates a new Virtual DOM tree representing the updated UI.
2. Diffing: It compares the new tree with a "snapshot" of the previous one to identify differences.
3. Commit: React applies only those specific differences to the actual DOM.
