# font-tidop-gis
*Icon font set for use with GIS and spatial analysis tools*


I've collected in this repo icons and graphics I've been using in my projects.
font-tidop-gis icons and font theme is designed mainly for GIS applications and web mapping tools. 
They can be easily included in a project using the font or svg images.


## Getting started

###  NPM package

font-tidop-gis is availiable on [npm](https://www.npmjs.com/package/font-tidop-gis):
```console
npm install --save font-tidop-gis
```
You can access the font or css in the `./font` and `./css` directory of the package.    
The svg sprites are located in the `./dist/font-tidop-gis.svg` SVG file.

### using font-tidop-gis

You can use font-tidop-gis as a font or as SVG symbols or images.

Use an inline element with a class prefixed with `ftg-` to add a new icon.    
```html
<!-- prefix: fg - icon name: poi -->
<i class="ftg-poi"></i>
<!-- using a <span> is more semantically correct but a little bit verbose. -->
<span class="ftg-polyline-pt"></span>
```

