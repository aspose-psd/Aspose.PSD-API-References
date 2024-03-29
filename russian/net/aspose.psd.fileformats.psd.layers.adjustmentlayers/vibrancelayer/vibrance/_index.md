---
title: VibranceLayer.Vibrance
second_title: Справочник по Aspose.PSD для .NET API
description: VibranceLayer свойство. Получает или устанавливает яркость.
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
## VibranceLayer.Vibrance property

Получает или устанавливает яркость.

```csharp
public int Vibrance { get; set; }
```

### Стоимость имущества

Вибрация.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Вибрация должна быть в диапазоне от -180 до +180 |

### Примеры

В следующем примере кода демонстрируется поддержка слоя VibranceLayer и возможность редактирования этой настройки.

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

### Смотрите также

* class [VibranceLayer](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../vibrancelayer/)
* сборка [Aspose.PSD](../../../)


