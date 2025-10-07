import * as React from 'react';
import { View, ImageBackground, Pressable, StyleSheet, StatusBar, Dimensions } from 'react-native';
import { NavigationContainer } from '@react-navigation/native';
import { createNativeStackNavigator } from '@react-navigation/native-stack';

const Stack = createNativeStackNavigator();

// IMPORT DAS IMAGENS (usando os assets enviados no Snack)
const IMG1 = require('./assets/screen1.png');
const IMG2 = require('./assets/screen2.png');
const IMG3 = require('./assets/screen3.png');

// Helpers: pega tamanho da tela para posicionar hotspots por porcentagem
const { width: W, height: H } = Dimensions.get('window');
const pct = (p, base) => Math.round((p/100) * base);

// ⚠️ Ajuste fino dos hotspots (em porcentagem da tela)
// Se a seta/botão ficar um pouco fora, mexa nesses números:
const HOTSPOTS = {
  // Tela 1: seta → (canto inferior direito)
  screen1_arrow: {
    leftPct: 72,   // quão à direita
    topPct: 72,    // quão pra baixo
    widthPct: 18,  // tamanho da área clicável
    heightPct: 18,
  },
  // Tela 2: botão "Cadastre-se" (último card/botão)
  screen2_cadastrese: {
    leftPct: 6,
    topPct: 66,
    widthPct: 88,
    heightPct: 12,
  },
  // Tela 3: seta ← (canto superior esquerdo)
  screen3_back: {
    leftPct: 4,
    topPct: 6,
    widthPct: 14,
    heightPct: 8,
  },
};

function Hotspot({ cfg, onPress }) {
  const style = {
    position: 'absolute',
    left: pct(cfg.leftPct, W),
    top: pct(cfg.topPct, H),
    width: pct(cfg.widthPct, W),
    height: pct(cfg.heightPct, H),
  };
  return <Pressable onPress={onPress} style={[style, styles.hit]} android_ripple={{borderless:true}} />;
}

function Screen1({ navigation }) {
  return (
    <View style={styles.container}>
      <StatusBar hidden />
      <ImageBackground source={IMG1} style={styles.bg} resizeMode="cover">
        <Hotspot
          cfg={HOTSPOTS.screen1_arrow}
          onPress={() => navigation.navigate('Screen2')}
        />
      </ImageBackground>
    </View>
  );
}

function Screen2({ navigation }) {
  return (
    <View style={styles.container}>
      <StatusBar hidden />
      <ImageBackground source={IMG2} style={styles.bg} resizeMode="cover">
        <Hotspot
          cfg={HOTSPOTS.screen2_cadastrese}
          onPress={() => navigation.navigate('Screen3')}
        />
      </ImageBackground>
    </View>
  );
}

function Screen3({ navigation }) {
  return (
    <View style={styles.container}>
      <StatusBar hidden />
      <ImageBackground source={IMG3} style={styles.bg} resizeMode="cover">
        <Hotspot
          cfg={HOTSPOTS.screen3_back}
          onPress={() => navigation.navigate('Screen2')}
        />
      </ImageBackground>
    </View>
  );
}

export default function App() {
  return (
    <NavigationContainer>
      <Stack.Navigator screenOptions={{ headerShown: false, animation: 'slide_from_right' }}>
        <Stack.Screen name="Screen1" component={Screen1} />
        <Stack.Screen name="Screen2" component={Screen2} />
        <Stack.Screen name="Screen3" component={Screen3} />
      </Stack.Navigator>
    </NavigationContainer>
  );
}

const styles = StyleSheet.create({
  container: { flex: 1, backgroundColor: '#000' },
  bg: { flex: 1, width: '100%', height: '100%' },
  // DEBUG: deixe opacity:0.2 para ver o retângulo da área clicável e ajustar.
  hit: { /* backgroundColor: 'rgba(255,0,0,0.15)' */ },
});
