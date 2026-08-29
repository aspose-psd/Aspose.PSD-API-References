---
title: "AiLayerSection.HasMultiLayerMasks"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "AiLayerSection प्रॉपर्टी। यह मान प्राप्त करता है या सेट करता है जो दर्शाता है कि इस इंस्टेंस में मल्टीलेयर मास्क हैं या नहीं"
type: docs
weight: 60
url: /hi/net/aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/
---
{{< psd/tize >}}
## AiLayerSection.HasMultiLayerMasks property

यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि इस इंस्टेंस में मल्टीलेयर मास्क हैं या नहीं।

```csharp
public bool HasMultiLayerMasks { get; set; }
```

### Property Value

`true` यदि इस इंस्टेंस में मल्टीलेयर मास्क हैं; अन्यथा, `false`।

## उदाहरण

निम्नलिखित कोड AiLayerSection में HasMultiLayerMasks और ColorIndex प्रॉपर्टीज़ के समर्थन को दर्शाता है।

```csharp
[C#]

string sourceFile = "example.ai";
string outputFilePath = "example.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AssertAreEqual(image.Layers.Length, 2);
    AssertAreEqual(image.Layers[0].HasMultiLayerMasks, false);
    AssertAreEqual(image.Layers[0].ColorIndex, -1);
    AssertAreEqual(image.Layers[1].HasMultiLayerMasks, false);
    AssertAreEqual(image.Layers[1].ColorIndex, -1);

    image.Save(outputFilePath, new PngOptions());
}
```

### देखें भी

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


