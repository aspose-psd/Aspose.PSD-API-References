---
title: "TextLayer.TransformMatrix"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "TextLayer प्रॉपर्टी। ट्रांसफ़ॉर्म मैट्रिक्स को प्राप्त या सेट करता है"
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
{{< psd/tize >}}
## TextLayer.TransformMatrix property

ट्रांसफ़ॉर्म मैट्रिक्स को प्राप्त करता है या सेट करता है।

```csharp
public double[] TransformMatrix { get; set; }
```

### Property Value

ट्रांसफ़ॉर्म मैट्रिक्स

## उदाहरण

निम्न कोड दर्शाता है कि टेक्स्ट लेयर में किसी भी टेक्स्ट भाग के लिए फ़ॉन्ट आकार कैसे प्राप्त किया जाए।

```csharp
[C#]

// गलत फ़ॉन्ट आकार निकाला गया
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // पुराना API (पहले पैराग्राफ़ फ़ॉन्ट का उपयोग करते हुए)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // बेस फ़ॉन्ट आकार की जाँच कर रहा है
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // वास्तविक फ़ॉन्ट आकार की जाँच कर रहा है
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // नया API (एक टेक्स्ट लेयर में किसी भी मात्रा में फ़ॉन्ट आकार हो सकते हैं)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // बेस भाग के फ़ॉन्ट आकार की जाँच
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // वास्तविक भाग के फ़ॉन्ट आकार की जाँच
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### देखें भी

* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


