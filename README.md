# Next JS Learning Notes

## Introduction Tutorial Link
https://nextjs.org/learn/foundations/about-nextjs

## What is Next JS
Next.js is a flexible React framework that gives you building blocks to create fast web applications.

## Building Blocks of a Web Application

- User Interface - how users will consume and interact with your application.
- Routing - how users navigate between different parts of your application.
- Data Fetching - where your data lives and how to get it.
- Rendering - when and where you render static or dynamic content.
- Integrations - what third-party services you use (CMS, auth, payments, etc) and how you connect to them.
- Infrastructure - where you deploy, store, and run your application code (Serverless, CDN, Edge, etc).
- Performance - how to optimize your application for end-users.
- Scalability - how your application adapts as your team, data, and traffic grow.
- Developer Experience - your team’s experience building and maintaining your application.

### React
https://react.dev/learn
### Next.js
Next.js is a React framework that gives you building blocks to create web applications.

## Understand DOM (Document Object Model)
The DOM is an object representation of the HTML elements. It acts as a bridge between your code and the user interface, and has a tree-like structure with parent and child relationships.

![Alt text](https://nextjs.org/static/images/learn/foundations/dom-to-ui.png)

### Imperative vs Declarative Programming
The code above is a good example of imperative programming. You’re writing the steps for how the user interface should be updated. But when it comes to building user interfaces, a declarative approach is often preferred because it can speed up the development process. Instead of having to write DOM methods, it would be helpful if developers were able to declare what they want to show (in this case, an h1 tag with some text).

In other words, imperative programming is like giving a chef step-by-step instructions on how to make a pizza. Declarative programming is like ordering a pizza without being concerned about the steps it takes to make the pizza. 

#### react is the core React library.
#### react-dom provides DOM-specific methods that enable you to use React with the DOM.

## What is JSX?
JSX is a syntax extension for JavaScript that allows you to describe your UI in a familiar HTML-like syntax.

### 3 JSX Rules
1. Return single root element
2. Close all the tags
3. camelCase most of the things

