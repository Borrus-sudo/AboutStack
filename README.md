<p align="center">
<img width="100px" src="https://api.iconify.design/logos:stackshare.svg" align="center" alt="awesome-stack hero icon" />
<h1 align="center">awesome-stack</h1>
<p align="center">⚡ Github Readme Stats for your favourite web dev stack.</p>
  <p align="center">
    <img src="https://github.com/Borrus-sudo/awesome-stack/actions/workflows/test.yml/badge.svg" align="center" alt="Test Badge" />
    <img src="https://img.shields.io/github/issues/Borrus-sudo/awesome-stack" align="center" alt="Issue Badge" />
    <img src="https://img.shields.io/github/stars/Borrus-sudo/awesome-stack" align="center" alt="Stars Badge" />
  </p>
</p>

<br/>

## Features:
🌈Supports a wide Variety Of themes and has high-quality icons for all your favorite tech  <br/>
🛠 Analyzes the most used technologies, frameworks, toolings, and figures out the most used stuff <br/>
🗂 Easy to get started with and creates a card based on it! <br/>
☄ Prevents the readme from cluttering by requiring you to put a simple link

## Why?

Existing GitHub readme stats do not showcase the specific favorite technologies/tools. So here comes my app. It analyzes your repositories and figures the most used toolings and framework. Based on the analyzed data, it creates a card. Currently, only javascript tooling and ecosystem are supported. More coming in the future.

## awesome-stack supports all these things :
![image](https://user-images.githubusercontent.com/58482194/129444524-1ee688b5-8b4d-47c7-9c0d-cbbc565a1cee.png)

## Themes 
https://github.com/Borrus-sudo/awesome-stack/blob/master/src/utils/themes.js
All themes of @anuraghazra github-readme-stats are supported.

## Endpoint:

` /api/v1/cards?name=your-github-username&repos=comma,separated,repos,upto,5&theme=your-theme`

Add this in your markup:
```markdown
![MyAwesomeWebDevStack](https://awesome-stack.glitch.me/api/v1/cards?name=Borrus-sudo&repos=jsgandalf,vue-generator-graph,awesome-stack&theme=dracula)
```
## Examples
![Example 1](./examples/Borrus-sudo.svg)
![Example 2](./examples/bencodezen.svg)

## Setup

```
yarn install
```

## Lint

```
yarn lint
```

## Test

```
yarn test
```

## Development

```
yarn dev
```

# Support me

Starring this repo shall encourage me to do more open sourcing. So consider starring!

# TO-DO

- Acquiring a GitHub API key

## Important note
CJ is not a contributor. Due to a weird shit mistake or bug (IDK), his name is appearing in the contributor list cause I used his create-express-API boilerplate and messed up in some steps.
