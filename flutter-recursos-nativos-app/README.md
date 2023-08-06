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

Cambios en Android Manifest (website url) e info.plist (iOS) (FlutterDeepLinkingEnabled true)

Agregar capacidades de la app (iOS) (Associated Domains) (Puede durar 1 dia en funcionar)

## Pruebas IOS
```
xcrun simctl openurl booted https://pokemon-deep-linking-app.up.railway.app/pokemons/10/

xcrun simctl openurl booted https://pokemon-deep-linking-app.up.railway.app/pokemons
```

## Cambiar API Keys de Google Maps https://pub.dev/packages/google_maps_flutter

## Generador de Código ( ISAR, Riverpod )
```
dart run build_runner build
flutter pub run build_runner build

flutter pub run build_runner watch

```

