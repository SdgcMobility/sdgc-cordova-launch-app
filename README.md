---
Launch any installed App on the device being used. Takes Package ID as input. No action performed if package ID not found.
---

### Usage

Should be called after the deviceready event is fired. See exmaple below

```Javascript 
window.OpenApplication("com.package.name"); 

Note: This should be called after *deviceready* is fired, for example:
```javascript
var openFn = function() {
   window.OpenApplication(app_package);
};
document.addEventListener('deviceready', openFn, false);
```

### Installation
```
cordova plugin add sdgc-cordova-launch-app
```

### Licence

Released under Apache License 2.0.

