# Старый софт Apple для Non-Metal Macs

Это последние совместимые версии приложений Apple для любых компьютеров Mac с видеокартами не Metal.  
Все эти приложения полностью функциональны на macOS 10.13 High Sierra, 10.14 Mojave и 10.15 Catalina. Совместимость со всеми другими версиями macOS зависит от рассматриваемого приложения.  
Пожалуйста, используйте платные приложения из этого списка (Final Cut Pro, Logic Pro, Motion, Compressor и MainStage), только если у вас есть копии этих приложений в Mac App Store. Я не оправдываю и никогда не буду оправдывать пиратство.  

https://archive.org/details/apple-apps-for-non-metal-macs

# Модели ноутбуков

https://github.com/dortania/OpenCore-Legacy-Patcher/blob/main/docs/MODELS.md#macbook-pro

# Создание загрузочной флешки MacOS

Для создании загрузочной флешки используем программу с официального сайта [balenaEtcher](https://etcher.balena.io/)  

> Работает под любую операционную систему (MacOS, Windows, Linux).  
> Программу не обязательно устанавливать, есть портативные варианты как для 32 битной так и для 64 битной систем Linux и Windows.  
> Скачиваем zip файл для Linux, распаковываем и пользуемся.  
> Аналогично и для иных систем.  
> В случае Linux и Windows понадобиться утилита dmg2img для [преобразования dmg файлов в img](https://www.youtube.com/watch?v=4c8o-54jVy8).  

Далее скачиваем MacOS загрузочных iso:
- [All macOS X images](https://archive.org/download/macOS-X-images)
- [MacOS-HighSierra10.13](https://disk.yandex.ru/d/BU9ZvcG5yIbuNQ) - лежит по этой ссылке. Файл называется "bckup.img".
- [MacOS-BigSur11.6.8](https://drive.google.com/drive/folders/16G1d_XnOOppaervgbi00isNpzprupvCT) - iso файл сжатый в rar
- Есть вариант [образы MacOS на официальном сайте Apple](https://support.apple.com/ru-ru/102662). Можно использовать только версии ниже HighSierra, так как если ставить версии выше то без патчей драйвера на видео карту и другое не встанут.  

# MacOS версий выше HighSierra 10.13 с патчем OpenCore.

- [OpenCore Legacy Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher) - это программа устанавливается на Mac, загружает новую версию Операционной системы не поддерживаемой Mac и создает флешку для установки. После установки патчит систему чтобы поставились драйвера видео и другого оборудования.
- https://github.com/dortania/OpenCore-Legacy-Patcher/releases/download/2.2.0/OpenCore-Patcher-GUI.app.zip

# X-Code
- [Список релизов X-Code с поддерживаемыми MacOS](https://xcodereleases.com/)  
- [Официальная документация по релизам X-Codes](https://developer.apple.com/documentation/xcode-release-notes/xcode-14_2-release-notes)  
- [Тут можео скачать старые версии X-Code и многого другого](https://developer.apple.com/download/all/)

# Dark Mode в macOS High Sierra

## Чтобы включить Dark Mode в macOS High Sierra 10.13 введите в терминале следующую команду:  

```
defaults write -g NSWindowDarkChocolate -bool TRUE
```

Перезагрузитесь.  

## Чтобы вернуть все обратно введите:  

```
defaults delete -g NSWindowDarkChocolate
```

Перезагрузитесь.  

## APPs for MacOS

- [Commander One PRO: FTP & Cloud](https://cdn.electronic.us/products/commander/mac/download/commander.dmg)
- [iTerm2](https://iterm2.com/)
- [10 лучших приложений для Mac — производительность и ежедневное использование ](https://www.youtube.com/watch?v=BXxpewzHbG4)
- 
