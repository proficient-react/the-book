# Chapter 1: Introduction to React.

## What is React?

React is a Javascript library for creating user interfaces (UIs) originally created by
Facebook and Instagram engineers. It's aimed to solve the challenges involved
when developing complex user interfaces with datasets that change over time.

 which is considered in the front-end development: the root of all evil.

## What makes React different?

Using React you simply express how your app should look based on your data at
any given point in time. When your data changes React handles automatically all
the UI updates, saving you from imperatively manipulate the DOM. Which makes
React very simple and declarative.

Since its not viable for performance reasons to actually trash and re-render the
entire interface every time state data changes, React uses a fast, in-memory and
lightweight representation of the DOM called virtual DOM. React basically uses a
very optimized diff algorithm that compares the virtual DOM of the current and
the previous state. The difference between them is what actually needs to be
changed in the real DOM and React computes the most efficient DOM mutation for
you.