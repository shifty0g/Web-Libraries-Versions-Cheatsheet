# Web Libraries Versions Cheatsheet
A Cheatsheet for Discovering Components with Known Vulnerabilities in Web Applications.

Note: I didnt do the inital groundwork im just adding to it. Standing on the shoulder of giants. Thank you @corneacristian.
I will try and add more as i go 

Input the following payloads into Web Browser's Console to check and validate the versions of components used within a specific website

## All in One Special

The idea of this is to slap this badboy in the dev console on a webapp test to get a nice list to validate. Also gives you a nice screenshot for console too 


## jQuery
```js
console.log('JQuery Version: ' + $.fn.jquery) 
```
```js
jQuery().jquery
```
## jQuery UI 
```js
$.ui.version
```
```js
$.ui
```
## Angular
```js
console.log('Angular Version:  angular.version)
```
```js
angular.version.full
```
```js
angular.version
```
## Bootstrap
```js
$.fn.tooltip.Constructor.VERSION
```
## Lodash
```js
console.log('Lodash Version: ' + _.VERSION)
_.VERSION
```
## MomentJS
```js
console.log('Moment Version:  moment.version) 
moment.version
```
## ExtJS
```js
Ext.version
```
```js
Ext.getVersion('extjs')
```
```js
Ext.getVersion().version
```
## CKEditor
```js
CKEDITOR.version
```
## Vue
```js
Vue.version
```
## Highcharts
```js
Highcharts.version
```
## Froala Editor
```js
$.FE.VERSION
```
```js
FroalaEditor.VERSION
```
## DataTablesJS
```js
$.fn.dataTable.version
```
```js
$.fn.dataTable.versionCheck()
```
## Dojo
```js
dojo.version.toString()
```
## Meteor
```js
Meteor.release
```
## React
```js
React.version
```
With React Dev Tools 
```js
__REACT_DEVTOOLS_GLOBAL_HOOK__.renderers.forEach(r => console.log(`${r.rendererPackageName}: ${r.version}`))
```
## Socket.IO
```js
io.version
```
## TinyMCE
```js
tinyMCE
```
## EmberJS
```js
Ember.VERSION
```
## Core-JS
```js
window['__core-js_shared__'].versions
```
```js
global['__core-js_shared__'].versions
```
