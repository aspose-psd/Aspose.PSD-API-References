---
title: "ShapeLayer.Fill"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété ShapeLayer. Obtient ou définit les paramètres de remplissage pour la zone interne des formes dans le calque Shape."
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.layers/shapelayer/fill/
---
{{< psd/tize >}}
## ShapeLayer.Fill property

Obtient ou définit les paramètres de remplissage pour la zone interne des formes dans le calque Shape.

```csharp
public IFillSettings Fill { get; set; }
```

## Exemples

Le code suivant montre la propriété Fill de ShapeLayer.

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

// Vérifier les modifications enregistrées
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

### Voir aussi

* interface [IFillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/)
* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


