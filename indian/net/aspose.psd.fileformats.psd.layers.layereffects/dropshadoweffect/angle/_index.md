---
title: DropShadowEffect.Angle
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: DropShadowEffect संपत्त. कण क डग्र में प्रप्त य सेट करत है
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/angle/
---
## DropShadowEffect.Angle property

कोण को डिग्री में प्राप्त या सेट करता है।

```csharp
public int Angle { get; set; }
```

### संपत्ति मूल्य

कोण.

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

* class [DropShadowEffect](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* सभा [Aspose.PSD](../../../)


