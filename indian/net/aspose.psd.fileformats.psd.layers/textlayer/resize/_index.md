---
title: TextLayer.Resize
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: TextLayer तरक. छव क आकर बदलत है डफ़ल्टLeftTopToLeftTopप्रयग कय जत है.
type: docs
weight: 90
url: /hi/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
## TextLayer.Resize method

छवि का आकार बदलता है। डिफ़ॉल्टLeftTopToLeftTopप्रयोग किया जाता है.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newWidth | Int32 | नई चौड़ाई. |
| newHeight | Int32 | नई ऊंचाई. |
| resizeType | ResizeType | आकार परिवर्तन का प्रकार[`ResizeType`](../../../aspose.psd/resizetype/) |

### उदाहरण

निम्न कोड आकार बदलने की प्रक्रिया को चुनने के लिए पैरामीटर के साथ TextLayer.Resize फ़ंक्शन को प्रदर्शित करता है।

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

    // यह तंत्र को सेट करता है कि आकार बदलने का कार्य परत का आकार कैसे बदलेगा (डिफ़ॉल्ट मान)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // पाठ परत के आकार बदलने का नया तंत्र यहाँ का उपयोग कर रहा है
    // केवल लेयर ही नहीं बल्कि टेक्स्ट लेयर का ट्रांसफॉर्मेशन मैट्रिक्स भी बदला जाएगा
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

### यह सभी देखें

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* सभा [Aspose.PSD](../../../)


