---
title: "ThresholdLayer.Level"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "ThresholdLayer property. थ्रेशहोल्ड स्तर प्राप्त करता है और सेट करता है"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/level/
---
{{< psd/tize >}}
## ThresholdLayer.Level property

थ्रेशोल्ड स्तर को प्राप्त करता है और सेट करता है।

```csharp
public short Level { get; set; }
```

### Property Value

स्तर।

## उदाहरण

निम्नलिखित कोड ThresholdLayer समायोजन लेयर के समर्थन को दर्शाता है।

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

// इमेज से Threshold समायोजन लेयर को प्राप्त करें, जाँचें और बदलें।
using (var image = (PsdImage)Image.Load(sourceFileWithThresholdLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is ThresholdLayer)
        {
            // Threshold समायोजन लेयर प्राप्त करें।
            ThresholdLayer thrsLayer = (ThresholdLayer)layer;
            var level = thrsLayer.Level;

            // लेयर पैरामीटर जाँचें।
            AssertAreEqual(level, (short)115);

            // लेयर पैरामीटर सेट करें।
            thrsLayer.Level = 50;

            image.Save(outputPsdWithThresholdLayer);
            image.Save(outputPngWithThresholdLayer, new PngOptions());
        }
    }
}

// इमेज में Threshold समायोजन लेयर जोड़ें और सेट करें।
using (var image = (PsdImage)Image.Load(sourceFileWithoutThresholdLayer))
{
    // Threshold Adjustment लेयर जोड़ें।
    ThresholdLayer thresholdLayer = image.AddThresholdAdjustmentLayer();

    // लेयर पैरामीटर सेट करें।
    thresholdLayer.Level = 115;

    image.Save(outputPsdWithoutThresholdLayer);
    image.Save(outputPngWithoutThresholdLayer, new PngOptions());
}
```

### देखें भी

* class [ThresholdLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


