---
title: "ShapeLayer.Fill"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ShapeLayer-Eigenschaft. Gibt die Füll-Einstellungen für den Innenbereich von Formen in der Shape-Ebene zurück oder legt sie fest."
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.layers/shapelayer/fill/
---
{{< psd/tize >}}
## ShapeLayer.Fill property

Ruft die Fülleinstellungen für den internen Bereich von Shapes im Shape layer ab oder legt sie fest.

```csharp
public IFillSettings Fill { get; set; }
```

## Beispiele

Der folgende Code demonstriert die Fill-Eigenschaft von ShapeLayer.

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

// Gespeicherte Änderungen überprüfen
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

### Siehe auch

* interface [IFillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/)
* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


