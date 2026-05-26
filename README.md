# Camera SAMBA 📱🎥

Aplicación móvil Flutter para usar tu celular como cámara profesional inalámbrica con **SAMBA Engine**.

Parte del ecosistema **BlackMagikBox**.

## Funcionalidades

- Transmisión de video en vivo vía **WHIP/WebRTC**
- Códec H.264 con aceleración hardware
- Conexión por código QR
- Orientación landscape/portrait dinámica
- Linterna (torch)
- Baja latencia (<100ms)

## Requisitos

- Android 10+ (API 29)
- SAMBA Engine corriendo en la misma red WiFi

## Build

```bash
flutter pub get
flutter build apk --release
```

El APK se genera en `build/app/outputs/flutter-apk/app-release.apk`.

## Licencia

Propietaria — BlackMagikBox
