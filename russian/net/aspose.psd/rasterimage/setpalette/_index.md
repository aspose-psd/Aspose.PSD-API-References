---
title: "RasterImage.SetPalette"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод RasterImage. Устанавливает палитру изображения"
type: docs
weight: 570
url: /ru/net/aspose.psd/rasterimage/setpalette/
---
{{< psd/tize >}}
## RasterImage.SetPalette method

Устанавливает палитру изображения.

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| палитра | IColorPalette | Палитра для установки. |
| updateColors | Boolean | Если установить в `true`, цвета будут обновлены в соответствии с новой палитрой; в противном случае индексы цветов останутся неизменными. Обратите внимание, что неизменные индексы могут привести к сбою изображения при загрузке, если некоторые индексы не имеют соответствующих записей в палитре. |

### См. также

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


