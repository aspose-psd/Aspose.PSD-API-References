---
title: "RawColorHelper.CreateArgb8BitColor"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод RawColorHelper. Создаёт 8‑битный на канал цвет ARGB"
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb8bitcolor/
---
{{< psd/tize >}}
## CreateArgb8BitColor(byte, byte, byte, byte) {#createargb8bitcolor_1}

Создаёт ARGB‑цвет с 8 битами на канал.

```csharp
public static RawColor CreateArgb8BitColor(byte a, byte r, byte g, byte b)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | Byte | Значение компонента alpha (0-255). |
| r | Byte | Значение компонента red (0-255). |
| g | Byte | Значение компонента green (0-255). |
| b | Byte | Значение компонента blue (0-255). |

### Возвращаемое значение

Новый экземпляр [`RawColor`](../../rawcolor/) , представляющий цвет ARGB.

## Примечания

Компоненты цвета упакованы в 32‑битное целое число в следующем порядке: alpha (биты 24‑31), red (биты 16‑23), green (биты 8‑15) и blue (биты 0‑7).

### См. также

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## CreateArgb8BitColor(Color) {#createargb8bitcolor}

Создаёт ARGB‑цвет с 8 битами на канал из Drawing.Color.

```csharp
public static RawColor CreateArgb8BitColor(Color drawingColor)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| drawingColor | Color | Тип System.Drawing Color |

### Возвращаемое значение

Новый экземпляр [`RawColor`](../../rawcolor/) , представляющий цвет ARGB.

## Примечания

Компоненты цвета упакованы в 32‑битное целое число в следующем порядке: alpha (биты 24‑31), red (биты 16‑23), green (биты 8‑15) и blue (биты 0‑7).

### См. также

* class [RawColor](../../rawcolor/)
* struct [Color](../../../aspose.psd/color/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


