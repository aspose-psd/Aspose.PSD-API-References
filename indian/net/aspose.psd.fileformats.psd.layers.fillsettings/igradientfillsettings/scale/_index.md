---
title: "IGradientFillSettings.Scale"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "IGradientFillSettings प्रॉपर्टी। प्राप्त करता है या सेट करता है सामान्यीकृत ग्रेडिएंट स्केल प्रतिशत में"
type: docs
weight: 90
url: /hi/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
{{< psd/tize >}}
## IGradientFillSettings.Scale property

**normalized** ग्रेडिएंट स्केल (प्रतिशत में) को प्राप्त करता है या सेट करता है।

```csharp
public int Scale { get; set; }
```

### Property Value

स्केल।

## उदाहरण

निम्नलिखित उदाहरण दर्शाता है कि स्केल प्रॉपर्टी का उपयोग करके ग्रेडिएंट के साथ FillLayer को कैसे स्केल किया जाए।

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // एक FillLayer प्राप्त करना
    FillLayer fillLayer = null;
    foreach (var layer in image.Layers)
    {
        fillLayer = layer as FillLayer;
        if (fillLayer != null)
        {
            break;
        }
    }

    var settings = fillLayer.FillSettings as IGradientFillSettings;

    // स्केल मान को अपडेट करें
    settings.Scale = 200;
    fillLayer.Update(); // Updates pixels data

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### देखें भी

* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


