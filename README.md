# Vue.js by sample

The goal of this project is to provide a set of step by step samples, covering core concepts of Vue.js
Each of the samples contains a `README.md` file that indicates the purpose of the sample plus an step by step guide to reproduce it.

# Demos

## 00 Boilerplate

In this sample we are going to setup a web project that can be easily managed
by webpack.

We won't install anything related to Vue.js, just some basic plumbing.

We will setup an initial <abbr title="Node.js package manager, a package manager for the JavaScript runtime environment Node.js">npm</abbr> project and give support to TypeScript. Then we will create a **helloworld.ts** sample.

Summary steps:

- Prerequisites: Install Node.js
- Initialize **package.json** (with `npm init`)
- Install:
    - Webpack and webpack-dev-server.
    - TypeScript.
    - Bootstrap.
- Setup **webpack.config.js**
- Create a test js file.
- Create a simple HTML file.

## 01 Hello VueJS

In this sample we are going to create our first Vue.js component and connect it with the DOM.

We will take a startup point sample _00 Boilerplate_.

Summary steps:
 - Install Vue.js devtools.
 - Install `vue.js` library.
 - Configure webpack to work with `vue.js`.
 - Update `index.html`.
 - Update `main.ts`.

## 02 Properties

In this sample we are going to learn a basic concept, handling properties.

We will take a startup point sample _01 Hello VueJS_.

Summary steps:
 - Update `main.ts` with and input element.
 - Use `v-model` directive.
 - Create our first component.
 - Passing properties from `main.ts` to `hello.ts`.
 - Other approach to work with properties.

## 03 Render

In this sample we are going to work with `render` function.

We will take a startup point sample _02 Properties_.

Summary steps:
 - Configure to work with runtime-only build.
 - Enable and configure jsx
 - Install `babel-plugin-transform-vue-jsx`
 - Rename to `main.tsx` and update it.
 - Rename to `hello.tsx` and update it.

## 04 Login

In this sample we are going to create a `login` page.

We will take a startup point sample _03 Render_.

Summary steps:
 - Delete `hello.tsx`.
 - Update `index.html`.
 - Create `login` page.
 - Configure router navigation.
 - Create `recipe list` page.
 - Create `LoginEntity` model.
 - Create fake `login` API.
 - Check valid login.

## 05 Recipe List

In this sample we are going to create a `recipe list` page.

We will take a startup point sample _04 Login_.

Summary steps:
 - Create `recipe` model.
 - Create fake `recipe` API.
 - Create `recipe list` page container.
 - Update `recipe list` page.
 - Navigate to `edit recipe` page.

## 06 Edit Recipe

In this sample we are going to create a `edit recipe` page.

We will take a startup point sample _05 Recipe List_.

Summary steps:
 - Create `API` methods.
 - Create `pageContainer`.
 - Update `page`.
 - Create `common` components.
 - Create `edit recipe` form.
 - Add `form validations` with `lc-form-validation`.

# About Lemoncode

We are a team of long-term experienced freelance developers, established as a group in 2010.
We specialize in Front End technologies and .NET. [Click here](http://lemoncode.net/services/en/#en-home) to get more info about us.

For the LATAM/Spanish audience we are running an Online Front End Master degree, more info: http://lemoncode.net/master-frontend
