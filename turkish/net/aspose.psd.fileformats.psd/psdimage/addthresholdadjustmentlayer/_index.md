---
title: "PsdImage.AddThresholdAdjustmentLayer"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PsdImage yöntemi. Threshold ayar katmanını ekler"
type: docs
weight: 480
url: /tr/net/aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddThresholdAdjustmentLayer method

Eşik ayar katmanını ekler.

```csharp
public ThresholdLayer AddThresholdAdjustmentLayer()
```

### Dönüş Değeri

Oluşturulan Threshold ayar katmanı.

## Örnekler

Aşağıdaki kod, ThresholdLayer ayar katmanının desteğini gösterir.

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

// Görüntüden Threshold ayar katmanını al, kontrol et ve değiştir.
using (var image = (PsdImage)Image.Load(sourceFileWithThresholdLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is ThresholdLayer)
        {
            // Threshold ayar katmanını al.
            ThresholdLayer thrsLayer = (ThresholdLayer)layer;
            var level = thrsLayer.Level;

            // Katman parametrelerini kontrol et.
            AssertAreEqual(level, (short)115);

            // Katman parametrelerini ayarla.
            thrsLayer.Level = 50;

            image.Save(outputPsdWithThresholdLayer);
            image.Save(outputPngWithThresholdLayer, new PngOptions());
        }
    }
}

// Threshold ayar katmanını görüntüye ekle ve ayarla.
using (var image = (PsdImage)Image.Load(sourceFileWithoutThresholdLayer))
{
    // Threshold Ayar Katmanı ekle.
    ThresholdLayer thresholdLayer = image.AddThresholdAdjustmentLayer();

    // Katman parametrelerini ayarla.
    thresholdLayer.Level = 115;

    image.Save(outputPsdWithoutThresholdLayer);
    image.Save(outputPngWithoutThresholdLayer, new PngOptions());
}
```

### Ayrıca Bakınız

* class [ThresholdLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


