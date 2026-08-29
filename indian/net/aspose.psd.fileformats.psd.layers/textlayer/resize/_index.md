---
title: "TextLayer.Resize"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "TextLayer मेथड। छवि को री-साइज़ करता है। डिफ़ॉल्ट LeftTopToLeftTop उपयोग किया जाता है"
type: docs
weight: 100
url: /hi/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
{{< psd/tize >}}
## TextLayer.Resize method

छवि का आकार बदलता है। डिफ़ॉल्ट LeftTopToLeftTop उपयोग किया जाता है।

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newWidth | Int32 | नई चौड़ाई। |
| newHeight | Int32 | नई ऊँचाई। |
| resizeType | ResizeType | री-साइज़ ट्रांसफ़ॉर्मेशन का प्रकार [`ResizeType`](../../../aspose.psd/resizetype/) |

## उदाहरण

निम्नलिखित कोड TextLayer.Resize फ़ंक्शन को प्रदर्शित करता है जिसमें री-साइज़िंग तंत्र चुनने के लिए पैरामीटर है।

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // यह टेक्स्ट लेयर का नया आकार सेट करता है
    const int NewWidth = 250;
    const int NewHeight = 250;

    // यह री-साइज़ फ़ंक्शन लेयर को कैसे री-साइज़ करेगा, उसके तंत्र को सेट करता है (डिफ़ॉल्ट मान)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // यहाँ उपयोग किए गए टेक्स्ट लेयर के री-साइज़िंग का नया तंत्र
    // केवल लेयर ही नहीं, बल्कि टेक्स्ट लेयर का ट्रांसफ़ॉर्म मैट्रिक्स भी बदल दिया जाएगा
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // डेल्टा का कारण अलग डिफ़ॉल्ट फ़ॉन्ट है
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // सब ठीक है
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### देखें भी

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


