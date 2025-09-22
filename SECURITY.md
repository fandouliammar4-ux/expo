iretur
{ StatusBar } from 'expo-status-bar';
import { StyleSheet, Text, View, TextInput, Button } from 'react-native';
import { useState } from 'react';

export default function App() {
  const [phone, setPhone] = useState("");

  return (
    <View style={styles.container}>
      <Text style={{fontSize: 24, marginBottom: 20}}>تسجيل الدخول</Text>
      <TextInput 
        style={styles.input}
        placeholder="اكتب رقم الهاتف"
        keyboardType="phone-pad"
        value={phone}
        onChangeText={setPhone}
      />
      <Button title="دخول" onPress={() => alert("رقمك: " + phone)} />
      <StatusBar style="auto" />
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: '#fff',
    alignItems: 'center',
    justifyContent: 'center',
  },
  input: {
    borderWidth: 1,
    borderColor: "#ccc",
    padding: 10,
    width: "80%",
    marginBottom: 20,
    borderRadiu# Security Policy

## Reporting a Vulnerability

Instead of opening a GitHub issue for security vulnerabilities, refer to our security.txt: https://expo.dev/.well-known/security.retur
tab
