# Design Patterns in TypeScript

It contains TypeScript examples for all classic GoF design patterns. Each pattern includes two examples:

- [x] **Conceptual** examples show the internal structure of patterns, including detailed comments.

- [ ] **RealWorld** examples show how patterns can be used in real-world web applications.

## Requirements

For simplicity reasons, the examples are console apps. In order to launch them, you have to install [Node.js and NPM](https://nodejs.org/en/) on your computer and then install [TypeScript compiler](https://github.com/Microsoft/TypeScript) and [TypeScript Node extension](https://github.com/TypeStrong/ts-node) like this:

```
npm install -g typescript
npm install -g ts-node
```

When you have all the required software installed, the examples can be launched via the command line as follows:

```
ts-node src/Path-to-example/Example.ts
```

For the best experience, I recommend working with examples with these IDEs:

- [WebStorm](https://www.jetbrains.com/webstorm/)
- [Visual Studio Code](https://code.visualstudio.com/)


## Guide

Here's a style guide which might help you to keep your changes consistent with the rest of the project's code:

1. All code should follow these two guidelines: [Unofficial TypeScript StyleGuide](https://github.com/basarat/typescript-book/blob/master/docs/styleguide/styleguide.md) and [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript).

2. Try to hard wrap the code at 80th's character. It helps to list the code on the website without scrollbars.

3. Example files should be located and named in the following manner:

    ```
    src/{PatternName}/{ExampleName}/index.ts
    ```

4. Aim to put all code within one file. Yes, I realize that it's not how it supposed to be done in production. But it helps people to better understand examples, since all code fits into one screen.


## License

This work is licensed under a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/80x15.png" /></a>

