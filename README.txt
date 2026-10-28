ТЕТРАДЬ СМЕРТИ — проект Android-приложения

Это готовый проект-обёртка Android WebView с игрой в assets/index.html. Это НЕ собранный APK: в среде создания нет Android SDK/Gradle, поэтому собрать и протестировать APK здесь невозможно.

Как получить APK:
1. Установите Android Studio на компьютер.
2. Откройте в Android Studio папку death-note-android.
3. Дождитесь синхронизации Gradle и установите Android SDK 35, если IDE попросит.
4. Выберите Build > Build Bundle(s) / APK(s) > Build APK(s).
5. APK будет в app/build/outputs/apk/debug/app-debug.apk.

Интернет нужен для внешнего шрифта и онлайн-мультиплеера PeerJS. Сюжетная игра загружается локально внутри приложения. Онлайн-мультиплеер требует сеть.
