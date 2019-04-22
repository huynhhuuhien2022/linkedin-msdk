
# react-native-linkedin-msdk

## Getting started

`$ npm install react-native-linkedin-msdk --save`

### Mostly automatic installation

`$ react-native link react-native-linkedin-msdk`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-linkedin-msdk` and add `RNLinkedinMsdk.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNLinkedinMsdk.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNLinkedinMsdkPackage;` to the imports at the top of the file
  - Add `new RNLinkedinMsdkPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-linkedin-msdk'
  	project(':react-native-linkedin-msdk').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-linkedin-msdk/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-linkedin-msdk')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNLinkedinMsdk.sln` in `node_modules/react-native-linkedin-msdk/windows/RNLinkedinMsdk.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Linkedin.Msdk.RNLinkedinMsdk;` to the usings at the top of the file
  - Add `new RNLinkedinMsdkPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNLinkedinMsdk from 'react-native-linkedin-msdk';

// TODO: What to do with the module?
RNLinkedinMsdk;
```
  