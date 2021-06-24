# react-native-cache-manager



## Getting started

Add to your package.json:

`"react-native-cache-manager": "izetmolla/react-native-cache-manager"`

### Mostly automatic installation

No need to link as of RN 0.60.

## Usage
```javascript
import ClearCache from 'react-native-cache-manager';

// get the storage usage
ClearCache.getAppCacheSize(data => {
  alert(data) // will show the App's storage usage in the app's cache.
});


// clear the storage
ClearCache.clearAppCache(data => {
  alert(data) // will alert the new size
});
```
