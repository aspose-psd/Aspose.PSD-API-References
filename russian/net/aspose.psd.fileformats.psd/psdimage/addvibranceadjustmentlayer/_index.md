---
title: PsdImage.AddVibranceAdjustmentLayer
second_title: Справочник по Aspose.PSD для .NET API
description: PsdImage метод. Добавляет корректирующий слой Vibrance.
type: docs
weight: 430
url: /ru/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
## PsdImage.AddVibranceAdjustmentLayer method

Добавляет корректирующий слой Vibrance.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### Возвращаемое значение

Недавно созданный слой Vibrance.

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

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* сборка [Aspose.PSD](../../../)


