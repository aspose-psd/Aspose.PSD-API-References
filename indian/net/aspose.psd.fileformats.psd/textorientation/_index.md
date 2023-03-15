---
title: Enum TextOrientation
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.TextOrientation एनुम. टेक्स्ट ओरएंटेशन मड के लए गणन.
type: docs
weight: 4010
url: /hi/net/aspose.psd.fileformats.psd/textorientation/
---
## TextOrientation enumeration

टेक्स्ट ओरिएंटेशन मोड के लिए गणना.

```csharp
public enum TextOrientation
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| Horizontal | `0` | क्षैतिज टेक्स्ट ओरिएंटेशन. |
| Vertical | `2` | वर्टिकल टेक्स्ट ओरिएंटेशन। |

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

* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* सभा [Aspose.PSD](../../)


