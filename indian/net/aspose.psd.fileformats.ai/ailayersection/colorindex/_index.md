---
title: "AiLayerSection.ColorIndex"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "AiLayerSection प्रॉपर्टी। रंग का इंडेक्स प्राप्त या सेट करता है। यह आर्ग्यूमेंट 1 से 26 के बीच मान ले सकता है। प्रत्येक पूर्णांक एक रंग का प्रतिनिधित्व करता है जिसे उपयोगकर्ता पहचान उद्देश्यों के लिए लेयर को असाइन किया जा सकता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.ai/ailayersection/colorindex/
---
{{< psd/tize >}}
## AiLayerSection.ColorIndex property

रंग का इंडेक्स प्राप्त करता है या सेट करता है। यह तर्क –1 से 26 के बीच मान ले सकता है। प्रत्येक पूर्णांक एक रंग का प्रतिनिधित्व करता है जिसे उपयोगकर्ता पहचान उद्देश्यों के लिए लेयर को असाइन किया जा सकता है।

```csharp
public int ColorIndex { get; set; }
```

### Property Value

रंग का इंडेक्स।

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


