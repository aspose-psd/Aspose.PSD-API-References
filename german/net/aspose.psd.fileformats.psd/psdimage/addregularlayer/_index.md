---
title: "PsdImage.AddRegularLayer"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdImage Methode. Fügt eine neue reguläre Ebene hinzu"
type: docs
weight: 440
url: /de/net/aspose.psd.fileformats.psd/psdimage/addregularlayer/
---
{{< psd/tize >}}
## PsdImage.AddRegularLayer method

Fügt eine neue reguläre Ebene hinzu.

```csharp
public Layer AddRegularLayer()
```

### Rückgabewert

Reguläre Ebene erstellt.

## Beispiele

Der folgende Code zeigt, wie die neu erzeugte reguläre Ebene zu PsdImage hinzugefügt wird.

```csharp
[C#]

string sourceFileName = "OneLayer.psd";
string exportPath = "OneLayerEdited.psd";
string exportPathPng = "OneLayerEdited.png";

using (var im = (PsdImage)Image.Load(sourceFileName))
{
    // Zwei int-Arrays werden vorbereitet
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

    // PSD speichern
    im.Save(exportPath, new PsdOptions());

    // PNG speichern
    im.Save(exportPathPng, new PngOptions());
}
```

### Siehe auch

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


