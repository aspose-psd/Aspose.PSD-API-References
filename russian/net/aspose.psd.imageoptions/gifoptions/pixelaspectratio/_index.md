---
title: "GifOptions.PixelAspectRatio"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство GifOptions. Получает или задает пиксельное соотношение сторон GIF"
type: docs
weight: 90
url: /ru/net/aspose.psd.imageoptions/gifoptions/pixelaspectratio/
---
{{< psd/tize >}}
## GifOptions.PixelAspectRatio property

Получает или задает соотношение сторон пикселя GIF.

```csharp
public byte PixelAspectRatio { get; set; }
```

### Property Value

Пиксельное соотношение сторон GIF.

## Примечания

Pixel Aspect Ratio — фактор, используемый для вычисления приближённого соотношения сторон пикселя в исходном изображении. Если значение поля не равно 0, это приближение соотношения сторон вычисляется по формуле: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Pixel Aspect Ratio определяется как отношение ширины пикселя к его высоте. Диапазон значений в этом поле позволяет задавать самый широкий пиксель 4:1 до самого высокого пикселя 1:4 с шагом 1/64. Значения: 0 — информация о соотношении сторон не предоставлена. 1..255 — значение, используемое в вычислениях.

### См. также

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


