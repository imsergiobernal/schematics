<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>

  <p align="center">A progressive <a href="http://nodejs.org" target="blank">Node.js</a> framework for building efficient and scalable server-side applications, heavily inspired by <a href="https://angular.io" target="blank">Angular</a>.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore"><img src="https://img.shields.io/npm/v/@nestjs/schematics.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore"><img src="https://img.shields.io/npm/l/@nestjs/schematics.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore"><img src="https://img.shields.io/npm/dm/@nestjs/schematics.svg" alt="NPM Downloads" /></a>
  <a href="https://coveralls.io/github/nestjs/nest?branch=master" target="_blank"><img src="https://coveralls.io/repos/github/nestjs/nest/badge.svg?branch=master#9" alt="Coverage" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg"/></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow"></a>

## Description

In order to help people manage their projects, the CLI tool has been created. It helps on many grounds at once, from scaffolding the project to build well-structured applications. The Nest CLI is based on the [@angular-devkit](https://github.com/angular/devkit) package. Also, there're special schematics that are dedicated to the Nest development [@nestjs/schematics](https://github.com/nestjs/schematics).


## Installation
### NPM:

```
$ npm install -g @nestjs/schematics
```

### Docker:
```
$ docker pull nestjs/cli[:version]
$ docker run -it -rm -p 3000:3000 -v $(pwd)/workspace nestjs/schematics[:version]
```

### GIT:
```
$ git clone https://github.com/nestjs/schematics.git <project>
$ cd <project>
```

With your Node runtime:
```
$ npm install
$ npm link
```

With Docker:

```
$ docker build -t nestjs/schematics .
```

## Usage

Learn more in the [official documentation](https://docs.nestjs.com/).

## Stay in touch

* CLI Author - [Thomas Ricart](https://github.com/ThomRick) and [Kamil Mysliwiec](https://github.com/kamilmysliwiec)
* Website - [https://nestjs.com](https://nestjs.com/)
* Twitter - [@nestframework](https://twitter.com/nestframework)
