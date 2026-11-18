# NinjaX PRO — releases

Aqui solo viven los APK firmados de NinjaX PRO.

Cada release lleva:

- tag `vX.Y` (la version que muestra la app)
- asset `NinjaX_PRO_X.Y.apk`

El actualizador de la app lee `GET /repos/loKordero90/ninjax-pro-releases/releases/latest`
con un token fine-grained de solo lectura y descarga el asset por la API.
