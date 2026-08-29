---
title: "GrdmResource.RndNumberSeed"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "GrdmResource Eigenschaft. Der Zufallszahlensamen, der zur Erzeugung von Farben für das Rauschen-Gradient verwendet wird"
type: docs
weight: 150
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/rndnumberseed/
---
{{< psd/tize >}}
## GrdmResource.RndNumberSeed property

Der Zufallszahl-Seed, der verwendet wird, um Farben für das Noise-Gradient zu erzeugen.

```csharp
public int RndNumberSeed { get; set; }
```

## Beispiele

Der folgende Code demonstriert die Unterstützung der GrdmResource-Ressource.

```csharp
[C#]

string sourceFile = "gradient_map_default.psd";
string outputFile = "gradient_map_res.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
            
    // aktuelle Werte prüfen
    AssertAreEqual(false, grdmResource.Reverse);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
            
            
    grdmResource.Reverse = true;
    // Rote Farbe für den zweiten Farbpunkt des Verlaufs
    grdmResource.ColorPoints[1].RawColor.Components[1].Value = ushort.MaxValue;
    grdmResource.ColorPoints[1].RawColor.Components[2].Value = 0;
    grdmResource.ColorPoints[1].RawColor.Components[3].Value = 0;

    image.Save(outputFile, new PsdOptions());
}

using (var image = (PsdImage)Image.Load(outputFile))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
    
    // geänderte Werte prüfen
    AssertAreEqual(true, grdmResource.Reverse);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
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

* class [GrdmResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


