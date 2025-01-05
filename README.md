# Tailwind CSS @apply Directive with Undefined Class

This repository demonstrates a common error when using Tailwind CSS's `@apply` directive: applying a class that is not defined in your Tailwind configuration.  This can lead to unexpected behavior or build errors.

## Bug Description

The `@apply` directive in Tailwind allows you to apply multiple classes from your configuration to a single element. If the referenced class is not defined or misspelled, Tailwind will either throw a build error (depending on your configuration) or simply ignore the `@apply` directive, leading to unintended styling.

## Bug Reproduction

The `bug.js` file contains a simple example where `@apply` is used with a non-existent class (`non-existent-class`).  Try building the project to observe the error or unexpected behavior.

## Solution

The `bugSolution.js` file demonstrates the correct way to use the `@apply` directive by ensuring that the referenced class is correctly defined within the Tailwind configuration.

## How to Run

1. Clone the repository.
2.  Ensure you have Node.js and npm (or yarn) installed.
3. Run `npm install` (or `yarn install`) to install dependencies.
4. Try building with your preferred build tool, such as Webpack or Vite. (This step is dependent on your project setup, you may have to configure Tailwind's build process in your chosen build tool)
