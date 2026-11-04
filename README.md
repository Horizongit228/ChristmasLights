# Christmas Lights

**Новогодняя гирлянда для рабочего стола Windows**  
*Animated holiday lights for your Windows desktop*

[Русский](#русский) · [English](#english)

## Русский

Christmas Lights — небольшое приложение для Windows, которое размещает анимированную гирлянду вдоль верхней границы экрана. Настройте цвета, формы лампочек и световые эффекты. Гирлянда не перехватывает нажатия мыши, а основные параметры доступны через значок в системном трее.

### Возможности

- Пять форм лампочек: классическая, шар, свеча, звезда и сердце
- Цветовые темы, регулировка яркости и насыщенности, переливание цветов и мерцание
- **Audio Wave** — световые волны, расходящиеся от центра в такт музыке
- Автоматическое количество лампочек по ширине экрана или ручной выбор (16–32)
- Настройка положения, провисания провода и взаимодействия с курсором
- Настраиваемое поведение поверх полноэкранных приложений
- Русский и английский интерфейс, автозапуск с Windows и ярлык на рабочем столе

### Загрузка и запуск

**Версия: 1.0 · Windows x64**

Программа распространяется в виде самостоятельного исполняемого файла. Устанавливать .NET отдельно **не требуется**.

1. Перейдите в раздел **[Releases](https://github.com/Horizongit228/ChristmasLights/releases)**
2. После публикации выпуска `v1.0.0` скачайте файл **`ChristmasLights.exe`** из блока **Assets**
3. Поместите файл в постоянную папку и запустите двойным щелчком
4. Для открытия настроек или выхода используйте значок в системном трее

**Системные требования:** Windows 10 (сборка 19041 или новее) либо Windows 11, 64-разрядная версия.

> **Статус выпуска:** исполняемый файл подготовлен и проходит публикацию; пока его нет в Releases, ссылка на скачивание недоступна.

### Проверка файла

Для подготовленной компактной сборки `ChristmasLights.exe`:

| Параметр | Значение |
| --- | --- |
| Размер | 73,01 МиБ (76 551 822 байта) |
| SHA-256 | `00d072d5f05b1123c6e6005a221ad9030c2ca908c9130bc6b319d7d7db40776e` |

Проверить контрольную сумму после загрузки можно в PowerShell:

```powershell
Get-FileHash .\ChristmasLights.exe -Algorithm SHA256
```

Сравните полученный хеш со значением выше. Если файл отличается, не запускайте его.

Первый выпуск может быть без цифровой подписи, поэтому Windows SmartScreen иногда показывает предупреждение о неизвестном издателе. Загружайте приложение только из официального раздела Releases.

### Ошибки и предложения

Для сообщений об ошибках и предложений используйте **[Issues](https://github.com/Horizongit228/ChristmasLights/issues)**. По возможности укажите версию Windows и шаги для воспроизведения ошибки.

---

## English

Christmas Lights adds an animated, customizable strand of glass bulbs along the top of the Windows desktop. Choose bulb shapes, colors, and lighting effects without blocking mouse interaction. Settings are available from the system tray.

### Features

- Five bulb shapes: classic, globe, candle, star, and heart
- Color themes, brightness and saturation controls, running colors, and twinkling
- **Audio Wave** — music-reactive light pulses moving outward from the center
- Automatic bulb count based on screen width or manual selection (16–32)
- Adjustable position, cable sag, and cursor interaction
- Configurable behavior over fullscreen applications
- Russian and English interface, optional Windows startup, and desktop shortcuts

### Download and run

**Version: 1.0 · Windows x64**

The application is distributed as a **self-contained executable**. No separate .NET installation is required.

1. Visit **[Releases](https://github.com/Horizongit228/ChristmasLights/releases)**
2. Once `v1.0.0` is published, download **`ChristmasLights.exe`** from **Assets**
3. Save the file in a permanent folder and double-click it
4. Use the system tray icon to open settings or exit

**Requirements:** Windows 10 (build 19041 or newer) or Windows 11, x64.

> **Release status:** the executable has been prepared but is not yet uploaded to Releases. The download becomes available after publication.

### File integrity

Prepared compact build: **73.01 MiB** (76,551,822 bytes)

SHA-256:

```text
00d072d5f05b1123c6e6005a221ad9030c2ca908c9130bc6b319d7d7db40776e
```

Verify the checksum with `Get-FileHash .\ChristmasLights.exe -Algorithm SHA256` in PowerShell.

Early releases may be unsigned, so Windows SmartScreen may show an unknown-publisher warning. Download only from this repository's official Releases page.

### Feedback

Report bugs and request improvements through **[Issues](https://github.com/Horizongit228/ChristmasLights/issues)**. Include your Windows version and reproduction steps when possible.

---

*The application's source code is not currently published in this repository. The repository provides release downloads, documentation, and issue tracking.*
