## jQuery Mobile Flat-UI Theme

Theme for jQuery Mobile based on [Flat-UI](http://designmodo.com/demo/flat-ui/).

## Demo

[http://ququplay.github.com/jquery-mobile-flat-ui-theme](http://ququplay.github.com/jquery-mobile-flat-ui-theme)

## Versions

We are going to use master branch to keep up to date with jQuery Mobile versions. Previous versions will be moved to corresponding branches.

### Current branch layout

- master - jQuery Mobile version 1.3.1
- jqm-1.3.0 - jQuery Mobile version 1.3.0

## Usage

Copy `jquery.mobile.flatui.css`, fonts and images from `generated` folder to your project.
Include link to `jquery.mobile.flatui.css`

```html
 <link rel="stylesheet" type="text/css" href="jquery.mobile.flatui.css" />
```

![jQuery-Mobile-Flat-UI-Theme](http://oi46.tinypic.com/xm2xlc.jpg)


## Setup

In order to add a new swatch or colors you can add a new stylus file under `src/stylus/swatches/` and run [grunt](http://gruntjs.com/) from your command line.

- brew install node
- npm install -g grunt-cli
- cd to project's folder
- npm install
- grunt watch
- start modifying css/stylus files

## Notes

The current work is based on jQuery Mobile v1.3. This is still a work in progress. Please don't be afraid to report any issues you will find.

## Contributors

* [@tomkuk](http://github.com/tomkuk)
* [@mkuklis](http://github.com/mkuklis)

##License:

[The WTFPL License](http://en.wikipedia.org/wiki/WTFPL)

