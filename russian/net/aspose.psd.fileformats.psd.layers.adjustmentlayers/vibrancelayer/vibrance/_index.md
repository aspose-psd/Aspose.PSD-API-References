---
title: "VibranceLayer.Vibrance"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство VibranceLayer. Получает или задает vibrance"
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
{{< psd/tize >}}
## VibranceLayer.Vibrance property

Получает или задает vibrance.

```csharp
public int Vibrance { get; set; }
```

### Property Value

Vibrance.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Vibrance должна быть в диапазоне от -180 до +180 |

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


