# Ancient Warriors: Order of the Seal — сборки игры

Здесь лежат готовые сборки одиночной ролевой игры **Ancient Warriors: Order of the Seal**.
Скачивать удобнее со страницы игры: **[Скачать игру](https://acient-warriors-web.vercel.app/ru/download/)**.
Там же системные требования, политика конфиденциальности и условия использования.

Каждая версия — отдельный [релиз](https://github.com/Lusiy321/ancient-warriors-releases/releases):

| Файл | Что это |
|---|---|
| `ancient-warriors-windows.zip` | Windows 10/11, 64-бит. Бесплатно, без рекламы и покупок. |
| `ancient-warriors.apk` | Android 10 и новее, arm64. Бесплатно, с рекламой. Появится в одном из следующих релизов. |

Самая свежая версия всегда по одним и тем же ссылкам:
[Windows](https://github.com/Lusiy321/ancient-warriors-releases/releases/latest/download/ancient-warriors-windows.zip) ·
[Android](https://github.com/Lusiy321/ancient-warriors-releases/releases/latest/download/ancient-warriors.apk).

## Как установить

**Windows.** Распакуйте архив в любую папку и запустите `ancient-warriors.exe`. Три
файла из архива должны лежать вместе. При первом запуске Windows может показать окно
«Система Windows защитила ваш компьютер»: файл не подписан платным сертификатом
разработчика. Нажмите «Подробнее», затем «Выполнить в любом случае». Герои хранятся
отдельно, в `%APPDATA%\AncientWarriors`, поэтому новую версию можно распаковать поверх
старой.

**Android.** Откройте скачанный APK на телефоне и разрешите браузеру установку
приложений. Новый APK ставится поверх старого, герои остаются на телефоне.

## Проверка файла

У каждого файла в релизе GitHub показывает контрольную сумму SHA-256, и она же есть на
странице загрузки. Сверить:

```
certutil -hashfile ancient-warriors-windows.zip SHA256   # Windows
shasum -a 256 ancient-warriors-windows.zip               # macOS
sha256sum ancient-warriors-windows.zip                   # Linux
```

Скачивайте игру только отсюда или со страницы игры: копия из другого места могла быть
изменена.

## Связь

Вопросы и сообщения об ошибках — в [Issues](https://github.com/Lusiy321/ancient-warriors-releases/issues).

---

# Ancient Warriors: Order of the Seal — game builds

The builds of the single-player RPG **Ancient Warriors: Order of the Seal**. The easiest
place to get them is the game's page: **[Download the game](https://acient-warriors-web.vercel.app/en/download/)**,
with the system requirements, the privacy policy and the terms of use.

| File | What it is |
|---|---|
| `ancient-warriors-windows.zip` | Windows 10/11, 64-bit. Free, no ads, no purchases. |
| `ancient-warriors.apk` | Android 10 or newer, arm64. Free, with ads. Comes in one of the next releases. |

The newest version is always at the same addresses:
[Windows](https://github.com/Lusiy321/ancient-warriors-releases/releases/latest/download/ancient-warriors-windows.zip) ·
[Android](https://github.com/Lusiy321/ancient-warriors-releases/releases/latest/download/ancient-warriors.apk).

**Windows:** unpack the archive into any folder and run `ancient-warriors.exe`; keep the
three files together. If Windows shows “Windows protected your PC” (the file is not signed
with a paid developer certificate), click “More info”, then “Run anyway”. Your heroes are
kept in `%APPDATA%\AncientWarriors`, so a new version can be unpacked over the old one.

**Android:** open the downloaded APK on your phone and allow your browser to install apps.
A new APK installs over the old one; your heroes stay on the phone.

Each release file shows its SHA-256 checksum on GitHub and on the download page. Get the
game only here or from the game's page: a copy from anywhere else may have been altered.

Questions and bug reports go to [Issues](https://github.com/Lusiy321/ancient-warriors-releases/issues).

© 2026 Ancient Warriors. All rights reserved. The game's code is not published here.
