---
title: TextLayer.TransformMatrix
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: TextLayer संपत्त. ट्रंसफर्म मैट्रक्स प्रप्त य सेट करत है
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
## TextLayer.TransformMatrix property

ट्रांसफॉर्म मैट्रिक्स प्राप्त या सेट करता है

```csharp
public double[] TransformMatrix { get; set; }
```

### संपत्ति मूल्य

रूपांतरण मैट्रिक्स

### उदाहरण

निम्न कोड प्रदर्शित करता है कि पाठ परत में किसी पाठ भाग के लिए फ़ॉन्ट आकार कैसे प्राप्त करें।

```csharp
[C#]

// निकाला गया गलत फ़ॉन्ट आकार 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // पुराना एपीआई (पहले पैराग्राफ फ़ॉन्ट का उपयोग करके)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // आधार फ़ॉन्ट आकार की जाँच करना
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // वास्तविक फ़ॉन्ट आकार की जाँच करना
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // नया एपीआई (एक पाठ परत में फ़ॉन्ट आकार की कितनी भी मात्रा हो सकती है)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // आधार भाग फ़ॉन्ट आकार की जाँच करना
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // वास्तविक भाग फ़ॉन्ट आकार की जाँच करना
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### यह सभी देखें

* class [TextLayer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* सभा [Aspose.PSD](../../../)


