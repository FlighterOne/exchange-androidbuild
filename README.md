# ExChange Android

Capacitor-оболочка сайта https://exchangeprojects.site

## Сборка APK (GitHub Actions)

1. Создай репозиторий `exchange-android`
2. Залей файлы из этой инструкции
3. Actions → **Build Android APK** → Run workflow
4. Artifacts → `exchange-android` → `exchange-android.apk`

## Release

git tag v1.0.1
git push origin v1.0.1

APK попадёт в Release.

## index.html (сайт)

android: 'https://github.com/FlighterOne/exchangeprojects/releases/download/v1.0.0/exchange-android.apk'