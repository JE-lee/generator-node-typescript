# TypeScript NodeJS Generator
[![Build Status](https://secure.travis-ci.org/ospatil/generator-node-typescript.png?branch=master)](https://travis-ci.org/ospatil/generator-node-typescript)
[![npm version](https://badge.fury.io/js/generator-node-typescript.svg)](http://badge.fury.io/js/generator-node-typescript)

Bonjour! I'm a minimal [Yeoman](http://yeoman.io) generator for creating NodeJS packages using TypeScript. I let you quickly setup a project with latest available tools and best practices.

I use:

- _npm_ - as task runner.
- _jest_ - as [testing and coverage framework](https://facebook.github.io/jest/) to write specs in **TypeScript** itself. You can choose to use _mocha_ or _ava_ instead.

You want to know if you can change any of these? Of course, why not? It is your package after all. I simply get down to business of generating, no questions asked and then quiety get out of the way!

## Usage

Install `generator-node-typescript` globally from this repo. It may take a couple minutes.

```sh
$npm install -g git://github.com/JE-lee/generator-node-typescript.git 
```

Create a new directory and `cd` into it.

```sh
$mkdir my-new-project && cd $_

```

Run the generator.

```sh
$yo node-typescript
```

You can choose to use _mocha_ as your test framework using command - `$yo node-typescript --mocha`

You can choose to use _ava_ as your test framework using command - `$yo node-typescript --ava`

Generate a new class and test file.

```sh
$yo node-typescript:classlib MyNewClass [--mocha | --ava]
```

## License

MIT
