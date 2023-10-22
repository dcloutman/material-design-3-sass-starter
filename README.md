# Material Design 3 Starter Kit

This repository contains Sass templates in the SCSS format that can be used to generate the foundations of a Material Design 3 system web implementation. The exemplar.html file can be used to preview your changes.

## Making Changes

The default settings, including typography and color, are either taken directly from the Material Design 3 documention or are based off of reasonable deductions from that documemtation. You will almost certainly want to change some or all of the values to meet your design requirements.

All Sass files live in `/src/sass`. Most changes can be made by modifying the values assigned to the variables at the top of each file.

## Compilation

Before your changes will be reflected in `exemplar.html`, you need to compile the Sass files into CSS. The resulting CSS is written to `/public/css/md3.css`. For development / debuggin purposes, you can compile with the command:

```
npm run sass-build
```

If you want a production-ready version of the file, use the command:

```
npm run sass-publish
```

This will produce a minified version of the CSS.

## Exporting CSS

To use the classes created by this project in your own project, simply copy the CSS from `/public/css/md3.css` to your project and `@import` it into your main stylesheet. The `exemplar.html` file may give you additional hints that inform your integration strategy.

## Installation

If you are using this respository for the first time on your machine, don't forget to run:

```
npm install
```

_v0.0.0_
