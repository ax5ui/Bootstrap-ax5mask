[![axisj-contributed](https://img.shields.io/badge/AXISJ.com-Contributed-green.svg)](https://github.com/axisj)
![](https://img.shields.io/badge/Seowoo-Mondo&Thomas-red.svg)

# bootstrap-ax5mask
"mask" is used for prevent user action during running the application.
> *Dependencies*
> * _[jQuery 1.X+](http://jquery.com/)_
> * _[ax5core](http://ax5.io/ax5core)_


### Install by bower
```sh
bower install bootstrap-ax5mask
```
[bower](http://bower.io/#install-bower) is web front-end package manager

### Install by npm
```sh
npm install jquery
npm install ax5core
npm install bootstrap-ax5mask
```
***
After you download the file in npm install, you will need to copy to the location where you want to use as a resource for the project.
If the inconvenience in the process that you want to copy the file and can be easily copied by using a `gulp` or `grunt`.
***


### Insert the "ax5mask" in the HTML HEAD.

Location of the folder can be determined freely in your project. But be careful not to accidentally caused
exactly the path.
```html
<html>
    <head>
        <link rel="stylesheet" type="text/css" href="../../bootstrap-ax5mask/dist/ax5mask.css" />
    
        <script type="text/javascript" src="../../jquery/jquery.min.js"></script>
        <script type="text/javascript" src="../../ax5core/dist/ax5core.min.js"></script>
        <script type="text/javascript" src="../../bootstrap-ax5mask/dist/ax5mask.min.js"></script>
    </head>
<body>
....
</body>
</html>
```

### Basic Usages
```js
var mask = new ax5.ui.mask();
mask.open();
```

### Preview
- [See Demostration](http://ax5.io/bootstrap-ax5mask/demo/index.html)