# react-native-qq-share-module

## Getting started

`$ npm install react-native-qq-share-module --save`

### Mostly automatic installation

`$ react-native link react-native-qq-share-module`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-qq-share-module` and add `QqShareModule.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libQqShareModule.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.QqShareModulePackage;` to the imports at the top of the file
  - Add `new QqShareModulePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-qq-share-module'
  	project(':react-native-qq-share-module').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-qq-share-module/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-qq-share-module')
  	```


## Usage
```javascript
import QqShareModule from 'react-native-qq-share-module';

// TODO: What to do with the module?
QqShareModule;
```
