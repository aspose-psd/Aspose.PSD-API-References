---
title: "ThresholdLayer.Level"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "ThresholdLayer property. Mendapatkan dan mengatur level ambang"
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/level/
---
{{< psd/tize >}}
## ThresholdLayer.Level property

Mendapatkan dan mengatur tingkat ambang.

```csharp
public short Level { get; set; }
```

### Property Value

Level tersebut.

## Contoh

Kode berikut menunjukkan dukungan lapisan penyesuaian ThresholdLayer.

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

// Dapatkan, periksa, dan ubah lapisan penyesuaian Threshold dari gambar.
using (var image = (PsdImage)Image.Load(sourceFileWithThresholdLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is ThresholdLayer)
        {
            // Dapatkan lapisan penyesuaian Threshold.
            ThresholdLayer thrsLayer = (ThresholdLayer)layer;
            var level = thrsLayer.Level;

            // Periksa parameter lapisan.
            AssertAreEqual(level, (short)115);

            // Atur parameter lapisan.
            thrsLayer.Level = 50;

            image.Save(outputPsdWithThresholdLayer);
            image.Save(outputPngWithThresholdLayer, new PngOptions());
        }
    }
}

// Tambahkan dan atur lapisan penyesuaian Threshold ke gambar.
using (var image = (PsdImage)Image.Load(sourceFileWithoutThresholdLayer))
{
    // Tambahkan lapisan Penyesuaian Threshold.
    ThresholdLayer thresholdLayer = image.AddThresholdAdjustmentLayer();

    // Atur parameter lapisan.
    thresholdLayer.Level = 115;

    image.Save(outputPsdWithoutThresholdLayer);
    image.Save(outputPngWithoutThresholdLayer, new PngOptions());
}
```

### Lihat Juga

* class [ThresholdLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


