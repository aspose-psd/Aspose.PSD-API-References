---
title: "IText.TextOrientation"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "IText प्रॉपर्टी। टेक्स्ट अभिविन्यास को प्राप्त या सेट करता है"
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
{{< psd/tize >}}
## IText.TextOrientation property

पाठ अभिविन्यास प्राप्त करता है या सेट करता है।

```csharp
public TextOrientation TextOrientation { get; set; }
```

### Property Value

टेक्स्ट अभिविन्यास।

## उदाहरण

निम्नलिखित कोड नई TextOrientation प्रॉपर्टी को संपादित करने की क्षमता को दर्शाता है। यह वर्तमान में रेंडरिंग को प्रभावित नहीं करता, बल्कि केवल आपको प्रॉपर्टी मान को संपादित करने की अनुमति देता है।

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // सही पढ़ना
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }

    textLayer.TextData.TextOrientation = TextOrientation.Horizontal;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Horizontal)
    {
        // सही पढ़ना
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### देखें भी

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


