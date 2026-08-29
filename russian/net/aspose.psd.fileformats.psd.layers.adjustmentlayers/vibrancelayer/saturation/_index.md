---
title: "VibranceLayer.Saturation"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство VibranceLayer. Получает или задает насыщенность"
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
{{< psd/tize >}}
## VibranceLayer.Saturation property

Получает или задает насыщенность.

```csharp
public int Saturation { get; set; }
```

### Property Value

Насыщенность.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Насыщенность должна быть в диапазоне от -100 до +100 |

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

* class [VibranceLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


