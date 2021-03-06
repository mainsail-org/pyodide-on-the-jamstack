# Pyodide on the Jamstack

[Pyodide](https://github.com/pyodide/pyodide) on the [Jamstack](https://jamstack.org/what-is-jamstack/) brings Python to Static Site Generators. The goal is to create an easy way to write and run code side-by-side with Math and Markdown.

## What's Pyodide
Pyodide brings the Python 3.9 runtime to the browser via WebAssembly, along with the Python scientific stack including NumPy, Pandas, Matplotlib, SciPy, and scikit-learn.  
This is the main [GitHub Repo](https://github.com/pyodide/pyodide) for the Pyodide project.

## What's the Jamstack?
Jamstack stands for "Javascript, API and Markup". It is a modern "serverless" architecture pattern for building things on the web.
You can read more about the Jamstack on [jamstack.org](https://jamstack.org/)

## How to put Pyodide on the Jamstack?
With the Jamstack architecture, pre-rendered content is served to a content delivery network (CDN) and made dynamic through **APIs** and **serverless functions**. We want to add WebAssembly and Python to the mix. Content can then be made dynamic by using **APIs**, **serverless functions** AND the **Python runtime in the browser**.

## Goals

Setup a Jamstack workflow and a static site generator that lets an author create a Python-enabled site.

These are some thing that an author should be able to do without having to learn Javascript:
- [ ] write prose in markdown
- [ ] write math using the Tex typesetting system
- [ ] load pyodide from a CDN
- [ ] load python code snippets from a python file
- [ ] load python code snippets and outputs from a Jupyter Notebook
- [ ] edit and execute code snippets in the browser
- [ ] use pyodide packages like numpy and pandas in the browser
- [ ] run asynchronous python code
- [ ] run python code in a service worker
- [ ] publish a Python-enabled site to the web, at no cost

## Which Static Site Generators?
We are getting started with [Hugo](https://gohugo.io/). It is a blasing fast static generator written in Go. Jekyll, Gatsby and other static generators will be added.

## Contributing
Thank you for your interest in contributing. You can contribute by:
- Using this project and submitting issues
- Adding features and fixing bugs through pull requests