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


## Styling variables

```
--t-search-user-menu-btn-bg-color               (Dropdown trigger button background color)
--t-search-user-menu-btn-bg-color-inversed      (Dropdown trigger button background color inversed)
--t-search-user-menu-btn-padding                (Dropdown trigger button padding)
--t-search-user-menu-btn-border-color           (Dropdown trigger button border color)
--t-search-user-menu-btn-border-color-inversed  (Dropdown trigger button border color inversed)
--t-search-user-menu-btn-font-size              (Dropdown trigger button font size)
--t-search-user-menu-btn-color                  (Dropdown trigger button text color)
--t-search-user-menu-btn-color-inversed         (Dropdown trigger button text color inversed)
--t-search-user-menu-btn-min-width              (Dropdown trigger button text min width)
--t-search-user-menu-btn-max-width              (Dropdown trigger button text max width)
``` 
```
--t-search-user-icon-button-width               (Dropdown trigger button icon width)
--t-search-user-icon-button-height              (Dropdown trigger button icon height)
--t-search-user-icon-button-padding             (Dropdown trigger button icon padding)
--t-search-user-icon-button-icon-color          (Dropdown trigger button icon color)
--t-search-user-icon-button-icon-color-inversed (Dropdown trigger button icon color inversed)
```
```
--t-search-user-icon-width                      (Component default icon width)
--t-search-user-icon-height                     (Component default icon height)
--t-search-user-icon-color-inversed             
```
```
--t-search-user-item-min-height                 (Dropdown list item min height)
--t-search-user-item-color                      (Dropdown list item text color)
--t-search-user-item-icon-color                 (Dropdown list item icon color)
--t-search-user-item-icon-color-inversed        (Dropdown list item icon color inversed)
--t-search-user-item-selected-weight            (Dropdown list item selected font weight)
--t-search-user-item-selected-color             (Dropdown list item selected text color)
--t-search-user-item-selected-bg                (Dropdown list item selected background color)
--t-search-user-item-focused-color              (Dropdown list item focused text color)
--t-search-user-item-focused-bg                 (Dropdown list item focused background color)
--t-search-user-item-hover-color                (Dropdown list item hover color)
```
```
--t-search-user-modal-max-width                 (Popup max width)
```
```
--t-search-user-input-padding                           (Search input padding)
--t-search-user-input-border                            (Search input border color)
--t-search-user-input-width                             (Search input width)
--t-search-user-input-underline-focused-border-color    (Search input focused underline border color)
```
```
--t-search-user-button-bg-color                         (Button background color)
--t-search-user-button-color                            (Button text color)
```
```
--t-search-user-border-color                            (Default border color)
--t-search-user-result-page-selected-bg                 (Pagination selected background color)
--t-search-user-result-page-selected-border-color       (Pagination selected border color)
```
