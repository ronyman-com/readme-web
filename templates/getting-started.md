# Getting Started

## Install readME from npm

```bash
mkdir Mydoc
cd Mydoc
npm init
```


## your packack.json look like this


```base
{
  "name": "reade-web",
  "version": "1.0.0",
  "description": "readME document site",
  "main": "index.js",
  "scripts": {
    "test": "test",
    "start": "readme start",
    "build": "readme build"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/ronyman-com/readME.git"
  },
  "keywords": [
    "readme",
    "ronyman"
  ],
  "author": "Rony MAN",
  "license": "MIT",
  "bugs": {
    "url": "https://github.com/ronyman-com/readME/issues"
  },
  "homepage": "https://github.com/ronyman-com/readME#readme",
  "dependencies": {
    "readme-framework": "^1.0.1"
  }
}

```

## Install readME from npm

```bash
npm install -g readme-framework

```
## Install readME from GitHub.
To get started, clone the repository and install the dependencies:

```bash
git clone https://github.com/ronyman-com/readME
cd readME
npm install
```

## Build and Start Server.

```bash
readme build templates
readme start
```