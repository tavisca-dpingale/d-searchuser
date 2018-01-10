# \<t-searchuser\>



## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Steps
```
npm install -g polymer-cli
```
```
make project folder : mkdir xyz && cd zyz
```
```
create index.html and add below files in head
```
```
<script src="/bower_components/webcomponentsjs/webcomponents-loader.js"></script>
```
```
<link rel="import" href="/bower_components/polymer/polymer.html">
```
```
type command : bower init : to add bower.json
```
```
type command : touch .gitignore : to add gitignore file
```
```
create first element : polymer init
```
```
select polymer-2-element
```
```
polymer serve : to run
```

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

