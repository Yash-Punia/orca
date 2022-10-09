# Contributing to Orca - Quickguide

This is a brief version for novice developers to contribute to Orca. An in-depth wiki is there for developers who are completely new to open source development (and are familiar with basic html, css and js at the very least)

## Table of Contents

  - [Tech Stack](#tech-stack)
    - [Svelte](#svelte)
    - [TailwindCSS](#tailwindcss)
  - [Code Contributions](#code-contributions)
    - [Creating a new component for the gallery](#creating-a-new-component-for-the-gallery)
    - [New features or components](#new-features-or-components)
  - [Pull Requests](#pull-requests)

## Tech Stack

Orca is made with ❤️ using -

- SvelteKit
- TailwindCSS

Yes, mainly these 2 web frameworks. If you know HTML, CSS and Javascript, you're good to go. If not, I suggest to look them up to get a refresher before you start contributing.

### Svelte

Svelte is one of the most loved web frameworks with no virtual DOM and in my opinion it is the most developer friendly framework. [SvelteKit](https://kit.svelte.dev/) is built on top of Svelte and provides the fastest way to create and deploy Svelte apps.

### TailwindCSS

> A utility-first CSS framework packed with classes like flex, pt-4, text-center and rotate-90 that can be composed to build any design, directly in your markup.

and it's just that, as said by the official TailwindCSS website. You don't need to leave your HTML markup and can quickly add CSS by appending classes to your elements

## Code Contributions

The contribution that you do is also divided into 2 main parts

### Creating a new component for the gallery

- Orca is a gallery of components like buttons, navbars, etc. You can create your own component and add it to the gallery
- Create your component in `lib/components/designs/<component>` directory
- Add the export to the correct `index.js` file in the component directory
- Test locally if your component is visible
- Push it to your remote repository
- Create pull request with proper guidelines

### New features or components

- There are many features that should be added to Orca like searching, username display etc.
- Additionally, bugs can be reported and worked upon to improve the existing build
- New issues can be created but keep in mind that the issue must be logical and something which can be discussed upon. It should not be misleading such as eg: "More cool button designs". This is an ambiguous issue title which shouldn't be used.

## Pull Requests and Issues

Make sure the pull requests that you create are in proper format -

```
New Feature

<Link to Issue number, if any>

Need of the feature

Describe Your Solution
```

If you're adding a new component, its fairly simple - 

```
New Component Type

Component Name

Any inspiration links (for eg: dribbble or any other design resource)
```

