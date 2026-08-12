---
title: "PsdImage.AddThresholdAdjustmentLayer"
second_title: "Справочник API Aspose.PSD для .NET"
description: "PsdImage метод. Добавляет слой корректировки порога"
type: docs
weight: 480
url: /ru/net/aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddThresholdAdjustmentLayer method

Добавляет слой коррекции порога.

```csharp
public ThresholdLayer AddThresholdAdjustmentLayer()
```

### Возвращаемое значение

Созданный слой корректировки Threshold.

## Примеры

Следующий код демонстрирует поддержку слоя корректировки ThresholdLayer.

```csharp
[C#]

string sourceFileWithThresholdLayer = "flowers_threshold_source.psd";
string outputPsdWithThresholdLayer = "flowers_threshold_output.psd";
string outputPngWithThresholdLayer = "flowers_threshold_output.png";

string sourceFileWithoutThresholdLayer = "flowers_source.psd";
string outputPsdWithoutThresholdLayer = "flowers_output.psd";
string outputPngWithoutThresholdLayer = "flowers_output.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// Получите, проверьте и измените слой корректировки Threshold из изображения.
using (var image = (PsdImage)Image.Load(sourceFileWithThresholdLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is ThresholdLayer)
        {
            // Получить слой корректировки Threshold.
            ThresholdLayer thrsLayer = (ThresholdLayer)layer;
            var level = thrsLayer.Level;

            // Проверьте параметры слоёв.
            AssertAreEqual(level, (short)115);

            // Установить параметры слоёв.
            thrsLayer.Level = 50;

            image.Save(outputPsdWithThresholdLayer);
            image.Save(outputPngWithThresholdLayer, new PngOptions());
        }
    }
}

// Добавьте и задайте слой корректировки Threshold в изображении.
using (var image = (PsdImage)Image.Load(sourceFileWithoutThresholdLayer))
{
    // Добавить слой корректировки Threshold.
    ThresholdLayer thresholdLayer = image.AddThresholdAdjustmentLayer();

    // Установить параметры слоёв.
    thresholdLayer.Level = 115;

    image.Save(outputPsdWithoutThresholdLayer);
    image.Save(outputPngWithoutThresholdLayer, new PngOptions());
}
```

### См. также

* class [ThresholdLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


