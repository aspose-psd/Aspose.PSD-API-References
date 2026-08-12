---
title: "RawColorHelper.CreateCmyk16BitBitColor"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод RawColorHelper. Создает 16‑битный на канал цвет CMYK"
type: docs
weight: 40
url: /ru/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk16bitbitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk16BitBitColor method

Создает 16‑битный CMYK‑цвет на канал.

```csharp
public static RawColor CreateCmyk16BitBitColor(ushort c, ushort m, ushort y, ushort k)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| c | UInt16 | Значение компоненты циана (0‑65535). |
| m | UInt16 | Значение компоненты мадженты (0‑65535). |
| y | UInt16 | Значение компоненты желтого (0‑65535). |
| k | UInt16 | Значение компонента key (чёрный) (0-65535). |

### Возвращаемое значение

Новый экземпляр [`RawColor`](../../rawcolor/) , представляющий цвет CMYK.

## Примечания

Компоненты цвета упакованы в 64‑битное целое число в следующем порядке: cyan (биты 48‑63), magenta (биты 32‑47), yellow (биты 16‑31) и key/black (биты 0‑15).

### См. также

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


