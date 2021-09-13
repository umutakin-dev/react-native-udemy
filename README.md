# React-Native

## Course

[React Native - The Practical Guide (2021)](https://www.udemy.com/course/react-native-the-practical-guide)

## What is React Native?

**React.js**  
A Javascript Library for building user interfaces  
Typically used for Web Development  
ReactDOM.render(...) adds the web support!  
React itself is platform agnostic  

**React Native**  
A collection of "special" React components.  
Components compiled to Native Widgets  
Native Platform APIs exposed to JavaScript  
Connects JS and Native Platform Code  

**Real Native Mobile Apps**  
IOS  
Android  

## Behind the Scenes

**React + React Native App**  

 ```javascript
 const App = props => {
     return {
        <View>
            <Text>Hello There!</Text>
        </View>
     };
 }
 ```

=> Compiled To **REAL NATIVE APP** (Views are compiled)  

## More Details

### React for the Web

<div>  
<input>  

### Native Component (Android)

android.view  
EditText  

### Native Component (iOS)

UIView  
UITextField  

### React Native

<View>  
<TextInput>  

## Add the JS Part/Our Logic?

UI  
Components exposed by React Native  
**Compiled to Native Views**  

Logic
Written by us, in JS  

JavaScript thread hosted by React Native App  
**NOT Compiled**  

## A Look Behind the Scenes

### Our React Native Code

Views  
Javascript Code  

### Native App/Native Platform

Compiled Views
Javascipt Code -> Javascipt Core <-> Bridge <- Native Platform Modules/APIs  
