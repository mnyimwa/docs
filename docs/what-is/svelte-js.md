title: What is Svelte

# What is [Svelte](https://svelte.dev/)
---

This is a short introduction to [Svelte](https://svelte.dev/) a JS Framework that provides a new approach to code user interfaces. Whereas traditional frameworks like React and Vue do the bulk of their work in the browser, Svelte shifts that work into a compile step that happens when you build your app.

Rather than putting a `<script src='svelte.js'>` tag on the page, or bringing it into your app with import or require, Svelte is a compiler that works behind the scenes to turn your component files into beautifully optimised JavaScript.

Svelte provides a different approach to building web apps than some of the other frameworks covered in this module. While frameworks like React and Vue do the bulk of their work in the user's browser while the app is running, Svelte shifts that work into a compile step that happens only when you build your app, producing highly-optimized vanilla JavaScript.

<br />

**A few advantages of using [Svelte](https://svelte.dev/)**

- Svelte is Fast - the execution time is fast because Svelte surgically updates only the parts of the DOM that change. In contrast to React, Vue.js, and other Virtual DOM frameworks, Svelte doesn’t use a virtual DOM.
- Svelte is Small - when a Svelte app is compiled, the resulting bundle size is tiny compared to most other popular frameworks.
- Svelte is Compiled - the reason Svelte apps are so tiny is because Svelte, in addition to being a framework, is also a compiler.

<br />

## How does [Svelte](https://svelte.dev/) work?
---

Being a compiler, Svelte can extend HTML, CSS, and JavaScript, generating optimal JavaScript code without any runtime overhead. To achieve this, Svelte extends vanilla web technologies in the following ways:

- It extends HTML by allowing JavaScript expressions in markup and providing directives to use conditions and loops, in a fashion similar to handlebars.
- It extends CSS by adding a scoping mechanism, allowing each component to define their own styles without the risk of clashing with other component's styles.
- It extends JavaScript by reinterpreting specific directives of the language to achieve true reactivity and ease component state management.

The compiler only intervenes in very specific situations and only in the context of Svelte components. Extensions to the JavaScript language are minimal and carefully picked in order to not break JavaScript syntax nor alienate developers. In fact, you will be mostly working with vanilla JavaScript.

<br />

## Simple [Svelte](https://svelte.dev/) App
---

The easiest way to create a starter app template is to just download the starter template application.
You can do that by visiting `sveltejs/template` on GitHub or you can avoid having to download and unzip it and just use `degit`.

To create your starter app template, run the following terminal commands:

```bash
$ npx degit sveltejs/template moz-todo-svelte
$ cd moz-todo-svelte
$ npm install
$ npm run dev
```

<br />

## Svelte Starter - [Notus Admin Template](https://www.creative-tim.com/product/notus-svelte?AFFILIATE=128200)
---

Notus Admin Template is an open-source product provided by Creative-Tim on top of Svelte and Tailwind CSS. It features multiple HTML and Svelte elements and it comes with dynamic components for Svelte. It is based on Tailwind Starter Kit by Creative Tim, and it is build with both presentation pages, and pages for an admin dashboard.

- [Svelte Admin Template - Notus](https://www.creative-tim.com/product/notus-svelte?AFFILIATE=128200) - product page
- [Svelte Admin Template - Notus Demo](https://demos.creative-tim.com/notus-svelte/?AFFILIATE=128200)

![Svelte Admin Template - Notus, open-source admin dashboard coded in Tailwind and Svelte.](https://raw.githubusercontent.com/ui-themes/svelte-admin-template-notus/master/media/svelte-admin-template-notus-screen-product.jpg)

<br />

## Links
---

- [Svelte JS](https://svelte.dev/) - the official website
- [Getting started with Svelte](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/Svelte_getting_started)
- [Get started with Svelte](https://svelte.dev/blog/the-easiest-way-to-get-started) - official tutorial
