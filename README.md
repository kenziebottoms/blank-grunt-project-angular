# Blank Grunt project

An empty Grunt-running setup including:

![](https://img.shields.io/badge/updated-july_27th_2018-green.svg)
![](https://img.shields.io/badge/grunt-v1.0.3-yellow.svg)
![](https://img.shields.io/badge/angularJS-v1.7.2-D00027.svg)
![](https://img.shields.io/badge/jquery-v3.3.1-005FAD.svg)
![](https://img.shields.io/badge/lodash-v4.17.10-3554FF.svg)

# Using this repo

### Initialize an `npm` project for use with Grunt

In the root:

```bash
npm init -y
```

`-y` says yes to every question `npm init` would otherwise ask you.

### Install necessary `npm` modules

These are listed as dependencies in `package.json` already.

```bash
npm install
```

### Run the server

```bash
hs -o
```

### File structure

```
root
 |--assets
 |   |--css
 |   |
 |   |--js
 |   |   |--ctrl
 |   |   |--data
 |   |   |--factory
 |   |   |--partials
 |   |   |--main.js
 |   |   `--router.js
 |   |
 |   |--sass
 |   |   |
 |   |   `--style.scss
 |   |
 |   `--partials
 |
 |--dist
 |   `--bundle.js
 |
 |--.gitignore
 |--Gruntfile.js
 |--package.json
 `--index.html
```