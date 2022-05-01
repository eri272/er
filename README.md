import{ StatusBar} from 'expo-status-bar';
import React from 'react';
import {StyleSheet,  Text, View} from 'react-native';
import {NavigationContainer} from '@react-navigation/native';
import {crateBottomTabNavigator, crateBottomTabNavigator} from '@react-navigation/battom-tabs'
import{webView} from 'react-native-webview';





function Tela01(){
  return(
    <webView source= {{uri: 'https://www.youtube.com/'}}></webView>
  );
}
