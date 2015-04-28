# list-block

The `list-block` object simply creates blocky lists from `ul`s or `ol`s.

## Dependencies

The `list-block` object depends on two other modules:

* [settings.defaults](https://github.com/treeframework/settings.defaults)
* [tools.functions](https://github.com/treeframework/tools.functions)

If you install the `list-block` object using Bower or npm, you will get these 
dependencies at the same time. If not using Bower or npm, please be sure to 
install and `@import` these dependencies in the relevant way.


## Instalation

You can install the `list-block` module via Bower, npm, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-list-block --save
```

Once installed, `@import` into your project in its Objects layer:

```scss
@import "bower_components/tree-list-block/object.list-block";
```

### Install using npm:

```sh
$ npm install tree-list-block --save
```

### Install via file download

The least recommended option for installation is to simply download
`_object.list-block.scss` into your project and `@import` it into your project 
in its Objects layer.

## Usage

Basic usage of the `list-block` object uses the required classes:

```html
<ul class="o-list-block">
    <li class="o-list-block__item">...</li>
    <li class="o-list-block__item">...</li>
    <li class="o-list-block__item">...</li>
</ul>
```

The only valid children of the `.o-list-block` node is `.o-list-block__item`.

## Options

Other, optional classes can supplement the required base classes:

* `.o-list-block--[tiny|small|large|huge]`: alter the spacing between list-block
items.

For example:

```html
<ul class="o-list-block  o-list-block--large">
    <li class="o-list-block__item">...</li>
    <li class="o-list-block__item">...</li>
    <li class="o-list-block__item">...</li>
</ul>
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
