/**
 * Sample React Native App
 * https://github.com/facebook/react-native
 *
 * @format
 * @flow strict-local
 
 ИФРЕЙМ 
 
 */

import React from 'react';
import {
  SafeAreaView,
  StyleSheet,
  ScrollView,
  View,
  Text,
  StatusBar,
} from 'react-native';
import { WebView } from 'react-native-webview';



const App: () => React$Node = () => {
  return (
    <>
      <View style={styles.conatiner}>
        <WebView source={{ uri: 'https://nofikoff.github.io/js-redirect4app/' }} />
      </View>
    </>
  );
};

const styles = StyleSheet.create({
  conatiner: {
    flex: 1
  }
});

export default App;
