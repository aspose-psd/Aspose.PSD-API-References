---
title: PsdImage.AddLayer
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: PsdImage तरक. परत जड़त है.
type: docs
weight: 370
url: /hi/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
## PsdImage.AddLayer method

परत जोड़ता है.

```csharp
public void AddLayer(Layer layer)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| layer | Layer | परत। |

### उदाहरण

निम्न उदाहरण प्रदर्शित करता है कि यदि Aspose.PSD में सरल कन्स्ट्रक्टर संस्करण का उपयोग किया जाता है तो आप नई बनाई गई परत पर कैसे आकर्षित कर सकते हैं

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // पेन टूल के साथ एक आयत बनाएं
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // सॉलिड ब्रश के साथ नीले रंग में एक और आयत बनाएं
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### यह सभी देखें

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* सभा [Aspose.PSD](../../../)


