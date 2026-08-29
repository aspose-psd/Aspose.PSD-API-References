---
title: "DropShadowEffect.IsVisible"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "DropShadowEffect प्रॉपर्टी। यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह इंस्टेंस दृश्यमान है या नहीं"
type: docs
weight: 60
url: /hi/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/
---
{{< psd/tize >}}
## DropShadowEffect.IsVisible property

एक मान को प्राप्त करता है या सेट करता है जो यह दर्शाता है कि यह इंस्टेंस दृश्यमान है या नहीं।

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` यदि यह इंस्टेंस दृश्यमान है; अन्यथा, `false`।

## उदाहरण

निम्नलिखित कोड DropShadowEffect की Opacity प्रॉपर्टी के उपयोग को दर्शाता है।

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

    // उदाहरण Opacity = 20 के साथ
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // उदाहरण Opacity = 200 के साथ
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### देखें भी

* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


