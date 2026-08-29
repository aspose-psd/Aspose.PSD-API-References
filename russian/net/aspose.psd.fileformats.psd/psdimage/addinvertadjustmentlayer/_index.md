---
title: "PsdImage.AddInvertAdjustmentLayer"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод PsdImage. Добавляет слой коррекции инверсии"
type: docs
weight: 380
url: /ru/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddInvertAdjustmentLayer method

Добавляет слой инверсии.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### Возвращаемое значение

Созданный слой инверсии

## Примеры

Следующий код демонстрирует поддержку InvertAdjustmentLayer и то, как добавить InvertAdjustmentLayer.

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

### См. также

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


