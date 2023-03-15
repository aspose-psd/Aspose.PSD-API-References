---
title: PsdImage.AddInvertAdjustmentLayer
second_title: Справочник по Aspose.PSD для .NET API
description: PsdImage метод. Добавляет инвертированный корректирующий слой.
type: docs
weight: 360
url: /ru/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
## PsdImage.AddInvertAdjustmentLayer method

Добавляет инвертированный корректирующий слой.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### Возвращаемое значение

Созданный инвертированный слой

### Примеры

Следующий код демонстрирует поддержку InvertAdjustmentLayer и способ добавления InvertAdjustmentLayer.

```csharp
[C#]

var filePath = "InvertStripes_before.psd";
var outputPath = "InvertStripes_after.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    im.AddInvertAdjustmentLayer();
    im.Save(outputPath);
}
```

### Смотрите также

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* сборка [Aspose.PSD](../../../)


