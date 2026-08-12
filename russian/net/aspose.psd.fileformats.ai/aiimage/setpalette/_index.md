---
title: "AiImage.SetPalette"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод AiImage. Устанавливает палитру изображения"
type: docs
weight: 200
url: /ru/net/aspose.psd.fileformats.ai/aiimage/setpalette/
---
{{< psd/tize >}}
## AiImage.SetPalette method

Устанавливает палитру изображения.

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| палитра | IColorPalette | Палитра для установки. |
| updateColors | Boolean | Если установить в `true`, цвета будут обновлены в соответствии с новой палитрой; в противном случае индексы цветов останутся неизменными. Обратите внимание, что неизменные индексы могут привести к сбою изображения при загрузке, если некоторые индексы не имеют соответствующих записей в палитре. |

### Исключения

| исключение | условие |
| --- | --- |
| NotImplementedException | Не реализовано |

### См. также

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


