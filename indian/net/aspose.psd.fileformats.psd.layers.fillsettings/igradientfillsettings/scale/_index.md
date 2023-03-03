---
title: IGradientFillSettings.Scale
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: IGradientFillSettings संपत्त. स्केल प्रप्त करत है य सेट करत है
type: docs
weight: 100
url: /hi/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
## IGradientFillSettings.Scale property

स्केल प्राप्त करता है या सेट करता है।

```csharp
public int Scale { get; set; }
```

### संपत्ति मूल्य

पैमाना।

### उदाहरण

निम्न उदाहरण दर्शाता है कि ग्रेडिएंट के साथ फिललेयर को स्केल करने के लिए स्केल प्रॉपर्टी का उपयोग कैसे करें।

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // एक भरण परत प्राप्त करना
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

    // अपडेट स्केल वैल्यू
    settings.Scale = 200;
    fillLayer.Update(); // पिक्सेल डेटा अपडेट करता है

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### यह सभी देखें

* interface [IGradientFillSettings](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../igradientfillsettings/)
* सभा [Aspose.PSD](../../../)


