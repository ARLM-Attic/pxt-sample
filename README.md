# Sample target for KindScript

# Getting started

> If you're making changes to kindscript repository itself, proceed to **Local installation** below.

* Clone this repo and run

```
npm install
```

* Install the `KindScript` tool and launch the local server:

```
npm install -g kindscript-cli
kind serve
```
To re-build the `built/target.json` file, re-run `kind serve`.


## Local installation

* Clone and build [KindScript](https://github.com/Microsoft/kindscript) in a `kindscript` folder.
* Clone this repo  in a `kindscript-microbit` folder next to `kindscript`

```
npm install
```
* To build and deploy new changes

```
npm install -g kindscript-cli
cd ../kindscript
jake
cd ../kindscript-microbit
npm link ../kindscript
```
* run this command to build and launch a local editor

```
kind serve
```
* open `localhost:3232` to try your editor!