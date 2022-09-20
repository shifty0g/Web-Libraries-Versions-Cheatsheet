# Web Libraries Versions Cheatsheet
A Cheatsheet for Discovering Components with Known Vulnerabilities in Web Applications.

Note: I didnt do the inital groundwork im just adding to it. Standing on the shoulder of giants. Thank you @corneacristian.
I will try and add more as i go 

Input the following payloads into Web Browser's Console to check and validate the versions of components used within a specific website

# All in One Special

The idea of this is to slap this badboy in the dev console on a webapp test to get a nice list to validate. Also gives you a nice screenshot for console too 

```
console.log('JQuery Version: ' + $.fn.jquery) & console.log('Lodash Version: ' + _.VERSION) & console.log('Moment Version:  moment.version) & console.log('Angular Version:  angular.version)
```

## jQuery
```
console.log('JQuery Version: ' + $.fn.jquery) 
jQuery().jquery
```
## jQuery UI 
```
$.ui.version
```
```
$.ui
```
## Angular
```
console.log('Angular Version:  angular.version)
```
```
angular.version.full
angular.version
```
## Bootstrap
```
$.fn.tooltip.Constructor.VERSION
```
## Lodash
```
console.log('Lodash Version: ' + _.VERSION)
```
```
_.VERSION
```
## MomentJS
```
console.log('Moment Version:  moment.version) 
```
```
moment.version
```
## ExtJS
```
Ext.version
```
```
Ext.getVersion('extjs')
```
```
Ext.getVersion().version
```
## CKEditor
```
CKEDITOR.version
```
## Vue
```
Vue.version
```
## Highcharts
```
Highcharts.version
```
## Froala Editor
```
$.FE.VERSION
```
```
FroalaEditor.VERSION
```
## DataTablesJS
```
$.fn.dataTable.version
```
```
$.fn.dataTable.versionCheck()
```
## Dojo
```
dojo.version.toString()
```
## Meteor
```
Meteor.release
```
## React
```
React.version
__REACT_DEVTOOLS_GLOBAL_HOOK__.renderers.forEach(r => console.log(`${r.rendererPackageName}: ${r.version}`))
```
## Socket.IO
```
io.version
```
## TinyMCE
```
tinyMCE
```
## EmberJS
```
Ember.VERSION
```
