---
title: PsdImage.AddRegularLayer
second_title: Référence de l'API Aspose.PSD pour .NET
description: PsdImage méthode. Ajoute un nouveau calque régulier.
type: docs
weight: 410
url: /fr/net/aspose.psd.fileformats.psd/psdimage/addregularlayer/
---
## PsdImage.AddRegularLayer method

Ajoute un nouveau calque régulier.

```csharp
public Layer AddRegularLayer()
```

### Return_Value

Couche régulière créée.

### Exemples

Le code suivant montre comment ajouter la couche régulière nouvellement générée à PsdImage.

```csharp
[C#]

string sourceFileName = "OneLayer.psd";
string exportPath = "OneLayerEdited.psd";
string exportPathPng = "OneLayerEdited.png";

using (var im = (PsdImage)Image.Load(sourceFileName))
{
    // Préparation de deux tableaux int
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

    // Enregistrer le psd
    im.Save(exportPath, new PsdOptions());

    // Enregistrer png
    im.Save(exportPathPng, new PngOptions());
}
```

### Voir également

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Assemblée [Aspose.PSD](../../../)


