# Webpack Core Concepts

After spending some time browsing the webpack docs for a project I'm working on, I decided to work through the core concepts of webpack and learn more about them here. 

Webpack Docs: https://webpack.js.org/concepts/

Video References: 
- https://www.youtube.com/watch?v=IZGNcSuwBZs&t=803s

## So far covered in this guide 
- [x] What is webpack
- [ ] Entry Points
- [ ] Output 
- [ ] Loaders
- [ ] Plugins
- [ ] Configuration
- [ ] Modules
- [ ] Hot Module Replacement
- [ ] Under The Hood

# What is Webpack
1) A Bundler
2) A Dependency Manager 

Webpack is a JavaScript module bundler used in web development to efficiently bundle and optimize assets like JavaScript, CSS, and images. It simplifies development by handling modular code, transpiling modern JavaScript, managing static assets, and integrating with other tools. With features like code splitting and hot module replacement, Webpack enhances performance and streamlines the development workflow. 

Some use cases may be:
- Bundling and optimizing assets
- When writing modular code or using modern JS features like ES6 modules, webpack handles the dependencies and creates a seemless experience.
- Transpiling code into older versions for compatability across browser versions
- Code splitting (breaking large projects into smaller chunks)
- Pre-processing css using pre-processors like scss or less

It is worth noting that Webpack is used in modern front end frameworks like React and Vue to accomplish the above tasks. 

# Entry and Entry Points 
This tells webpack where to look when starting to build the bundle (and dependency graphs).
