---
title: PsdImage.AddRegularLayer
second_title: Aspose.PSD för .NET API-referens
description: PsdImage metod. Lägger till ett nytt vanligt lager.
type: docs
weight: 410
url: /sv/net/aspose.psd.fileformats.psd/psdimage/addregularlayer/
---
## PsdImage.AddRegularLayer method

Lägger till ett nytt vanligt lager.

```csharp
public Layer AddRegularLayer()
```

### Returvärde

Skapade vanligt lager.

### Exempel

Följande kod visar hur man lägger till det nygenererade vanliga lagret till PsdImage.

```csharp
[C#]

string sourceFileName = "OneLayer.psd";
string exportPath = "OneLayerEdited.psd";
string exportPathPng = "OneLayerEdited.png";

using (var im = (PsdImage)Image.Load(sourceFileName))
{
    // Förbereder två int-arrayer
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

    // Spara psd
    im.Save(exportPath, new PsdOptions());

    // Spara png
    im.Save(exportPathPng, new PngOptions());
}
```

### Se även

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* hopsättning [Aspose.PSD](../../../)


