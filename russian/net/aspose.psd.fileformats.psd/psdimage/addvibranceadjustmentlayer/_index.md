---
title: "PsdImage.AddVibranceAdjustmentLayer"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод PsdImage. Добавляет слой корректировки Vibrance"
type: docs
weight: 490
url: /ru/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddVibranceAdjustmentLayer method

Добавляет слой коррекции яркости.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### Возвращаемое значение

Новосозданный слой Vibrance.

## Примеры

Следующий пример кода демонстрирует поддержку слоя VibranceLayer и возможность редактировать эту коррекцию.

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // Создание нового VibranceLayer
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### См. также

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


