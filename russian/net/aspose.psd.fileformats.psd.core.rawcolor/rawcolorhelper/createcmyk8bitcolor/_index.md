---
title: "RawColorHelper.CreateCmyk8BitColor"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод RawColorHelper. Создает 8‑битный на канал цвет CMYK"
type: docs
weight: 50
url: /ru/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk8bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk8BitColor method

Создает 8‑битный CMYK‑цвет на канал.

```csharp
public static RawColor CreateCmyk8BitColor(byte c, byte m, byte y, byte k)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| c | Byte | Значение компоненты циана (0‑255). |
| m | Byte | Значение компоненты мадженты (0‑255). |
| y | Byte | Значение компоненты желтого (0‑255). |
| k | Byte | Значение ключевой (черной) компоненты (0‑255). |

### Возвращаемое значение

Новый экземпляр [`RawColor`](../../rawcolor/) , представляющий цвет CMYK.

## Примечания

Компоненты цвета упакованы в 32‑битное целое число в следующем порядке: циан (биты 24‑31), маджента (биты 16‑23), желтый (биты 8‑15) и ключ/черный (биты 0‑7).

### См. также

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


