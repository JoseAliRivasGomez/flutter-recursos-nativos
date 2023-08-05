# Miscelaneos

Renombrar App ID
```
flutter pub run change_app_package_name:main com.joserivasgomez.recursosnativos
```

sha-256 (Play Store o con cd android y ./gradlew signingReport (usar 1 de debug en development))
```
cd android
./gradlew signingReport
```


## Pruebas IOS
```
xcrun simctl openurl booted https://pokemon-deep-linking.up.railway.app/pokemons/1/

xcrun simctl openurl booted https://pokemon-deep-linking.up.railway.app/pokemons
```

## Cambiar API Keys de Google Maps


## Generador de Código ( ISAR, Riverpod )
```
dart run build_runner build
flutter pub run build_runner build

flutter pub run build_runner watch

```

