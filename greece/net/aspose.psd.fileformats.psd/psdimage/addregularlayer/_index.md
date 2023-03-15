---
title: PsdImage.AddRegularLayer
second_title: Aspose.PSD για Αναφορά API .NET
description: PsdImage μέθοδος. Προσθέτει ένα νέο κανονικό επίπεδο.
type: docs
weight: 410
url: /el/net/aspose.psd.fileformats.psd/psdimage/addregularlayer/
---
## PsdImage.AddRegularLayer method

Προσθέτει ένα νέο κανονικό επίπεδο.

```csharp
public Layer AddRegularLayer()
```

### Επιστρεφόμενη Αξία

Δημιουργήθηκε κανονικό επίπεδο.

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να προσθέσετε το νέο κανονικό επίπεδο που δημιουργήθηκε στο PsdImage.

```csharp
[C#]

string sourceFileName = "OneLayer.psd";
string exportPath = "OneLayerEdited.psd";
string exportPathPng = "OneLayerEdited.png";

using (var im = (PsdImage)Image.Load(sourceFileName))
{
    // Προετοιμασία δύο πινάκων int
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

    // Αποθήκευση psd
    im.Save(exportPath, new PsdOptions());

    // Αποθήκευση png
    im.Save(exportPathPng, new PngOptions());
}
```

### Δείτε επίσης

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* συνέλευση [Aspose.PSD](../../../)


