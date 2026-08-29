---
title: "RawColorHelper.CreateArgb16BitColor"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод RawColorHelper. Создает 16‑битный на канал цвет ARGB"
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb16bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateArgb16BitColor method

Создаёт ARGB‑цвет с 16 битами на канал.

```csharp
public static RawColor CreateArgb16BitColor(ushort a, ushort r, ushort g, ushort b)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | UInt16 | Значение альфа‑компоненты (0‑65535). |
| r | UInt16 | Значение компоненты красного (0‑65535). |
| g | UInt16 | Значение компоненты зеленого (0‑65535). |
| b | UInt16 | Значение компоненты синего (0‑65535). |

### Возвращаемое значение

Новый экземпляр [`RawColor`](../../rawcolor/) , представляющий цвет ARGB.

## Примечания

Компоненты цвета упакованы в 64‑битное целое число в следующем порядке: альфа (биты 48‑63), красный (биты 32‑47), зеленый (биты 16‑31) и синий (биты 0‑15).

### См. также

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


