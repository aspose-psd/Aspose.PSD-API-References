---
title: PsdImage.AddLayer
second_title: Aspose.PSD voor .NET API-referentie
description: PsdImage methode. Voegt de laag toe.
type: docs
weight: 370
url: /nl/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
## PsdImage.AddLayer method

Voegt de laag toe.

```csharp
public void AddLayer(Layer layer)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layer | Layer | De laag. |

### Voorbeelden

Het volgende voorbeeld laat zien hoe u kunt tekenen op een nieuw gemaakte laag als de eenvoudige constructorversie wordt gebruikt in Aspose.PSD

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

    // teken een rechthoek met het gereedschap Pen
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // teken nog een rechthoek met Solid Brush in blauwe kleur
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Zie ook

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* naamruimte [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* montage [Aspose.PSD](../../../)


