# 🚀 Alloy

![Alloy Logo](docs/img/alloylang.png)

## 🌟 Overview

Alloy is a cutting-edge programming language that seamlessly blends TypeScript and HTML, allowing developers to create dynamic, robust web applications with ease. Inspired by the simplicity of HTML and the power of modern JavaScript frameworks like React and Svelte, Alloy offers a unique approach to web development.

## ✨ Features

- **Seamless TypeScript Integration** 🔄: Write TypeScript code directly within your HTML-Svelte-like syntax.
- **Component-Based Architecture** 🏗️: Utilize React and Svelte components effortlessly within your Alloy code.
- **Modern Syntax** 💻: Designed for readability and ease of use, Alloy syntax is intuitive and straightforward.
- **Powerful Toolchain** ⚙️: Includes a compiler that transforms Alloy code into optimized HTML and JavaScript.
- **Little Boilerplate** 🛠️: Focus on writing your application logic without being bogged down by excessive configuration and setup.
- **Fast Shipping** 🚚: Get your applications up and running quickly with Alloy's efficient compilation process and straightforward deployment.
- **Easy to Learn** 📚: Alloy's syntax and structure are simple to understand, making it accessible for both beginners and experienced developers.




## Getting Started





## Hello World

```html
<lang.ts>
// TypeScript code
import React from 'react';


// Simple TypeScript function
function greet(): string {
  return "Hello, World! ";
}

// React Component
const HelloWorldComponent = () => (
  <div className="text-center text-2xl text-blue-500">
    {greet()}
  </div>
);

</lang.ts>



<div className="w-full max-w-xs mx-auto">
  <div className="text-center my-4">
   <HelloWorldComponent />
    <img src="docs/img/logo.png" alt="Alloy" className="mx-auto w-24 h-24"/>
  </div>
</div>

```
