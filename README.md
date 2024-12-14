Install: 
```js
npm install react-native-color-gradient
```
<p align="center">
     <img src="image/preview.png" alt="Alt text" width="250" height="250">
</p>
![Supports Android, iOS, macOS, Windows and Web](https://img.shields.io/badge/platforms-android%20|%20ios%20|%20macos%20|%20windows%20|%20web-lightgrey.svg) ![MIT License](https://img.shields.io/npm/l/@react-native-community/netinfo.svg) [![Lean Core Extracted](https://img.shields.io/badge/Lean%20Core-Extracted-brightgreen.svg)](https://github.com/facebook/react-native/issues/23313)
Example :
```tsx
import { StyleSheet, SafeAreaView, View } from 'react-native'
import React from 'react'
import Picker from 'react-native-color-gradient'
export default function App() {
  return (
    <SafeAreaView style={styles.container}>
      <View style={styles.box}>
        <Picker width={300} />
      </View>
    </SafeAreaView>
  )
}

const styles = StyleSheet.create({
  container: { flex: 1 },
  box: { flex: 1, justifyContent: 'center', alignItems: 'center' }
})
```
| Prop                         | Type         | Default | Description                                                                                                                                                      |
| ---------------------------- | ------------ | ------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| width | number      | 100    | set the diameter of the hexagon  |
 