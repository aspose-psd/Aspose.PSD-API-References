---
title: DropShadowEffect.IsVisible
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: DropShadowEffect संपत्त. एक मन प्रप्त करत है य सेट करत है ज दर्शत है क यह उदहरण दृश्यमन है य नहं
type: docs
weight: 60
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/
---
## DropShadowEffect.IsVisible property

एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि यह उदाहरण दृश्यमान है या नहीं।

```csharp
public bool IsVisible { get; set; }
```

### संपत्ति मूल्य

`सत्य` यदि यह उदाहरण दिखाई दे रहा है; अन्यथा,`असत्य` .

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


