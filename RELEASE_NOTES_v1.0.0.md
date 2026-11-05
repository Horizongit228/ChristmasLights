# Christmas Lights v1.0.0 🎄

**Первый публичный выпуск Christmas Lights для Windows.**

Christmas Lights добавляет на верхний край рабочего стола настраиваемую новогоднюю гирлянду. Она может мягко светиться, переливаться разными цветами и реагировать на музыку.

## Скачать

**[Скачать ChristmasLights.exe (Windows x64)](https://github.com/Horizongit228/ChristmasLights/releases/download/v1.0.0/ChristmasLights.exe)**

- Windows 10 (сборка 19041+) или Windows 11, x64
- Portable EXE, 73,01 МиБ
- .NET включён в приложение — отдельно устанавливать не требуется

## Возможности

- Пять форм лампочек: Classic, Globe, Candle, Star и Heart
- Цветовые темы, яркость, насыщенность, переливание и мерцание
- **Audio Wave** — световые импульсы, распространяющиеся от центра в такт звуку
- Автоматическое количество лампочек по ширине экрана (16–32)
- Настройка положения и провисания провода, взаимодействие с курсором
- Настройка поведения поверх полноэкранных приложений
- Русский и английский интерфейс, автозапуск Windows
- Управление через значок в системном трее

## Запуск

1. Скачайте `ChristmasLights.exe`.
2. Сохраните его в удобной постоянной папке.
3. Запустите двойным щелчком.
4. Для настроек и выхода используйте значок в системном трее.

## Проверка целостности

SHA-256 файла `ChristmasLights.exe` (76 551 822 байта):

```text
00d072d5f05b1123c6e6005a221ad9030c2ca908c9130bc6b319d7d7db40776e
```

PowerShell:

```powershell
Get-FileHash .\ChristmasLights.exe -Algorithm SHA256
```

Сравните значение с указанным выше. Приложение может не иметь цифровой подписи, поэтому Windows SmartScreen иногда показывает предупреждение о неизвестном издателе.

## Известные ограничения

- Гирлянда рассчитана прежде всего на **основной монитор**.
- Отображение над полноэкранными приложениями зависит от режима и настроек.

Сообщить о проблеме: **[GitHub Issues](https://github.com/Horizongit228/ChristmasLights/issues)**.

---

# English

**The first public release of Christmas Lights for Windows.**

Christmas Lights brings a customizable strand of holiday lights to the top of your desktop. Enjoy a cozy glow, animated colors, and music-reactive lighting.

## Download

**[Download ChristmasLights.exe (Windows x64)](https://github.com/Horizongit228/ChristmasLights/releases/download/v1.0.0/ChristmasLights.exe)**

- Windows 10 (build 19041+) or Windows 11, x64
- Portable, self-contained EXE (73.01 MiB)
- No separate .NET installation required

## Features

- Five bulb styles: Classic, Globe, Candle, Star, and Heart
- Color themes, brightness, saturation, running colors, and twinkling
- **Audio Wave** — audio-reactive light pulses travelling outward from the center
- Automatic bulb count based on display width (16–32)
- Adjustable placement, cable sag, and cursor interaction
- Configurable fullscreen overlay behavior
- English and Russian interface, optional Windows startup
- Settings and exit controls in the system tray

## Run

1. Download `ChristmasLights.exe`.
2. Save it in a permanent location.
3. Launch the executable.
4. Open settings or exit via the system tray.

## Verify the download

SHA-256 of `ChristmasLights.exe` (76,551,822 bytes):

```text
00d072d5f05b1123c6e6005a221ad9030c2ca908c9130bc6b319d7d7db40776e
```

In PowerShell:

```powershell
Get-FileHash .\ChristmasLights.exe -Algorithm SHA256
```

Compare the result before running the app. The build may be unsigned and Windows SmartScreen may warn about an unknown publisher.

## Known limitations

- The garland is designed primarily for the **main monitor**.
- Fullscreen overlay behavior depends on display mode and user preferences.

Feedback and bug reports: **[GitHub Issues](https://github.com/Horizongit228/ChristmasLights/issues)**.

---

*This document describes the public **v1.0.0** release only. Later development previews are not included in this download.*