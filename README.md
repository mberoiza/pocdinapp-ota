# pocdinapp-ota

Repositorio de bundles OTA para la aplicación móvil PocDinApp.

## Estructura

- `api/` - Endpoint de versiones (version.json)
- `bundles/android/` - Bundles para Android
- `bundles/ios/` - Bundles para iOS

## Uso

Este repositorio está configurado para servir bundles OTA a través de GitHub Pages.

El endpoint de versiones está disponible en:
`https://mberoiza.github.io/pocdinapp-ota/api/version.json`

## Deployment

Usa el script `deploy-ota-github.ps1` desde el repositorio principal para generar y desplegar nuevos bundles.
