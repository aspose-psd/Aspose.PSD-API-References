---
title: "PsdImage.AddLayer"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PsdImage विधि. परत जोड़ता है"
type: docs
weight: 390
url: /hi/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
{{< psd/tize >}}
## PsdImage.AddLayer method

लेयर जोड़ता है।

```csharp
public void AddLayer(Layer layer)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| लेयर | लेयर | लेयर। |

## उदाहरण

निम्न उदाहरण दर्शाता है कि आप Aspose.PSD में सरल कंस्ट्रक्टर संस्करण का उपयोग करने पर नए बनाए गए लेयर पर कैसे ड्रॉ कर सकते हैं

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

    // Pen टूल से एक आयत बनाएं
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // नीले रंग में Solid Brush से एक और आयत बनाएं
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### देखें भी

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


