---
title: PsdImage.AddInvertAdjustmentLayer
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: PsdImage तरक. एक उलट समयजन परत जड़त है
type: docs
weight: 360
url: /hi/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
## PsdImage.AddInvertAdjustmentLayer method

एक उलटी समायोजन परत जोड़ता है।

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### प्रतिलाभ की मात्रा

बनाई गई उलटी परत

### उदाहरण

निम्न कोड InvertAdjustmentLayer और InvertAdjustmentLayer को जोड़ने के तरीके के लिए समर्थन प्रदर्शित करता है।

```csharp
[C#]

var filePath = "InvertStripes_before.psd";
var outputPath = "InvertStripes_after.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    im.AddInvertAdjustmentLayer();
    im.Save(outputPath);
}
```

### यह सभी देखें

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* सभा [Aspose.PSD](../../../)


