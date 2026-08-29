---
title: "ShapeLayer.Fill"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "ShapeLayer eigenschap. Krijgt of stelt Fill-instellingen in voor het interne gebied van Shapes in de Shape-laag"
type: docs
weight: 30
url: /nl/net/aspose.psd.fileformats.psd.layers/shapelayer/fill/
---
{{< psd/tize >}}
## ShapeLayer.Fill property

Haalt of stelt de vulinstellingen voor het interne gebied van vormen in de vormlaag in.

```csharp
public IFillSettings Fill { get; set; }
```

## Voorbeelden

De volgende code toont de Fill-eigenschap van ShapeLayer.

```csharp
[C#]

string srcFile = "ShapeInternalSolid.psd";
string outFile = "ShapeInternalSolid.psd.out.psd";

using (PsdImage image = (PsdImage)Image.Load(
           srcFile,
           new PsdLoadOptions { LoadEffectsResource = true }))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    ColorFillSettings fillSettings = (ColorFillSettings)shapeLayer.Fill;
    fillSettings.Color = Color.Red;

    shapeLayer.Update();

    image.Save(outFile);
}

// Controleer opgeslagen wijzigingen
using (PsdImage image = (PsdImage)Image.Load(
           outFile,
           new PsdLoadOptions { LoadEffectsResource = true }))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    ColorFillSettings fillSettings = (ColorFillSettings)shapeLayer.Fill;

    AssertAreEqual(Color.Red, fillSettings.Color);

    image.Save(outFile);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### Zie ook

* interface [IFillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/)
* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


