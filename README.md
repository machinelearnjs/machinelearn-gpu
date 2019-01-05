# machinelearn-gpu

machinelearn-gpu is a module to enable GPU acceleration for machinelearn.js projects.

[![Build status](https://ci.appveyor.com/api/projects/status/p8vmgdesb9i5h92h?svg=true)](https://ci.appveyor.com/project/JasonShin/machinelearn-node)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FJasonShin%2Fkalimdorjs.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FJasonShin%2Fkalimdorjs?ref=badge_shield)
[![Slack](https://slack.bri.im/badge.svg)](https://slack.bri.im)

<img src="https://i.imgur.com/CpZA2U7.png">

# User Installation

You must install [machinelearn-node](https://github.com/kalimdorjs/machinelearn-node) first since it is a dependency

```bash
$ yarn add machinelearn-node
```

Using yarn

```bash
$ yarn add machinelearn-gpu
```

Using NPM

```bash
$ npm install --save machinelearn-gpu
```

Then you should require the package in your project

```javascript
require('machinelearn-gpu');
```

Above will enable GPU acceleration provided by [tfjs-node-gpu](https://github.com/tensorflow/tfjs-node)

# Development

We welcome new contributors of all level of experience. The development guide will be added
to assist new contributors to easily join the project.

- You want to participate in a Machine Learning project, which will boost your Machine Learning skills and knowledge
- Looking to be part of a growing community
- You want to learn Machine Learning
- You like Typescript :heart: Machine Learning

# Testing

Testing ensures you that you are currently using the most stable version of Kalimdor.js

```bash
$ npm run test
```

# Supporting

Simply give us a :star2: by clicking on <img width="45" src="https://i.imgur.com/JEOaKBk.png">

# Contributing

We simply follow "fork-and-pull" workflow of Github. Please read CONTRIBUTING.md for more detail.
