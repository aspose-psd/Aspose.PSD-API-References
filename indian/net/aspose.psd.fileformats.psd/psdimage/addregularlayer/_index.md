---
title: PsdImage.AddRegularLayer
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: PsdImage तरक. एक नई नयमत परत जड़त है.
type: docs
weight: 410
url: /hi/net/aspose.psd.fileformats.psd/psdimage/addregularlayer/
---
## PsdImage.AddRegularLayer method

एक नई नियमित परत जोड़ता है.

```csharp
public Layer AddRegularLayer()
```

### प्रतिलाभ की मात्रा

नियमित परत बनाई गई।

### उदाहरण

निम्न कोड दिखाता है कि नई उत्पन्न नियमित परत को PsdImage में कैसे जोड़ा जाए।

```csharp
[C#]

string sourceFileName = "OneLayer.psd";
string exportPath = "OneLayerEdited.psd";
string exportPathPng = "OneLayerEdited.png";

using (var im = (PsdImage)Image.Load(sourceFileName))
{
    // दो इंट सरणियों की तैयारी
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

    // पीएसडी बचाओ
    im.Save(exportPath, new PsdOptions());

    // पीएनजी सहेजें
    im.Save(exportPathPng, new PngOptions());
}
```

### यह सभी देखें

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* सभा [Aspose.PSD](../../../)


