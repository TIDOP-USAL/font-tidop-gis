# <img src="https://github.com/Viglino/font-tidop-gis/blob/main/svg/globe/uEA82-globe-poi.svg" height="40" /> font-tidop-gis
*Icon font set for use with GIS and spatial analysis tools*

[![](https://img.shields.io/npm/v/font-tidop-gis.svg)](https://www.npmjs.com/package/font-tidop-gis)
![](https://img.shields.io/npm/dt/font-tidop-gis.svg)
![](https://img.shields.io/npm/dw/font-tidop-gis)
![](https://img.shields.io/npm/l/font-tidop-gis.svg)

I've collected in this repo icons and graphics I've been using in my projects.
font-tidop-gis icons and font theme is designed mainly for GIS applications and web mapping tools. 
They can be easily included in a project using the font or svg images.

[See demo page and examples <img src="https://github.com/Viglino/font-tidop-gis/blob/main/svg/search/uEA5F-search-map.svg" height="25" />](https://viglino.github.io/font-tidop-gis/)

## <img src="https://github.com/Viglino/font-tidop-gis/blob/main/svg/routing/uEA8F-timer.svg" height="35" align="left" />Getting started

###  NPM package

font-tidop-gis is availiable on [npm](https://www.npmjs.com/package/font-tidop-gis):
```console
npm install --save font-tidop-gis
```
You can access the font or css in the `./font` and `./css` directory of the package.    
The svg sprites are located in the `./dist/font-tidop-gis.svg` SVG file.

### using font-tidop-gis

You can use font-tidop-gis as a font or as SVG symbols or images.

To use it in a web page, just add the css in your project.
```html
<link href="https://viglino.github.io/font-tidop-gis/css/font-tidop-gis.css" rel="stylesheet" />
```
Then use an inline element with a class prefixed with `ftg-` to add a new icon.    
<img src="https://github.com/Viglino/font-tidop-gis/blob/main/svg/poi/uEA16-poi.svg" height="30" />
<img src="https://github.com/Viglino/font-tidop-gis/blob/main/svg/geom/uEA02-polyline-pt.svg" height="30" />
```html
<!-- prefix: fg - icon name: poi -->
<i class="ftg-poi"></i>
<!-- using a <span> is more semantically correct but a little bit verbose. -->
<span class="ftg-polyline-pt"></span>
```
Or use it as an svg sprite (svg sprites are inlocated in the `./dist/font-tidop-gis.svg` file):    
<img src="https://github.com/Viglino/font-tidop-gis/blob/main/svg/geom/uEA03-polygon-pt.svg" height="30" />
```html
<svg class="font-tidop-gis ftg-3x"><use xlink:href="path/to/dist/font-tidop-gis.svg#ftg-polyline-pt" /></svg>
```

## <img src="https://github.com/Viglino/font-tidop-gis/blob/main/svg/edit/uEA51-copy-poly.svg" height="35" align="left" />Contributing
Please use the [GitHub issue tracker](https://github.com/Viglino/font-tidop-gis/issues) to ask for new features 
or create a pull request.    
Font is created from the files in the `./svg` folder, you only have to create a new file in this folder. 
Use the `./templates/template.svg` template to create a new icon.  
You can add a new glyph in the [font-tidop-gis.json](https://github.com/Viglino/font-tidop-gis/blob/main/font-tidop-gis.json) file with a theme and search tags 
(other fields will be filled automatically).

Your contribution will be published under [font-tidop-gis license](https://github.com/Viglino/font-tidop-gis/blob/main/LICENSE.md) as per [GitHub's terms of service](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license).

If you wan't to build the font and create the dist, use the build script (run `npm install` to install the dev dependencies before):
```console
npm run build
```
Use a local server (http://localhost:8181/) to see result on the page:
```console
npm start
```


## <img src="https://github.com/Viglino/font-tidop-gis/blob/main/svg/map/uEA7A-map-book.svg" height="35" align="left" />Licenses

**font-tidop-gis is licensed under [Apache-2.0](https://github.com/Viglino/font-tidop-gis/blob/main/LICENSE-APACHE.md)**    
Copyright (c) 2021 Jean-Marc Viglino

[font-tidop-gis](https://viglino.github.io/font-tidop-gis/) is free, open source, and GPL friendly. 
You can use it for commercial projects, open source projects, or really almost whatever you want.
[Read full font-tidop-gis license](https://github.com/Viglino/font-tidop-gis/blob/main/LICENSE.md)

Dual-license can be used for each specific part:
* font-tidop-gis **font** is licensed under the [SIL OFL 1.1 License](https://github.com/Viglino/font-tidop-gis/blob/main/LICENSE-OFL.md)
* **Icons** and **SVG** files are licensed under the [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)
* **Codes** and all non font or icon files are licensed under the [MIT License](https://github.com/Viglino/font-tidop-gis/blob/main/LICENSE-MIT.md)

Attribution is required by Apache, MIT, SIL OFL, and CC BY licenses. font-tidop-gis files already 
contain embedded comments with sufficient attribution, so **you shouldn't need to 
do anything additional when using these files normally**.

## <img src="https://github.com/Viglino/font-tidop-gis/blob/main/svg/map/uEB2B-story-maps.svg" height="35" align="left" />Press

* [GIS-Symbole gesucht? font-tidop-gis!](https://geoobserver.wordpress.com/2021/05/06/gis-symbole-gesucht-font-tidop-gis/)
* [GIS-Symbole gesucht? font-tidop-gis! | #geoObserver](https://osgis.org/2021/05/gis-symbole-gesucht-font-tidop-gis-geoobserver/)
* [Geotribu: Revue de presse du 7 mai 2021](https://static.geotribu.fr/rdp/2021/rdp_2021-05-07/#font-tidop-gis)
* [OSGeo icon set](https://wiki.osgeo.org/wiki/OSGeo_icon_set)
