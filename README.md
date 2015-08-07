#Static Build Tool

This builder is made to help create a pegboard skin employing the DRY concept of coding.

##Setup in terminal
- `sudo npm install` *can take a few mins*
- `sudo bower install`
- `gulp`
- upload the `render/` folder to the skins folder in pegboard

##Assets 
- found under `cwd/assets/*` 
- convert to `render/assets/*`

##HTML
Using the same structure for pegboard.
- Layouts
- Pages
- Collections
- Emails
- Forms

##Frameworks 
- [Bower](http://bower.io/)
- [gulpjs](http://gulpjs.com/)
- [sass](sass link here)
- [Npm](https://www.npmjs.com/)
- [Nodejs](https://nodejs.org/)


###Includes
found under `cwd/includes` set as base for includes here is some example include code
```
			@@include('h1.html',{
                "text": "Hello World"
                })
``` 
Html includes allow variables like so this would be `h1.html`
```html
<h1>@@text</h1>
```
This would render
```html
<h1>Hello World</h1>
```

##Less
bootstrap less files and your less files are concatnated from
`cwd/assets/less/*.less`
`bower_components/less/*less` = `render/skin.css`
##Js
bootstrap js files and your js files are concatnated from
`cwd/assets/js/*.js`
`bower_components/js/*js` = `render/skin.css`


##Gulp
###Commands
<<<<<<< HEAD
Only 1 command so far `gulp`
*more coming soon*

###Installation Progress###
Install node.js (windows, linux, mac)
- npm install
- bower install
- gulp
- gulp watch
Dependiences

=======
 - `gulp` 
