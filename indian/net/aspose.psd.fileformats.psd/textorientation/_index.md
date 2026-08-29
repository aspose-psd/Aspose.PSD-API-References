---
title: "एनम TextOrientation"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.TextOrientation एनम। टेक्स्ट ओरिएंटेशन मोड के लिए एनेमरेशन"
type: docs
weight: 4480
url: /hi/net/aspose.psd.fileformats.psd/textorientation/
---
{{< psd/tize >}}
## TextOrientation enumeration

टेक्स्ट ओरिएंटेशन मोड के लिए एन्यूमरेशन।

```csharp
public enum TextOrientation
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Horizontal | `0` | क्षैतिज टेक्स्ट ओरिएंटेशन। |
| Vertical | `2` | ऊर्ध्वाधर टेक्स्ट ओरिएंटेशन। |

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

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


