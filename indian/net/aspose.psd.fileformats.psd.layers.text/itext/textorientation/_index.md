---
title: IText.TextOrientation
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: IText संपत्त. टेक्स्ट ओरएंटेशन प्रप्त य सेट करत है
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
## IText.TextOrientation property

टेक्स्ट ओरिएंटेशन प्राप्त या सेट करता है।

```csharp
public TextOrientation TextOrientation { get; set; }
```

### संपत्ति मूल्य

टेक्स्ट ओरिएंटेशन.

### उदाहरण

निम्न कोड नई टेक्स्टऑरिएंटेशन संपत्ति को संपादित करने की क्षमता प्रदर्शित करता है। यह इस समय रेंडरिंग को प्रभावित नहीं करता है, लेकिन केवल आपको संपत्ति के मूल्य को संपादित करने की अनुमति देता है।

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

### यह सभी देखें

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* सभा [Aspose.PSD](../../../)


