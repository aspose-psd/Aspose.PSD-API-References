---
title: "PsdImage.AddLayer"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode PsdImage. Ajoute la couche"
type: docs
weight: 390
url: /fr/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
{{< psd/tize >}}
## PsdImage.AddLayer method

Ajoute le calque.

```csharp
public void AddLayer(Layer layer)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| calque | Calque | Le calque. |

## Exemples

L'exemple suivant montre comment vous pouvez dessiner sur une couche nouvellement créée si la version simple du constructeur est utilisée dans Aspose.PSD

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

    // dessinez un rectangle avec l'outil Pen
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // dessinez un autre rectangle avec Solid Brush en couleur bleue
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Voir aussi

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


