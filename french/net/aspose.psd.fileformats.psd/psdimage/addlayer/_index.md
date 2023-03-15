---
title: PsdImage.AddLayer
second_title: Référence de l'API Aspose.PSD pour .NET
description: PsdImage méthode. Ajoute le calque.
type: docs
weight: 370
url: /fr/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
## PsdImage.AddLayer method

Ajoute le calque.

```csharp
public void AddLayer(Layer layer)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| layer | Layer | La couche. |

### Exemples

L'exemple suivant montre comment vous pouvez dessiner sur un calque nouvellement créé si la version du constructeur simple est utilisée dans Aspose.PSD

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

    // dessine un rectangle avec l'outil Plume
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // dessine un autre rectangle avec Solid Brush de couleur bleue
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Voir également

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* Assemblée [Aspose.PSD](../../../)


