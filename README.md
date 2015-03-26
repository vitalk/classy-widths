# Classy Widths

Human-readable width classes for 12-column grid. These are used in conjunction
with other objects and abstractions.

## Installation

The recommended installation method is a [bower](http://bower.io).

```shell
bower install --save classy-widths
```

# Usage

Mixin `.classy-widths-setup(@namespace)` allows you to generate a series of
width classes (`.onecol`, `.twocol`, etc.) for sizing UI components.

Variable | Description
---|---
`@classy-widths-namespace` | Namespace uses for class names.


## Responsive widths classes

Use `classy-media-queries` package to create responsive widths classes:

```less
@import 'classy-media-queries/defaults.media-queries.less';
@import 'classy-widths/generic.widths.less';


@media @laptop {
    .classy-widths-setup(lap-);
}
```

## License

Licensed under the [MIT license](http://mit-license.org/vitalk).
