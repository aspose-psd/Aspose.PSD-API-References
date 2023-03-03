---
title: DropShadowEffect.BlendMode
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: DropShadowEffect संपत्त. ब्लेंड मड प्रप्त य सेट करत है
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/blendmode/
---
## DropShadowEffect.BlendMode property

ब्लेंड मोड प्राप्त या सेट करता है।

```csharp
public BlendMode BlendMode { get; set; }
```

### संपत्ति मूल्य

ब्लेंड मोड.

### उदाहरण

निम्न कोड DropShadowEffect के अपारदर्शिता गुण का उपयोग करके प्रदर्शित करता है।

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // उदाहरण अपारदर्शिता = 20 के साथ
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // उदाहरण अपारदर्शिता = 20 के साथ0
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### यह सभी देखें

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [DropShadowEffect](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* सभा [Aspose.PSD](../../../)


