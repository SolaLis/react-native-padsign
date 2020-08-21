
# react-native-padsign

## Getting started

`$ npm install react-native-padsign --save`

### Mostly automatic installation

`$ react-native link react-native-padsign`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-padsign` and add `RNPadsign.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNPadsign.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.foundrn.padsign.RNPadsignPackage;` to the imports at the top of the file
  - Add `new RNPadsignPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-padsign'
  	project(':react-native-padsign').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-padsign/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-padsign')
  	```


## Usage
```javascript
import RNPadsign from 'react-native-padsign';

// TODO: What to do with the module?
RNPadsign;
```
  