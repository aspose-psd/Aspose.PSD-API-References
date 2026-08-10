---
title: "PsdImage.AddRegularLayer"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "PsdImage मेथड। एक नया रेगुलर लेयर जोड़ता है"
type: docs
weight: 440
url: /hi/net/aspose.psd.fileformats.psd/psdimage/addregularlayer/
---
{{< psd/tize >}}
## PsdImage.AddRegularLayer method

एक नया नियमित लेयर जोड़ता है।

```csharp
public Layer AddRegularLayer()
```

### रिटर्न वैल्यू

रेगुलर लेयर बनाया गया।

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे नई उत्पन्न रेगुलर लेयर को PsdImage में जोड़ें।

```csharp
[C#]

string sourceFileName = "OneLayer.psd";
string exportPath = "OneLayerEdited.psd";
string exportPathPng = "OneLayerEdited.png";

using (var im = (PsdImage)Image.Load(sourceFileName))
{
    // दो इंट एरे तैयार कर रहे हैं
    var data1 = new int[2500];
    var data2 = new int[2500];

    var rect1 = new Rectangle(0, 0, 50, 50);
    var rect2 = new Rectangle(0, 0, 100, 25);

    for (int i = 0; i < 2500; i++)
    {
        data1[i] = -10000000;
        data2[i] = -10000000;
    }

    var layer1 = im.AddRegularLayer();
    layer1.Left = 25;
    layer1.Top = 25;
    layer1.Right = 75;
    layer1.Bottom = 75;
    layer1.SaveArgb32Pixels(rect1, data1);

    var layer2 = im.AddRegularLayer();
    layer2.Left = 25;
    layer2.Top = 150;
    layer2.Right = 125;
    layer2.Bottom = 175;
    layer2.SaveArgb32Pixels(rect2, data2);

    // psd सहेजें
    im.Save(exportPath, new PsdOptions());

    // png सहेजें
    im.Save(exportPathPng, new PngOptions());
}
```

### देखें भी

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


