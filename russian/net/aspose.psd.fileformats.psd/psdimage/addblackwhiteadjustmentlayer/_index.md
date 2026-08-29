---
title: "PsdImage.AddBlackWhiteAdjustmentLayer"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод PsdImage. Добавляет слой корректировки черно‑белого."
type: docs
weight: 300
url: /ru/net/aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddBlackWhiteAdjustmentLayer method

Добавляет слой коррекции черно‑белого.

```csharp
public BlackWhiteAdjustmentLayer AddBlackWhiteAdjustmentLayer()
```

### Возвращаемое значение

Созданный слой корректировки черно‑белого.

## Примеры

В следующем примере показано, как можно добавить слой коррекции черно-белого изображения во время выполнения в Aspose.PSD

```csharp
[C#]

string sourceFileName = "Stripes.psd";
string outputFileName = "OutputStripes.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    BlackWhiteAdjustmentLayer newLayer = image.AddBlackWhiteAdjustmentLayer();
    newLayer.Name = "BlackWhiteAdjustmentLayer";
    newLayer.Reds = 22;
    newLayer.Yellows = 92;
    newLayer.Greens = 70;
    newLayer.Cyans = 79;
    newLayer.Blues = 7;
    newLayer.Magentas = 28;

    image.Save(outputFileName, new PsdOptions());
}
```

### См. также

* class [BlackWhiteAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


