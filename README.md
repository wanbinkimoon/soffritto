
# Soffritto
An italian frontend boilerplate
![soffritto dependencies testing](https://david-dm.org/wanbinkimoon/soffritto.svg)

## Intro
Soffritto is a basic sass normalizer with a config file to customize your starter base.

## Install
Via `bower`
```
bower install --save soffritto
```
Via `npm`
```
npm install --save soffritto
```

## Usage
### Initialize  
First of all `cd` into the folder and run   
```
npm install
```
Set your custom variables in `build/modules/config.sass`

### Compiling sass
Compile your package with standard human readable `css` running
```
npm run sass
```
Compile as minified `css`
```
npm run sass:min
```
Watch and compile on the fly
```
npm run sass:watch
```

### Test your variables
**Soffritto** can run a local HTTP server using `browser-sync`, to run it just
```
npm run server
```
once the server is running you can choose what display editing the code in `index.html`

##What does it do?
* Preserves useful defaults, unlike many CSS resets.
* Styles in a single config a wide range of elements.
* Corrects bugs and common browser inconsistencies.
* Improves flexibility with subtle variables.
* Explains what code does using detailed comments.

##Browser support
* Chrome (last five)
* Edge (last five)
* Firefox (last five)
* Opera (last five)
* Internet Explorer 8+
* Safari 6+

## Acknowledgements
**Soffritto** is a project by [Nicola Bertelloni](mailto:nicola.bertelloni@gmail.com)
