## Awesome Best practices for Web(frontend/backend)

> A curated list of awesome things related to Vue.js

## Table of Contents
  - [Monorepo](#monorepo)
    - [What is it?](#what-is-it)
    - [Best Practice Monorepo?](#best-practice-monorepo)



## Monorepo

### What is it
A Mono-Repo hosts one or more projects or packages. These packages are 
"Mini-Repos" that can be versioned, built, and published independently. 
Therefore, every package contains its own package.json file due to the 
fact that every package is a full-fledged project on its own. Packages might 
have dependency relations between each other. Managing these dependencies 
are implemented by symlinks. monorepo is a good practice for developing packages 
which has some  connection in a semantic way under one repository which helps alot 
to make our code more re-use-able and manageable. There are lots of projects which are using 
monorepo like vue-cli, bablejs, react, etc...

### Best Practice Monorepo

You can use this github project, which has a ready to use monorepo and 
great step-by-step article for this purpose. Its also are under active develop to add more features and make it better 
like adding a bootstrapping functionality to it. it will be very good to contribute on it.
https://github.com/SeyyedKhandon/yarn_lerna_jest_typescript
 


