import { StatusBar } from 'expo-status-bar';
import React from 'react';
import { StyleSheet, Text, View, ScrollView } from 'react-native';
 
function App(){
  return(
    <View style={styles.container}>
    <Text style={styles.textoPrincipal}>Testando as primeiras informações
    </Text>
    <Text style={styles.alinharTexto}>Trabalhando com estilos
    </Text>
    </View>
  )
}
const styles=StyleSheet.create({
  container:{
    marginTop:20
  },
  textoPrincipal:{
    color:"red",
    fontSize:20
  },
  alinharTexto:{
  textAlign:"center"  
  },
})
export default App;
